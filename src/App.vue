<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
    data() {
        return {
            isOpen: false
        };
    }
};
</script>

<template>
<nav class="bg-emerald-900">
    <div class="container mx-auto px-44 py-1 flex justify-between items-center">
        <!-- Logo -->
        <div>
            <p class="text-white text-right ...">
                I am a baby retro chillwave letterpress small batch beard, paleo ugh banjo hot chicken godard craft beer
            </p>
        </div>
        <!-- Menú móvil (mostrado solo en dispositivos pequeños) -->
    </div>
</nav>

<!--Sub menu-->
<div class="bg-neutral-100 py-8">
    <div class="container mx-auto px-0 py-0 max-w-screen-xl flex items-center">
        <!-- Contenido del div -->
        <h3 class="text-left px-40 font-bold mr-4">COMPANY NAME</h3>
        <h6 class="px-10">email@example.com</h6>
        <h6 class="px-20"> +44 123 456 789</h6>

        <button class="bg-amber-500 border border-amber-60 text-white flex items-center gap-2 px-4 py-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-cart" viewBox="0 0 16 16">
                <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5M3.102 4l1.313 7h8.17l1.313-7zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4m7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4m-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2m7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2" />
            </svg>
            <span>GET STARTED</span>

        </button>
    </div>
</div>

