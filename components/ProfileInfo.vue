<template>
        <figure class="p-6">
            <img
                class="w-32 h-32 mx-auto rounded-full"
                :src="photo"
                alt="profile picture"
                width="400"
                height="400"
            />
            <div class="pt-6 text-center spacce-y-4">
                <figcaption class="font-medium">
                    <div class="text-cyan-900 text-xl">{{ title }}</div>
                    <div class="text-gray-500 font-light">{{ subtitle }}</div>
                </figcaption>
                <blockquote>
                    <p class="text-lg font-medium">{{ headline }}</p>
                </blockquote>
            </div>
        </figure>
</template>

<script setup>
    const { photo, title, subtitle, headline } = defineProps(['photo', 'title', 'subtitle', 'headline']);
</script>