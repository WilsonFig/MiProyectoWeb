<template>
    <!-- Testimonials -->
    <div class="slider-1">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">

                    <!-- Card Slider -->
                    <div class="slider-container">
                        <div class="swiper-container card-slider">
                            <div class="swiper-wrapper">
                                
                                <!-- Slide -->
                                <div class="swiper-slide">
                                    <div class="card">
                                        <img class="card-image" src="../assets/testimonial-1.jpg" alt="alternative">
                                        <div class="card-body">
                                            <p class="testimonial-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, animi!</p>
                                            <p class="testimonial-author">Maria Lopez - Psicóloga</p>
                                        </div>
                                        <div id="divPadre">
                                            <div id="divHijo">
                                                <a href="#seccion-footer" class="btn-solid-reg">Solicitar Cita</a>
                                              </div>
                                            </div>
                                    </div>
                                </div> <!-- end of swiper-slide -->
                                <!-- end of slide -->
        
                                <!-- Slide -->
                                <div class="swiper-slide">
                                    <div class="card">
                                        <img class="card-image" src="../assets/testimonial-2.jpg" alt="alternative">
                                        <div class="card-body">
                                            <p class="testimonial-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, animi!</p>
                                            <p class="testimonial-author">José Navarro - Psicólogo</p>
                                        </div>
                                        <div id="divPadre">
                                            <div id="divHijo">
                                                <a href="#seccion-footer" class="btn-solid-reg">Solicitar Cita</a>
                                              </div>
                                            </div>
                                    </div>        
                                </div> <!-- end of swiper-slide -->
                                <!-- end of slide -->
        
                                <!-- Slide -->
                                <div class="swiper-slide">
                                    <div class="card">
                                        <img class="card-image" src="../assets/testimonial-3.jpg" alt="alternative">
                                        <div class="card-body">
                                            <p class="testimonial-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, animi!</p>
                                            <p class="testimonial-author">Isabel Díaz - Psicóloga</p>
                                        </div>
                                        <div id="divPadre">
                                            <div id="divHijo">
                                                <a href="#seccion-footer" class="btn-solid-reg">Solicitar Cita</a>
                                              </div>
                                            </div>
                                    </div>        
                                </div> <!-- end of swiper-slide -->
                                <!-- end of slide -->
        
                                <!-- Slide -->
                                <div class="swiper-slide">
                                    <div class="card">
                                        <img class="card-image" src="../assets/testimonial-4.jpg" alt="alternative">
                                        <div class="card-body">
                                            <p class="testimonial-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, animi!</p>
                                            <p class="testimonial-author">Segio Castillo - Psicólogo</p>
                                        </div>
                                        <div id="divPadre">
                                            <div id="divHijo">
                                                <a href="#seccion-footer" class="btn-solid-reg">Solicitar Cita</a>
                                              </div>
                                            </div>
                                    </div>
                                </div> <!-- end of swiper-slide -->
                                <!-- end of slide -->
        
                                <!-- Slide -->
                                <div class="swiper-slide">
                                    <div class="card">
                                        <img class="card-image" src="../assets/testimonial-5.jpg" alt="alternative">
                                        <div class="card-body">
                                            <p class="testimonial-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, animi!</p>
                                            <p class="testimonial-author">Laura Molina - Psicóloga</p>
                                        </div>
                                        <div id="divPadre">
                                            <div id="divHijo">
                                                <a href="#seccion-footer" class="btn-solid-reg">Solicitar Cita</a>
                                              </div>
                                            </div>
                                    </div>        
                                </div> <!-- end of swiper-slide -->
                                <!-- end of slide -->
        
                                <!-- Slide -->
                                <div class="swiper-slide">
                                    <div class="card">
                                        <img class="card-image" src="../assets/testimonial-6.jpg" alt="alternative">
                                        <div class="card-body">
                                            <p class="testimonial-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium, animi!</p>
                                            <p class="testimonial-author">Ann Gil - Psicóloga</p>
                                        </div>
                                        <div id="divPadre">
                                            <div id="divHijo">
                                                <a href="#seccion-footer" class="btn-solid-reg">Solicitar Cita</a>
                                              </div>
                                            </div>
                                    </div>       
                                </div> <!-- end of swiper-slide -->
                                <!-- end of slide -->
                            
                            </div> <!-- end of swiper-wrapper -->
        
                            <!-- Add Arrows -->
                            <div class="swiper-button-next"></div>
                            <div class="swiper-button-prev"></div>
                            <!-- end of add arrows -->
                        
                        </div> <!-- end of swiper-container -->
                    </div> <!-- end of slider-container -->
                    <!-- end of card slider -->
                </div> <!-- end of col -->
            </div> <!-- end of row -->
        </div> <!-- end of container -->
    </div> <!-- end of slider-1 -->
    <!-- end of testimonials -->
</template>

<style scoped>




/************************/
/*     Testimonials     */
/************************/
.slider-1 {
	padding-top: 9rem;
	padding-bottom: 11rem;
	background: url('../assets/testimonials-background.jpg') center bottom no-repeat;
	background-size: cover; 
}

.slider-1 .slider-container {
	position: relative;
}

.slider-1 .swiper-container {
	position: static;
	width: 88%;
	text-align: center;
}

.slider-1 .swiper-button-prev:focus,
.slider-1 .swiper-button-next:focus {
	/* even if you can't see it chrome you can see it on mobile device */
	outline: none;
	
}

.slider-1 .swiper-button-prev {
	left: -14px;
	background-image: url("data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%2028%2044'%3E%3Cpath%20d%3D'M0%2C22L22%2C0l2.1%2C2.1L4.2%2C22l19.9%2C19.9L22%2C44L0%2C22L0%2C22L0%2C22z'%20fill%3D'%23ffffff'%2F%3E%3C%2Fsvg%3E");
	background-size: 18px 28px;
}

.slider-1 .swiper-button-next {
	right: -14px;
	background-image: url("data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%2028%2044'%3E%3Cpath%20d%3D'M27%2C22L27%2C22L5%2C44l-2.1-2.1L22.8%2C22L2.9%2C2.1L5%2C0L27%2C22L27%2C22z'%20fill%3D'%23ffffff'%2F%3E%3C%2Fsvg%3E");
	background-size: 18px 28px;
}

.slider-1 .card {
	position: relative;
	border: none;
	background-color: transparent;
}

.slider-1 .card-image {
	width: 96px;
	height: 96px;
	margin-right: auto;
	margin-bottom: 1.5rem;
	margin-left: auto;
	border-radius: 50%;
}

.slider-1 .card-body {
	padding: 0;
}

.slider-1 .testimonial-text,
.slider-1 .testimonial-author {
	color: #ffffff;
}

.slider-1 .testimonial-author {
	margin-bottom: 0;
}

</style>

