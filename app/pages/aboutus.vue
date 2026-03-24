<template>
  <UPageSection>
    <div class="mx-auto max-w-4xl space-y-8">
      <p class="text-lg text-gray-700 dark:text-gray-200">
        Knowage is the open source Business Intelligence and data analytics platform by <a href="https://www.eng.it" target="_blank" rel="noopener noreferrer" class="font-semibold underline underline-offset-2 hover:opacity-75 transition-opacity">Engineering — Ingegneria Informatica</a>, Italy's leading ICT group. We are a team of professionals committed to empowering organizations with secure, reliable and flexible analytics tools — built on open standards and driven by a deep passion for data innovation.
      </p>

      <section class="space-y-4">
        <h2 class="text-2xl font-semibold">
          Where We Work
        </h2>
        <p class="text-base text-gray-500 dark:text-gray-400">
          A distributed team rooted across Europe, bringing local expertise and a shared passion for data innovation.
        </p>

        <div class="overflow-hidden rounded-lg border border-gray-200 dark:border-gray-700">
          <ClientOnly>
            <EngMap />
            <template #fallback>
              <div class="flex h-[460px] w-full items-center justify-center bg-gray-100 dark:bg-gray-800 text-sm text-gray-500">
                Loading map…
              </div>
            </template>
          </ClientOnly>
        </div>
      </section>

      <section class="space-y-4">
        <h2 class="text-2xl font-semibold">
          Contact us
        </h2>

        <div class="rounded-xl border border-gray-200 dark:border-gray-700 bg-gradient-to-br from-gray-50 to-white dark:from-gray-900 dark:to-gray-800 p-8 flex flex-col items-center gap-5 text-center shadow-sm">
          <div class="flex items-center justify-center w-14 h-14 rounded-full bg-primary/10 text-primary">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-7 h-7" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="1.8">
              <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25H4.5a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5H4.5a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
            </svg>
          </div>
          <div class="space-y-1">
            <p class="text-base text-gray-500 dark:text-gray-400">
              Have a question or want to learn more? Drop us a line — we'd love to hear from you.
            </p>
          </div>
          <a
            href="mailto:knowage@eng.it?subject=Knowage%20inquiry"
            class="inline-flex items-center gap-2 rounded-lg bg-primary px-6 py-3 text-base font-semibold text-white shadow hover:opacity-90 transition-opacity"
          >
            <svg xmlns="http://www.w3.org/2000/svg" class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 01-2.25 2.25H4.5a2.25 2.25 0 01-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0019.5 4.5H4.5a2.25 2.25 0 00-2.25 2.25m19.5 0v.243a2.25 2.25 0 01-1.07 1.916l-7.5 4.615a2.25 2.25 0 01-2.36 0L3.32 8.91a2.25 2.25 0 01-1.07-1.916V6.75" />
            </svg>
            Write to knowage@eng.it
          </a>
          <p class="text-xs text-gray-400 dark:text-gray-500">
            Opens your default mail client
          </p>
        </div>
      </section>
    </div>
  </UPageSection>
</template>
