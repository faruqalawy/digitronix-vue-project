<template>
  <div
    class="w-full"
    :style="{
      backgroundImage: `linear-gradient(to bottom, rgba(241, 241, 241, 1) 0%, rgba(241, 241, 241, 0) 80%), 
                        linear-gradient(to right, rgba(241, 241, 241, 1) 0%, rgba(241, 241, 241, 0) 85%),
                        url(https://res.cloudinary.com/dnwvsqlh1/image/upload/f_auto,q_auto/v1/digitronix/home-hero-background)`,
      backgroundSize: 'cover',
      backgroundPosition: 'center'
    }"
  >
    <div class="grid grid-cols-4 custom-display">
      <div class="col-span-4 lg:col-span-3 text-darkBlue my-8 md:my-20 lg:my-32">
        <h3 class="md:text-h2 lg:text-5xl">
          Where Innovation Meet <br />
          Affordability, Get All Your <br />
          Favourite Items Here
        </h3>
        <h3 class="text-h5 md:text-h4 lg:text-h2 font-light lg:my-3">Smart Choices for Smart Living</h3>
        <a href="#categories">
          <button
            type="button"
            class="text-white bg-brightYellow py-2 lg:py-3 px-8 lg:px-14 rounded-full md:text-h4 lg:text-h3 font-normal mt-2"
          >
            Shop Now
          </button>
        </a>
      </div>
    </div>
  </div>
</template>
