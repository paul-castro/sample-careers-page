<template>
    <div class="header flex flex-row items-center">
        <img class="header__logo" src="~/assets/images/logo.svg" />
        <div class="header__navbar flex w-full justify-between">
            <ul class="nav flex justify-between items-center mx-34">
                <li class="nav__item"><a href="">Products</a></li>
                <li class="nav__item"><a href="">Solutions</a></li>
                <li class="nav__item"><a href="">Partners</a></li>
                <li class="nav__item"><a href="">Pricing</a></li>
                <li class="nav__item"><a href="">Support</a></li>
            </ul>
            <div class="flex justify-between">
                <a class="btn btn--sm btn--secondary" href="">Sign Up</a>
                <a class="btn btn--sm btn--default ml-25" href="">Login</a>
                <a class="country-picker">
                    <img class="country-picker__icon" src="~/assets/images/icon-flag.svg" />
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>