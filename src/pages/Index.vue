<template>
  <Layout>
    <ClientOnly>
      <full-page ref="fullpage" :options="options" id="fullpage">
        <div class="section">
          <div
            class="bg-cover bg-right h-full relative"
            style="background-image: url(images/karen.jpg)"
          >
            <div class="absolute bottom-0 px-4 pb-1">
              <h1 class="text-4xl md:text-6xl w-max bg-black text-white px-2 md:px-4">Karen Benitez</h1>
              <h3 class="text-xl md:text-3xl px-2 md:px-4">Nurse</h3>
            </div>
          </div>
        </div>
        <div class="section">
          <div class="bg-green-300 p-4 md:p-16 h-full relative">
            <h2 class="text-4xl md:text-6xl w-max bg-black text-white px-4">What I Do</h2>
            <div
              class="px-4 pr-10 w-full max-w-xl absolute top-1/2 transform -translate-y-1/2 md:text-xl"
            >
              <p class="my-4">I nurse.</p>
            </div>
          </div>
        </div>
        <div class="section">
          <div class="bg-orange-300 bg-top p-4 md:p-16 h-full relative">
            <h2 class="text-4xl md:text-6xl w-max bg-black text-white px-4 pr-8">Questions?</h2>
            <div
              class="px-4 pr-10 w-full max-w-xl absolute top-1/2 transform -translate-y-1/2 md:text-xl"
            >
              <p class="text-center md:text-left my-4">
                Email me at
                <a
                  class="block my-4 text-center md:inline underline"
                  href="mailto:karen@benite.care"
                >karen@benitez.care</a>
              </p>
            </div>
          </div>
        </div>
      </full-page>
    </ClientOnly>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home",
  },
  data: () => ({
    options: {
      licenseKey: "140569C6-E8DB49A5-BEF373F3-E4003E0D",
      navigation: true,
    },
  }),
};
</script>

<style>
</style>
