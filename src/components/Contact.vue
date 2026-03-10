<template>
  <div class="bg-gray-950 text-white min-h-screen">

    <!-- HEADER -->
    <section class="py-24 text-center">
      <h1 class="text-5xl font-bold">
        Contact <span class="text-red-500">Us</span>
      </h1>
      <p class="text-gray-400 mt-4">
        Have questions? Get in touch with our team.
      </p>
    </section>

    <section class="max-w-6xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-16">

      <!-- FORM -->
      <form class="bg-gray-900 p-10 rounded-2xl space-y-6">

        <div>
          <label class="text-sm text-gray-400">Name</label>
          <input
            type="text"
            class="w-full mt-2 p-3 bg-gray-800 rounded-lg outline-none focus:ring-2 focus:ring-red-500"
          />
        </div>

        <div>
          <label class="text-sm text-gray-400">Email</label>
          <input
            type="email"
            class="w-full mt-2 p-3 bg-gray-800 rounded-lg outline-none focus:ring-2 focus:ring-red-500"
          />
        </div>

        <div>
          <label class="text-sm text-gray-400">Message</label>
          <textarea
            rows="4"
            class="w-full mt-2 p-3 bg-gray-800 rounded-lg outline-none focus:ring-2 focus:ring-red-500"
          ></textarea>
        </div>

        <button
          class="w-full py-3 bg-red-500 rounded-xl font-semibold hover:bg-red-600 transition"
        >
          Send Message
        </button>

      </form>

      <!-- CONTACT INFO -->
      <div class="space-y-8">

        <div>
          <h3 class="text-xl font-semibold mb-2">Address</h3>
          <p class="text-gray-400">
            123 Fitness Street, Mumbai, India
          </p>
        </div>

        <div>
          <h3 class="text-xl font-semibold mb-2">Phone</h3>
          <p class="text-gray-400">
            +91 98765 43210
          </p>
        </div>

        <div>
          <h3 class="text-xl font-semibold mb-2">Email</h3>
          <p class="text-gray-400">
            contact@ironcoregym.com
          </p>
        </div>

      </div>

    </section>

  </div>
</template>