# IP-DEV
ui programmer

<html lang="en" xmlns="http://www.w3.org/1999/html"> <!--<![endif]-->


<body class="home-page">
<div class="wrapper">
<!-- ******HEADER****** -->

<!--//header-->

<!-- ******NAV****** -->
<?php include 'header.php'; ?>
<!--//main-nav-->

<!-- ******CONTENT****** -->
<div class="content container">
<div id="promo-slider" class="slider flexslider">
    <ul class="slides">
        <li>
            <img src="assets/images/slides/slide-1.jpg" alt="Html5,CSS3,Javascript"/>

            <p class="flex-caption">
                <span class="main">HTML5, CSS3, Javascript</span>
                <br>
                <span class="secondary clearfix">Learning tomorrows standards today...</span>
            </p>
        </li>
        <li>
            <img src="assets/images/slides/slide-2.jpg" alt="Bootstrap,JQuery,PhoneGap"/>

            <p class="flex-caption">
                <span class="main">Bootstrap, JQuery, PhoneGap</span>
                <br>
                <span class="secondary clearfix">Interactive front end development, web and mobile...</span>
            </p>
        </li>
        <li>
            <img src="assets/images/slides/slide-3.jpg" alt=""/>

            <p class="flex-caption">
                <span class="main">AngularJS, EmberJS, BackboneJS</span>
                <br>
                <span class="secondary clearfix">Single Page Applications and MVC...</span>
            </p>
        </li>
        <li>
            <img src="assets/images/slides/slide-4.jpg" alt=""/>

            <p class="flex-caption">
                <span class="main">NodeJS, MongoDB</span>
                <br>
                <span class="secondary clearfix">Server side javascript, the future...</span>
            </p>
        </li>
    </ul>
    <!--//slides-->
</div>
<!--//promo-->
<section class="news">
    <h1 class="section-heading text-highlight"><span class="line">Latest News</span></h1>

    <div class="carousel-controls">
        <a class="prev" href="#news-carousel" data-slide="prev"><i class="fa fa-caret-left"></i></a>
        <a class="next" href="#news-carousel" data-slide="next"><i class="fa fa-caret-right"></i></a>
    </div>
    <!--//carousel-controls-->
    <div class="section-content clearfix">
        <div id="news-carousel" class="news-carousel carousel slide">
            <div class="carousel-inner">
                <div class="item active">
                    <div class=news-item">
                                <span>Rekha got placed in Intel, Santa Clara, CA. Srividya got placed in
                                    Macy's, SFO, CA. Ram got placed in Capital One, Northern VA, VA.</span>
                    </div>
                </div>
                <!--//item-->
                <div class="item">
                    <div class=news-item">
                        <span><strong>FrisbyJS</strong> is added to the coursework. Frisby is a REST API testing framework built on node.js and Jasmine that makes testing API endpoints easy, fast, and fun.</span>
                    </div>
                </div>
                <!--//item-->
            </div>
            <!--//carousel-inner-->
        </div>
        <!--//news-carousel-->
    </div>
    <!--//section-content-->
</section>
<!--//news-->
<!--//flexslider-->
<section class="promo box box-dark">
    <div class="col-md-9">
        <h1 class="section-heading">Why UI Course?</h1>

        <p>We train front end developer/designer for web and mobile
            applications using HTML5, CSS3, Bootstrap, Javascript and JQuery, application developers to use MVC
            tools AngularJS and Javascript libraries, and Server-Side developers using NodeJS and MongoDB.</p>
    </div>
    <div class="col-md-3">
        <a class="btn btn-cta" href="contact.html"><i class="fa fa-play-circle"></i>Enroll Now</a>
    </div>
</section>

