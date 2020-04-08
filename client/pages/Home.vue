<template>
    <div>
        <h1 class="my-32 text-center text-brown" v-if="!auth">
            Login to cryptoverter
        </h1>
        <h1 class="my-24 text-center text-brown" v-if="auth">
            Welcome, {{ user.name }}
        </h1>

        <div class="container mx-auto" v-if='auth'>
            <div class="w-full border border-gold-light text-brown py-8 px-3 flex justify-center rounded">
                Crypto Conversion functionality is coming soon
            </div>
        </div>
    </div>
</template>
