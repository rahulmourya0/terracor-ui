<template>
  <div class="deatils-section pt-90">
    <div class="create-account-block" id="login-terracor">
      <div class="container">
        <div class="row">
          <div class="col-md-5 col-sm-12 m-auto">
            <div class="create-account-text pb-4">
              <h1>
                Gem Technology for<br /><span class="gradient-text"
                  >the New Generation</span
                >
              </h1>
              <button class="create-account-button mt-3">Create Account</button>
            </div>
          </div>
          <div class="col-md-7 col-sm-12 m-auto">
            <div class="create-account-image">
              <b-img
                src="../assets/images/login.png"
                fluid
                alt="Responsive image"
              ></b-img>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="about-terracor-block" id="about-us-terracor">
      <div class="container">
        <div class="row">
          <div class="col-md-6 col-sm-12 m-auto">
            <div class="about-terracor-text pb-3">
              <h1>About <span class="gradient-text">Terra cor</span></h1>
              <h6 class="pt-3">
                We are a tech company creating a disruption in the diamond
                space. Our patented technology can help work with your diamonds
                a lot more effectively. We at Terracor want to add the maximum
                amount of value to your diamond business.
              </h6>
            </div>
          </div>
          <div class="col-md-6 col-sm-12 m-auto">
            <div class="about-terracor-image">
              <b-img
                src="../assets/images/about.png"
                fluid
                alt="Responsive image"
              ></b-img>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- <div class="how-it-work-block" id="how-it-works-terracor">
		<div class="container">
			<div class="how-it-work-heading text-center">
				<h1>How it <span class="gradient-text">Works</span></h1>
			</div>
			<div class="row pt-4">
				<div class="col-md-4 col-sm-6 m-auto">
					<div class="how-it-work text-center pb-3">
						<div>
						  <b-embed
    						type="iframe"
    						src="../assets/videos/Fish.mp4"
  							></b-embed>
						</div>
						<div class="how-it-work-details pt-3 pb-3">
							<h4>
								Stone Counting
							</h4>
						</div>
					</div>
				</div>

				<div class="col-md-4 col-sm-6 m-auto">
					<div class="how-it-work text-center pb-3">
						<div>
						  <b-embed
    						type="iframe"
    						src="../assets/videos/Fish.mp4"
  							></b-embed>
						</div>
						<div class="how-it-work-details pt-3 pb-3">
							<h4>
								Clarity Map and Grade
							</h4>
						</div>
					</div>
				</div>

				<div class="col-md-4 col-sm-6 m-auto">
					<div class="how-it-work text-center pb-3">
						<div>
						  <b-embed
    						type="iframe"
    						src="../assets/videos/Fish.mp4"
  							></b-embed>
						</div>

						<div class="how-it-work-details pt-3 pb-3">
							<h4>
								Stone Counting
							</h4>
						</div>
					</div>
				</div>
			
				<div class="col-md-4 col-sm-6 m-auto">
					<div class="how-it-work text-center">
						<div>
						  <b-embed
    						type="iframe"
    						src="../assets/videos/Fish.mp4"
  							></b-embed>
						</div>

						<div class="how-it-work-details text-center pt-3 pb-3">
							<h4>
								Stone Matching
							</h4>
						</div>
					</div>
				</div>

				<div class="col-md-4 col-sm-6 m-auto">
					<div class="how-it-work text-center">
						<div>
						  <b-embed
    						type="iframe"
    						src="../assets/videos/Fish.mp4"
  							></b-embed>
						</div>

						<div class="how-it-work-details pt-3 pb-3">
							<h4>
								Diamond Faceting
							</h4>
						</div>
					</div>
				</div>

				<div class="col-md-4 col-sm-6 m-auto">
					<div class="how-it-work text-center">
						<div>
						  <b-embed
    						type="iframe"
    						src="../assets/videos/Fish.mp4"
  							></b-embed>
						</div>

						<div class="how-it-work-details pt-3 pb-3">
							<h4>
								Memo Builder
							</h4>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>   -->

    <div class="get-terracor-block" id="get-terracor">
      <div class="container">
        <div class="row">
          <div class="col-md-5 col-sm-12 m-auto">
            <div class="get-terracor-image text-center pb-4">
              <b-img
                src="../assets/images/get-terra.png"
                fluid
                alt="Responsive image"
              ></b-img>
            </div>
          </div>
          <div class="col-md-7 col-sm-12 m-auto">
            <div class="get-terracor-text">
              <!-- <b-img src="../assets/images/appstore.png" fluid alt="Responsive image"></b-img> -->
              <h1>
                Get The Terra cor <span class="gradient-text">Mobile App</span>
              </h1>
            </div>
            <div class="row">
              <div class="col m-auto get-terracor-mob">
                <b-img
                  src="../assets/images/google-play.png"
                  fluid
                  alt="Responsive image"
                ></b-img>
              </div>
              <div class="col m-auto get-terracor-mob">
                <b-img
                  src="../assets/images/app-store.png"
                  fluid
                  alt="Responsive image"
                ></b-img>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {},
};
</script>
<style lang="scss" scoped>
@import "@/assets/scss/variable.scss";

