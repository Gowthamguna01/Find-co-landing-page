<script setup>

</script>

<template>
    <section>
        <div class="container mx-auto lg:py-12 md:py-6 py-12">

            <!--section 1-->
            <div class="grid md:grid-cols-4 grid-cols-1 gap-4 my-6">

                <div class="pt-14 md:block hidden">
                    <img src="/images/image1.png" alt="Your Image">
                </div>

                <div class="col-span-2">
                    <h1 class="lg:text-6xl md:text-4xl text-4xl font-bold font-serif text-center">A place for your</h1>
                    <h1 class="lg:text-6xl md:text-4xl text-4xl font-bold font-serif text-center lg:leading-24 md:leading-20 leading-16">perfect <span class="text-[#9747FF]">dream job</span></h1>
                    <p class="text-md font-medium text-slate-350 text-center py-8 leading-6 md:px-4 px-4">Lets find a perfect dream job that will make you fell your the one to be chosen.Build and scale with confidence</p>
                </div>

                <div class="lg:block md:block hidden">
                    <img src="/images/botsit.png" alt="Your Image" />
                </div>
            </div>

            <!--section 2 search bar-->
            <div class="flex justify-center my-10 mx-10 lg:mx-0 md:mx-12">
                <div class="py-3 px-3 border border-slate-200 lg:rounded-full md:rounded-full rounded-xl w-full max-w-3xl">

                    <div class="lg:flex md:flex lg:justify-between md:justify-between">

                        <div class="flex pl-6 pt-2 content-center">

                            <span class="py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-5">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z" />
                                </svg>
                            </span>

                            <p class="text-slate-400 flex text-md px-1 py-1">Job title or keyword</p>

                            <span class="py-2">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="size-5">
                                <path fill-rule="evenodd" d="M5.22 8.22a.75.75 0 0 1 1.06 0L10 11.94l3.72-3.72a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L5.22 9.28a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd" />
                            </svg>
                            </span>

                        </div>

                        <div class="flex pt-2 lg:pl-0 md:pl-0 pl-6">

                             <span class="py-1">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-5.5">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z" />
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z" />
                                </svg>
                             </span>

                            <p class="text-slate-400 flex text-md py-1 ">Location</p>
                        </div>

                        <div class="flex pt-2 lg:pl-0 md:pl-0 pl-7">
                            <p class="text-slate-400 flex text-md py-1">Remotely</p>

                            <span class="py-2">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="size-5">
                                <path fill-rule="evenodd" d="M5.22 8.22a.75.75 0 0 1 1.06 0L10 11.94l3.72-3.72a.75.75 0 1 1 1.06 1.06l-4.25 4.25a.75.75 0 0 1-1.06 0L5.22 9.28a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd" />
                            </svg>
                            </span>
                        </div>

                        <div class="flex lg:px-0 md:px-0 px-14  lg:my-0 md:my-0 my-4 md-ml-0 ml-6">
                            <a href="" class="bg-[#9747FF] rounded-full text-white px-4 py-2 font-medium lg:text-lg md:text-lg text-md ">Search Job</a>
                        </div>

                    </div>
                </div>
            </div>


            <!--section 3 Trending searches-->
            <div class="lg:my-34 md:my-34 my-16">

                <h1 class="font-bold text-2xl font-serif flex justify-center">Trending searches</h1>

                <div class="flex justify-center  my-4 lg:mx-0 md:mx-6 mx-4">
                    <div class="grid lg:grid-cols-6 md:grid-cols-3 grid-cols-2  lg:gap-10 md:gap-4 gap-4 py-4 flex text-center text-lg">
                        <a href="" class="border border-slate-300 rounded-full  lg:py-3 md:py-6 py-3 px-3 font-medium my-3">Remote job</a>
                        <a href="" class="border border-slate-300 rounded-full  lg:py-3 md:py-6 py-3 px-3 font-medium my-3">web designer</a>
                        <a href="" class="border border-slate-300 rounded-full  lg:py-3 md:py-6 py-3 px-3 font-medium my-3">Product designer</a>
                        <a href="" class="border border-slate-300 rounded-full  lg:py-3 md:py-6 py-3 px-3 font-medium my-3">Development</a>
                        <a href="" class="border border-slate-300 rounded-full  lg:py-3 md:py-6 py-3 px-3 font-medium my-3">Ui designer</a>
                        <a href="" class="border border-slate-300 rounded-full  lg:py-3 md:py-6 py-3 px-3 font-medium my-3">Ux designer</a>
                    </div>
                </div>



            </div>

            <!--section 4 How it-->
            <div class="my-28 lg:mx-16 md:mx-16 mx-14">

                <p class="text-[#9747FF] text-md font-medium  text-center">HOW IT WORKS</p>

                <h1 class="text-4xl font-serif font-bold text-center py-7">Simple steps to get your next job</h1>


                <div class="grid lg:grid-cols-3 md:lg:grid-cols-3 grid-cols-1 gap-12 py-8">

                    <!--div1 star-->
                    <div class="border border-gray-100 shadow-xl rounded-md py-14 lg:px-8 md:px-8 px-4">

                        <!--icon head-->
                        <div class="flex justify-center py-5">
                            <div class="rounded-full p-4 w-fit bg-gray-300">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="size-6">
                                    <path fill-rule="evenodd" d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401Z" clip-rule="evenodd" />
                                </svg>
                            </div>
                        </div>

                        <!--icon content-->
                        <div class="px-4">
                            <h1 class="text-lg font-bold font-serif py-2 text-center">Register your account</h1>

                            <p class="font-medium text-center text-slate-400">
                                Starts with introduce your self and the employer
                                why you're apply for this job.
                            </p>
                        </div>

                    </div>

                    <!--div2 upload-->
                    <div class="border border-gray-100 shadow-xl rounded-md py-14 lg:px-8 md:px-8 px-4">

                        <!--icon head-->
                        <div class="flex justify-center py-6">
                            <div class="rounded-full p-4 w-fit bg-blue-300 ">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                                    <path d="M11.47 1.72a.75.75 0 0 1 1.06 0l3 3a.75.75 0 0 1-1.06 1.06l-1.72-1.72V7.5h-1.5V4.06L9.53 5.78a.75.75 0 0 1-1.06-1.06l3-3ZM11.25 7.5V15a.75.75 0 0 0 1.5 0V7.5h3.75a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3v-9a3 3 0 0 1 3-3h3.75Z" />
                                </svg>
                            </div>
                        </div>

                        <!--icon content-->
                        <div>
                            <h1 class="text-lg font-bold font-serif py-2 text-center">Update Resume</h1>

                            <p class="font-medium text-center text-slate-400">
                               An initial step for your job search is <br>
                                to write an effective resume.
                            </p>
                        </div>
                    </div>

                    <!--div3 job-->
                    <div class="border border-gray-100 shadow-xl rounded-md py-14 lg:px-8 md:px-8 px-4">

                        <!--icon head-->
                        <div class="flex justify-center py-6">
                            <div class="rounded-full p-4 w-fit bg-yellow-300 ">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-6">
                                    <path fill-rule="evenodd" d="M7.5 5.25a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v.205c.933.085 1.857.197 2.774.334 1.454.218 2.476 1.483 2.476 2.917v3.033c0 1.211-.734 2.352-1.936 2.752A24.726 24.726 0 0 1 12 15.75c-2.73 0-5.357-.442-7.814-1.259-1.202-.4-1.936-1.541-1.936-2.752V8.706c0-1.434 1.022-2.7 2.476-2.917A48.814 48.814 0 0 1 7.5 5.455V5.25Zm7.5 0v.09a49.488 49.488 0 0 0-6 0v-.09a1.5 1.5 0 0 1 1.5-1.5h3a1.5 1.5 0 0 1 1.5 1.5Zm-3 8.25a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Z" clip-rule="evenodd" />
                                    <path d="M3 18.4v-2.796a4.3 4.3 0 0 0 .713.31A26.226 26.226 0 0 0 12 17.25c2.892 0 5.68-.468 8.287-1.335.252-.084.49-.189.713-.311V18.4c0 1.452-1.047 2.728-2.523 2.923-2.12.282-4.282.427-6.477.427a49.19 49.19 0 0 1-6.477-.427C4.047 21.128 3 19.852 3 18.4Z" />
                                </svg>
                            </div>
                        </div>

                        <!--icon content-->
                        <div>
                            <h1 class="text-lg font-bold font-serif py-2 text-center">Apply for a new job</h1>

                            <p class="font-medium text-center text-slate-400">
                                You'll want to make it precise for <br>
                                the job role you have applied.
                            </p>
                        </div>
                    </div>


                </div>

            </div>

        </div>

        <!-- div section 4 Featured Jobs-->
        <div class="bg-gray-100">
            <div class="container mx-auto py-6 lg:px-20 md:px-10 px-4 ">
                <div class="my-8 lg:py-12 md:py-8 py-2">
                    <div class="grid lg:grid-cols-3 md:grid-cols-3 grid-cols-1 gap-4">

                        <div class="col-span-2">
                            <p class="font-medium text-base text-[#9747FF] my-2">JOBS NEAR ME</p>
                            <p class="text-5xl font-bold my-6">Featured Jobs</p>
                            <p class="text-lg font-medium text-slate-500 my-6">Employee and employers way to find everything</p>
                        </div>

                        <!--left arrow-->
                        <div class="flex gap-6 py-6 pl-32 lg:block md:hidden hidden">

                            <div class="py-4">
                                <svg xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 24 24" fill="currentColor" class="size-8">
                                    <path stroke-width="22" fill-rule="evenodd" d="M11.03 3.97a.75.75 0 0 1 0 1.06l-6.22 6.22H21a.75.75 0 0 1 0 1.5H4.81l6.22 6.22a.75.75 0 1 1-1.06 1.06l-7.5-7.5a.75.75 0 0 1 0-1.06l7.5-7.5a.75.75 0 0 1 1.06 0Z" clip-rule="evenodd" />
                                </svg>
                            </div>


                            <!--right arrow-->
                            <div class="bg-[#9747FF] rounded-full h-fit w-fit p-4">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-8">
                                    <path fill-rule="evenodd" d="M12.97 3.97a.75.75 0 0 1 1.06 0l7.5 7.5a.75.75 0 0 1 0 1.06l-7.5 7.5a.75.75 0 1 1-1.06-1.06l6.22-6.22H3a.75.75 0 0 1 0-1.5h16.19l-6.22-6.22a.75.75 0 0 1 0-1.06Z" clip-rule="evenodd" />
                                </svg>
                            </div>

                        </div>
                    </div>
                </div>

                <!--box -->
                <div class="grid lg:grid-cols-3 md:grid-cols-2 grid-cols-1 lg:gap-6 md:gap-10 gap-4 py-4 lg:px-6 md:px-2 px-2">

                    <!--div 1 microsoft-->
                    <div class="bg-white shadow-xl rounded-2xl p-8">
                        <div class="flex gap-2">
                            <div class="bg-gray-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="34" height="34" viewBox="0 0 48 48">
                                    <path fill="#ff5722" d="M6 6H22V22H6z" transform="rotate(-180 14 14)"></path><path fill="#4caf50" d="M26 6H42V22H26z" transform="rotate(-180 34 14)"></path><path fill="#ffc107" d="M26 26H42V42H26z" transform="rotate(-180 34 34)"></path><path fill="#03a9f4" d="M6 26H22V42H6z" transform="rotate(-180 14 34)"></path>
                                    </svg>
                                </span>
                            </div>
                            <div class="pr-4">
                                <p class="text-md font-semibold">Microsoft</p>
                                <p class="text-xs">4days ago</p>
                            </div>
                        </div>

                        <div class="py-6">
                            <p class="text-2xl font-semibold p-2">Senior UI/UX developer with strong designer skills</p>
                            <div class="flex gap-4 mt-8">
                                <p href="" alt="" class="rounded-full bg-pink-200 px-4 py-2">Osla,Norway</p>
                                <p href="" alt="" class="rounded-full bg-gray-200 px-4 py-2 ">Partime</p>
                            </div>
                        </div>
                    </div>

                    <!--div 2 Ford-->
                    <div class="bg-white shadow-xl rounded-2xl p-8">
                        <div class="flex gap-2">
                            <div class="bg-gray-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="34" height="34" viewBox="0 0 100 100">
                                    <ellipse cx="50" cy="48.992" fill="#e3e2e3" rx="49" ry="20"></ellipse><ellipse cx="50" cy="48.992" fill="#375ca9" rx="45" ry="16"></ellipse><ellipse cx="50" cy="48.992" fill="none" stroke="#1f212b" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" stroke-width="2" rx="49" ry="20"></ellipse><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-miterlimit="10" d="M93.52,52.242 c-4.288,7-22.144,12.25-43.52,12.25c-24.577,0-44.5-6.94-44.5-15.5s19.923-15.5,44.5-15.5c9.052,0,17.473,0.941,24.5,2.559"></path><path fill="none" stroke="#1f212b" stroke-linecap="round" stroke-miterlimit="10" d="M81.351,37.992 c8.121,2.808,13.149,6.7,13.149,11"></path><path fill="#f5f9fc" d="M74.564,43.742c-0.17,0-0.256,0.021-0.336,0.177l0,0c-0.262,0.503-3.485,5.668-4.079,6.597l0,0 c-0.1,0.141-0.222,0.123-0.238-0.04l0,0c-0.06-0.552-0.537-1.186-1.289-1.491l0,0c-0.571-0.232-1.133-0.275-1.713-0.198l0,0 c-1.05,0.141-1.987,0.696-2.81,1.321l0,0c-1.242,0.942-2.311,2.166-3.693,3.067l0,0c-0.754,0.492-1.787,0.922-2.477,0.281l0,0 c-0.626-0.581-0.556-1.868,0.401-2.863l0,0c0.102-0.106,0.222-0.019,0.204,0.075l0,0c-0.09,0.451,0.021,0.899,0.362,1.214l0,0 c0.418,0.373,1.016,0.417,1.527,0.168l0,0c0.603-0.298,0.959-0.876,1.061-1.532l0,0c0.16-1.016-0.622-1.913-1.602-1.985l0,0 c-0.795-0.057-1.559,0.221-2.302,0.835l0,0c-0.371,0.309-0.584,0.537-0.907,0.995l0,0c-0.079,0.111-0.2,0.123-0.196-0.043l0,0 c0.038-1.302-0.501-2.034-1.578-2.058l0,0c-0.835-0.019-1.728,0.435-2.424,0.988l0,0c-0.762,0.613-1.429,1.423-2.143,2.187l0,0 c-0.089,0.094-0.168,0.09-0.192-0.09l0,0c-0.021-0.863-0.237-1.698-0.637-2.292l0,0c-0.141-0.207-0.437-0.309-0.688-0.17l0,0 c-0.115,0.062-0.516,0.247-0.809,0.483l0,0c-0.143,0.119-0.202,0.292-0.138,0.515l0,0c0.385,1.287,0.302,2.752-0.222,3.989l0,0 c-0.481,1.133-1.414,2.156-2.509,2.501l0,0c-0.722,0.23-1.474,0.117-1.938-0.522l0,0c-0.637-0.884-0.381-2.42,0.571-3.696l0,0 c0.841-1.123,2.053-1.836,3.265-2.298l0,0c0.143-0.055,0.172-0.147,0.132-0.268l0,0c-0.066-0.198-0.172-0.469-0.213-0.594l0,0 c-0.111-0.296-0.422-0.343-0.803-0.302l0,0c-0.88,0.102-1.674,0.403-2.458,0.824l0,0c-2.053,1.099-3.082,3.227-3.532,4.366l0,0 c-0.217,0.549-0.403,0.888-0.643,1.191l0,0c-0.322,0.407-0.729,0.777-1.474,1.431l0,0c-0.066,0.058-0.117,0.183-0.06,0.3l0,0 c0.077,0.156,0.464,0.703,0.571,0.75l0,0c0.121,0.058,0.262-0.023,0.317-0.064l0,0c0.52-0.352,1.142-0.91,1.448-1.289l0,0 c0.106-0.13,0.215-0.075,0.271,0.123l0,0c0.285,1.012,1.027,1.842,2.056,2.187l0,0c1.883,0.635,3.836-0.285,5.31-1.885l0,0 c0.937-1.016,1.274-1.672,1.634-2.115l0,0c0.607-0.754,1.808-2.441,3.238-3.523l0,0c0.524-0.401,1.146-0.705,1.455-0.503l0,0 c0.251,0.162,0.332,0.541-0.07,1.27l0,0c-1.457,2.663-3.746,5.921-4.14,6.68l0,0c-0.072,0.13-0.011,0.236,0.128,0.236l0,0 c0.763-0.004,1.519-0.002,2.211-0.002l0,0c0.115-0.006,0.168-0.058,0.224-0.141l0,0c1.118-1.749,2.315-3.549,3.442-5.272l0,0 c0.064-0.1,0.121-0.023,0.124,0.023l0,0c0.023,0.401,0.123,0.948,0.358,1.306l0,0c0.426,0.663,1.031,0.948,1.702,0.954l0,0 c0.532,0.006,0.803-0.075,1.376-0.288l0,0c0.469-0.175,0.846-0.401,1.133-0.609l0,0c0.168-0.117,0.198,0.079,0.194,0.109l0,0 c-0.258,1.389,0.062,3.037,1.442,3.719l0,0c1.653,0.814,3.47-0.332,4.516-1.365l0,0c0.102-0.1,0.211-0.089,0.222,0.124l0,0 c0.021,0.394,0.202,0.863,0.528,1.193l0,0c0.875,0.878,2.645,0.53,4.416-0.843l0,0c1.139-0.878,2.33-2.121,3.406-3.436l0,0 c0.041-0.051,0.07-0.132-0.011-0.217l0,0c-0.164-0.17-0.401-0.368-0.564-0.518l0,0c-0.074-0.062-0.183-0.045-0.245,0.004l0,0 c-1.103,1.048-2.096,2.245-3.532,3.235l0,0c-0.483,0.337-1.255,0.611-1.602,0.141l0,0c-0.136-0.183-0.119-0.435,0.015-0.765l0,0 c0.418-1.042,7.072-11.508,7.415-12.103l0,0c0.06-0.104,0-0.179-0.132-0.179l0,0c-0.682,0-1.576,0.002-2.286,0.002 M64.031,56.514 c-0.341-0.177-0.488-0.654-0.481-1.037l0,0c0.017-1.088,0.498-2.202,1.389-3.299l0,0c1.088-1.336,2.288-2.032,3.078-1.651l0,0 c0.816,0.388,0.554,1.335,0.19,2.075l0,0c-0.026,0.058-0.028,0.106-0.015,0.155l0,0c0.013,0.077,0.113,0.151,0.211,0.187l0,0 c0.036,0.013,0.055,0.038,0.015,0.119l0,0c-0.281,0.603-0.541,0.954-0.893,1.476l0,0c-0.324,0.484-0.69,0.863-1.135,1.227l0,0 c-0.516,0.426-1.186,0.882-1.817,0.882l0,0C64.391,56.648,64.206,56.608,64.031,56.514"></path><path fill="#f5f9fc" d="M39.32,38c-0.633,0-1.267,0.025-1.908,0.075l0,0c-4.071,0.343-7.945,2.637-7.954,6.115l0,0 c0,1.766,1.252,3.195,3.195,3.133l0,0c2.285-0.077,4.16-1.908,5.142-4.215l0,0c0.371-0.875-0.319-1.238-0.647-0.735l0,0 c-0.586,0.909-1.412,1.612-2.305,2.049l0,0c-1.074,0.528-2.224,0.385-2.571-0.49l0,0c-0.49-1.231,0.528-3.072,2.852-3.941l0,0 c3.355-1.242,6.867-0.42,10.245,0.215l0,0c0.049,0,0.228,0.1,0.068,0.183l0,0c-0.603,0.33-1.199,0.598-2.126,1.397l0,0 c-0.667,0.569-1.536,1.327-2.211,2.154l0,0c-0.667,0.814-1.142,1.542-1.768,2.345l0,0c-0.089,0.117-0.196,0.111-0.194,0.111l0,0 c-1.529,0.258-3.025,0.43-4.396,1.384l0,0c-0.283,0.196-0.407,0.543-0.234,0.809l0,0c0.155,0.236,0.507,0.26,0.75,0.083l0,0 c0.852-0.637,1.728-0.937,2.733-0.963l0,0c0.043,0.002,0.064,0.011,0.077,0.036l0,0c0.011,0.015,0,0.047-0.015,0.072l0,0 c-1.506,2.089-1.883,2.56-3.014,3.855l0,0c-0.581,0.665-1.15,1.227-1.787,1.811l0,0c-2.571,2.388-5.336,2.349-6.328,0.85l0,0 c-0.592-0.899-0.515-1.842-0.124-2.626l0,0c0.477-0.959,1.444-1.661,2.247-2.072l0,0c0.298-0.153,0.385-0.533,0.085-0.88l0,0 c-0.188-0.228-0.65-0.268-0.993-0.205l0,0c-1.054,0.196-2.298,0.991-3.033,1.949l0,0c-0.827,1.076-1.242,2.381-1.103,3.845l0,0 c0.249,2.645,2.426,4.171,4.895,4.154l0,0c1.966-0.017,3.819-0.611,6.047-2.873l0,0c2.079-2.111,3.97-5.261,5.742-8.183l0,0 c0.055-0.094,0.094-0.145,0.364-0.177l0,0c1.11-0.138,2.752-0.298,3.804-0.358l0,0c0.236-0.013,0.283-0.009,0.375,0.107l0,0 c0.275,0.345,0.686,0.639,1.016,0.816l0,0c0.16,0.089,0.238,0.13,0.364,0.134l0,0c0.156,0.004,0.277-0.081,0.354-0.17l0,0 c0.111-0.123,0.143-0.281,0.083-0.385l0,0c-0.062-0.107-0.797-0.515-0.82-0.679l0,0c-0.017-0.104,0.096-0.128,0.096-0.128l0,0 c0.539-0.17,1.101-0.516,1.44-1.169l0,0c0.334-0.641,0.388-1.499-0.224-1.974l0,0c-0.535-0.417-1.346-0.351-1.992,0.228l0,0 c-0.631,0.564-0.843,1.384-0.756,2.102l0,0c0.015,0.124,0.011,0.168-0.162,0.181l0,0c-0.973,0.077-1.909,0.104-2.952,0.158l0,0 c-0.07,0.006-0.09-0.041-0.051-0.09l0,0c1.199-2.085,2.991-3.568,4.971-5.029l0,0c0.13-0.098,0.09-0.285,0.085-0.441l0,0 c3.578,0.777,7.033,2.224,10.746,2.192l0,0c1.534-0.013,3.003-0.245,4.405-1.016l0,0c1.235-0.675,1.903-1.25,1.939-1.896l0,0 c0.03-0.449-0.281-0.729-0.724-0.635l0,0c-3.749,0.861-7.49,0.805-11.223,0.354l0,0C47.593,39.056,43.532,38,39.321,38l0,0 c0,0,0,0-0.011,0 M45.779,45.513c-0.055-0.396,0.075-0.927,0.498-1.302l0,0c0.211-0.188,0.5-0.232,0.677-0.081l0,0 c0.198,0.17,0.104,0.59-0.096,0.882l0,0c-0.217,0.322-0.588,0.599-0.926,0.667l0,0c-0.011,0.002-0.019,0.004-0.028,0.004l0,0 C45.851,45.681,45.804,45.642,45.779,45.513"></path>
                                    </svg>
                                </span>
                            </div>
                            <div class="pr-4">
                                <p class="text-md font-semibold">Ford</p>
                                <p class="text-xs">4days ago</p>
                            </div>
                        </div>

                        <div class="py-6">
                            <p class="text-2xl font-semibold p-2">Senior UI/UX developer with strong designer skills</p>
                            <div class="flex gap-4 mt-8">
                                <p href="" alt="" class="rounded-full bg-pink-200 px-4 py-2">Osla,Norway</p>
                                <p href="" alt="" class="rounded-full bg-gray-200 px-4 py-2 ">Partime</p>
                            </div>
                        </div>
                    </div>

                    <!--div 3 Nike-->
                    <div class="bg-white shadow-xl rounded-2xl p-8">
                        <div class="flex gap-2">
                            <div class="bg-gray-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="34" height="34" viewBox="0 0 50 50">
                                    <path fill-rule="evenodd" d="M 6.40625 16.800781 C 3.152344 20.621094 0 25.234375 0 28.902344 C 0 31.019531 1.78125 33.996094 6.132813 33.996094 C 8.484375 33.996094 10.820313 33.050781 12.648438 32.320313 C 15.730469 31.085938 49.789063 16.296875 49.789063 16.296875 C 50.117188 16.132813 50.058594 15.925781 49.644531 16.027344 C 49.480469 16.070313 12.566406 26.074219 12.566406 26.074219 C 11.855469 26.273438 11.128906 26.382813 10.421875 26.382813 C 7.230469 26.382813 5.078125 24.851563 5.078125 21.503906 C 5.078125 20.207031 5.484375 18.640625 6.40625 16.800781 Z"></path>
                                    </svg>
                                </span>
                            </div>
                            <div class="pr-4">
                                <p class="text-md font-semibold">Nike</p>
                                <p class="text-xs">4days ago</p>
                            </div>
                        </div>

                        <div class="py-6">
                            <p class="text-2xl font-semibold p-2">Senior UI/UX developer with strong designer skills</p>
                            <div class="flex gap-4 mt-8">
                                <p href="" alt="" class="rounded-full bg-pink-200 px-4 py-2">Osla,Norway</p>
                                <p href="" alt="" class="rounded-full bg-gray-200 px-4 py-2 ">Partime</p>
                            </div>
                        </div>
                    </div>

                    <!--div 4 apple -->
                    <div class="bg-white shadow-xl rounded-2xl p-8">
                        <div class="flex gap-2">
                            <div class="bg-gray-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="34" height="34" viewBox="0 0 30 30">
                                    <path d="M25.565,9.785c-0.123,0.077-3.051,1.702-3.051,5.305c0.138,4.109,3.695,5.55,3.756,5.55 c-0.061,0.077-0.537,1.963-1.947,3.94C23.204,26.283,21.962,28,20.076,28c-1.794,0-2.438-1.135-4.508-1.135 c-2.223,0-2.852,1.135-4.554,1.135c-1.886,0-3.22-1.809-4.4-3.496c-1.533-2.208-2.836-5.673-2.882-9 c-0.031-1.763,0.307-3.496,1.165-4.968c1.211-2.055,3.373-3.45,5.734-3.496c1.809-0.061,3.419,1.242,4.523,1.242 c1.058,0,3.036-1.242,5.274-1.242C21.394,7.041,23.97,7.332,25.565,9.785z M15.001,6.688c-0.322-1.61,0.567-3.22,1.395-4.247 c1.058-1.242,2.729-2.085,4.17-2.085c0.092,1.61-0.491,3.189-1.533,4.339C18.098,5.937,16.488,6.872,15.001,6.688z"></path>
                                    </svg>
                                </span>
                            </div>
                            <div class="pr-4">
                                <p class="text-md font-semibold">Apple</p>
                                <p class="text-xs">4days ago</p>
                            </div>
                        </div>

                        <div class="py-6">
                            <p class="text-2xl font-semibold p-2">Senior UI/UX developer with strong designer skills</p>
                            <div class="flex gap-4 mt-8">
                                <p href="" alt="" class="rounded-full bg-pink-200 px-4 py-2">Osla,Norway</p>
                                <p href="" alt="" class="rounded-full bg-gray-200 px-4 py-2 ">Partime</p>
                            </div>
                        </div>
                    </div>

                    <!--div 5 google-->
                    <div class="bg-white shadow-xl rounded-2xl p-8">
                        <div class="flex gap-2">
                            <div class="bg-gray-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="34" height="34" viewBox="0 0 48 48">
                                    <path fill="#fbc02d" d="M43.611,20.083H42V20H24v8h11.303c-1.649,4.657-6.08,8-11.303,8c-6.627,0-12-5.373-12-12	s5.373-12,12-12c3.059,0,5.842,1.154,7.961,3.039l5.657-5.657C34.046,6.053,29.268,4,24,4C12.955,4,4,12.955,4,24s8.955,20,20,20	s20-8.955,20-20C44,22.659,43.862,21.35,43.611,20.083z"></path><path fill="#e53935" d="M6.306,14.691l6.571,4.819C14.655,15.108,18.961,12,24,12c3.059,0,5.842,1.154,7.961,3.039	l5.657-5.657C34.046,6.053,29.268,4,24,4C16.318,4,9.656,8.337,6.306,14.691z"></path><path fill="#4caf50" d="M24,44c5.166,0,9.86-1.977,13.409-5.192l-6.19-5.238C29.211,35.091,26.715,36,24,36	c-5.202,0-9.619-3.317-11.283-7.946l-6.522,5.025C9.505,39.556,16.227,44,24,44z"></path><path fill="#1565c0" d="M43.611,20.083L43.595,20L42,20H24v8h11.303c-0.792,2.237-2.231,4.166-4.087,5.571	c0.001-0.001,0.002-0.001,0.003-0.002l6.19,5.238C36.971,39.205,44,34,44,24C44,22.659,43.862,21.35,43.611,20.083z"></path>
                                    </svg>
                                </span>
                            </div>
                            <div class="pr-4">
                                <p class="text-md font-semibold">Google</p>
                                <p class="text-xs">4days ago</p>
                            </div>
                        </div>

                        <div class="py-6">
                            <p class="text-2xl font-semibold p-2">Senior UI/UX developer with strong designer skills</p>
                            <div class="flex gap-4 mt-8">
                                <p href="" alt="" class="rounded-full bg-pink-200 px-4 py-2">Osla,Norway</p>
                                <p href="" alt="" class="rounded-full bg-gray-200 px-4 py-2 ">Partime</p>
                            </div>
                        </div>
                    </div>

                    <!--div 6 logitech-->
                    <div class="bg-white shadow-xl rounded-2xl p-8">
                        <div class="flex gap-2">
                            <div class="bg-gray-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="34" height="34" viewBox="0 0 48 48">
                                    <path fill="#74cccf" d="M24.066,44.453l0.212-7.854c0,0-11.42-3.226-11.929-12.481s11.815-12.29,11.815-12.29l0.963-8.979 c0,0-6.071-0.892-15.665,8.193S6.108,33.5,6.108,33.5S11.373,43.264,24.066,44.453z"></path><polygon fill="#74cccf" points="25,20.212 24.958,28.321 34.637,28.151 34.127,37.618 43.594,37.83 42.278,19.618"></polygon><path fill="#010101" d="M42.952,19.662c-0.008-0.329-0.275-0.488-0.53-0.48c-5.884-0.177-11.773,0.02-17.632,0.59 c-0.198,0.019-0.327,0.133-0.402,0.274c-0.108,0.08-0.186,0.203-0.188,0.378c-0.033,2.547-0.067,5.094-0.1,7.641 c-0.003,0.199,0.095,0.329,0.226,0.405c0.08,0.109,0.203,0.188,0.377,0.193c3.094,0.08,6.188,0.099,9.283,0.067 c0.047,1.327,0.179,2.657,0.183,3.978c0.002,0.802-0.145,1.622-0.274,2.411c-0.128,0.786-0.241,1.625-0.546,2.366 c-0.124,0.302,0.187,0.641,0.482,0.633c1.34-0.037,2.682-0.043,4.022-0.028c1.871,0.021,3.714,0.201,5.576,0.314 c0.254,0.016,0.521-0.242,0.5-0.5C43.431,31.834,43.105,25.751,42.952,19.662z M34.524,37.113c0.155-0.566,0.242-1.161,0.334-1.728 c0.139-0.853,0.293-1.734,0.308-2.6c0.014-0.835-0.112-1.686-0.144-2.523c-0.026-0.678-0.045-1.356-0.056-2.034 c-0.004-0.268-0.226-0.503-0.5-0.5c-3.121,0.039-6.242,0.017-9.363-0.059c0.03-2.31,0.06-4.62,0.091-6.93 c5.575-0.526,11.176-0.714,16.774-0.564c0.153,5.738,0.46,11.47,0.92,17.192c-1.679-0.112-3.347-0.258-5.036-0.278 C36.743,37.077,35.633,37.091,34.524,37.113z"></path><path fill="#010101" d="M24.39,36.298c-1.414-0.155-2.648-0.955-3.841-1.67c-1.138-0.682-2.276-1.389-3.223-2.328 c-0.471-0.467-0.882-0.989-1.364-1.444c-0.541-0.51-1.047-0.971-1.401-1.639c-0.613-1.158-1.076-2.501-1.403-3.766 c-0.882-3.41,0.739-6.969,3.235-9.291c2.227-2.071,5.071-2.941,7.903-3.85c0.154-0.049,0.321-0.177,0.349-0.349 c0.48-2.943,1.001-5.967,1.027-8.953c0.002-0.263-0.165-0.413-0.362-0.461c-0.019-0.007-0.031-0.019-0.052-0.024 c-2.6-0.61-5.126,0.581-7.385,1.753c-2.342,1.215-4.554,2.67-6.61,4.323c-1.176,0.945-2.415,1.916-3.326,3.132 c-0.738,0.985-1.37,2.052-1.928,3.147C4.208,18.416,3.185,22.416,3.482,26.4c0.189,2.535,0.837,5.06,2.208,7.219 c1.244,1.96,2.794,3.736,4.548,5.255c3.948,3.422,8.895,5.573,14.096,6.083c0.271,0.027,0.498-0.251,0.5-0.5 c0.019-2.553,0.038-5.106,0.057-7.659C24.892,36.506,24.658,36.328,24.39,36.298z M7.548,34.549 c-0.728-0.968-1.422-1.996-1.906-3.11c-0.48-1.104-0.774-2.311-0.974-3.495C4.005,24.026,4.764,19.959,6.4,16.368 c0.951-2.088,2.068-3.969,3.741-5.493c2.049-1.867,4.3-3.507,6.701-4.893c2.257-1.303,5.096-3.007,7.813-2.556 c-0.064,2.679-0.5,5.379-0.932,8.02c-2.65,0.851-5.268,1.705-7.455,3.501c-1.631,1.34-2.903,3.086-3.669,5.053 c-0.597,1.534-0.864,3.205-0.593,4.837c0.246,1.486,0.827,2.954,1.429,4.329c0.588,1.343,1.623,2.134,2.582,3.196 c1.114,1.234,2.424,2.163,3.842,3.019c1.279,0.772,2.56,1.551,4.029,1.836c-0.017,2.225-0.033,4.449-0.05,6.674 c-4.215-0.506-8.255-2.164-11.646-4.713C10.444,37.864,8.862,36.296,7.548,34.549z"></path>
                                    </svg>
                                </span>
                            </div>
                            <div class="pr-4">
                                <p class="text-md font-semibold">Logitech</p>
                                <p class="text-xs">4days ago</p>
                            </div>
                        </div>

                        <div class="py-6">
                            <p class="text-2xl font-semibold p-2">Senior UI/UX developer with strong designer skills</p>
                            <div class="flex gap-4 mt-8">
                                <p href="" alt="" class="rounded-full bg-pink-200 px-4 py-2">Osla,Norway</p>
                                <p href="" alt="" class="rounded-full bg-gray-200 px-4 py-2 ">Partime</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>

        <!--choose by category-->
        <div class="container mx-auto lg:my-24 md:my-24 my-16">

            <div class="py-12 text-center">
                <p class="text-base font-semibold text-[#9747FF] ">100+ JOBS CATEGORY</p>
                <h1 class="text-4xl font-serif font-bold mt-8">Choose by category</h1>
                <p class="text-slate-400 my-4">Employees and employers way to find everything</p>
            </div>

            <div class="grid lg:grid-cols-3 md:grid-cols-3 grid-cols-1 lg:mx-28 md:mx-12 mx-14 lg:gap-12 md:gap-6 gap-10">

                <!-- div1 work-->
                <div class="bg-white border border-slate-300 rounded-2xl p-10 ">
                    <div class="flex gap-2 flex justify-center">
                        <div class="bg-orange-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-12">
                                        <path fill-rule="evenodd" d="M7.5 5.25a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v.205c.933.085 1.857.197 2.774.334 1.454.218 2.476 1.483 2.476 2.917v3.033c0 1.211-.734 2.352-1.936 2.752A24.726 24.726 0 0 1 12 15.75c-2.73 0-5.357-.442-7.814-1.259-1.202-.4-1.936-1.541-1.936-2.752V8.706c0-1.434 1.022-2.7 2.476-2.917A48.814 48.814 0 0 1 7.5 5.455V5.25Zm7.5 0v.09a49.488 49.488 0 0 0-6 0v-.09a1.5 1.5 0 0 1 1.5-1.5h3a1.5 1.5 0 0 1 1.5 1.5Zm-3 8.25a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5Z" clip-rule="evenodd" />
                                        <path d="M3 18.4v-2.796a4.3 4.3 0 0 0 .713.31A26.226 26.226 0 0 0 12 17.25c2.892 0 5.68-.468 8.287-1.335.252-.084.49-.189.713-.311V18.4c0 1.452-1.047 2.728-2.523 2.923-2.12.282-4.282.427-6.477.427a49.19 49.19 0 0 1-6.477-.427C4.047 21.128 3 19.852 3 18.4Z" />
                                    </svg>
                                </span>
                        </div>
                    </div>

                    <div class="py-4 space-y-2  text-center">

                        <p class="text-2xl font-semibold ">Bussiness</p>
                        <p href="" alt="" class="text-xl text-slate-600">29+ vacencies</p>

                    </div>
                </div>

                <!-- div2 design-->
                <div class="bg-white border border-slate-300  rounded-2xl p-10 ">
                    <div class="flex gap-2 flex justify-center">
                        <div class="bg-green-300 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="size-12">
                                    <path fill-rule="evenodd" d="M13.5 4.938a7 7 0 1 1-9.006 1.737c.202-.257.59-.218.793.039.278.352.594.672.943.954.332.269.786-.049.773-.476a5.977 5.977 0 0 1 .572-2.759 6.026 6.026 0 0 1 2.486-2.665c.247-.14.55-.016.677.238A6.967 6.967 0 0 0 13.5 4.938ZM14 12a4 4 0 0 1-4 4c-1.913 0-3.52-1.398-3.91-3.182-.093-.429.44-.643.814-.413a4.043 4.043 0 0 0 1.601.564c.303.038.531-.24.51-.544a5.975 5.975 0 0 1 1.315-4.192.447.447 0 0 1 .431-.16A4.001 4.001 0 0 1 14 12Z" clip-rule="evenodd" />
                                    </svg>

                                </span>
                        </div>
                    </div>

                    <div class="py-4 space-y-2  text-center">
                        <p class="text-2xl font-semibold ">Design</p>
                        <p href="" alt="" class="text-xl text-slate-600">24+ vacencies</p>
                    </div>
                </div>

                <!-- div3 development-->
                <div class="bg-white border border-slate-300  rounded-2xl p-10 ">
                    <div class="flex gap-2 flex justify-center">
                        <div class="bg-yellow-400 w-fit rounded-lg px-2 mx-2 py-2">
                                <span>
                                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="size-12">
                                    <path d="M5.507 4.048A3 3 0 0 1 7.785 3h8.43a3 3 0 0 1 2.278 1.048l1.722 2.008A4.533 4.533 0 0 0 19.5 6h-15c-.243 0-.482.02-.715.056l1.722-2.008Z" />
                                    <path fill-rule="evenodd" d="M1.5 10.5a3 3 0 0 1 3-3h15a3 3 0 1 1 0 6h-15a3 3 0 0 1-3-3Zm15 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm2.25.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5ZM4.5 15a3 3 0 1 0 0 6h15a3 3 0 1 0 0-6h-15Zm11.25 3.75a.75.75 0 1 0 0-1.5.75.75 0 0 0 0 1.5ZM19.5 18a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z" clip-rule="evenodd" />
                                    </svg>
                                </span>
                        </div>
                    </div>

                    <div class="py-4 space-y-2  text-center">
                        <p class="text-2xl font-semibold ">Development</p>
                        <p href="" alt="" class="text-xl text-slate-600">50+ vacencies</p>
                    </div>
                </div>

            </div>

            <!--view all-->
            <div class="flex justify-center my-12">
                <a href="" src="" class="text-[#9747FF] border border-[#9747FF] rounded-full px-4 py-2 ">View all</a>
            </div>
        </div>

        <!--Pricing-->
        <div class="container mx-auto my-18">

            <div class="grid lg:grid-cols-4 md:grid-cols-2 grid-cols-1 lg:gap-6 md:gap-6 gap-6 lg:px-24 md:px-8 px-12 ">

                <!--our pricing-->
                <div class="lg:col-span-2 md:col-span-2 content-center lg:pl-0 md:pl-24 pl-0">
                    <div>
                        <p class="text-[#9747FF] font-medium">PRICING</p>

                        <h1 class="text-4xl font-serif font-bold pt-6">Our pricing for <br> employers</h1>

                        <p class=" text-lg text-slate-600 font-medium py-2">Better pricing then the others with less hassle</p>

                        <p class="text-[#9747FF] font-semibold rounded-full w-fit text-lg p-2 px-6 my-2 border border-[#9747FF]">View all pricing</p>
                    </div>
                </div>

                <!--div2 -->
                <div class="shadow-xl rounded-2xl p-10">

                    <div class="">
                        <h1 class="text-4xl font-serif font-bold text-center">Basic</h1>
                        <p class="text-medium text-slate-700 py-2 text-center">yearly package</p>
                        <p class="font-bold font-serif text-4xl py-2 text-center">$97.<sup>99</sup></p>
                        <p class="font-semibold text-slate-500 py-2 text-center mt-12">Anonymous user</p>
                        <p class="font-semibold text-slate-500 py-2 text-center">Bot detection</p>
                        <p class="font-semibold text-slate-500 py-2 text-center">Registration</p>
                        <p class="font-semibold text-slate-500 py-2 text-center">Directory</p>
                        <div class="flex justify-center my-4 cursor-pointer">
                            <a class="text-white  font-semibold rounded-full w-fit text-base p-2 px-4 bg-[#9747FF] ">Get started now</a>
                        </div>
                        </div>


                </div>

                <!--div3 -->
                <div class="shadow-xl rounded-2xl my-10">

                    <div class="">
                        <h1 class="text-4xl font-serif font-bold text-center">Premium</h1>
                        <p class="text-medium text-slate-700 py-2 text-center">yearly package</p>
                        <p class="font-bold font-serif text-4xl py-2 text-center">$107.<sup>99</sup></p>
                        <p class="font-semibold text-slate-500 text-lg py-2 text-center">Anonymous user</p>
                        <p class="font-semibold text-slate-500 text-lg py-2 text-center">Bot detection</p>
                        <p class="font-semibold text-slate-500 text-lg py-2 text-center">Registration</p>
                        <div class="flex justify-center my-4">
                            <p class="border border-[#9747FF]  font-semibold rounded-full w-fit text-base p-2 px-4 my-2 text-[#9747FF]">Get started now</p>
                        </div>
                    </div>
                </div>

            </div>

        </div>

        <!--Testimonals-->
        <div class="container mx-auto lg:my-34 md:my-18 my-14">

            <div class="text-center">
                <p class="text-md font-semibold text-[#9747FF] py-2">TESTIMONIALS</p>
                <h1 class="py-2 font-bold font-serif text-5xl my-8">What our customers say</h1>
            </div>

            <div class="flex justify-center">
                <div class="lg:my-8 md:my-4 my-4 flex max-w-4xl">
                <div class="grid lg:grid-cols-3 md:grid-cols-3 grid-cols-1 lg:gap-2 md:gap-2 gap-10 ">

                    <!--image-->
                    <div class="pl-12 lg:pt-0 md:pt-6 pt-0">
                        <img src="/images/professional_img4.webp" alt="Your Image" class="rounded-full rounded-full " />
                    </div>

                    <div class="col-span-2 lg:py-12 md:py-10 py-4 lg:px-8 md:px-8 px-16">

                        <div class="flex justify-center">
                            <p class="lg:text-3xl md:text-3xl text-2xl font-serif font-semibold">"Learning curve infrastructure value proposition advisor strategy user experience hypothesis investor."</p>
                        </div>

                        <div class="py-6">
                            <p class="text-md font-medium">LARRY D, MANAGER,<span class="text-slate-400"> PRODUCT @BEHANCE</span></p>
                        </div>
                    </div>

                </div>
            </div>
            </div>


        </div>

        <!--updates are the real process-->
        <div class="container mx-auto lg:my-18 md:my-10 my-10 ">

            <div class="bg-pink-50 rounded-lg lg:p-18 md:p-18 p-6 lg:mx-32 md:mx-20 mx-10">
                <p class="lg:text-4xl md:text-4xl text-2xl font-serif font-bold text-center py-6 px-4">Updates are the real process</p>

                    <div class="lg:flex lg:justify-center md:flex md:justify-center md:gap-4 space-y-4 my-4">
                        <div class="lg:mx-0 md:mx-0 mx-5">
                            <input class="bg-white text-slate-500 rounded-full py-3 px-8" placeholder="Email Address">
                        </div>

                        <div class="lg:mx-0 md:mx-0 mx-5">
                            <p class="text-white text-center  font-semibold rounded-full text-base py-3 px-8 bg-[#9747FF]">Subscribe</p>
                        </div>
                    </div>
            </div>
        </div>

    </section>
</template>

<style scoped>

</style>
