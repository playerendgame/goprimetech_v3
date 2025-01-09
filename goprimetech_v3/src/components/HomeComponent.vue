<script setup>
import NavbarComponent from './NavbarComponent.vue';
</script>

<template>
    <!--Cover Section-->
    <div class="container-fluid" id="main-cover">
        <div class="overlay">
            <NavbarComponent class="navbar"/>

            <div class="container" style="padding-top: 5rem;;">
                <div class="row p-5" style="margin-top: 2rem;">
                    <span class="display-2">
                        <b>
                            <span>Elevating <span style="color:  greenyellow;">Lives,</span></span><br> 
                            <span>Empowering the</span><br>
                            <span >Future.</span>
                        </b>
                    </span>
                    <div class="buttons pt-3">
                        <button class="btn btn-success p-3">Contact Us!</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!--Section 2-->
    <div class="container pt-5">
        <div class="row d-flex justify-content-center">
            <div class="col-md-4">
                <div class="row">
                    <div class="d-flex align-items-center">
                        <svg style="margin-right: 20px;" xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="green" class="bi bi-telephone-fill mr-3" viewBox="0 0 16 16">
                            <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.68.68 0 0 0 .178.643l2.457 2.457a.68.68 0 0 0 .644.178l2.189-.547a1.75 1.75 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.6 18.6 0 0 1-7.01-4.42 18.6 18.6 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877z"/>
                        </svg>
                        <div>
                            <span><b>Contact Information:</b></span><br>
                            <span>Phone: (+63)998 961 0894</span><br>
                            <span>Email: admin@goprime.ph</span>

                        </div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="row">
                    <div class="d-flex align-items-center">
                        <svg style="margin-right: 20px;" xmlns="http://www.w3.org/2000/svg" width="60" height="60" fill="green" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
                            <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10m0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6"/>
                        </svg>
                        <div>
                            <span><b>Address:</b></span><br>
                            <span>2F, Earn Building, Alabang-Zapote Road, Pamplona Uno,Las Piñas, Philippines</span><br>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row" style="padding-top: 7rem;">
            <div class="row align-content-center align-items-center">
                <div class="col-md-6 w-50">
                    <video class="showCaseContainer rounded-4" width="100%" height="100%" autoplay muted loop>
                        <source src="../assets/images/showcaseVid.mp4">
                    </video>
                </div>
                <div class="col-md-6">
                    <div class="sectionContentCard card rounded-4">
                        <div class="sectionCard1 card-body rounded-4">
                            <div class="main-content text-center">
                                <span class="text-light h2"><b>GoPrime Technology Corp</b></span>
                                <p class="text-light">Your One-Stop Solution for Home and Commercial Needs</p>
                            </div>
                            <hr style="border-color: white; border-width: 3px;">                            
                            <div class="row align-content-center align-items-center pt-3">
                                <p class="text-light text-center">Over the past seven years, we’ve focused on delivering exceptional tech solutions, 
                                    building lasting relationships, and continuously evolving to meet the needs 
                                    of a fast-changing world. Together, we’ve achieved so much—and the best is yet to come.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!--Section 3-->
    <div class="container-fluid" style="padding-top: 7rem;">
        <div>
            <div class="rpw">
                <div class="col-md-6">
                    
                </div>
            </div>
        </div>
    </div>
</template>

