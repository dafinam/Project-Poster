<template>
  <div>
    <!-- Preloader-content -->
    <div class="preloader">
    </div>
    <!-- MainMenu-Area -->
    <nav class="mainmenu-area" data-spy="affix" data-offset-top="200">
        <div class="container-fluid">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#primary_menu">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                <a class="navbar-brand icon-txt" href="#">YUPAA</a>
            </div>
            <div class="collapse navbar-collapse" id="primary_menu">
                <ul class="nav navbar-nav mainmenu">
                    <li class="active"><a href="#home_page">Home</a></li>
                    <li><a href="#about_page">About</a></li>
                    <li><a href="#features_page">Features</a></li>
                    <li><a href="#gallery_page">Gallery</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- MainMenu-Area-End -->
    <!-- Home-Area -->
    <header class="home-area overlay" id="home_page">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 hidden-sm col-md-5">
                    <figure class="mobile-image wow fadeInUp" data-wow-delay="0.2s">
                        <img src="images/MainScreen.png" alt="">
                    </figure>
                </div>
                <div class="col-xs-12 col-md-7">
                    <div class="space-80 hidden-xs"></div>
                    <h1 class="wow fadeInUp" data-wow-delay="0.4s">Your personal activity app.</h1>
                    <div class="space-20"></div>
                    <div class="desc wow fadeInUp" data-wow-delay="0.6s">
                        <p>Welcome to Yupaa! An application that will help people manage their time by promoting activities and goals in a fun and socially interactive way.</p>
                    </div>
                    <div class="space-20"></div>
                </div>
            </div>
        </div>
    </header>
    <!-- Home-Area-End -->
    <!-- About-Area -->
    <section class="section-padding" id="about_page">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-md-10 col-md-offset-1">
                    <div class="page-title text-center">
                        <div class="space-20"></div>
                        <h5 class="title">About Yupaa</h5>
                        <div class="space-30"></div>
                        <h3 class="blue-color">A beautiful application designed and developed with care and targeted for all user groups that want to take more control over their activities, goals and achievements.
                        </h3>
                        <div class="space-20"></div>
                        <p>Yupaa is an application values efficiency and completeness while engaging users during their daily activities by enforcing social interaction such as sharing their activities, goals, streaks and many more.
                            We believe that doing activities, achiving goals and reaching milestones is sometimes done best by sharing it with peers which enforce motivation and encuragement.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- About-Area-End -->
    <!-- Progress-Area -->
    <section class="progress-area gray-bg" id="progress_page">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-md-6">
                    <div class="page-title section-padding">
                        <h5 class="title wow fadeInUp" data-wow-delay="0.2s">Our Goal</h5>
                        <div class="space-10"></div>
                        <h3 class="dark-color wow fadeInUp" data-wow-delay="0.4s">A fun, engaing and helpful app</h3>
                        <div class="space-20"></div>
                        <div class="desc wow fadeInUp" data-wow-delay="0.6s">
                            <p>
                                <strong>Have you ever downloaded an app that promotes helath activities, improving productivity and mnaging your free time by doing things better?</strong>
                                <br>
                                Studies show that a very small percentage of users tend to keep using these kind of apps after the first couple of weeks despite the benefits. Out intention is to leverage the same principle
                                but in addition to focusing about productivity, health, and managing free time, we also tried to make enforce the social factor which other apps usually lack.
                            </p>
                        </div>
                        <div class="space-50"></div>
                    </div>
                </div>
                <div class="col-xs-12 col-md-6">
                    <figure class="mobile-image">
                        <img src="images/SocialFeed.png" alt="">
                    </figure>
                </div>
            </div>
        </div>
    </section>
    <!-- Progress-Area-End -->
    <!-- Feature-Area -->
    <section class="feature-area section-padding-top" id="features_page">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-sm-8 col-sm-offset-2">
                    <div class="page-title text-center">
                        <h5 class="title">Features</h5>
                        <div class="space-10"></div>
                        <h3>Powerful &amp; Engaging Features</h3>
                        <div class="space-60"></div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-12 col-sm-6 col-md-4">
                    <div class="service-box wow fadeInUp" data-wow-delay="0.2s">
                        <h4>Variaty of Activities</h4>
                        <p>Select from a variaty of activities to manage. Or create your own!</p>
                    </div>
                    <div class="space-60"></div>
                    <div class="service-box wow fadeInUp" data-wow-delay="0.4s">
                        <h4>Clean User Interface</h4>
                        <p>Yupaa app has been designed with a minimalistic design approach with makes it beautiful and elegant</p>
                    </div>
                    <div class="space-60"></div>
                    <div class="service-box wow fadeInUp" data-wow-delay="0.6s">
                        <h4>Social Circle</h4>
                        <p>Share your activities, workout plans, reached streaks with your peers.</p>
                    </div>
                    <div class="space-60"></div>
                </div>
                <div class="hidden-xs hidden-sm col-md-4">
                    <figure class="mobile-image">
                        <img src="images/NewActivity.png" alt="Feature Photo">
                    </figure>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4">
                    <div class="service-box wow fadeInUp" data-wow-delay="0.2s">
                        <h4>Goals</h4>
                        <p>Setup new goals to complete and motivate yourself while yupaa notifies on goal progress.</p>
                    </div>
                    <div class="space-60"></div>
                    <div class="service-box wow fadeInUp" data-wow-delay="0.4s">
                        <h4>Notifications</h4>
                        <p>Never miss a scheduled activity with Yupaa's notification system.</p>
                    </div>
                    <div class="space-60"></div>
                    <div class="service-box wow fadeInUp" data-wow-delay="0.6s">
                        <h4>Cross Platform App</h4>
                        <p>Developed with latest cross platform tech, yuppa is available for iOS and Android</p>
                    </div>
                    <div class="space-60"></div>
                </div>
            </div>
        </div>
    </section>
    <!-- Feature-Area-End -->
    <!-- Gallery-Area -->
    <section class="gallery-area section-padding" id="gallery_page">
        <div class="container-fluid">
            <div class="row">
                <div class="col-xs-12 col-sm-8 col-sm-offset-2">
                    <div class="page-title text-center">
                        <h5 class="white-color title fadeInUp" data-wow-delay="0.2s">Screenshots</h5>
                        <div class="space-10"></div>
                    </div>
                    <div class="space-20"></div>
                    <div class="desc wow fadeInUp" data-wow-delay="0.6s">
                        <p>Screenshot from the iOS Yupaa Application</p>
                    </div>
                    <div class="space-50"></div>
                </div>
            </div>
            <div class="row">
                <div class="w3-content w3-display-container" style="max-width:800px">
                    <img v-for="item in images" v-bind:key="item" class="mySlides" :src="item" >
                    <div class="w3-center w3-container w3-section w3-large w3-text-white w3-display-bottommiddle" style="width:100%">
                        <div class="w3-left w3-hover-text-khaki" @click="plusDivs(-1)">&#10094;</div>
                        <div class="w3-right w3-hover-text-khaki" @click="plusDivs(1)">&#10095;</div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Gallery-Area-End -->
    <!-- Download-Area -->
    <div class="download-area overlay">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-sm-6 hidden-sm">
                    <figure class="mobile-image">
                        <img src="images/Activity-Streak.png" alt="">
                    </figure>
                </div>
                <div class="col-xs-12 col-md-6 section-padding">
                    <h3 class="white-color">Soon available for download</h3>
                    <div class="space-20"></div>
                    <p>The app will be available as both iOS and Android application with fully functional features</p>
                    <div class="space-60"></div>
                    <a href="javascript:void(0)" class="bttn-white sq"><img src="images/apple-icon.png" alt="apple icon"> Apple Store</a>
                    <a href="javascript:void(0)" class="bttn-white sq"><img src="images/play-store-icon.png" alt="Play Store Icon"> Play Store</a>
                </div>
            </div>
        </div>
    </div>
    <!-- Download-Area-End -->
    <!--Vendor-JS-->
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {
    slideIndex: number = 1;
    images: Array<string> = [
        "images/Gallery1.png",
        "images/Gallery2.png",
        "images/Gallery3.png",
        "images/Gallery4.png",
        "images/Gallery5.png",
        "images/Gallery6.png",
        "images/Gallery7.png",
        "images/Gallery8.png",
        "images/Gallery9.png",
    ];
    
    mounted () {
        this.showDivs(this.slideIndex)
    }

    plusDivs(n: number) {
        this.showDivs(this.slideIndex += n);
    }

    currentDiv(n: number) {
        this.showDivs(this.slideIndex = n);
    }

    showDivs(n: number) {
        var i;
        var x = document.getElementsByClassName("mySlides");
        if (n > x.length) {this.slideIndex = 1}
        if (n < 1) {this.slideIndex = x.length}
        for (i = 0; i < x.length; i++) {
            // @ts-ignore
            x[i].style.display = "none";  
        }
        // @ts-ignore
        x[this.slideIndex-1].style.display = "block";
    }

    // carousel() {
    //     var i;
    //     var x = document.getElementsByClassName("mySlides");
    //     console.log('Slides: ', x.length);
    //     for (i = 0; i < x.length; i++) {
    //         x[i].style.display = "none";  
    //     }
    //     this.slideIndex += 1;
    //     if (this.slideIndex > x.length) {this.slideIndex = 1}
    //     x[this.slideIndex-1].style.display = "block";
    //     setTimeout(this.carousel, 4000);
    // }
}
</script>
