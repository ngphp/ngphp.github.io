<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ngphp | Next Generation PHP Micro Framework👋</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.0.2/tailwind.min.css">
</head>

<body>

    <!-- Section 1 -->
    <section class="w-full px-6 pb-12 antialiased bg-white" data-tails-scripts="//unpkg.com/alpinejs">
        <div class="mx-auto max-w-7xl">

            <nav class="relative z-50 h-24 select-none" x-data="{ showMenu: false }">
                <div
                    class="container relative flex flex-wrap items-center justify-between h-24 mx-auto overflow-hidden font-medium border-b border-gray-200 md:overflow-visible lg:justify-center sm:px-4 md:px-2 lg:px-0">
                    <div class="flex items-center justify-start w-1/4 h-full pr-4">
                        <a href="#_" class="inline-block py-4 md:py-0">
                            <span class="p-1 text-xl font-black leading-none text-gray-900">ngphp.</span>
                        </a>
                    </div>
                    <div class="top-0 left-0 items-start hidden w-full h-full p-4 text-sm bg-gray-900 bg-opacity-50 md:items-center md:w-3/4 md:absolute lg:text-base md:bg-transparent md:p-0 md:relative md:flex"
                        :class="{'flex fixed': showMenu, 'hidden': !showMenu }">
                        <div
                            class="flex-col w-full h-auto overflow-hidden bg-white rounded-lg md:bg-transparent md:overflow-visible md:rounded-none md:relative md:flex md:flex-row">
                            <a href="#_"
                                class="inline-flex items-center block w-auto h-16 px-6 text-xl font-black leading-none text-gray-900 md:hidden">tails<span
                                    class="text-indigo-600">.</span></a>
                            <div
                                class="flex flex-col items-start justify-center w-full space-x-6 text-center lg:space-x-8 md:w-2/3 md:mt-0 md:flex-row md:items-center">
                                <a href="#_"
                                    class="inline-block w-full py-2 mx-0 ml-6 font-medium text-left text-indigo-600 md:ml-0 md:w-auto md:px-0 md:mx-2 lg:mx-3 md:text-center">Home</a>
                                <a href="#_"
                                    class="inline-block w-full py-2 mx-0 font-medium text-left text-gray-700 md:w-auto md:px-0 md:mx-2 hover:text-indigo-600 lg:mx-3 md:text-center">Features</a>
                                <a href="#_"
                                    class="inline-block w-full py-2 mx-0 font-medium text-left text-gray-700 md:w-auto md:px-0 md:mx-2 hover:text-indigo-600 lg:mx-3 md:text-center">Blog</a>
                                <a href="#_"
                                    class="inline-block w-full py-2 mx-0 font-medium text-left text-gray-700 md:w-auto md:px-0 md:mx-2 hover:text-indigo-600 lg:mx-3 md:text-center">Contact</a>
                                <a href="#_"
                                    class="absolute top-0 left-0 hidden py-2 mt-6 ml-10 mr-2 text-gray-600 lg:inline-block md:mt-0 md:ml-2 lg:mx-3 md:relative">
                                    <svg class="inline w-5 h-5" fill="none" stroke-linecap="round"
                                        stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24"
                                        stroke="currentColor">
                                        <path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                                    </svg>
                                </a>
                            </div>
                            <div
                                class="flex flex-col items-start justify-end w-full pt-4 md:items-center md:w-1/3 md:flex-row md:py-0">
                                <a href="#" class="w-full px-3 py-2 mr-0 text-gray-700 md:mr-2 lg:mr-3 md:w-auto">Sign
                                    In</a>
                                <a href="#_"
                                    class="inline-flex items-center w-full px-6 py-3 text-sm font-medium leading-4 text-white bg-indigo-600 md:px-3 md:w-auto md:rounded-full lg:px-5 hover:bg-indigo-500 focus:outline-none md:focus:ring-2 focus:ring-0 focus:ring-offset-2 focus:ring-indigo-600">Sign
                                    Up</a>
                            </div>
                        </div>
                    </div>
                    <div @click="showMenu = !showMenu"
                        class="absolute right-0 flex flex-col items-center items-end justify-center w-10 h-10 bg-white rounded-full cursor-pointer md:hidden hover:bg-gray-100">
                        <svg class="w-6 h-6 text-gray-700" x-show="!showMenu" fill="none" stroke-linecap="round"
                            stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor"
                            x-cloak="">
                            <path d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                        <svg class="w-6 h-6 text-gray-700" x-show="showMenu" fill="none" stroke="currentColor"
                            viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" x-cloak="">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M6 18L18 6M6 6l12 12"></path>
                        </svg>
                    </div>
                </div>
            </nav>

            <!-- Main Hero Content -->
            <div class="container max-w-lg px-4 py-32 mx-auto mt-px text-left md:max-w-none md:text-center">
                <h1
                    class="text-5xl font-extrabold leading-10 tracking-tight text-left text-gray-900 md:text-center sm:leading-none md:text-6xl lg:text-7xl">

                    <span
                        class="w-full text-transparent bg-clip-text bg-gradient-to-r from-green-400 via-blue-500 to-purple-500 lg:inline">
                        Next Generation PHP</span>
                    <span class="inline md:block">Micro Framework</span>
                </h1>
                <div class="mx-auto mt-5 text-gray-500 md:mt-12 md:max-w-lg md:text-center lg:text-lg">ngphp is a
                    next-generation, lightweight PHP framework designed for rapid web application development. It’s
                    optimized for modern cloud environments where speed, performance, and size matter!</div>
                <div class="flex flex-col items-center mt-12 text-center">
                    <span class="relative inline-flex w-full md:w-auto">
                        <a href="#_" type="button"
                            class="inline-flex items-center justify-center w-full px-8 py-4 text-base font-bold leading-6 text-white bg-indigo-600 border border-transparent rounded-full md:w-auto hover:bg-indigo-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-600">
                            Get Startet
                        </a>
                        <!--
                        <span class="absolute top-0 right-0 px-2 py-1 -mt-3 -mr-6 text-xs font-medium leading-tight text-white bg-green-400 rounded-full">only $15/mo</span>
                    -->
                    </span>
                    <a href="#_" class="mt-3 text-sm text-indigo-500">Install ngphp</a>
                </div>
            </div>
            <!-- End Main Hero Content -->
        </div>
    </section>

    <!-- Section 3 -->
    <section class="h-auto bg-white">
        <div class="px-10 py-24 mx-auto max-w-7xl">
            <div class="w-full mx-auto text-left md:text-center">
                <h1
                    class="mb-6 text-5xl font-extrabold leading-none max-w-5xl mx-auto tracking-normal text-gray-900 sm:text-6xl md:text-6xl lg:text-7xl md:tracking-tight">
                    Open Source, Free, and License-Free. </h1>
                <p class="px-0 mb-6 text-lg text-gray-600 md:text-xl lg:px-24"> Develop your own framework, create your
                    own application. You are free to use and sell it. Discover flexibility and freedom with ngphp, and
                    take your projects to the next level.</p>

                <br>
                <pr>
                    <code class="bg-black text-white p-4 rounded" id="install-command"
                        onclick="copyToClipboard()">composer require ngphp</code>
                    </pre>
                    <script>
                        function copyToClipboard() {
                            const command = document.getElementById('install-command').textContent;
                            navigator.clipboard.writeText(command).then(() => {
                                alert('Command copied to clipboard!');
                            });
                        }
                    </script>
            </div>
        </div>
    </section>

    <!-- Section 4 -->
    <section class="py-20 bg-white">
        <div class="container max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold tracking-tight text-center">Key Features</h2>
            <p class="mt-2 text-lg text-center text-gray-600">Explore the features that make ngphp an excellent choice
                for modern web development.</p>
            <div class="grid grid-cols-4 gap-8 mt-10 sm:grid-cols-8 lg:grid-cols-12 sm:px-8 xl:px-0">

                <div
                    class="relative flex flex-col items-center justify-between col-span-4 px-8 py-12 space-y-4 overflow-hidden bg-gray-100 sm:rounded-xl">
                    <div class="p-3 text-white bg-blue-500 rounded-full">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 " viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <path d="M14 3v4a1 1 0 0 0 1 1h4"></path>
                            <path d="M5 8v-3a2 2 0 0 1 2 -2h7l5 5v11a2 2 0 0 1 -2 2h-5"></path>
                            <circle cx="6" cy="14" r="3"></circle>
                            <path d="M4.5 17l-1.5 5l3 -1.5l3 1.5l-1.5 -5"></path>
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium text-gray-700">Agile Compatibility</h4>
                    <p class="text-base text-center text-gray-500">Ideal for rapid MVP development with minimal setup.
                    </p>
                </div>

                <div
                    class="flex flex-col items-center justify-between col-span-4 px-8 py-12 space-y-4 bg-gray-100 sm:rounded-xl">
                    <div class="p-3 text-white bg-blue-500 rounded-full">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 " viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <line x1="15" y1="5" x2="15" y2="7"></line>
                            <line x1="15" y1="11" x2="15" y2="13"></line>
                            <line x1="15" y1="17" x2="15" y2="19"></line>
                            <path
                                d="M5 5h14a2 2 0 0 1 2 2v3a2 2 0 0 0 0 4v3a2 2 0 0 1 -2 2h-14a2 2 0 0 1 -2 -2v-3a2 2 0 0 0 0 -4v-3a2 2 0 0 1 2 -2">
                            </path>
                        </svg>
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                            class="icon icon-tabler icons-tabler-outline icon-tabler-json">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path d="M20 16v-8l3 8v-8" />
                            <path d="M15 8a2 2 0 0 1 2 2v4a2 2 0 1 1 -4 0v-4a2 2 0 0 1 2 -2z" />
                            <path d="M1 8h3v6.5a1.5 1.5 0 0 1 -3 0v-.5" />
                            <path
                                d="M7 15a1 1 0 0 0 1 1h1a1 1 0 0 0 1 -1v-2a1 1 0 0 0 -1 -1h-1a1 1 0 0 1 -1 -1v-2a1 1 0 0 1 1 -1h1a1 1 0 0 1 1 1" />
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium text-gray-700">Lean Startup Ready</h4>
                    <p class="text-base text-center text-gray-500">Download, run, and develop" model for frequent
                        product releases.</p>
                </div>

                <div
                    class="flex flex-col items-center justify-between col-span-4 px-8 py-12 space-y-4 bg-gray-100 sm:rounded-xl">
                    <div class="p-3 text-white bg-blue-500 rounded-full">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                            class="icon icon-tabler icons-tabler-outline icon-tabler-cloud">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path
                                d="M6.657 18c-2.572 0 -4.657 -2.007 -4.657 -4.483c0 -2.475 2.085 -4.482 4.657 -4.482c.393 -1.762 1.794 -3.2 3.675 -3.773c1.88 -.572 3.956 -.193 5.444 1c1.488 1.19 2.162 3.007 1.77 4.769h.99c1.913 0 3.464 1.56 3.464 3.486c0 1.927 -1.551 3.487 -3.465 3.487h-11.878" />
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium text-gray-700">Cloud-Ready</h4>
                    <p class="text-base text-center text-gray-500">Runs seamlessly on any PHP hosting, ensuring high
                        performance.</p>
                </div>

                <div
                    class="flex flex-col items-center justify-between col-span-4 px-8 py-12 space-y-4 bg-gray-100 sm:rounded-xl">
                    <div class="p-3 text-white bg-blue-500 rounded-full">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 " viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <polyline points="12 3 20 7.5 20 16.5 12 21 4 16.5 4 7.5 12 3"></polyline>
                            <line x1="12" y1="12" x2="20" y2="7.5"></line>
                            <line x1="12" y1="12" x2="12" y2="21"></line>
                            <line x1="12" y1="12" x2="4" y2="7.5"></line>
                            <line x1="16" y1="5.25" x2="8" y2="9.75"></line>
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium text-gray-700">Integrated Core Features</h4>
                    <p class="text-base text-center text-gray-500">Built-in error handling, logging, email, JWT
                        authentication, and more.</p>
                </div>

                <div
                    class="flex flex-col items-center justify-between col-span-4 px-8 py-12 space-y-4 bg-gray-100 sm:rounded-xl">
                    <div class="p-3 text-white bg-blue-500 rounded-full">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8 " viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <path d="M8 9l3 3l-3 3"></path>
                            <line x1="13" y1="15" x2="16" y2="15"></line>
                            <rect x="3" y="4" width="18" height="16" rx="2"></rect>
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium text-gray-700">Minimalist Architecture</h4>
                    <p class="text-base text-center text-gray-500">Lightweight and efficient, reducing resource usage.
                    </p>
                </div>

                <div
                    class="flex flex-col items-center justify-between col-span-4 px-8 py-12 space-y-4 bg-gray-100 sm:rounded-xl">
                    <div class="p-3 text-white bg-blue-500 rounded-full">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none"
                            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"
                            class="icon icon-tabler icons-tabler-outline icon-tabler-json">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path d="M20 16v-8l3 8v-8" />
                            <path d="M15 8a2 2 0 0 1 2 2v4a2 2 0 1 1 -4 0v-4a2 2 0 0 1 2 -2z" />
                            <path d="M1 8h3v6.5a1.5 1.5 0 0 1 -3 0v-.5" />
                            <path
                                d="M7 15a1 1 0 0 0 1 1h1a1 1 0 0 0 1 -1v-2a1 1 0 0 0 -1 -1h-1a1 1 0 0 1 -1 -1v-2a1 1 0 0 1 1 -1h1a1 1 0 0 1 1 1" />
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium text-gray-700">RESTful API Support</h4>
                    <p class="text-base text-center text-gray-500">Robust and easy-to-use API creation..</p>
                </div>

            </div>
        </div>
    </section>

    <section class="py-24 bg-white">
        <div class="px-8 mx-auto max-w-7xl lg:px-16">
            <h2 class="mb-4 text-xl font-bold md:text-3xl">Frequently Asked Questions</h2>
            <div class="grid grid-cols-1 gap-0 text-gray-600 md:grid-cols-2 md:gap-16">
                <div>
                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        What is ngPHP?</h5>
                    <p class="hidden">ngPHP is a next-generation PHP framework designed to be minimalistic, powerful,
                        and easy to use for modern web development.</p>

                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        Can I try ngPHP for free?</h5>
                    <p class="hidden">Absolutely, ngPHP is open-source and free to use. You can download and start using
                        it right away. For advanced features, you can explore the enterprise version.</p>

                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        Where do I go to upgrade to the enterprise version?</h5>
                    <p class="hidden">
                        You can upgrade to the enterprise version by visiting <a href="#"
                            class="text-indigo-500 underline">The Pro Upgrade Page</a>. You will gain access to
                        additional features and priority support.
                    </p>

                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        How long will I have access to ngPHP?</h5>
                    <p class="hidden">
                        You will have lifetime access to ngPHP. However, to get updates and premium support, you may
                        consider upgrading to the enterprise version.
                    </p>
                </div>
                <div>
                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        How do I implement ngPHP into my project?</h5>
                    <p class="hidden">Implementation is straightforward. You can follow the documentation to integrate
                        ngPHP into your existing project or start a new one using our starter templates.</p>

                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        What is the license for ngPHP?</h5>
                    <p class="hidden">ngPHP is licensed under the MIT license, allowing you to use, modify, and
                        distribute the framework with very few restrictions.</p>

                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        Can I cancel my enterprise subscription if I no longer need it?</h5>
                    <p class="hidden">Yes, you can cancel your enterprise subscription at any time. You will still have
                        access to the open-source version of ngPHP.</p>

                    <h5 class="mt-10 mb-3 font-semibold text-gray-900 cursor-pointer" onclick="toggleAccordion(this)">
                        What if I need help with ngPHP?</h5>
                    <p class="hidden">If you need assistance, you can contact our support team or visit the <a href="#"
                            class="text-indigo-500 underline">question section</a> on our website.</p>
                </div>
            </div>
        </div>
    </section>

    <script>
        function toggleAccordion(element) {
            var content = element.nextElementSibling;
            if (content.classList.contains('hidden')) {
                content.classList.remove('hidden');
            } else {
                content.classList.add('hidden');
            }
        }
    </script>

    <!-- Section 7 -->
    <section class="text-gray-700 bg-white body-font">
        <div class="container flex flex-col items-center px-8 py-8 mx-auto max-w-7xl sm:flex-row">
            <a href="#_" class="text-xl font-black leading-none text-gray-900 select-none logo">ngphp<span
                    class="text-indigo-600">.</span></a>
            <p class="mt-4 text-sm text-gray-500 sm:ml-4 sm:pl-4 sm:border-l sm:border-gray-200 sm:mt-0">© 2024 ngphp -
                Tailwindcss Page Builder</p>
            <span class="inline-flex justify-center mt-4 space-x-5 sm:ml-auto sm:mt-0 sm:justify-start">
                <a href="https://github.com/ngphp" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">GitHub</span>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path fill-rule="evenodd"
                            d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                            clip-rule="evenodd"></path>
                    </svg>
                </a>
                <a href="https://www.youtube.com/@ngphp" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">YouTube</span>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path fill-rule="evenodd"
                            d="M23.499 6.186a2.991 2.991 0 00-2.11-2.11C19.41 3.505 12 3.505 12 3.505s-7.41 0-9.388.571a2.991 2.991 0 00-2.11 2.11C.5 8.163.5 12 .5 12s0 3.837.571 5.814a2.991 2.991 0 002.11 2.11c1.978.571 9.388.571 9.388.571s7.41 0 9.388-.571a2.991 2.991 0 002.11-2.11C23.5 15.837 23.5 12 23.5 12s0-3.837-.001-5.814zM9.546 15.568v-7.137l6.394 3.569-6.394 3.568z"
                            clip-rule="evenodd"></path>
                    </svg>
                </a>
                <!--
            <a href="https://ngphp.slack.com" class="text-gray-400 hover:text-gray-500">
                <span class="sr-only">Slack</span>
            </a>
            <a href="https://bitbucket.org/ngphp/" class="text-gray-400 hover:text-gray-500">
                <span class="sr-only">Bitbucket</span>
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                    <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd"></path>
                </svg>
            </a>
            <a href="https://mastodon.social/@ngphp" class="text-gray-400 hover:text-gray-500">
                <span class="sr-only">Mastodon</span>
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                    <path fill-rule="evenodd" d="M23.499 6.186a2.991 2.991 0 00-2.11-2.11C19.41 3.505 12 3.505 12 3.505s-7.41 0-9.388.571a2.991 2.991 0 00-2.11 2.11C.5 8.163.5 12 .5 12s0 3.837.571 5.814a2.991 2.991 0 002.11 2.11c1.978.571 9.388.571 9.388.571s7.41 0 9.388-.571a2.991 2.991 0 002.11-2.11C23.5 15.837 23.5 12 23.5 12s0-3.837-.001-5.814zM9.546 15.568v-7.137l6.394 3.569-6.394 3.568z" clip-rule="evenodd"></path>
                </svg>                
            </a>
            <a href="https://www.reddit.com/user/ngphp/" class="text-gray-400 hover:text-gray-500">
                <span class="sr-only">Reddit</span>
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                    <path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z" clip-rule="evenodd"></path>
                </svg>
            </a>
            -->
                <a href="https://discord.com/channels/ngphp" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Discord</span>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path
                            d="M21.472 4.618a19.791 19.791 0 00-4.885-1.548.073.073 0 00-.078.036c-.675 1.23-1.46 2.84-2.038 4.276a20.244 20.244 0 00-5.856 0 18.593 18.593 0 00-2.038-4.276.077.077 0 00-.078-.036 19.824 19.824 0 00-4.885 1.548.07.07 0 00-.032.03C.756 10.058-.213 15.391.177 20.646a.073.073 0 00.028.048 20.175 20.175 0 006.074 3.067.076.076 0 00.083-.028c.47-.641.885-1.32 1.24-2.027a.074.074 0 00-.041-.101 13.905 13.905 0 01-1.987-.765.073.073 0 01-.007-.125c.133-.097.266-.197.394-.297a.074.074 0 01.071-.007c4.147 1.952 8.635 1.952 12.715 0a.073.073 0 01.072.006c.129.101.262.201.395.298a.073.073 0 01-.006.125 13.777 13.777 0 01-1.988.764.073.073 0 00-.04.102c.36.706.775 1.386 1.242 2.027a.075.075 0 00.083.028 20.135 20.135 0 006.073-3.067.073.073 0 00.028-.048c.429-5.098-.763-10.387-4.294-15.997a.075.075 0 00-.034-.03zM8.01 16.501c-1.183 0-2.155-1.084-2.155-2.419 0-1.334.953-2.419 2.155-2.419 1.2 0 2.174 1.088 2.153 2.419 0 1.335-.953 2.419-2.153 2.419zm7.982 0c-1.184 0-2.155-1.084-2.155-2.419 0-1.334.953-2.419 2.155-2.419 1.2 0 2.174 1.088 2.153 2.419 0 1.335-.953 2.419-2.153 2.419z">
                        </path>
                    </svg>
                </a>
                <a href="https://www.linkedin.com/company/ngphp" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">LinkedIn</span>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path fill-rule="evenodd"
                            d="M20.447 20.452h-3.755v-5.569c0-1.327-.027-3.033-1.849-3.033-1.851 0-2.135 1.447-2.135 2.941v5.661H8.946V9h3.607v1.561h.05c.501-.95 1.722-1.949 3.546-1.949 3.793 0 4.49 2.496 4.49 5.744v6.099zM5.337 7.433c-1.212 0-2.193-.983-2.193-2.193 0-1.212.983-2.193 2.193-2.193 1.212 0 2.193.983 2.193 2.193 0 1.212-.982 2.193-2.193 2.193zM6.869 20.452H3.807V9h3.062v11.452zM22.225 0H1.771C.792 0 0 .792 0 1.771v20.453C0 23.207.792 24 1.771 24h20.453C23.207 24 24 23.208 24 22.225V1.771C24 .792 23.207 0 22.225 0z"
                            clip-rule="evenodd"></path>
                    </svg>
                </a>
                <a href="https://twitter.com/ngphp_official" class="text-gray-400 hover:text-gray-500">
                    <span class="sr-only">Twitter</span>
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                        <path
                            d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84">
                        </path>
                    </svg>
                </a>
            </span>
        </div>
    </section>


    <!-- AlpineJS Library -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/alpinejs/2.8.0/alpine.js"></script>

</body>

</html>