<!-- Middle message-->
<div class="relative">
    <img src="/src/img/bg2.jpg" class="w-full py-0 px-0" alt="img" style="max-height: 500px;">

    <div class="absolute inset-0 flex flex-col justify-center items-center text-white">
        <div class="container mb-20 px-44">
            <!-- Texto -->
            <p class="text-sm mb-4 text-right px-80">Supporting Subheadline Goes here</p>
            <h2 class="text-2xl font-bold mb-2 px-52 text-right">My Amazing Headline Goes Here</h2>
            <div class="container px-44 py-1 text-right">
                <p class="text-sm mb-4 text-right px-20 py-0">
                    I am baby retro chillwave letterpress smal batch beard, paleo ugh banjo hot chicken godard craft beer.
                    Biodiesel pork belly green juice VHS farm-to-table- taxidermy heirloom scenester.
                </p>
            </div>

            <!-- Botones -->
            <div class="flex space-x-4 top-5 px-80">
                <button class="bg-amber-500 border border-amber-60 text-white flex items-center gap-2 px-10 py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-cart" viewBox="0 0 16 16">
                        <path d="M0 1.5A.5.5 0 0 1 .5 1H2a.5.5 0 0 1 .485.379L2.89 3H14.5a.5.5 0 0 1 .491.592l-1.5 8A.5.5 0 0 1 13 12H4a.5.5 0 0 1-.491-.408L2.01 3.607 1.61 2H.5a.5.5 0 0 1-.5-.5M3.102 4l1.313 7h8.17l1.313-7zM5 12a2 2 0 1 0 0 4 2 2 0 0 0 0-4m7 0a2 2 0 1 0 0 4 2 2 0 0 0 0-4m-7 1a1 1 0 1 1 0 2 1 1 0 0 1 0-2m7 0a1 1 0 1 1 0 2 1 1 0 0 1 0-2" />
                    </svg>
                    <span>GET STARTED</span>
                </button>
            </div>

        </div>
        <div class="absolute px-10 py-6 top-96 bottom-11 left-20 right-20 bg-gray-100 bg-opacity-100 rounded-lg">
            <div class="flex justify-between">
                <button class="bg-amber-500 order-1">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-controller" viewBox="0 0 16 16">
                        <path d="M11.5 6.027a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0m-1.5 1.5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 1-1 0 .5.5 0 0 1 1 0m-1.5 1.5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1m-6.5-3h1v1h1v1h-1v1h-1v-1h-1v-1h1z" />
                        <path d="M3.051 3.26a.5.5 0 0 1 .354-.613l1.932-.518a.5.5 0 0 1 .62.39c.655-.079 1.35-.117 2.043-.117.72 0 1.443.041 2.12.126a.5.5 0 0 1 .622-.399l1.932.518a.5.5 0 0 1 .306.729q.211.136.373.297c.408.408.78 1.05 1.095 1.772.32.733.599 1.591.805 2.466s.34 1.78.364 2.606c.024.816-.059 1.602-.328 2.21a1.42 1.42 0 0 1-1.445.83c-.636-.067-1.115-.394-1.513-.773-.245-.232-.496-.526-.739-.808-.126-.148-.25-.292-.368-.423-.728-.804-1.597-1.527-3.224-1.527s-2.496.723-3.224 1.527c-.119.131-.242.275-.368.423-.243.282-.494.575-.739.808-.398.38-.877.706-1.513.773a1.42 1.42 0 0 1-1.445-.83c-.27-.608-.352-1.395-.329-2.21.024-.826.16-1.73.365-2.606.206-.875.486-1.733.805-2.466.315-.722.687-1.364 1.094-1.772a2.3 2.3 0 0 1 .433-.335l-.028-.079zm2.036.412c-.877.185-1.469.443-1.733.708-.276.276-.587.783-.885 1.465a14 14 0 0 0-.748 2.295 12.4 12.4 0 0 0-.339 2.406c-.022.755.062 1.368.243 1.776a.42.42 0 0 0 .426.24c.327-.034.61-.199.929-.502.212-.202.4-.423.615-.674.133-.156.276-.323.44-.504C4.861 9.969 5.978 9.027 8 9.027s3.139.942 3.965 1.855c.164.181.307.348.44.504.214.251.403.472.615.674.318.303.601.468.929.503a.42.42 0 0 0 .426-.241c.18-.408.265-1.02.243-1.776a12.4 12.4 0 0 0-.339-2.406 14 14 0 0 0-.748-2.295c-.298-.682-.61-1.19-.885-1.465-.264-.265-.856-.523-1.733-.708-.85-.179-1.877-.27-2.913-.27s-2.063.091-2.913.27" />
                    </svg>
                    <span></span>
                </button>
                <button class="bg-amber-500">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-truck" viewBox="0 0 16 16">
                        <path d="M0 3.5A1.5 1.5 0 0 1 1.5 2h9A1.5 1.5 0 0 1 12 3.5V5h1.02a1.5 1.5 0 0 1 1.17.563l1.481 1.85a1.5 1.5 0 0 1 .329.938V10.5a1.5 1.5 0 0 1-1.5 1.5H14a2 2 0 1 1-4 0H5a2 2 0 1 1-3.998-.085A1.5 1.5 0 0 1 0 10.5zm1.294 7.456A2 2 0 0 1 4.732 11h5.536a2 2 0 0 1 .732-.732V3.5a.5.5 0 0 0-.5-.5h-9a.5.5 0 0 0-.5.5v7a.5.5 0 0 0 .294.456M12 10a2 2 0 0 1 1.732 1h.768a.5.5 0 0 0 .5-.5V8.35a.5.5 0 0 0-.11-.312l-1.48-1.85A.5.5 0 0 0 13.02 6H12zm-9 1a1 1 0 1 0 0 2 1 1 0 0 0 0-2m9 0a1 1 0 1 0 0 2 1 1 0 0 0 0-2" />
                    </svg>
                    <span></span>
                </button>
                <button class="bg-amber-500">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-bank" viewBox="0 0 16 16">
                        <path d="m8 0 6.61 3h.89a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H15v7a.5.5 0 0 1 .485.38l.5 2a.498.498 0 0 1-.485.62H.5a.498.498 0 0 1-.485-.62l.5-2A.5.5 0 0 1 1 13V6H.5a.5.5 0 0 1-.5-.5v-2A.5.5 0 0 1 .5 3h.89zM3.777 3h8.447L8 1zM2 6v7h1V6zm2 0v7h2.5V6zm3.5 0v7h1V6zm2 0v7H12V6zM13 6v7h1V6zm2-1V4H1v1zm-.39 9H1.39l-.25 1h13.72z" />
                    </svg>
                    <span></span>
                </button>
                <button class="bg-amber-500">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-flag" viewBox="0 0 16 16">
                        <path d="M14.778.085A.5.5 0 0 1 15 .5V8a.5.5 0 0 1-.314.464L14.5 8l.186.464-.003.001-.006.003-.023.009a12 12 0 0 1-.397.15c-.264.095-.631.223-1.047.35-.816.252-1.879.523-2.71.523-.847 0-1.548-.28-2.158-.525l-.028-.01C7.68 8.71 7.14 8.5 6.5 8.5c-.7 0-1.638.23-2.437.477A20 20 0 0 0 3 9.342V15.5a.5.5 0 0 1-1 0V.5a.5.5 0 0 1 1 0v.282c.226-.079.496-.17.79-.26C4.606.272 5.67 0 6.5 0c.84 0 1.524.277 2.121.519l.043.018C9.286.788 9.828 1 10.5 1c.7 0 1.638-.23 2.437-.477a20 20 0 0 0 1.349-.476l.019-.007.004-.002h.001M14 1.221c-.22.078-.48.167-.766.255-.81.252-1.872.523-2.734.523-.886 0-1.592-.286-2.203-.534l-.008-.003C7.662 1.21 7.139 1 6.5 1c-.669 0-1.606.229-2.415.478A21 21 0 0 0 3 1.845v6.433c.22-.078.48-.167.766-.255C4.576 7.77 5.638 7.5 6.5 7.5c.847 0 1.548.28 2.158.525l.028.01C9.32 8.29 9.86 8.5 10.5 8.5c.668 0 1.606-.229 2.415-.478A21 21 0 0 0 14 7.655V1.222z" />
                    </svg>
                    <span></span>
                </button>
            </div>
        </div>
    </div>

