<script>
  import Footer from "$lib/footer.svelte";
  import Header from "$lib/header.svelte";
</script>

<svelte:head>
  <title>Contact</title>
</svelte:head>
<div>
  <div class="bg-white">
    <Header activeTab="contact" />

    <main class="overflow-hidden">
      <!-- Header -->
      <div class="bg-warm-gray-50">
        <div class="py-24 lg:py-32">
          <div
            class="relative z-10 max-w-7xl mx-auto pl-4 pr-8 sm:px-6 lg:px-8"
          >
            <h1
              class="text-4xl font-extrabold tracking-tight text-warm-gray-900 sm:text-5xl lg:text-6xl"
            >
              Get in touch
            </h1>
            <p class="mt-6 text-xl text-warm-gray-500 max-w-3xl">
              Vel nunc non ut montes, viverra tempor. Proin lectus nibh
              phasellus morbi non morbi. In elementum urna ut volutpat. Sagittis
              et vel et fermentum amet consequat.
            </p>
          </div>
        </div>
      </div>

      <!-- Contact grid -->
      <section aria-labelledby="offices-heading">
        <div class="max-w-7xl mx-auto py-24 px-4 sm:py-32 sm:px-6 lg:px-8">
          <h2
            id="offices-heading"
            class="text-3xl font-extrabold text-warm-gray-900"
          >
            Our offices
          </h2>
          <p class="mt-6 text-lg text-warm-gray-500 max-w-3xl">
            Varius facilisi mauris sed sit. Non sed et duis dui leo, vulputate
            id malesuada non. Cras aliquet purus dui laoreet diam sed lacus,
            fames.
          </p>
          <div
            class="mt-10 grid grid-cols-1 gap-10 sm:grid-cols-2 lg:grid-cols-4"
          >
            <div>
              <h3 class="text-lg font-medium text-warm-gray-900">
                Los Angeles
              </h3>
              <p class="mt-2 text-base text-warm-gray-500">
                <span class="block">4556 Brendan Ferry</span>

                <span class="block">Los Angeles, CA 90210</span>
              </p>
            </div>

            <div>
              <h3 class="text-lg font-medium text-warm-gray-900">New York</h3>
              <p class="mt-2 text-base text-warm-gray-500">
                <span class="block">886 Walter Streets</span>

                <span class="block">New York, NY 12345</span>
              </p>
            </div>

            <div>
              <h3 class="text-lg font-medium text-warm-gray-900">Toronto</h3>
              <p class="mt-2 text-base text-warm-gray-500">
                <span class="block">7363 Cynthia Pass</span>

                <span class="block">Toronto, ON N3Y 4H8</span>
              </p>
            </div>

            <div>
              <h3 class="text-lg font-medium text-warm-gray-900">London</h3>
              <p class="mt-2 text-base text-warm-gray-500">
                <span class="block">114 Cobble Lane</span>

                <span class="block">London N1 2EF</span>
              </p>
            </div>
          </div>
        </div>
      </section>
    </main>
    <Footer />
  </div>
</div>
