<template>
  <section
    class="relative bg-white overflow-hidden"
    :style="{
      backgroundImage: 'url(/src/assets/svg/pattern-white.svg)',
      backgroundPosition: 'center',
    }"
  >
    <div class="py-20 md:py-28">
      <div class="container px-4 mx-auto">
        <div class="flex justify-center flex-wrap xl:items-center -mx-4">
          <div class="w-full md:w-1/2 px-4 mb-16 md:mb-0">
            <span
              class="inline-block py-px px-2 mb-4 text-xs leading-5 text-white bg-violet-500 uppercase rounded-9xl"
            >
              Product
            </span>
            <h1
              class="mb-6 text-3xl md:text-5xl lg:text-6xl leading-tight font-bold tracking-tight"
            >
              A small business is only as good as its tools.
            </h1>
            <p class="mb-8 text-lg md:text-xl text-coolGray-500 font-medium">
              We’re different. Flex is the only saas business platform that lets
              you run your business on one platform, seamlessly across all
              digital channels.
            </p>
            <div class="flex flex-wrap justify-center">
              <div class="w-full md:w-auto py-1 md:py-0 md:mr-4">
                <a
                  class="inline-block py-5 px-7 w-full text-base md:text-lg leading-4 text-violet-50 font-medium text-center bg-violet-500 hover:bg-violet-600 focus:ring-2 focus:ring-violet-500 focus:ring-opacity-50 border border-violet-500 rounded-md shadow-sm"
                  href="#"
                >
                  Request a Demo
                </a>
              </div>
              <div class="w-full md:w-auto py-1 md:py-0">
                <a
                  class="inline-block py-5 px-7 w-full text-base md:text-lg leading-4 text-coolGray-800 font-medium text-center bg-white hover:bg-coolGray-100 focus:ring-2 focus:ring-coolGray-200 focus:ring-opacity-50 border border-coolGray-200 rounded-md shadow-sm"
                  href="#"
                >
                  Sign Up
                </a>
              </div>
            </div>
          </div>
          <!-- <div class="w-full md:w-1/2 px-4">
            <div class="relative mx-auto md:mr-0 max-w-max">
              <img
                class="absolute z-10 -left-14 -top-12 w-28 md:w-auto"
                src="flex-ui-assets/elements/circle3-green.svg"
                alt=""
              />
              <img
                class="absolute z-10 -right-7 -bottom-8 w-28 md:w-auto"
                src="flex-ui-assets/elements/dots3-yellow.svg"
                alt=""
              />
              <img
                class="relative rounded-7xl"
                src="flex-ui-assets/images/headers/header.jpg"
                alt=""
              />
            </div>
          </div> -->
        </div>
      </div>
    </div>
  </section>
</template>

<script setup></script>
