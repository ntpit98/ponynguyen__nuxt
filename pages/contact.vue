<template>
  <section
    id="contact-section"
    class="min-h-screen bg-gradient-to-r from-blue-600 via-blue-800 to-blue-900 shadow-lg dark:from-gray-700 dark:via-gray-800 dark:to-gray-900"
  >
    <div class="container mx-auto flex min-h-screen flex-col px-6 py-12">
      <div class="flex-1 lg:-mx-6 lg:flex lg:items-center">
        <div class="text-white lg:mx-6 lg:w-1/2">
          <h1 class="text-3xl font-semibold capitalize lg:text-5xl">
            Get a quote
          </h1>
          <p class="mt-6 max-w-xl">
            Ask us everything and we would love to hear from you
          </p>
          <div class="mt-6 space-y-8 md:mt-8">
            <p class="-mx-2 flex items-start">
              <svg
                class="mx-2 h-6 w-6 text-white"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path
                  d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                ></path>
                <path d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
              </svg>
              <span class="mx-2 w-72 truncate text-white">
                Cecilia Chapman 711-2880 Nulla St. Mankato Mississippi 96522
              </span>
            </p>
            <!-- Other contact info blocks -->
          </div>
          <div class="mt-6 md:mt-8">
            <h3 class="text-gray-300">Follow us</h3>
            <div class="-mx-1.5 mt-4 flex">
              <!-- Social media links -->
            </div>
          </div>
        </div>
        <div class="mt-8 lg:mx-6 lg:w-1/2">
          <div
            class="mx-auto w-full overflow-hidden rounded-xl bg-white px-8 py-10 shadow-2xl dark:bg-gray-900 lg:max-w-xl"
          >
            <!-- Contact form -->
            <form class="mt-6" onSubmit="{handleOnSubmit}">
              <div class="flex-1">
                <label
                  class="mb-2 block text-sm text-gray-600 dark:text-gray-200"
                >
                  Full Name
                </label>
                <input
                  required
                  id="fullName"
                  type="text"
                  placeholder="John Doe"
                  class="mt-2 block w-full rounded-md border border-gray-200 bg-white px-5 py-3 text-gray-700 focus:border-blue-400 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-40 dark:border-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:focus:border-blue-300"
                />
              </div>

              <div class="mt-6 flex-1">
                <label
                  class="mb-2 block text-sm text-gray-600 dark:text-gray-200"
                >
                  Email address
                </label>
                <input
                  id="email"
                  name="_replyto"
                  required
                  type="email"
                  placeholder="johndoe&#64;example.com"
                  class="mt-2 block w-full rounded-md border border-gray-200 bg-white px-5 py-3 text-gray-700 focus:border-blue-400 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-40 dark:border-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:focus:border-blue-300"
                />
              </div>

              <div class="mt-6 w-full">
                <label
                  class="mb-2 block text-sm text-gray-600 dark:text-gray-200"
                >
                  Message
                </label>
                <textarea
                  class="mt-2 block h-32 w-full rounded-md border border-gray-200 bg-white px-5 py-3 text-gray-700 placeholder-gray-400 focus:border-blue-400 focus:outline-none focus:ring focus:ring-blue-300 focus:ring-opacity-40 dark:border-gray-600 dark:bg-gray-900 dark:text-gray-300 dark:focus:border-blue-300 md:h-48"
                  placeholder="Message"
                  id="message"
                  name="message"
                  required
                ></textarea>
              </div>

              <button
                type="submit"
                disabled="{status.submitting}"
                class="mt-6 w-full transform rounded-md bg-blue-600 px-6 py-3 text-sm font-medium capitalize tracking-wide text-white transition-colors duration-300 hover:bg-blue-500 focus:outline-none focus:ring focus:ring-blue-400 focus:ring-opacity-50"
              >
                Submit
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
