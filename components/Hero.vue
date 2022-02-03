<template>
    <div class="hero flex flex-col">
        <div class="container mx-auto">
            <Header />
        </div>

        <div class="container h-full mx-auto pl-20 my-auto">
            <div>
                <span class="hero__label">Careers</span>
                <h1 class="hero__title">Step into your future</h1>
                <p class="hero__text">Join our team as we continue building the world’s fastest growing SMS and AI messaging platform.</p>
                <a class="btn btn--lg btn--primary">View Open Roles</a>
            </div>
            <img class="hero__image" src="~/assets/images/hero-image.png">
        </div>
    </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>