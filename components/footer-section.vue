<template>
	<div class="footer-section">
		<div class="container">
			<div class="row">
				<div class="col-sm-12 text-left pt-5 pb-5">
					<div class="footer-logo">
						<img src="@/assets/images/logo.png" alt="footer-logo" />
					</div>
				</div>
			</div>
		</div>
	</div>
</template>
<style lang="scss">
@import "~assets/scss/variable";
.footer-section {
	// padding: 20px 0 0 0;
	background: $black;
	font-weight: 500;
	color: $white;
	font-size: 0.75rem;
	// line-height: 200%;
}

@media only screen and (max-width: 767px) {
	.footer-logo {
		text-align: center !important;
	}
}

.footer-logo {
	text-align: left;
}

.footer-logo img{
	height: 65px;
}

</style>
