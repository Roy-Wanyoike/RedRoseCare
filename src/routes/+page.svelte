<script>
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";

</script>

<Header></Header>

<main>
    <!-- Banner -->
    <section class="section image-infinite-bg position-relative"
        style="background-size: cover; background-position: center ;padding: 15em 1em 15em 1em;"
        data-images='["image/picture5.png" , "image/picture3.png"]'>
        <div class="r-container h-100">
            <div class="image-overlay"></div>
            <div class="d-flex flex-column justify-content-center gap-3 h-100 position-relative"
                style="max-width: 768px; z-index: 2;">
                <h1 class="text-title text-primary fw-bold font-5 lh-1">Red Rose Care Limited</h1>
                <p class="text-white f-18 text-font">Hello and welcome to your haven of health, Redrose care. Explore an innovative and 
                    comfortable digital world. Learn the skill of mindful living by immersing yourself in carefully chosen content. Your guide 
                    to a peaceful lifestyle, HomeCare Living offers everything from wellness advice to game-changing interior design concepts.
                     Set off on a journey where each click advances you toward transforming your house into a caring and motivating sanctuary. 
                     Rethink life with HomeCare Living, where your house is transformed into a meticulously crafted work of art."
 </p>
                <div class="text-center m-2">
                    <a type="button" href="/about"
                       class="btn bg-accent-color text-font text-white border rounded-0 m-2">LEARN MORE</a>
                    
                    <a type="button" href="/services"
                       class="btn bg-accent-color text-font border rounded-0 me-2">SERVICES</a>
                </div>
                
            </div>
        </div>
    </section>

    <section class="position-relative" style="margin-top: -80px;">
        <div class="r-container px-lg-0 px-4">
            <div class="overflow-hidden rounded-4">
                <div class="row row-cols-1 row-cols-lg-3">
                    <div class="col bg-accent-color-1 text-white">
                        <div class="d-flex flex-row gap-2 align-items-center  p-4">
                            <div class="rounded-circle bg-accent-color icon-box">
                                <i class="fa-solid fa-user-doctor"></i>
                            </div>
                            <div class="d-flex flex-column">
                                <span class="fw-bold font-1 text-primary fs-4">Our Services</span>
                                <span class="fw-bold font-1 fs-3 lh-1">
                                    Professional & Expert Nurses
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="col bg-accent-color text-white ">
                        <div class="d-flex flex-row gap-2 align-items-center  p-4">
                            <div class="rounded-circle bg-accent-color-2 icon-box">
                                <i class="fa-solid fa-stethoscope"></i>
                            </div>
                            <div class="d-flex flex-column">
                                <span class="fw-bold font-1 fs-4">Clinical Advice</span>
                                <span class="fw-bold font-1 fs-3 lh-1">
                                    Trusted Quality Care Solutions
                                </span>
                            </div>
                        </div>
                    </div>
                    <div class="col bg-accent-color-2 text-white">
                        <div class="d-flex flex-row gap-2 align-items-center  p-4">
                            <div class="rounded-circle bg-accent-color-1 icon-box">
                                <i class="fa-solid fa-earth-asia"></i>
                            </div>
                            <div class="d-flex flex-column">
                                <span class="fw-bold font-1 fs-4">Our Expertises</span>
                                <span class="fw-bold font-1 fs-3 lh-1">
                                    World Class Senior Services
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Welcome To Red Rose Care -->
    <section class="section">
        <div class="r-container">
            <div class="row row-cols-1 row-cols-lg-2">
                <div class="col mb-3 pe-lg-3 position-relative">
                    <div class="overlay right"></div>
                    <div class="position-relative pe-5">
                        <img src="image/image-600x700-1.jpg" alt="" class="img-fluid" style="z-index: -2;">
                        <div class="position-absolute bottom-0 start-0 ms-4 mb-4">
                            <div class="modal fade bg-overlay" id="exampleModal" tabindex="-1"
                                aria-labelledby="exampleModalLabel" aria-hidden="true">
                                <div class="modal-dialog modal-dialog-centered modal-lg">
                                
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col mb-3">
                    <div class="d-flex flex-column gap-3 p-3">
                        <h6 class="accent-color font-2 ">Welcome To Red Rose Care Limited</h6>
                        <h3 class="text-black font-1 lh-1 fw-semibold">See & Experience A New Perspective Of Life
                        </h3>
                        <p class="text-gray">
                            Discover a sanctuary of comfort at Red Rose Care Limited. Embrace a new life perspective with personalized care, tranquility, and rejuvenation. Our promises include;
                        </p>
                        <div class="row row-cols-2">
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="ri-check-double-fill"></i>
                                    <span class="text-gray">Tailored Comfort</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="ri-check-double-fill"></i>
                                    <span class="text-gray">Exceptional Care</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="ri-check-double-fill"></i>
                                    <span class="text-gray">Tranquil Living
                                    </span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="ri-check-double-fill"></i>
                                    <span class="text-gray">Rejuvenation Hub</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="ri-check-double-fill"></i>
                                    <span class="text-gray">Personalized Services</span>
                                </div>
                            </div>
                            <div class="col mb-2">
                                <div class="d-flex flex-row gap-2 align-items-center">
                                    <i class="ri-check-double-fill"></i>
                                    <span class="text-gray">Quality Lifestyle
                                    </span>
                                </div>
                            </div>
                        </div>
                        <div class="my-4 border-bottom w-100"></div>
                        <div class="row row-cols-1 row-cols-lg-2">
                            <div class="col mb-3">
                                <div
                                    class="d-flex flex-lg-row flex-column justify-content-lg-start align-items-center gap-2 justify-content-center">
                                    <div class="bg-accent-color text-white rounded-3 icon-box"
                                        style="font-size: 20px; width: 3rem; height: 3rem;">
                                        <i class="fa-solid fa-user-doctor"></i>
                                    </div>
                                    <span class="font-1 fs-3 lh-1 fw-semibold">Expert Nursing Staff</span>
                                </div>
                            </div>
                            <div class="col mb-3">
                                <div
                                    class="d-flex flex-lg-row flex-column justify-content-lg-start align-items-center gap-2 justify-content-center">
                                    <div class="bg-accent-color text-white rounded-3 icon-box"
                                        style="font-size: 20px; width: 3rem; height: 3rem;">
                                        <i class="fa-solid fa-house-medical-circle-check"></i>
                                    </div>
                                    <span class="font-1 fs-3 lh-1 fw-semibold">Safe Solution For Health</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Types Of Care -->
    <section class="section bg-light">
        
        <div class="r-container">
            <div class="d-flex flex-column gap-3 justify-content-center text-center">
                <h6 class="accent-color font-2 ">OUR SERVICES</h6>
                <h3 class="text-black font-1 lh-1 fw-semibold">Providing Quality Senior Care</h3>
                <p class="text-gray mx-auto" style="max-width: 768px;">
                    Homecare Limited, where a new perspective on life unfolds. Explore our diverse types of care, dedicated to providing quality senior living experiences with compassion, support, and excellence
                </p>
                <div class="row row-cols-1 row-cols-lg-3">
                    <div class="col">
                        <div class="card p-3 with-border-bottom border-0 shadow rounded-3">
                            <img src="image/picture11.png" class="card-img-top rounded-3" alt="...">
                            <div class="card-body ">
                                <h5 class="font-1 fw-bold">Live-in Care</h5>
                                <p class="text-gray">As viable alternative to residential care, live-in care is the perfect solution for round-the clock support in your own home</p>
                                <div class="d-flex justify-content-center">
                                    <a type="button" href="/"
                                        class="btn post-button font-2 d-flex flex-row align-items-center gap-2">Talk to us<i class="fa-solid fa-circle-arrow-right mt-1"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card p-3 with-border-bottom border-0 shadow rounded-3">
                            <img src="image/picture12.png" class="card-img-top rounded-3" alt="...">
                            <div class="card-body ">
                                <h5 class="font-1 fw-bold">Hourly visiting care</h5>
                                <p class="text-gray">From 30 minutes per week to regular visits throughout the day, visiting care provides the support you need, whenever you need it.</p>
                                <div class="d-flex justify-content-center">
                                    <a type="button" href="/"
                                        class="btn post-button font-2 d-flex flex-row align-items-center gap-2">Talk to us <i class="fa-solid fa-circle-arrow-right mt-1"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col">
                        <div class="card p-3 with-border-bottom border-0 shadow rounded-3">
                            <img src="image/picture13.png" class="card-img-top rounded-3" alt="...">
                            <div class="card-body ">
                                <h5 class="font-1 fw-bold">Dementia care</h5>
                                <p class="text-gray">As one of the UKs leading dementia home care providers, our dementia care provides specialist support to you and your family.</p>
                                <div class="d-flex justify-content-center">
                                    <a type="button" href="/"
                                        class="btn post-button font-2 d-flex flex-row align-items-center gap-2">Talk to us<i class="fa-solid fa-circle-arrow-right mt-1"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="d-flex justify-content-center my-4">
                    <a href="/services" type="button" class="btn bg-accent-color p-3 font-2">All Services</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Red Rose Care -->
    <section class="section">
        <div class="r-container">
            <div class="d-flex flex-lg-row flex-column-reverse">
                <div class="col mb-3">
                    <div class="d-flex flex-column gap-3 p-3 h-100 justify-content-center">
                        <h6 class="accent-color font-2 ">Why Choose Redrosscare ?</h6>
                        <h3 class="text-black font-1 lh-1 fw-bold">Our Heart Is Full Of Compassion For Your Care
                        </h3>
                        <div class="d-flex flex-lg-row flex-column">
                        
                            <div class="col col-lg-8">
                                <div class="d-flex flex-column ps-3">
                                    <p>
                                        Discover Redrosscare, where our compassion shapes superior care. Our heartfelt commitment is evident through:
                                    </p>
                                    <div class="d-flex flex-column gap-2">
                                        <div class="d-flex flex-row gap-2 align-items-center">
                                            <i class="fa-solid fa-square-check accent-color"></i>
                                            Personalized Attention
                                        </div>
                                        <div class="d-flex flex-row gap-2 align-items-center">
                                            <i class="fa-solid fa-square-check accent-color"></i>
                                            Expert Caregivers
                                        </div>
                                        <div class="d-flex flex-row gap-2 align-items-center">
                                            <i class="fa-solid fa-square-check accent-color"></i>
                                            Safe and Supportive Atmosphere
                                        </div>
                                        <div class="d-flex flex-row gap-2 align-items-center">
                                            <i class="fa-solid fa-square-check accent-color"></i>
                                            Community Integration
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col mb-5 pe-lg-3 position-relative">
                    <div class="overlay left"></div>
                    <div class="position-relative ps-5">
                        <img src="image/image-600x700-2.jpg" alt="" class="img-fluid rounded-3"
                            style="z-index: -2;">
                        <div class="position-absolute bottom-0 end-0 d-flex justify-content-end">
                            <div class=" bg-accent-color rounded-3 p-4 w-75" style="margin-bottom: -3rem;">
                                <h6 class="font-1 text-white fw-bold">The Patient Is First Priority In Our Passion
                                </h6>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="section pt-0">
        <div class="r-container">
            <div class="row row-cols-1 row-cols-lg-4">
                <div class="col">
                    <div
                        class="card with-border-bottom border-0 shadow d-flex flex-column justify-content-center  align-items-center p-2">
                        <h3 class="accent-color font-1 fw-bold lh-1">250+</h3>
                        <h5 class="font-1 fw-bold">Completed Cases</h5>
                    </div>
                </div>
                <div class="col">
                    <div
                        class="card with-border-bottom border-0 shadow d-flex flex-column justify-content-center  align-items-center p-2">
                        <h3 class="accent-color font-1 fw-bold lh-1">50+</h3>
                        <h5 class="font-1 fw-bold">Nursing Staff</h5>
                    </div>
                </div>
                <div class="col">
                    <div
                        class="card with-border-bottom border-0 shadow d-flex flex-column justify-content-center  align-items-center p-2">
                        <h3 class="accent-color font-1 fw-bold lh-1">20+</h3>
                        <h5 class="font-1 fw-bold">Senior Doctors</h5>
                    </div>
                </div>
                <div class="col">
                    <div
                        class="card with-border-bottom border-0 shadow d-flex flex-column justify-content-center  align-items-center p-2">
                        <h3 class="accent-color font-1 fw-bold lh-1">200+</h3>
                        <h5 class="font-1 fw-bold">Happy Couples</h5>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- We Care With Compassion -->
    <section class="position-relative" style="background-image: url(image/image-1920x900-6.jpg);">
        <div class="r-container">
            <div class="image-overlay"></div>
            <div class="d-flex flex-column justify-content-center align-items-center text-center position-relative gap-3"
                style="z-index: 2; min-height: 70vh;">
                <div>
                    <!-- Button trigger modal -->
                    <div class="d-flex flex-row gap-3 align-items-center">
                        <button type="button" class="btn request-loader" data-bs-toggle="modal"
                            data-bs-target="#videomodal">
                            <i class="fa-solid fa-play"></i>
                        </button>
                    </div>
                </div>
                <h4 class="font-1 text-white fw-bold">ElderJoy Haven Care</h4>
                <p class="text-white" style="max-width: 768px;">
                    At Redrosscare, we go beyond healthcare, creating a thriving environment for the elderly. Our personalized care, compassionate professionals, and focus on holistic well-being redefine senior living, fostering comfort, dignity, and joy.
                </p>
            </div>
        </div>
    
    </section>

    <!-- What They Say ? -->
    <section class="section pt-0 position-relative" style="margin-top: -100px;">
        <div class="r-container">
            <div class="overflow-hidden rounded-4">
                <div class="row row-cols-1 row-cols-lg-2">
                    <div class="col bg-accent-color text-white ">
                        <div class="d-flex flex-column gap-3 p-5 h-100 justify-content-center">
                            <h6 class="font-2 ">What They Say ?</h6>
                            <h3 class="font-1 lh-1 fw-bold fs-1">Nurturing Lives, Enriching Souls: Redrosscare, Where Compassion Meets Comfort.</h3>
                            <p class="fs-6">
                                To be the beacon of compassionate care, fostering a world where every elderly individual experiences a life of dignity, joy, and wellness through our dedicated support at Redrosscare.
                            </p>
                            <div>
                                <a href="/contact" type="button" class="btn bg-accent-color-1 p-3">Contact Us</a>
                            </div>
                        </div>
                    </div>
                    <div class="col bg-light text-white">
                        <div class="overflow-hidden h-100 d-flex align-items-center">
                            <div class="swiper">
                                <!-- Additional required wrapper -->
                                <div class="swiper-wrapper">
                                    <!-- Slides -->
                                    <div class="swiper-slide">
                                        <div class="d-flex flex-column gap-3 p-4 text-black">
                                            <ul class="d-flex flex-row gap-2 p-0 m-0 text-warning"
                                                style="list-style: none;">
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                            </ul>
                                            <p class="text-black">Nursing for the elderly at home is not just a duty; it's a privilege. It's about bringing comfort, kindness, and a healing touch to those who deserve the warmth of care in the golden chapters of their lives.
                                            </p>
                                            <div class="d-flex justify-content-between">
                                                <div class="d-flex flex-row gap-3">
                                                    <img src="image/image-400x400-1.jpg" alt=""
                                                        class="img-fluid rounded-circle" width="70" height="70">
                                                    <div class="d-flex flex-column h-100 justify-content-center">
                                                        <span class="text-black">Elsa Verina</span>
                                                        <span class="text-gray">Designation</span>
                                                    </div>
                                                </div>
                                                <div class="accent-color" style="font-size: 3rem;">
                                                    <i class="fa-solid fa-quote-right"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="swiper-slide">
                                        <div class="d-flex flex-column gap-3 p-4 text-black">
                                            <ul class="d-flex flex-row gap-2 p-0 m-0 text-warning"
                                                style="list-style: none;">
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                            </ul>
                                            <p>At home, nursing for the elderly is a tapestry of love, woven with skill and compassion.
                                            </p>
                                            <div class="d-flex justify-content-between">
                                                <div class="d-flex flex-row gap-3">
                                                    <img src="image/image-400x400-2.jpg" alt=""
                                                        class="img-fluid rounded-circle" width="70" height="70">
                                                    <div class="d-flex flex-column h-100 justify-content-center">
                                                        <span class="text-black">Florence Nightingale</span>
                                                        <span class="text-gray">Designation</span>
                                                    </div>
                                                </div>
                                                <div class="accent-color" style="font-size: 3rem;">
                                                    <i class="fa-solid fa-quote-right"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="swiper-slide">
                                        <div class="d-flex flex-column gap-3 p-4 text-black">
                                            <ul class="d-flex flex-row gap-2 p-0 m-0 text-warning"
                                                style="list-style: none;">
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                                <li><i class="fa-solid fa-star"></i></li>
                                            </ul>
                                            <p>Providing home-based care for the elderly is an art, where love and healing intertwine seamlessly.
                                            </p>
                                            <div class="d-flex justify-content-between">
                                                <div class="d-flex flex-row gap-3">
                                                    <img src="image/image-400x400-3.jpg" alt=""
                                                        class="img-fluid rounded-circle" width="70" height="70">
                                                    <div class="d-flex flex-column h-100 justify-content-center">
                                                        <span class="text-black"> Mary Seacole</span>
                                                        <span class="text-gray">Designation</span>
                                                    </div>
                                                </div>
                                                <div class="accent-color" style="font-size: 3rem;">
                                                    <i class="fa-solid fa-quote-right"></i>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <!-- If we need pagination -->
                                <div class="swiper-pagination"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Work ? -->
    <section class="section text-secondary">
        <div class="r-container">
            <div class="row row-cols-1 row-cols-lg-2">
                <div class="col mb-3">
                    <div class="d-flex flex-column gap-3 h-100 justify-content-center">
                        <h6 class="font-2 accent-color">How It Work ?</h6>
                        <h3 class="font-1 lh-1 fw-bold fs-1 mb-3">The Amazing Steps Of Our Treatment</h3>
                        <div class="d-flex flex-column gap-5">
                            <div class="d-flex flex-row gap-3 align-items-center">
                                <div class="bg-accent-color rounded-3 py-2 px-4 text-white">
                                    <h4 class="lh-1 m-0 p-0 fw-bold font-1">1</h4>
                                </div>
                                <div class="d-flex flex-column">
                                    <h5 class="font-1 fw-bold lh-1 m-0">
                                        Book Your Appointment
                                    </h5>
                                    <p class="text-gray m-0">
                                        Experience ease and care. Book an appointment at Redrosscare for personalized, compassionate, and dignified elder services.
                                    </p>
                                </div>
                            </div>
                            <div class="d-flex flex-row gap-3 align-items-center">
                                <div class="bg-accent-color rounded-3 py-2 px-4 text-white">
                                    <h4 class="lh-1 m-0 p-0 fw-bold font-1">2</h4>
                                </div>
                                <div class="d-flex flex-column">
                                    <h5 class="font-1 fw-bold lh-1 m-0">
                                        In Person Counselling
                                    </h5>
                                    <p class="text-gray m-0">
                                        Find solace in home. In-person counseling at Redrosscare offers personalized support for emotional well-being.
                                    </p>
                                </div>
                            </div>
                            <div class="d-flex flex-row gap-3 align-items-center">
                                <div class="bg-accent-color rounded-3 py-2 px-4 text-white">
                                    <h4 class="lh-1 m-0 p-0 fw-bold font-1">3</h4>
                                </div>
                                <div class="d-flex flex-column">
                                    <h5 class="font-1 fw-bold lh-1 m-0">
                                        Weekly Followup
                                    </h5>
                                    <p class="text-gray m-0">
                                        Stay connected with Redrosscare. Weekly follow-ups ensure ongoing care and well-being for a brighter tomorrow.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col mb-3">
                    <div class="bg-accent-color rounded-4">
                        <div class="h-100 d-flex flex-column p-5">
                            <h6 class="font-2 text-white">Fill The Form</h6>
                            <h3 class="font-1 lh-1 fw-bold fs-1 mb-3 text-white">Get In Touch</h3>
                            <div class="success_msg toast align-items-center w-100 shadow-none mb-3 border border-success rounded-0 my-4"
                                role="alert" aria-live="assertive" aria-atomic="true">
                                <div class="d-flex p-2">
                                    <div
                                        class="toast-body f-18 d-flex flex-row gap-3 align-items-center text-success">
                                        <i class="fa-solid fa-check f-36 text-success"></i>
                                        Your Message Successfully Send.
                                    </div>
                                    <button type="button"
                                        class="me-2 m-auto bg-transparent border-0 ps-1 pe-0 text-success"
                                        data-bs-dismiss="toast" aria-label="Close"><i
                                            class="fa-solid fa-xmark"></i></button>
                                </div>
                            </div>
                            <div class="error_msg toast align-items-center w-100 shadow-none border-danger mb-3 my-4 border rounded-0"
                                role="alert" aria-live="assertive" aria-atomic="true">
                                <div class="d-flex p-2">
                                    <div
                                        class="toast-body f-18 d-flex flex-row gap-3 align-items-center text-danger">
                                        <i class="fa-solid fa-triangle-exclamation f-36 text-danger"></i>
                                        Something Wrong ! Send Form Failed.
                                    </div>
                                    <button type="button"
                                        class="me-2 m-auto bg-transparent border-0 ps-1 pe-0 text-danger"
                                        data-bs-dismiss="toast" aria-label="Close"><i
                                            class="fa-solid fa-xmark"></i></button>
                                </div>
                            </div>
                            <form action="#"
                                class="d-flex flex-column h-100 justify-content-center w-100 needs-validation mb-3 form"
                                novalidate>
                                <div class="mb-3">
                                    <input type="text" class="form-control py-2 px-4" name="name" id="name"
                                        placeholder="Name" required>
                                    <div class="invalid-feedback">
                                        The field is required.
                                    </div>
                                </div>
                                <div class="mb-3">
                                    <input type="email" class="form-control py-2 px-4" name="email" id="email"
                                        placeholder="Email" required>
                                    <div class="invalid-feedback">
                                        The field is required.
                                    </div>
                                </div>
                                <div class="mb-3">
                                    <input type="text" class="form-control py-2 px-4" name="subject" id="subject"
                                        placeholder="Subject" required>
                                    <div class="invalid-feedback">
                                        The field is required.
                                    </div>
                                </div>
                                <div class="mb-3">
                                    <textarea class="form-control py-2 px-4" id="message" name="message" rows="5"
                                        placeholder="Message"></textarea>
                                </div>
                                <div class="mb-3">
                                    <button type="submit" class="btn submit_form py-3">
                                        Send Message
                                    </button>
                                </div>
                            </form>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</main>
<Footer></Footer>