.deatils-section {
  background-color: #000000;
  color: #ffffff;
  font-family: "Poppins", sans-serif;
  .container {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
    margin-top: 4rem;
  }
  .gradient-text {
    background-image: linear-gradient(
      180deg,
      #ffffff 31.94%,
      #cacaca 53.79%,
      #ffffff 73.61%
    );
    background-size: 100%;
    background-repeat: repeat;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    -moz-background-clip: text;
    -moz-text-fill-color: transparent;
  }
}

.create-account-block {
  .create-account-text h1 {
    font-size: 40px;
    font-weight: 400;
  }
  .create-account-text h1 span {
    font-size: 40px;
    font-weight: 700;
    // background: linear-gradient(180deg, #FFFFFF 31.94%, #CACACA 53.79%, #FFFFFF 73.61%);
  }
  .create-account-button {
    background: linear-gradient(
      180deg,
      #ffffff 0%,
      #cacaca 51.87%,
      #ffffff 100%
    );
    box-shadow: 0px 6px 10px rgba(0, 0, 0, 0.05);
    border-radius: 50px;
    padding: 16px 24px;
    font-size: 24px;
  }
}

.about-terracor-block {
  .about-terracor-text h1 {
    font-size: 48px;
    font-weight: 400;
  }
  .about-terracor-text h1 span {
    font-size: 48px;
    font-weight: 700;
    color: linear-gradient(
      180deg,
      #ffffff 31.94%,
      #cacaca 53.79%,
      #ffffff 73.61%
    );
  }
  .about-terracor-text h6 {
    font-size: 16px;
    font-weight: 300;
    line-height: 1.6;
  }
}

.how-it-work-block {
  .how-it-work-heading h1 {
    font-weight: 400;
  }
  .how-it-work-heading h1 span {
    font-weight: 700;
    color: linear-gradient(
      180deg,
      #ffffff 31.94%,
      #cacaca 53.79%,
      #ffffff 73.61%
    );
  }
}

.get-terracor-block {
  .get-terracor-text h1 {
    font-size: 35px;
    font-weight: 400;
  }
  .get-terracor-text h1 span {
    font-size: 35px;
    font-weight: 700;
    color: linear-gradient(
      180deg,
      #ffffff 31.94%,
      #cacaca 53.79%,
      #ffffff 73.61%
    );
  }
}

@media screen and (max-width: 768px) {
  .create-account-block {
    .create-account-text h1 {
      font-size: 24px;
    }
    .create-account-text h1 span {
      font-size: 24px;
    }
    .create-account-button {
      border-radius: 50px;
      padding: 8px 12px;
      font-size: 16px;
    }
  }

  .about-terracor-block {
    .about-terracor-text h1 {
      font-size: 24px;
    }
    .about-terracor-text h1 span {
      font-size: 24px;
    }
    .about-terracor-text h6 {
      font-size: 12px;
    }
  }

  .how-it-work-block {
    .how-it-work-heading h1 {
      font-size: 24px;
    }
    .how-it-work-heading h1 span {
      font-size: 24px;
    }
    .how-it-work-details h4 {
      font-size: 16px;
    }
  }

  .get-terracor-block {
    .get-terracor-text h1 {
      font-size: 19px;
      font-weight: 400;
    }
    .get-terracor-text h1 span {
      font-size: 19px;
      font-weight: 700;
      color: linear-gradient(
        180deg,
        #ffffff 31.94%,
        #cacaca 53.79%,
        #ffffff 73.61%
      );
    }
    .get-terracor-image .img-fluid {
      max-height: 70vh;
    }
  }
}

@media screen and (max-width: 576px) {
  .get-terracor-text h1,
  .get-terracor-mob {
    text-align: center;
  }
}

@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap");
</style>
