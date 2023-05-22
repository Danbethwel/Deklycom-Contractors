#fc5e28;
#3D4594;



/*** Header ***/
@media (max-width: 768px) {
    .header-carousel .owl-carousel-item {
        position: relative;
        min-height: 500px;
    }
    
    .header-carousel .owl-carousel-item img {
        position: absolute;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    .header-carousel .owl-carousel-item h5,
    .header-carousel .owl-carousel-item p {
        font-size: 14px !important;
        font-weight: 400 !important;
    }

    .header-carousel .owl-carousel-item h1 {
        font-size: 30px;
        font-weight: 600;
    }
}

.header-carousel .owl-nav {
    position: absolute;
    width: 200px;
    height: 45px;
    bottom: 30px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    justify-content: space-between;
}

.header-carousel .owl-nav .owl-prev,
.header-carousel .owl-nav .owl-next {
    width: 45px;
    height: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #FFFFFF;
    background: transparent;
    border: 1px solid #FFFFFF;
    font-size: 22px;
    transition: .5s;
}

.header-carousel .owl-nav .owl-prev:hover,
.header-carousel .owl-nav .owl-next:hover {
    background: var(--primary);
    border-color: var(--primary);
}

.header-carousel .owl-dots {
    position: absolute;
    height: 45px;
    bottom: 30px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    align-items: center;
    justify-content: center;
}

.header-carousel .owl-dot {
    position: relative;
    display: inline-block;
    margin: 0 5px;
    width: 15px;
    height: 15px;
    background: transparent;
    border: 1px solid #FFFFFF;
    transition: .5s;
}

.header-carousel .owl-dot::after {
    position: absolute;
    content: "";
    width: 5px;
    height: 5px;
    top: 4px;
    left: 4px;
    background: transparent;
    border: 1px solid #FFFFFF;
}

.header-carousel .owl-dot.active {
    background: var(--primary);
    border-color: var(--primary);
}




<div class="container-fluid p-0 pb-5">
        <div class="owl-carousel header-carousel position-relative">
            <div class="owl-carousel-item position-relative">
                <img class="img-fluid" src="img/carousel-5.jpg" alt="">
                <div class="position-absolute top-0 start-0 w-100 h-100 d-flex align-items-center" style="background: rgba(53, 53, 53, .7);">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-12 col-lg-8 text-center">
                                <h5 class="text-white text-uppercase mb-3 animated slideInDown">WELCOME TO:</h5>
                                <h1 class="display-3 text-white animated slideInDown mb-4">Drilling Experts Contractors LTD</h1>
                                <p class="fs-5 fw-medium text-white mb-4 pb-2">The best company in surveying,Drilling and Tank installation</p>
                                <a href="" class="btn btn-primary py-md-3 px-md-5 me-3 animated slideInLeft">Read More</a>
                                <a href="" class="btn btn-light py-md-3 px-md-5 animated slideInRight">Free Quote</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="owl-carousel-item position-relative">
                <img class="img-fluid" src="img/carousel-4.jpg" alt="">
                <div class="position-absolute top-0 start-0 w-100 h-100 d-flex align-items-center" style="background: rgba(53, 53, 53, .7);">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-12 col-lg-8 text-center">
                                <h5 class="text-white text-uppercase mb-3 animated slideInDown">Water 💦 Is Life</h5>
                                <h1 class="display-3 text-white animated slideInDown mb-4">Hydro-Geological Survey</h1>
                                <p class="fs-5 fw-medium text-white mb-4 pb-2">We have the best team of geologists and hydrologists who use specialized equipment and techniques to map out the geology of the area, identify potential water sources, and analyze the flow of groundwater.</p>
                                <a href="" class="btn btn-primary py-md-3 px-md-5 me-3 animated slideInLeft">Read More</a>
                                <a href="" class="btn btn-light py-md-3 px-md-5 animated slideInRight">Free Quote</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="owl-carousel-item position-relative">
                <img class="img-fluid" src="img/carousel-3.jpg" alt="">
                <div class="position-absolute top-0 start-0 w-100 h-100 d-flex align-items-center" style="background: rgba(53, 53, 53, .7);">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-12 col-lg-8 text-center">
                                <h5 class="text-white text-uppercase mb-3 animated slideInDown">Water 💦 Is Life</h5>
                                <h1 class="display-3 text-white animated slideInDown mb-4">Test Pumping And Water Quality Analysis.</h1>
                                <p class="fs-5 fw-medium text-white mb-4 pb-2"> We do testing and analyzing of water to determine its physical, chemical, and biological properties. This information is used to assess the suitability of the water for its intended use, such as drinking, irrigation, or industrial purposes.</p>
                                <a href="" class="btn btn-primary py-md-3 px-md-5 me-3 animated slideInLeft">Read More</a>
                                <a href="" class="btn btn-light py-md-3 px-md-5 animated slideInRight">Free Quote</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="owl-carousel-item position-relative">
                <img class="img-fluid" src="img/carousel-2.jpg" alt="">
                <div class="position-absolute top-0 start-0 w-100 h-100 d-flex align-items-center" style="background: rgba(53, 53, 53, .7);">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-12 col-lg-8 text-center">
                                <h5 class="text-white text-uppercase mb-3 animated slideInDown">Water 💦 Is Life</h5>
                                <h1 class="display-3 text-white animated slideInDown mb-4">Clean water supply to Communities</h1>
                                <p class="fs-5 fw-medium text-white mb-4 pb-2">Even communities the in most remote parts of Kenya gain access to reliable source clean drinking water </p>
                                <a href="" class="btn btn-primary py-md-3 px-md-5 me-3 animated slideInLeft">Read More</a>
                                <a href="" class="btn btn-light py-md-3 px-md-5 animated slideInRight">Free Quote</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Carousel End -->



    <section class="ftco-section ftco-no-pt ftco-no-pb ftco-services-2">
		<div class="container">
			<div class="row no-gutters d-flex">
				<div class="col-lg-4 d-flex align-self-stretch ftco-animate">
					<div class="media block-6 services d-flex">
						<div class="icon justify-content-center align-items-center d-flex"><span class="flaticon-engineer-1"></span></div>
						<div class="media-body pl-4">
							<h3 class="heading mb-3">Quality Construction</h3>
							<p>A small river named Duden flows by their place and supplies it with the necessary regelialia.</p>
						</div>
					</div>      
				</div>
				<div class="col-lg-4 d-flex align-self-stretch ftco-animate">
					<div class="media block-6 services services-2 d-flex">
						<div class="icon justify-content-center align-items-center d-flex"><span class="flaticon-worker-1"></span></div>
						<div class="media-body pl-4">
							<h3 class="heading mb-3">Professional Liability</h3>
							<p>A small river named Duden flows by their place and supplies it with the necessary regelialia.</p>
						</div>
					</div>      
				</div>
				<div class="col-lg-4 d-flex align-self-stretch ftco-animate">
					<div class="media block-6 services d-flex">
						<div class="icon justify-content-center align-items-center d-flex"><span class="flaticon-engineer"></span></div>
						<div class="media-body pl-4">
							<h3 class="heading mb-3">Dedicated To Our Clients</h3>
							<p>A small river named Duden flows by their place and supplies it with the necessary regelialia.</p>
						</div>
					</div>      
				</div>
			</div>
		</div>
	</section>



    <section class="hero-wrap js-fullheight" style="background-image: url('images/bg_1.jpg');" data-stellar-background-ratio="0.5">
		<div class="overlay"></div>
		<div class="container">
			<div class="row no-gutters slider-text js-fullheight align-items-center" data-scrollax-parent="true">
				<div class="col-lg-6 ftco-animate">
					<div class="mt-5">
						<h1 class="mb-4">We Build <br>Great Projects</h1>
						<p class="mb-4">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove.</p>
						<p><a href="#" class="btn btn-primary">Our Services</a> <a href="#" class="btn btn-white" data-toggle="modal" data-target="#exampleModalCenter">Request A Quote</a></p>
					</div>
				</div>
			</div>
			<div class="row no-gutters slider-text js-fullheight align-items-center" data-scrollax-parent="true">
				<div class="col-lg-6 ftco-animate">
					<div class="mt-5">
						<h1 class="mb-4">We Build <br>Nice Projects</h1>
						<p class="mb-4">Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove.</p>
						<p><a href="#" class="btn btn-primary">Our Services</a> <a href="#" class="btn btn-white" data-toggle="modal" data-target="#exampleModalCenter">Request A Quote</a></p>
					</div>
				</div>
			</div>
		</div>
	</section>




    AVANTI ARCHITECTURE LTD Copyright © | All rights reserved | Privacy Policy