</div>

<div class="bg-gray-200 py-96">
    <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center items-start px-1">
            <!-- Contenido del div -->
            <div class=" relative px-16 py-16 top-(-32) bottom-80 left-60 right-80 bg-gray-100 bg-opacity-100 rounded-lg">
                <img src="/src/img/img1.png" class="w-full py-0 px-0" alt="">
            </div>
        </div>

    </div>
</div>

<div class="bg-orange-100 py-52">
    <div class="container mx-auto px-48 flex flex-wrap">
        <!-- Contenido del div -->
        <!-- Columna izquierda -->
        <div class=" relative w-full md:w-1/4 bg-white bg-opacity-40 p-40 py-10">
            <!-- Contenido de la columna izquierda -->
            <img src="/src/img/img4.png" class="w-full py-0 px-0" alt="img">
        </div>

        <!-- Columna derecha -->
        <div class="w-full md:w-2/5 md:flex md:flex-col">
            <!-- Columna 1 de la derecha -->
            <div class="bg-green-200 p-20 mb-4 md:mb-0">
                <!-- Contenido de la primera columna derecha -->
            </div>

            <!-- Columna 2 de la derecha -->
            <div class="bg-gray-200 p-24">
                <!-- Contenido de la segunda columna derecha -->
            </div>
        </div>
    </div>
</div>

