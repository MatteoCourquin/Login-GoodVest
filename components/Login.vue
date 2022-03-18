<template>
    <div class="bg-white sm:w-container-login sm:h-fit sm:rounded-xl mt-20 w-full">
        <div class="h-80 bg-center bg-cover sm:rounded-t-xl bg-hero-login"></div>
        <div class="sm:px-16 px-5">
        <h1 class="text-center pt-8 text-4xl sm:text-6xl font-source-serif-pro">Sign in</h1>
        <form class="flex flex-col">
            <label class="pb-2 font-bold text-lg sm:text-xl pt-8" for="username"
            >Username or email</label
            >
            <input
            class="rounded-md border px-3 py-3 duration-150 hover:bg-gray-100 focus:border-purple-800 outline-none"
            type="text"
            id="username"
            name="username"
            placeholder="Your username or email"
            />

            <label class="pb-2 font-bold text-lg sm:text-xl pt-8" for="password"
            >Password</label
            >
            <input
            class="rounded-md border px-3 py-3 duration-150 hover:bg-gray-100 focus:border-purple-800 outline-none"
            type="password"
            id="password"
            name="password"
            placeholder="Your password"
            />
        </form>
        <NuxtLink class="text-my-purple duration-150 hover:text-purple-800 font-bold" to="/forgot-password"
            >Forgot password?</NuxtLink
        >
        </div>
        <div
        class="footer-login flex items-center justify-between border-t sm:px-16 px-5 mt-6 py-6"
        >
        <p>
            Don't have an account?
            <NuxtLink class="text-my-purple duration-150 hover:text-purple-800" to="/sign-up">Sign up</NuxtLink>
        </p>
        <button
            class="text-white bg-my-purple duration-150 hover:bg-purple-800 rounded-lg py-4 flex-shrink-0 px-10 font-black text-sm sm:text-lg"
        >
            Sign in
        </button>
        </div>
    </div>
</template>
