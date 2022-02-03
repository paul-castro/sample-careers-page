<template>
    <div class="section section-overview">
        <div class="container section-overview__mission flex items-center justify-between mx-auto pl-20">
            <div class="w-1/2">
                <p class="section-overview__label">Our Mission</p>
                <h2 class="section-overview__title">We make business more human</h2>
                <div class="section-overview__description">
                    <p class="mb-39">Tech has and will continue to change the way we live. We embrace evolution and stay connected without losing the human element that makes communication so powerful.</p>
                    
                    <p>We envision a world in which businesses build lasting relationships with people through the power of conversation.</p>
                </div>
            </div>
            <div class="section-overview__images">
                <div class="section-overview__image">
                    <img src="~/assets/images/overview-img1.png">
                </div>
                <div class="section-overview__image">
                    <img src="~/assets/images/overview-img2.png">
                    <span class="section-overview__image-caption">Company Founders, Alex and Brad</span>
                </div>
            </div>
        </div>

        <div class="container section-overview__company flex items-center justify-between mx-auto pl-20 pr-20">

            <div class="section-overview__images">
                <div class="section-overview__image ml-75">
                    <img src="~/assets/images/overview-img3.png">
                </div>
                <div class="section-overview__image">
                    <img src="~/assets/images/overview-img4.png">
                </div>
            </div>

            <div class="w-1/2">
                <p class="section-overview__label">Our Company</p>
                <div class="section-overview__description">
                    <p class="mb-39">Burst SMS is a company that doesn’t stand still. We evolve everyday just as technology evolves, reward creative thinking, and value diversity in all its forms.</p>
                    
                    <p>We own 3 core messaging products which allows you the opportunity to evolve with us and take on a multifaceted role.</p>
                </div>
            </div>
        </div>

        <div class="container section-overview__staff flex items-center justify-between mx-auto pl-20 pr-20">
            <div class="section-overview__card staff-card flex flex-col justify-between items-center">
                <div class="flex flex-col items-center">
                    <h4 class="staff-card__title w-3/4">Global Flexibility</h4>
                    <p class="staff-card__description">This is a dummy text paragraph. Please copy and paste across the next 2 columns.</p>
                </div>
                <img src="~/assets/images/staff-img1.png" class="staff-card__image">
            </div>
            <div class="section-overview__card staff-card flex flex-col justify-between items-center">
                <div class="flex flex-col items-center">
                    <h4 class="staff-card__title w-3/4">Career Advancement</h4>
                    <p class="staff-card__description">This is a dummy text paragraph. Please copy and paste across the next 2 columns.</p>
                </div>
                <img src="~/assets/images/staff-img2.png" class="staff-card__image">
            </div>
            <div class="section-overview__card staff-card flex flex-col justify-between items-center">
                <div class="flex flex-col items-center">
                    <h4 class="staff-card__title w-3/4">Creating New Opportunities</h4>
                    <p class="staff-card__description">This is a dummy text paragraph. Please copy and paste across the next 2 columns.</p>
                </div>
                <img src="~/assets/images/staff-img3.png" class="staff-card__image">
            </div>
        </div>

        <div class="container section-overview__story mx-auto">
            <div class="story-card flex flex-col items-center">
                <img class="story-card__logo" src="~/assets/images/logo.svg" />
                <h1 class="story-card__title">Story</h1>
                <img class="story-card__bg" src="~/assets/images/staff-img4.png">
                <a class="story-card__btn btn btn--lg btn--primary">Read Our Story</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'SectionOverview'
}
</script>