<div class="row cols-wrapper">
    <div class="col-md-3">
        <section class="events">
            <h1 class="section-heading text-highlight"><span class="line">Recent Classes</span></h1>

            <div class="section-content">

                <div class="event-item">
                    <p class="date-label">
                        <span class="month">Apr</span>
                        <span class="date-number">21</span>

                    </p>

                    <div class="details">
                        <h2 class="title"><a
                                href="login.html">
                                Apr 21, 2015 MongoDb CRUD operations</a></h2>

                    </div>
                    <!--//details-->
                </div>
                <!--event-item-->

                <div class="event-item">
                    <p class="date-label">
                        <span class="month">Apr</span>
                        <span class="date-number">20</span>

                    </p>

                    <div class="details">
                        <h2 class="title"><a
                                href="login.html">
                                UI Apr 19,2015 HTML5 API - Video, Forms</a></h2>

                    </div>
                    <!--//details-->
                </div>
                <!--event-item-->

                <div class="event-item">
                    <p class="date-label">
                        <span class="month">Apr</span>
                        <span class="date-number">14</span>

                    </p>

                    <div class="details">
                        <h2 class="title"><a
                                href="login.html">
                                Apr 14, 2015 UI MongoDb Intro</a></h2>

                    </div>
                    <!--//details-->
                </div>
                <!--event-item-->

                <div class="event-item">
                    <p class="date-label">
                        <span class="month">Apr</span>
                        <span class="date-number">12</span>

                    </p>

                    <div class="details">
                        <h2 class="title"><a
                                href="login.html">
                                UI HTML5 Semantics</a></h2>

                    </div>
                    <!--//details-->
                </div>
                <!--event-item-->

                <a href="login.html" class="read-more">Recordings<i class="fa fa-chevron-right"></i></a>
            </div>
            <!--//section-content-->
        </section>
        <!--//events-->
    </div>
    <!--//col-md-3-->
    <div class="col-md-6">
        <!--//course-finder-->
        <section class="video">
            <h1 class="section-heading text-highlight"><span class="line">Video Tour</span></h1>

            <div class="carousel-controls">
                <a class="prev" href="#videos-carousel" data-slide="prev"><i class="fa fa-caret-left"></i></a>
                <a class="next" href="#videos-carousel" data-slide="next"><i class="fa fa-caret-right"></i></a>
            </div>
            <!--//carousel-controls-->
            <div class="section-content">
                <div id="videos-carousel" class="videos-carousel carousel slide">
                    <div class="carousel-inner">
                        <div class="item active">
                            <iframe class="video-iframe"
                                    src="//www.youtube.com/embed/YAVqIzhPYeU?rel=0&amp;wmode=transparent"
                                    frameborder="0" allowfullscreen=""></iframe>
                        </div>
                        <!--//item-->
                        <div class="item">
                            <iframe class="video-iframe"
                                    src="//www.youtube.com/embed/1ltXZk2OFNs?rel=0&amp;wmode=transparent"
                                    frameborder="0" allowfullscreen=""></iframe>
                        </div>
                        <!--//item-->
                        <div class="item">
                            <iframe class="video-iframe"
                                    src="//www.youtube.com/embed/XR6YKYCQ5rA?rel=0&amp;wmode=transparent"
                                    frameborder="0" allowfullscreen=""></iframe>
                        </div>
                        <!--//item-->
                    </div>
                    <!--//carousel-inner-->
                </div>
                <!--//videos-carousel-->
                <p class="description">Get access to the excellent training portal with thousands of recorded
                    tutorials, classes and much more by joining our program.</p>
            </div>
            <!--//section-content-->
        </section>
        <!--//video-->
    </div>
    <div class="col-md-3">
        <!--//links-->
        <section class="testimonials">
            <h1 class="section-heading text-highlight"><span class="line"> Testimonials</span></h1>

            <div class="carousel-controls">
                <a class="prev" href="#testimonials-carousel" data-slide="prev"><i class="fa fa-caret-left"></i></a>
                <a class="next" href="#testimonials-carousel" data-slide="next"><i
                        class="fa fa-caret-right"></i></a>
            </div>
            <!--//carousel-controls-->
            <div class="section-content">
                <div id="testimonials-carousel" class="testimonials-carousel carousel slide">
                    <div class="carousel-inner">
                        <div class="item active">
                            <blockquote class="quote">
                                <p><i class="fa fa-quote-left"></i>Training was excellent. Learned a lot of new
                                    topics in testing, Selenium and SOAP UI. Since I knew Java and SQL before,
                                    the training pace was good and I was able to keep up with learning new
                                    topics. I also liked working with Venkatesh during training and Reena after
                                    training (mainly in interview preparations). They were very helpful. Sampath
                                    and Shilpi have good knowledge and their training has helped me a lot.
                                    Overall, the training is EXCELLENT...</p>
                            </blockquote>
                            <div class="row">
                                <p class="people col-md-8 col-sm-3 col-xs-8"><span class="name">Rupa Atre</span><br/><span
                                        class="title">Yapstone</span></p>

                            </div>
                        </div>
                        <!--//item-->
                        <div class="item">
                            <blockquote class="quote">
                                <p><i class="fa fa-quote-left"></i>
                                    The training itself is great, short term and precise. The amount of
                                    knowledge we gain in that period of time is life changing..

                                </p>
                            </blockquote>
                            <div class="row">
                                <p class="people col-md-8 col-sm-3 col-xs-8"><span
                                        class="name">Arti Sharma</span><br/><span
                                        class="title">Bank Of West</span></p>

                            </div>
                        </div>
                        <!--//item-->
                        <div class="item">
                            <blockquote class="quote">
                                <p><i class="fa fa-quote-left"></i>
                                    I want to take the time and thank both of you for believing in me, that I
                                    can do it while I was going through the ups and downs of the marketing
                                    phase. You have been there through out the whole process motivating and
                                    encouraging me. I have learnt not only technical skills but also how to stay
                                    positive at all times from you. Both of you are a great team and mentors and
                                    that is what makes Innovapath such a wonderful company. Now just hoping to
                                    establish myself in this whole new career world of QA.!!!!</p>
                            </blockquote>
                            <div class="row">
                                <p class="people col-md-8 col-sm-3 col-xs-8"><span
                                        class="name">Lakshmi Vijayan</span><br/><span
                                        class="title"> Walmart</span></p>
                            </div>
                        </div>
                        <!--//item-->

                    </div>
                    <!--//carousel-inner-->
                </div>
                <!--//testimonials-carousel-->
            </div>
            <!--//section-content-->
        </section>
        <!--//testimonials-->
    </div>
    <!--//col-md-3-->
</div>
<!--//cols-wrapper-->

</div>
<!--//content-->
</div>
<!--//wrapper-->

<!-- ******FOOTER****** -->

<?php include 'footer.php'; ?>
<!--//footer-->

<!-- *****CONFIGURE STYLE****** -->


</body>
9052580838
</html>
