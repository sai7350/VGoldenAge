<template>
  <div>
    <section class="text-gray-600 mb-14 body-font">
      <div
        class="container mx-auto flex px-3 py-9 md:flex-row flex-col items-start"
      >
        <div
          class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
        >
          <h1
            class="title-font sm:text-4xl text-3xl mb-4 md:-ml-10 font-extrabold md:mt-20 text-gray-900"
          >
            Luxury Center <br class="hidden lg:inline-block md:-ml-10" />For
            Dementia Care
          </h1>
          <p class="mb-8 md:-ml-10 text-lg leading-relaxed">
            Dementia Care Patients are Provided with 24 x 7 Assistance, Medical
            Care, Healthy Food, Secure Living & Companionship.
          </p>
          <div class="flex">
            <NuxtLink to="/contactUs"
               class="inline-flex text-white bg-indigo-500 border-0 py-2 btn glass focus:outline-none hover:bg-indigo-700 rounded text-lg"
            >
              Contact Us
            </NuxtLink>
          </div>
        </div>
        <div class="lg:max-w-lg lg:w-full shadow-lg rounded-md md:w-1/2 w-3/4">
          <div class="carousel rounded-box p-2">
            <div class="carousel-item">
              <img
                src="../assets/Images/GoldenAge.webp"
                alt="Burger"
                class="w-96 p-2"
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/Images/lobby.webp"
                alt="Burger"
                class="w-96 p-2"
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/Images/passage2.webp"
                alt="Burger"
                class="w-96 p-2"
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/Images/SanjayShinde2.webp"
                alt="Burger"
                class="w-96 p-2"
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/Images/Demensia.webp"
                alt="Burger"
                class="w-96 p-2"
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/Images/we.webp"
                alt="Burger"
                class="w-96 p-2"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <Features />
    <Photos/>
    <Photos2/>
    <Unique/>
    <AdditionalFeatures/>
   <!-- <hr /> -->
   <AboutUs/>
    <hr/>
    <ContactUs/>
    
  </div>
</template>

<script>









</script>

<style scoped></style>
