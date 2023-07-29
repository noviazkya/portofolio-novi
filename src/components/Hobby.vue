<template>
    <div class="bg-white">
      <div class="mx-auto grid max-w-2xl grid-cols-1 items-center gap-x-8 gap-y-16 px-4 py-24 sm:px-6 sm:py-32 lg:max-w-7xl lg:grid-cols-2 lg:px-8">
        <div>
          <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl"> hobby and expertise </h2>
          <p class="mt-4 text-gray-500"> i save everything about my hobby and expertise, because it's funny and i really like it when it's remembered ! HAHAHA </p>
  
          <dl class="mt-16 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 sm:gap-y-16 lg:gap-x-8">
            <div v-for="feature in features" :key="feature.name" class="border-t border-gray-200 pt-4">
              <dt class="font-medium text-gray-900">{{ feature.name }}</dt>
              <dd class="mt-2 text-sm text-gray-500">{{ feature.description }}</dd>
            </div>
          </dl>
        </div>
        <div class="grid grid-cols-2 grid-rows-2 gap-4 sm:gap-6 lg:gap-8">
          <img src="https://i.pinimg.com/564x/5b/63/9c/5b639c2f7a73f37dfa56df9e1521dad2.jpg" alt="Walnut card tray with white powder coated steel divider and 3 punchout holes." class="rounded-lg bg-gray-100" />
          <img src="https://i.pinimg.com/564x/64/4b/0f/644b0f245e3922cbac3c1b6dd77eaf15.jpg" alt="Top down view of walnut card tray with embedded magnets and card groove." class="rounded-lg bg-gray-100" />
          <img src="https://i.pinimg.com/564x/c5/54/06/c55406531bacebfe369917a776d7c0e1.jpg" alt="Side of walnut card tray with card groove and recessed card area." class="rounded-lg bg-gray-100" />
          <img src="https://i.pinimg.com/564x/30/04/bd/3004bde24f06d9e4e3c74a7a054348a3.jpg" alt="Walnut card tray filled with cards and card angled in dedicated groove." class="rounded-lg bg-gray-100" />
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  const features = [
    { name: 'Watching Movie & Anime', description: 'watching movies is an alternative entertainment that is often chosen when feeling tired or bored with routine, i prefer horror and murder genre films :>' },
    { name: 'Listening Music', description: 'besides being beneficial for mental health, music can also improve mood. it feels like the heart is carried away with joy to hear joyful rhythmic songs. likewise when we listen to songs with fast rhythms that ignite enthusiasm.' },
    { name: 'Reading Manga', description: 'i like reading manga because the more i read a lot of manga books the vocabulary increases :D' },
    { name: 'Create Websites', description: 'my first specialty was making websites, because my school major was software engineering so i could become a programmer anytime.' },
    { name: 'Dance', description: 'my second specialty was dancing, i followed dance extracurricular at school :3' },
    { name: 'English Language', description: 'my third skill is English. even though i still dont really know this language, i really like it ! HAHA' },
  ]
  </script>