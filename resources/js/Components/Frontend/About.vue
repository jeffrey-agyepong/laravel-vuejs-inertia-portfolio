<template>
  <section id="about" class="section bg-light-secondary dark:bg-dark-secondary">
    <div
      class="container mx-auto"
      v-motion
      :initial="{
        opacity: 0,
        y: 100,
      }"
      :visible="{
        opacity: 1,
        y: 0,
      }"
    >
      <div class="flex flex-col xl:flex-row gap-24">
              <img
              class="object-cover h-[50%] w-[50%] md:mx-auto lg:mx-0 rounded-2xl"
              src="img/about.jpg"
              alt="about"
              />
        <div
          class="
            flex flex-col
            items-center
            text-center
            lg:items-start lg:text-left
          "
        >
          <div class="flex flex-col">
            <h2 class="text-3xl lg:text-4xl font-medium lg:font-extrabold mb-3">
              About Me
            </h2>
            <P class="mb-4 text-accent">Freelance frontend Web developer</P>
            <hr class="mb-8 opacity-90 dark:opacity-5" />
            <p class="mb-8">
              As a self-taught freelancer turned NAIT student, I am a passionate web developer
               and designer with a keen eye for quality and customer satisfaction. My experience includes developing modern, 
              user-friendly websites for small businesses, e-commerce stores, and personal portfolios
               <br />
              <br />
              I specialize in creating fully responsive websites optimized for performance and search engine rankings,
               using the latest technologies such as HTML, CSS, JavaScript, Vue.js, PHP, and CMS platforms like WordPress. 
               With a focus on timely delivery and customer satisfaction, 
              I am dedicated to providing high-quality work that exceeds client expectations. 
            </p>
          </div>
          <a href="#contact" class="btn btn-md bg-accent text-light-tail-100">
            Contact me
          </a>
        </div>
      </div>
    </div>
  </section>
</template>