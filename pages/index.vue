
<template>
    <div class="font-sans text-gray-800 min-h-screen flex flex-col">
  
      <!-- ================= HEADER ================= -->
      <header class="bg-white shadow-sm z-50">
        <nav 
          class="container mx-auto flex items-center justify-center py-6"
          aria-label="Main Navigation"
        >
          <!-- Logo or brand text placeholder 
          <img 
            src="/images/with-jeremy-logo-placeholder.svg"
            alt="With Jeremy Logo Placeholder"
            class="h-12 w-auto mr-4"
          />-->
          <!-- Brand Name in large text (serif look) -->
          <h1 class="font-serif-custom text-2xl md:text-4xl font-bold text-center">
            Best Backyard Builders Florence
          </h1>
        </nav>
      </header>
  
      <!-- ================= HERO SECTION ================= -->
      <section 
        class="relative flex-1 flex items-center justify-center text-center bg-cover bg-center bg-no-repeat"
        style="background-image: url('/images/hero-luxury-backyard.jpg');"
        aria-label="Luxury Backyard Hero Image"
      >
        <div class="bg-black bg-opacity-50 w-full h-full absolute top-0 left-0"></div>
        <div class="relative z-10 px-4 py-20 max-w-4xl mx-auto">
          <!-- Ludicrously large font for hero headline -->
          <h2 class="text-white font-serif-custom font-extrabold text-6xl md:text-8xl leading-tight mb-6">
            Elevate Your Backyard
          </h2>
          <p class="text-white text-xl md:text-2xl max-w-2xl mx-auto mb-8">
            Our Builders Are Licensed &amp; Insured <br />High-End Outdoor Living - With Jeremy
          </p>
          <a
            href="#quote-form"
            class="inline-block border-2 border-gold text-white font-semibold py-4 px-8 text-xl md:text-2xl rounded-full bg-transparent hover:bg-gold hover:text-green-800 transition"
          >
            Get a Quote Now!
          </a>
        </div>
      </section>
  
      <!-- ================= MINIMAL SERVICES SECTION ================= -->
      <section class="bg-white py-16 px-4">
        <div class="container mx-auto text-center">
          <div class="mb-12">
            <h3 class="font-serif-custom text-3xl md:text-5xl font-bold text-gray-800 mb-4">
              Transformations We Offer
            </h3>
            <p class="text-gray-600 text-lg md:text-xl">
              Everything you need for a backyard oasis.
            </p>
          </div>
  
          <!-- Quick, minimal service callouts with image placeholders -->
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl mx-auto">
            <!-- Outdoor Kitchen -->
            <div class="flex flex-col items-center">
             <!--  <img 
                src="/images/service-outdoor-kitchen.jpg" 
                alt="Outdoor kitchen design" 
                class="mb-4 rounded shadow-md"
              /> -->
              <h4 class="text-xl md:text-2xl font-bold mb-2">Outdoor Kitchens</h4>
              <p class="text-gray-600 text-sm md:text-base">
                Delicious gatherings under the sky.
              </p>
            </div>
  
            <!-- Decks or Patios -->
            <div class="flex flex-col items-center">
            <!--   <img 
                src="/images/service-deck-lounge.jpg"
                alt="Luxury deck and lounge area"
                class="mb-4 rounded shadow-md"
              /> -->
              <h4 class="text-xl md:text-2xl font-bold mb-2">Patios &amp; Decks</h4>
              <p class="text-gray-600 text-sm md:text-base">
                Expand living space with style.
              </p>
            </div>
  
            <!-- Water Feature -->
            <div class="flex flex-col items-center">
             <!--  <img 
                src="/images/service-water-feature.jpg"
                alt="Beautiful water fountain in backyard"
                class="mb-4 rounded shadow-md"
              /> -->
              <h4 class="text-xl md:text-2xl font-bold mb-2">Water Features</h4>
              <p class="text-gray-600 text-sm md:text-base">
                Serenity meets elegance.
              </p>
            </div>
          </div>
        </div>
      </section>
  
      <!-- ================= SHORT SEO SECTION ================= -->
      <!-- Enough text to cover local SEO but kept simple/clean for the user -->
      <section class="bg-gray-50 py-8 px-4">
        <div class="container mx-auto text-center">
          <h5 class="font-serif-custom text-2xl md:text-3xl font-bold text-gray-800 mb-4">
            Florence, AL’s Premier Outdoor Builder
          </h5>
          <p class="text-gray-600 max-w-4xl mx-auto text-sm md:text-base">
            Best Backyard Builders Florence offers outdoor kitchens, decks, fences, patios,
            fire pits, pergolas, and customized hardscapes. Serving Florence, AL and
            surrounding areas, we’re licensed, insured, and committed to creating
            an outdoor living space that boosts both your home’s value and your
            personal enjoyment. Start your dream project today!
          </p>
        </div>
      </section>
  
      <!-- ================= LEAD CAPTURE FORM ================= -->
      <section id="quote-form" class="bg-white py-16 px-4">
        <div class="container mx-auto max-w-xl bg-gray-100 shadow-lg p-8 rounded-md">
          <h3 class="font-serif-custom text-3xl md:text-4xl font-bold text-center text-gray-800 mb-6">
            Get Your Free Quote
          </h3>
          <!-- For demonstration, using mailto. Replace with real form endpoint for production. -->
          <form 
            method="POST"
            action="mailto:jeremy@withjeremy.com?subject=Backyard%20Builder%20Lead"
            encType="text/plain"
            class="space-y-6"
          >
            <div>
              <label for="name" class="block text-gray-700 font-medium mb-2">
                Name
              </label>
              <input
                type="text"
                id="name"
                name="Name"
                required
                class="w-full border border-gray-300 rounded px-3 py-2 focus:outline-none focus:ring-2 focus:ring-green-600"
              />
            </div>
            <div>
              <label for="email" class="block text-gray-700 font-medium mb-2">
                Email
              </label>
              <input
                type="email"
                id="email"
                name="Email"
                required
                class="w-full border border-gray-300 rounded px-3 py-2 focus:outline-none focus:ring-2 focus:ring-green-600"
              />
            </div>
            <div>
              <label for="phone" class="block text-gray-700 font-medium mb-2">
                Phone
              </label>
              <input
                type="text"
                id="phone"
                name="Phone"
                required
                class="w-full border border-gray-300 rounded px-3 py-2 focus:outline-none focus:ring-2 focus:ring-green-600"
              />
            </div>
            <div>
              <label for="project-details" class="block text-gray-700 font-medium mb-2">
                What can we build for you?
              </label>
              <textarea
                id="project-details"
                name="Project Details"
                rows="3"
                required
                class="w-full border border-gray-300 rounded px-3 py-2 focus:outline-none focus:ring-2 focus:ring-green-600"
              ></textarea>
            </div>
            <button
              type="submit"
              class="w-full border-2 border-gold text-white font-semibold py-3 rounded-full bg-gold hover:bg-white hover:text-green-800 transition text-xl"
            >
              Submit
            </button>
          </form>
        </div>
      </section>
  
      <!-- ================= FOOTER ================= -->
      <footer class="bg-gray-800 text-white py-4 mt-auto">
        <div class="container mx-auto text-center">
          <p class="text-sm md:text-base">
            © <span class="font-bold">Best Backyard Builders Florence</span> | Proudly serving Florence, AL.
          </p>
          <p class="text-xs mt-2">
            Licensed &amp; Insured • 
            <a href="https://withjeremy.com" class="underline hover:text-gray-300">
              withjeremy.com
            </a>
          </p>
        </div>
      </footer>
  
    </div>
  </template>
  
  <script setup>
  definePageMeta({
    title: 'Best Backyard Builders Florence | Elevate Your Outdoor Space',
    meta: [
      {
        name: 'description',
        content:
          'Transform your backyard in Florence, AL with our premium outdoor kitchens, decks, patios, and water features. Licensed, insured, and specializing in high-end projects.'
      }
    ]
  })
  </script>
  
  <style scoped>
  /* 
    1. Custom gold color. Adjust the hex to your preference.
    2. Custom serif font for headings. 
  */
  
  /* Tailwind doesn't automatically include custom fonts. This is a quick example. */
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&display=swap');
  
  .font-serif-custom {
    font-family: 'Playfair Display', serif;
  }
  
  .border-gold {
    border-color: #D4AF37; /* Gold-ish color */
  }
  
  .bg-gold {
    background-color: #D4AF37;
  }
  
  </style>
  
  