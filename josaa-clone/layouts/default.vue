<template>
    <div>
        <nav class="p-6 flex items-center justify-between bg-teal-800">
            <NuxtLink to="/" class="text-xl text-white">JOSAA Analysis</NuxtLink>

            <div class="flex items-center space-x-4">
                <NuxtLink to="/dashboard" class="py-4 px-6 bg-teal-900 hover:bg-teal-700 text-white rounded-xl">Dashboard</NuxtLink>
                <NuxtLink to="/insights" class="py-4 px-6 bg-teal-600 hover:bg-teal-700 text-white rounded-xl">Make Insights</NuxtLink>
                <NuxtLink to="/login" class="py-4 px-6 bg-teal-900 hover:bg-teal-700 text-white rounded-xl">Log in</NuxtLink>
            </div>
        </nav>

        <slot />

        <footer class="p-6 flex flex-wrap items-center justify-between bg-gray-900">
            <p class="text-gray-300">Copiright (c) Sayan 😂 2023</p>

            <div class="flex mt-6 md:mt-0 items-center space-x-4 w-60 text-gray-50">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos eaque, dolore voluptate distinctio modi voluptatem obcaecati assumenda ad nesciunt tenetur.
            </div>
        </footer>
    </div>
</template>