<div class="bg-gray-50 py-20">
    <div class="container mx-auto px-52">
        <!-- Contenido del div -->
        <!--Primer sensible design -->
        <div class="p-10 max-w-4xl bg-gray-200 rounded-xl shadow-lg flex items-center justify-center space-x-4">
            <div class="md:shrink-0">
                    <img class="h-48 w-full object-cover md:h-full md:w-48" src="/src/img/glass.jpg" alt="Modern building architecture">
                </div>
          <div class="max-w-md bg-white rounded-xl shadow-md overflow-hidden md:max-w-xl">
            <div class="md:flex">
                <div class="p-8">
                    <div class="uppercase tracking-wide text-sm text-emerald-800 font-bold text-left">Ingredients</div>
                    <p class="mt-2 text-slate-500 text-left text-sm">
                        Looking to take your team away on a retreat to enjoy awesome food and take in some sunshine? We have a list of places to do just that.
                    </p>
                </div>
            </div>
        </div>
        </div>
        
        <br>
        <!--Segundo sensible design -->
        <div class="p-10 max-w-4xl bg-gray-200 rounded-xl shadow-lg flex items-center justify-center space-x-4">
            <div class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-4xl">
                <div class="md:flex">
                    <div class="md:shrink-0">
                        <img class="h-48 w-full object-cover md:h-full md:w-48" src="/src/img/img7.jpg" alt="Modern building architecture">
                    </div>
                    <div class="p-8">
                        <div class="uppercase tracking-wide text-sm text-emerald-800 font-bold text-left">Headline Goes Here</div>
                        <p class="mt-2 text-slate-500 text-left text-sm">Looking to take your team away on a retreat to enjoy awesome food and take in some sunshine? We have a list of places to do just that.</p>
                    </div>
                </div>
                <div>
                    <h6 class="text-xl font-bold mb-5 px-5 text-left">My Amazing Headline Goes Here</h6>
                    <div class="flex items-center">
                        <div>
                            <p class="mt-2 text-slate-500 text-left text-sm">
                                Looking to take your team away on a retreat to enjoy awesome food.
                                Looking to take your team away on a retreat
                            </p>
                        </div>
                        <div class="flex justify-end">
                            <button id="third_button" class="mr-2">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-capsule-pill" viewBox="0 0 16 16">
                                    <path d="M11.02 5.364a3 3 0 0 0-4.242-4.243L1.121 6.778a3 3 0 1 0 4.243 4.243l5.657-5.657Zm-6.413-.657 2.878-2.879a2 2 0 1 1 2.829 2.829L7.435 7.536zM12 8a4 4 0 1 1 0 8 4 4 0 0 1 0-8m-.5 1.042a3 3 0 0 0 0 5.917zm1 5.917a3 3 0 0 0 0-5.917z" />
                                </svg>
                                <span>2X</span>
                            </button>
                            <button id="third_button" class="mr-2">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-clock-fill" viewBox="0 0 16 16">
                                    <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0M8 3.5a.5.5 0 0 0-1 0V9a.5.5 0 0 0 .252.434l3.5 2a.5.5 0 0 0 .496-.868L8 8.71z" />
                                </svg>
                                <span> DAILY</span>
                            </button>
                            <button id="third_button" class="mr-2">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="currentColor" class="bi bi-wrench-adjustable" viewBox="0 0 16 16">
                                    <path d="M16 4.5a4.5 4.5 0 0 1-1.703 3.526L13 5l2.959-1.11q.04.3.041.61" />
                                    <path d="M11.5 9c.653 0 1.273-.139 1.833-.39L12 5.5 11 3l3.826-1.53A4.5 4.5 0 0 0 7.29 6.092l-6.116 5.096a2.583 2.583 0 1 0 3.638 3.638L9.908 8.71A4.5 4.5 0 0 0 11.5 9m-1.292-4.361-.596.893.809-.27a.25.25 0 0 1 .287.377l-.596.893.809-.27.158.475-1.5.5a.25.25 0 0 1-.287-.376l.596-.893-.809.27a.25.25 0 0 1-.287-.377l.596-.893-.809.27-.158-.475 1.5-.5a.25.25 0 0 1 .287.376M3 14a1 1 0 1 1 0-2 1 1 0 0 1 0 2" />
                                </svg>
                                <span class="text-sm">MEAL</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</div>

<div class="bg-gray-300 py-10 px-80 p-10">
    <div class="container mx-auto px-4">
        <!-- Contenido del div -->
        <p class="text-left left-44">hohoh</p>
        <div>
            <img src="/src/img/pills.jpg" alt="#">
        </div>
    </div>
</div>

<div class="bg-gray-50 py-10">
    <div class="container mx-auto px-64">
        <!-- Contenido del div -->
        <div class="p-10 max-w-2xl bg-gray-100 rounded-xl shadow-lg flex items-center justify-center space-x-4">
            <div class="p-10 max-w-4xl bg-white rounded-xl shadow-lg flex items-center justify-center space-x-4">
                <div class="shrink-0">
                </div>
                <div>
                    <p class="text-orange-500 font-bold text-center">
                        180 Days Money Back Guarantee
                    </p>
                    <div class="text-xl font-medium text-black text-left">
                        <h4 class="text-2xl font-bold mb-2 px-10 ">My Amazing Headline Goes Here</h4>
                    </div>
                    <p class="text-slate-500">
                        I am baby retro chillwave letterpress smal batch beard, paleo ugh banjo hot chicken godard craft beer.
                        Biodiesel pork belly green juice VHS farm-to-table- taxidermy heirloom scenester.
                    </p>
                </div>
            </div>
        </div>

    </div>
