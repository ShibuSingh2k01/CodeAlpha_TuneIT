<script setup>
import HomeCard from "../components/HomeCard.vue";
</script>

<template>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Podcasts to make you smarter
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="https://picsum.photos/id/30/300/300"
        title="Happiness Logic"
        subTitle="Exploring positive psychology"
      />
      <HomeCard
        image="https://picsum.photos/id/45/300/300"
        title="Indian Trends"
        subTitle="Latest in Indian Life"
      />
      <HomeCard
        class="md:block hidden"
        image="https://picsum.photos/id/65/300/300"
        title="Mindset Mastery"
        subTitle="Personal development"
      />
      <HomeCard
        class="lg:block hidden"
        image="https://picsum.photos/id/67/300/300"
        title="History Unveiled"
        subTitle="Intriguing historical events"
      />
      <HomeCard
        class="xl:block hidden"
        image="https://picsum.photos/id/100/300/300"
        title="Tour de World"
        subTitle="Tips on travelling"
      />
    </div>
  </div>

  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recommended radio
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="https://picsum.photos/id/120/300/300"
        title="Classic Rock Radio"
        subTitle="The best of rock music"
      />
      <HomeCard
        image="https://picsum.photos/id/110/300/300"
        title="Jazz & Blues"
        subTitle="Smooth and soulful tunes"
      />
      <HomeCard
        class="md:block hidden"
        image="https://picsum.photos/id/221/300/300"
        title="Top Hits"
        subTitle="Today's hottest tracks"
      />
      <HomeCard
        class="lg:block hidden"
        image="https://picsum.photos/id/232/300/300"
        title="Country Roads"
        subTitle="All-time country favorites"
      />
      <HomeCard
        class="xl:block hidden"
        image="https://picsum.photos/id/187/300/300"
        title="Indie Waves"
        subTitle="Discover new indie music"
      />
    </div>
  </div>

  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recommended songs
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="https://picsum.photos/id/88/300/300"
        title="Blinding Lights"
        subTitle="The Weeknd"
      />
      <HomeCard
        image="https://picsum.photos/id/243/300/300"
        title="Levitating"
        subTitle="Dua Lipa"
      />
      <HomeCard
        class="md:block hidden"
        image="https://picsum.photos/id/123/300/300"
        title="Save Your Tears"
        subTitle="The Weeknd"
      />
      <HomeCard
        class="lg:block hidden"
        image="https://picsum.photos/id/121/300/300"
        title="Peaches"
        subTitle="Justin Bieber"
      />
      <HomeCard
        class="xl:block hidden"
        image="https://picsum.photos/id/99/300/300"
        title="Good 4 U"
        subTitle="Olivia Rodrigo"
      />
    </div>
  </div>
</template>
