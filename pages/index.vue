<template>
    <div class="max-w-screen-lg mx-auto p-4 min-h-screen">
        <div class="flex flex-col justify-center items-center mt-12">
            <img src="/img/logo.svg" class="w-52 h-52 mb-2">
            <h1
                class="text-[36px] sm:text-[45px] font-bold text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-sky-600">
                Parch Linux
            </h1>
            <p class="px-3 text-sm max-w-lg text-center mb-8">Parch Linux is an
                open-source, Arch-based Linux distribution, that tried to be pretty, easy to use, light, fast and stable.
            </p>

            <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                <NuxtLink to="/download">
                    <button
                        class="font-medium inline-flex items-center justify-center bg-gradient-to-r from-blue-500 to-indigo-700 px-6 py-2 rounded-xl hover:translate-y-2 transition">
                        Download
                        <Icon name="iconoir:download" class="w-6 h-6 text-white ml-2" />
                    </button>
                </NuxtLink>
                <a href="https://daramet.com/parchlinux">
                    <button
                        class="font-medium inline-flex items-center justify-center border-zinc-900 border px-6 py-2 rounded-xl hover:translate-y-2 transition">
                        Donate
                        <Icon name="fluent-mdl2:coffee-script" class="w-6 h-6 text-white ml-2" />
                    </button>
                </a>
            </div>

        </div>
    </div>


    <div class="p-6 flex justify-center">
        <div class="flex flex-col justify-center items-center my-20">
            <div class="text-center flex flex-col gap-4 max-w-screen-sm">
                <h2
                    class="font-bold text-[45px] text-transparent bg-clip-text bg-gradient-to-r from-indigo-500 to-sky-500 mb-10">
                    New Industry
                </h2>
            </div>

            <div class="flex flex-wrap justify-center p-2 gap-12 text-justify mt-4">

                <div class="max-w-sm p-2">
                    <div class="flex items-center gap-2 mb-2">
                        <Icon name="fluent:settings-24-regular" class='w-7 h-7 text-blue-500' />


                        <h3 class="text-[20px] font-normal ">Simple</h3>
                    </div>
                    <p class="font-normal mt-6">
                        Parch linux uses calamares graphical installer by default which makes it easier for you to install
                        and use it.
                    </p>
                </div>

                <div class="max-w-sm p-2">
                    <div class="flex items-center gap-2 mb-2">
                        <Icon name="simple-line-icons:lock" class='w-7 h-7 text-blue-500' />


                        <h3 class="text-[20px] font-normal ">Privacy</h3>
                    </div>
                    <p class="font-normal mt-6">
                        Unlike any other proprietary operating systems, Parch Linux respects your privacy and doesn't
                        collect any information or data from you.
                    </p>
                </div>

                <div class="max-w-sm p-2">
                    <div class="flex items-center gap-2 mb-2">
                        <Icon name="ion:rocket-outline" class='w-7 h-7 text-blue-500' />


                        <h3 class="text-[20px] font-normal ">Fast</h3>
                    </div>
                    <p class="font-normal mt-6">Parch Linux requires at least 1.5 GB of RAM with xfce desktop and at least 1
                        GB with lxqt desktop
                        Give your old system a second chance with Parch Linux.</p>
                </div>

                <div class="max-w-sm p-2">
                    <div class="flex items-center gap-2 mb-2">
                        <Icon name="heroicons:chat-bubble-left" class='w-7 h-7 text-blue-500' />


                        <h3 class="text-[20px] font-normal ">Community</h3>
                    </div>
                    <p class="font-normal mt-6">
                        Parch Linux in <a href="https://t.me/parchlinux" class='text-blue-500'>Telegram</a> has an active
                        community that will quickly solve your problems. If you have a bug or problem, you can report it in
                        the community.
                    </p>
                </div>
            </div>
        </div>
    </div>

    <div class="max-w-[860px] flex items-center justify-center flex-col mx-auto p-6 min-h-screen my-10">

        <div class="flex flex-col justify-center items-center gap-4 text-center px-4">
            <h2 class="text-2xl sm:text-[32px] font-bold text-transparent bg-clip-text bg-gradient-to-r from-indigo-500 to-sky-500">
                What is Parch Linux?
            </h2>

            <p class="font-normal text-[15px] leading-6">
                The <strong>Parch Linux</strong> is a Linux distro based on <span class="text-sky-500">Arch</span>, that
                tried to be pretty, easy to use, light, fast and stable.
            </p>

            <h2 class="text-2xl sm:text-[32px] font-bold mt-8 text-transparent bg-clip-text bg-gradient-to-r from-sky-500 to-indigo-500">
                Why do we call this Parch?
            </h2>

            <p class="font-normal text-[15px] leading-6">
                At the beginning of our work, we planned to make Parch a platform for Persian-speaking users, that's why
                we
                named it Parch ( <span class="text-sky-500">P</span>ersian <span class="text-sky-500">Arch</span> ). But
                now
                we have more comprehensive goals than before.
            </p>
        </div>
    </div>

</template>

<script setup>
useHead({
    title: "Parch Linux",
})
</script>