</div>
<div class="bg-orange-300 py-5">
    <div class="container mx-auto px-4">
        <!-- Contenido del div -->
        <div class="flex justify-around">
            <div class="order-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="#e7e5e4" class="bi bi-shield-check" viewBox="0 0 16 16">
                    <path d="M5.338 1.59a61 61 0 0 0-2.837.856.48.48 0 0 0-.328.39c-.554 4.157.726 7.19 2.253 9.188a10.7 10.7 0 0 0 2.287 2.233c.346.244.652.42.893.533q.18.085.293.118a1 1 0 0 0 .101.025 1 1 0 0 0 .1-.025q.114-.034.294-.118c.24-.113.547-.29.893-.533a10.7 10.7 0 0 0 2.287-2.233c1.527-1.997 2.807-5.031 2.253-9.188a.48.48 0 0 0-.328-.39c-.651-.213-1.75-.56-2.837-.855C9.552 1.29 8.531 1.067 8 1.067c-.53 0-1.552.223-2.662.524zM5.072.56C6.157.265 7.31 0 8 0s1.843.265 2.928.56c1.11.3 2.229.655 2.887.87a1.54 1.54 0 0 1 1.044 1.262c.596 4.477-.787 7.795-2.465 9.99a11.8 11.8 0 0 1-2.517 2.453 7 7 0 0 1-1.048.625c-.28.132-.581.24-.829.24s-.548-.108-.829-.24a7 7 0 0 1-1.048-.625 11.8 11.8 0 0 1-2.517-2.453C1.928 10.487.545 7.169 1.141 2.692A1.54 1.54 0 0 1 2.185 1.43 63 63 0 0 1 5.072.56" />
                    <path d="M10.854 5.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 7.793l2.646-2.647a.5.5 0 0 1 .708 0" />
                </svg>
            </div>

            <div>
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="#e7e5e4" class="bi bi-bank" viewBox="0 0 16 16">
                    <path d="m8 0 6.61 3h.89a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H15v7a.5.5 0 0 1 .485.38l.5 2a.498.498 0 0 1-.485.62H.5a.498.498 0 0 1-.485-.62l.5-2A.5.5 0 0 1 1 13V6H.5a.5.5 0 0 1-.5-.5v-2A.5.5 0 0 1 .5 3h.89zM3.777 3h8.447L8 1zM2 6v7h1V6zm2 0v7h2.5V6zm3.5 0v7h1V6zm2 0v7H12V6zM13 6v7h1V6zm2-1V4H1v1zm-.39 9H1.39l-.25 1h13.72z" />
                </svg>

            </div>

            <div>
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="#e7e5e4" class="bi bi-cash-coin" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M11 15a4 4 0 1 0 0-8 4 4 0 0 0 0 8m5-4a5 5 0 1 1-10 0 5 5 0 0 1 10 0" />
                    <path d="M9.438 11.944c.047.596.518 1.06 1.363 1.116v.44h.375v-.443c.875-.061 1.386-.529 1.386-1.207 0-.618-.39-.936-1.09-1.1l-.296-.07v-1.2c.376.043.614.248.671.532h.658c-.047-.575-.54-1.024-1.329-1.073V8.5h-.375v.45c-.747.073-1.255.522-1.255 1.158 0 .562.378.92 1.007 1.066l.248.061v1.272c-.384-.058-.639-.27-.696-.563h-.668zm1.36-1.354c-.369-.085-.569-.26-.569-.522 0-.294.216-.514.572-.578v1.1zm.432.746c.449.104.655.272.655.569 0 .339-.257.571-.709.614v-1.195z" />
                    <path d="M1 0a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h4.083q.088-.517.258-1H3a2 2 0 0 0-2-2V3a2 2 0 0 0 2-2h10a2 2 0 0 0 2 2v3.528c.38.34.717.728 1 1.154V1a1 1 0 0 0-1-1z" />
                    <path d="M9.998 5.083 10 5a2 2 0 1 0-3.132 1.65 6 6 0 0 1 3.13-1.567" />
                </svg>
            </div>
        </div>

    </div>
</div>

<div class="bg-teal-900 py-5">
    <div class="container mx-auto px-4">
        <!-- Contenido del div --><img src="/src/img/img5.png" class="w-full py-0 px-0" alt="">
        <p>hola</p>
    </div>
</div>
</template>

<style scoped>
.logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
}

.logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
    filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
