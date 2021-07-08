<template>
	<div>
		<div class="header-section">
			<div class="container">
				<b-navbar toggleable="md" class="">
					<!-- logo -->

					<!-- Just an image -->
					<b-navbar variant="faded" type="light">
						<b-navbar-brand href="#">
							<img
								src="@/assets/images/logo.png"
								class="img-fluid header-logo"
								alt="terracor"
							/>
						</b-navbar-brand>
					</b-navbar>

					<b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
					<b-collapse id="nav-collapse" is-nav>
						<b-navbar-nav class="text-center ml-auto">
							<nuxt-link class="nav-link" to="/">
								<div class="font-12">Home</div></nuxt-link
							>
							<nuxt-link class="nav-link" to="/#about-us-terracor">
								<div class="font-12">About Us</div></nuxt-link
							>
							<nuxt-link class="nav-link" to="/#how-it-works-terracor">
								<div class="font-12">How it works</div></nuxt-link
							>
							<nuxt-link class="nav-link" to="/#login-terracor">
								<div class="font-12">Login</div></nuxt-link
							>
						</b-navbar-nav>
					</b-collapse>
				</b-navbar>
			</div>
		</div>
	</div>
</template>
<style lang="scss" scoped>
@import "@/assets/scss/variable.scss";

.header-section {
	position: fixed;
	width: 100%;
	z-index: 9999;
	background-color: #000000;
	@media (max-width: 400px) {
		.header-logo {
			height: 20px;
			float: left;
			display: block;
		}
	}

	.container {
		width: 100%;
		padding-right: 15px ;
		padding-left: 15px ;
		margin-right: auto;
		margin-left: auto;
	}

	.header-logo {
		float: left;
		height: 50px;
	}
	.navbar {
		font-weight: 600;
		.nuxt-link-exact-active.nuxt-link-active {
			color: $white;
			font-weight: 600;
			padding: 8px 16px;
			background: linear-gradient(180deg, #FFFFFF 0%, #CACACA 51.87%, #FFFFFF 100%);
			color: #000000;
			border-radius: 40px;
		}
		.nav-link {
			color: $white;
			padding: 8px 16px;
			font-weight: 600;
		}
		// .nav-link:hover {
		// 	color: #902a00;
		// 	font-weight: 600;
		// }
	}
}

.font-12 {
	font-family: 'Poppins', sans-serif;
	font-size: 18px;
}
.col-lg-4,
.col-md-12,
.col-sm-12 {
	position: relative;
	width: 100%;
	// padding-right: 15px;
	// padding-left: 15px;
}

.navbar-light .navbar-toggler{
	background-color: #ffffff;
}

@media screen and (max-width: 768px) {
		.font-12 {
			font-size: 14px;
		}
}

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');
@import "@/assets/scss/mobile.scss";
</style>
