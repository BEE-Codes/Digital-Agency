<script setup>
</script>

<template>
    <nav class="w-full h-[100px] flex px-16 items-center justify-between text-[16px] text-[#5D5D5D] font-Inter hover:cursor-pointer">
        <div class="flex justify-between w-[70%]">
            <img src="./assets/Images/logo.png" alt="" class="w-[15%] h-[25px]">
            <router-link to="" class="text-[#00A283] font[700]">Home</router-link>  
            <router-link to="">About Us</router-link>
            <router-link to="">Services</router-link>
            <router-link to="">Pages</router-link>
            <router-link to="">Blog</router-link>
            <router-link to="">FAQ</router-link>
            <router-link to="">Contact Us</router-link>
        </div>

        <div class="flex w-[15%] items-center justify-evenly text-[18px]">
            <p class=" text-[#00826C] ">Log in</p>
            <button class="bg-[#00826C] px-5 py-2 border rounded-lg text-white">Sign Up</button>
        </div>
    </nav>

    <section class="w-full flex pt-5 justify-evenly font-Inter">
        <div class="w-[50%] ml-10 ">
                <h1 class="text-[60px] leading-[72px] font-[600] w-[95%] pb-1">
                    Design is not just what it looks like and feels like. Design is how it works.
                </h1>
                <p class="text-[18px] leading-[28px] w-[98%] my-8 text-[#5D5D5D] ">
                    We are a digital agency that helps businesses thrive in the online world.
                    Our team of experts combines creativity and technology to deliver exceptional results
                </p>
                <div class="w-[45%] flex justify-between">
                    <button class="border px-7 py-2 rounded-lg bg-[#00826C] text-white font-[600] text-[18px]">Let's Start</button>
                    <button class="border px-7 py-2 rounded-lg border-[#00826C] text-[#00826C] text-[18px] font-[600]">Read More </button>
                </div>
        </div>

        <div class="w-40% text-white">
            <img src="./assets/Images/sample.png" alt="" class="w-[598px] h-[448px] pt-10">
            <div class="w-[412px] bg-[#00826C] rounded-md ml-[29%] mb-0 py-7 -translate-16">
                <h3 class="text-[30px] font-[700] pl-8">
                    Web Design
                </h3>
                <div class="ml-8 w-64 ">
                    <p class="text-[18px]">
                        Create stunning websites that captivate your audience.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section class="w-full justify-evenly flex font-Inter">
        <div class="w-[45%] ml-10">
            <div class="w-[80%] flex justify-evenly mb-6 items-center"> 
                <div class="w-[80%]">
                    <h4 class="text-[30px] font-[600] leading-[38px] text-[#110804]">Web Design</h4>
                    <p class="text-[18px] leading-[27px]font-[300] text-[#5D5D5D] font-Roboto">
                        We create stunning websites that captivate your audience and drive results
                    </p>
                </div>
                <div class="w-[23.33px] h-[23.33px]">
                    <img src="./assets/Images/arrowup.png" alt="">
                </div>
            </div>

            <div class="w-[80%] flex justify-evenly items-center mb-6"> 
                <div class="w-[80%]">
                    <h4 class="text-[30px] font-[600] leading-[38px] text-[#110804]">SEO Services</h4>
                    <p class="text-[18px] leading-[27px]font-[300] text-[#5D5D5D] font-Roboto">
                        Improve your online visibility and drive organic traffic with our SEO strategies
                    </p>
                </div>
                <div  class="w-[23.33px] h-[23.33px]">
                    <img src="./assets/Images/arrowup.png" alt="">
                </div>
            </div>

            <div class="w-[80%] flex justify-evenly mb-6 bg-[#00826C] rounded-lg items-center py-2"> 
                <div class="w-[80%]">
                    <h4 class="text-[30px] font-[600] leading-[38px] text-white">Social Media</h4>
                    <p class="text-[18px] leading-[27px]font-[300] text-[#D1D1D1] font-Roboto">
                    Engage and grow your audience with our effective social media marketing campaigns
                    </p>
                </div>
                <div class=" w-[23.33px] h-[23.33px]">
                    <img src="./assets/Images/rightarrow.png" alt="">
                </div>
            </div>
            
            <div class="w-[80%] flex justify-evenly items-center"> 
                <div class="w-[80%]">
                    <h4 class="text-[30px] font-[600] leading-[38px] text-[#110804]">Content Marketing</h4>
                    <p class="text-[18px] leading-[27px]font-[300] text-[#5D5D5D] font-Roboto">
                        Deliver valuable and engaging content that drives traffic and conversions
                    </p>
                </div>
                <div class="w-[23.33px] h-[23.33px]">
                    <img src="./assets/Images/arrowup.png" alt="">
                </div>
            </div>
        </div>

        <div class="w-[45%] font-Inter">
            <div class="">
                <h6 class="text-[16px] font-[400] text-[#5D5D5D]">
                    OUR SERVICES
                </h6>
                <h1 class="text-[#006656] text-[48px] font-[600] leading-[60px]">
                    Revolutionizing Enterprises through Digital Solutions
                </h1>
            </div>
            <div class="">
                <img src="./assets/Images/marketing.png" alt="">
            </div>
        </div>

    </section>

    <section class="w-full flex p-10 justify-between items-center font-Inter">
        <div class="w-[40%]">
            <img src="./assets/Images/work.png" alt="" class="w-[494px] h-[544px]">
        </div>

        <div class="w-[50%]">
            <div class="w-[552px]">
                <h1 class="text-[48px] text-[#00826C] font-[600] leading-[60px]">
                Unlock the Potential of Our Digital Solutions
                </h1>

                <p class="text-[16px] text-[#5D5D5D] font-[400] leading-[24px] pt-8">
                    Discover how our expertise and innovative strategies have helped businesses achieve remarkable success
                </p>
            </div>

            <div class="flex pt-10 justify-between">
                <div class="w-[40%]">
                    <h1 class="text-[#00826C] text-[48px] font-[600] leading-[60px]">50%</h1>
                    <p class="text-[16px] text-[#000000] font-[400] leading-[24px]">Increase your online visibility and drive more conversions</p>
                </div>
                <div class="w-[50%]">
                    <h1 class="text-[#00826C] text-[48px] font-[600] leading-[60px]">50%</h1>
                    <p class="text-[16px] text-[#000000] font-[400] leading-[24px]">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros.</p>
                </div>
            </div>
        </div>
    </section>
    <section class="w-full mb-10 font-Inter">
        <div class="w-[85%] m-auto">
            <h1 class="text-[#00826C] text-[48px] font-[600] leading-[60px] text-center">Some Creative Works</h1>
            <p class=" text-[#5D5D5D] text-[18px] font-[400] leading-[28px] text-center py-7">
                Lorem ipsum dolor sit amet consectetur. 
                Sit quis viverra at fermentum commodo urna. Malesuada netus semper sagittis fermentum. Nisl neque tortor ultricies risus interdum.
            </p>
            <div class="flex justify-between">
                <div class="w-[70%] flex justify-between items-center text-[#1D2939] text-[20px] font-[400] leading-[32px]">
                    <router-link to="" class="text-[#00826C] font-[700]">All</router-link>
                    <router-link to="">Web Development</router-link> 
                    <router-link to="">Web Design</router-link>
                    <router-link to="">Plug in Development Design</router-link>
                </div>
                <button class="border px-5 py-2 rounded-lg border-[#00826C] text-[#00826C] font-[600] text-[18px] leading-[28px]">More Work</button>
            </div>
        </div>
        <div class="images mt-10 w-[85%] m-auto">
            <div class="flex justify-between">
                <img src="./assets/Images/placeholder(1).png" alt="" class="w-[558px] h-[450px]">
                <img src="./assets/Images/Place holder(2).png" alt="" class="w-[558px] h-[450px]">
            </div>
            <div class="flex justify-between mt-7">
                <img src="./assets/Images/Placeholder(3).png" alt="" class="w-[558px] h-[450px]">
                <img src="./assets/Images/Placeholder (4).png" alt="" class="w-[558px] h-[450px]">
            </div>
        </div>
    </section>

    <section class="w-full font-Inter">
        <div class="w-[60%] m-auto">
            <h6 class="text-[#5D5D5D] text-[16px] font-[400] leading-[24px] text-center py-7">OUR TEAM</h6>
            <h1 class="text-[#00826C] text-[48px] font-[600] leading-[60px] text-center">The most qualified and talented individuals </h1>
            <p class=" text-[#5D5D5D] text-[18px] font-[400] leading-[28px] text-center py-7">
                Our team excels through expertise, collaboration, and unwavering commitment, ensuring exceptional results for every project
            </p>
        </div>

        <div class="w-[85%] m-auto">
            <div class="flex">
                <div class="w-[380px] h-[400px] grid place-items-center  hover:shadow-lg hover:rounded-lg border-r border-[#E7E7E7]">
                    <div>
                        <img src="./assets/Images/akhalas.png" alt="">
                    </div>
                    <h1 class="text-[#00826C] text-[24px] font-[600] ">Akhalas Amin</h1>
                    <p class="text-[16px] text-[#5D5D5D] font-[400] -mt-20">Web Developer</p>
                </div>

                <div class="w-[380px] h-[400px] grid place-items-center border-b border-[#E7E7E7] hover:shadow-lg hover:rounded-lg ">
                    <div>
                        <img src="./assets/Images/refat.png" alt="">
                    </div>
                    <h1 class="text-[#00826C] text-[24px] font-[600] ">Rifat Ahmed</h1>
                    <p class="text-[16px] text-[#5D5D5D] font-[400] -mt-20">Web Developer</p>
                </div>

                <div class="w-[380px] h-[400px] grid place-items-center  hover:shadow-lg hover:rounded-lg border-l border-[#E7E7E7]">
                    <div>
                        <img src="./assets/Images/naeem.png" alt="">
                    </div>
                    <h1 class="text-[#00826C] text-[24px] font-[600] ">Naeem Rahman</h1>
                    <p class="text-[16px] text-[#5D5D5D] font-[400] -mt-20">Web Developer</p>
                </div>
            </div>

            <div class="flex">
                <div class="w-[380px] h-[400px]  grid place-items-center hover:shadow-lg hover:rounded-lg border-t border-[#E7E7E7]">
                    <div>
                        <img src="./assets/Images/mumeet.png" alt="">
                    </div>
                    <h1 class="text-[#00826C] text-[24px] font-[600] ">Mumeet Pathan</h1>
                    <p class="text-[16px] text-[#5D5D5D] font-[400] -mt-20">Web Developer</p>
                </div>

                <div  class="w-[380px] h-[400px] grid place-items-center hover:shadow-lg hover:rounded-lg border-l border-r border-[#E7E7E7]">
                    <div>
                        <img src="./assets/Images/ome.png" alt="">
                    </div>
                    <h1 class="text-[#00826C] text-[24px] font-[600] ">Ome Ahmed</h1>
                    <p class="text-[16px] text-[#5D5D5D] font-[400] -mt-20">Web Developer</p>
                </div>

                <div  class="w-[380px] h-[400px] grid place-items-center hover:shadow-lg hover:rounded-lg border-t border-[#E7E7E7]">
                    <div>
                        <img src="./assets/Images/kibria.png" alt="">
                    </div>
                    <h1 class="text-[#00826C] text-[24px] font-[600]">AKibria Talha</h1>
                    <p class="text-[16px] text-[#5D5D5D] font-[400] -mt-20">Web Developer</p>
                </div>
            </div>
        </div>
    </section>

    <section class="w-full mb-10 font-Inter">
        <div class="w-[50%] m-auto">
            <p class="pt-10 text-[#00826C] text-[48px] font-[600] leading-[60px] text-center ">How Others Describe Our Services</p>
            <div class="mt-16">
                <div class="w-[112px] h-[112px] m-auto -mb-11">
                    <img src="./assets/Images/zulfikar.png" alt="">
                </div>
                <div class="border border-[#EDEDED] rounded-lg pt-20 pb-7">
                    <p class="text-center w-[85%] text-[#5D5D5D] text-[18px] font-[400] leading-[28px] m-auto">
                        "The creative agency provided innovative solutions and a fresh perspective. 
                        Their team was responsive and delivered high-quality work within our timelines.
                        Overall, a valuable partner for our creative needs."
                    </p>
                    <h6 class="text-center py-3 text-[#1F1F1F] text-[18px] font-[600] leading-[28px]">Zulfikar Mohammad</h6>
                    <h6 class="text-center text-[#5D5D5D] text-[16px] font-[400] leading-[24px]">Web Developer</h6>
                </div>
            </div>
        </div>
    </section>
    <section class="w-full font-Inter">
        <h1 class="text-[#00826C] text-[48px] font-[600] leading-[60px] text-center py-20">
            Frequently Asked Questions
        </h1>
        <div class="flex justify-evenly">
            <div class="w-[45%]">

                <div class="w-full py-6  mb-5 rounded-lg shadow-lg">
                    <div class="flex justify-evenly items-center py-2"> 
                        <div class=" w-[23.33px] h-[23.33px]">
                            <img src="./assets/Images/minus.png" alt="">
                        </div>
                        <div class="w-[80%]">
                            <h4 class="text-[18px] font-[600] leading-[28px] text-[#1F1F1F] pb-2">How long until we deliver your first blog post?</h4>
                            <p class="text-[14px] leading-[20px]font-[400] text-[#5D5D5D]">
                                It takes 2-3 weeks to get your first blog post ready. That includes the in-depth research & creation 
                                of your monthly content marketing strategy that we MUST do before writing your first blog post.                            
                            </p>
                        </div> 
                    </div>
                </div>

                <div class="w-full rounded-lg shadow-lg mb-5">
                    <div class="flex justify-evenly items-center py-5"> 
                        <div class=" w-[23.33px] h-[23.33px]">
                            <img src="./assets/Images/plus.png" alt="">
                        </div>
                        <div class="w-[80%]">
                            <p class="text-[18px] leading-[27px]font-[300] text-[#4B423E]">
                            How long until we deliver your first blog post?
                            </p>
                        </div> 
                    </div>
                </div>
            </div>

            <div class="w-[45%]">
                <div class="w-full rounded-lg shadow-lg mb-5">
                    <div class="flex justify-evenly items-center py-5"> 
                        <div class=" w-[23.33px] h-[23.33px]">
                            <img src="./assets/Images/plus.png" alt="">
                        </div>
                        <div class="w-[80%]">
                            <p class="text-[18px] leading-[27px]font-[300] text-[#4B423E]">
                            How long until we deliver your first blog post?
                            </p>
                        </div> 
                    </div>
                </div>

                <div class="w-full rounded-lg shadow-lg mb-5">
                    <div class="flex justify-evenly items-center py-5 "> 
                        <div class=" w-[23.33px] h-[23.33px]">
                            <img src="./assets/Images/plus.png" alt="">
                        </div>
                        <div class="w-[80%]">
                            <p class="text-[18px] leading-[27px]font-[300] text-[#4B423E]">
                            How long until we deliver your first blog post?
                            </p>
                        </div> 
                    </div>
                </div>

                <div class="w-full rounded-lg shadow-lg">
                    <div class="flex justify-evenly items-center py-5"> 
                        <div class=" w-[23.33px] h-[23.33px]">
                            <img src="./assets/Images/plus.png" alt="">
                        </div>
                        <div class="w-[80%]">
                            <p class="text-[18px] leading-[27px]font-[300] text-[#4B423E]">
                                How long until we deliver your first blog post?
                            </p>
                        </div> 
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="font-Inter">
        <div class="bg-[#00826C] w-[70%] m-auto py-9 rounded-lg text-white translate-15">
            <h1 class="text-center text-[48px] font-[700] leading-[60px] mb-5">Subscribe Newsletter</h1>
            <p class="text-center text-[18px] font-[400] leading-[28px] w-[40%] m-auto mb-10"> 
                We operate our banking services in many countries around the world.
            </p>
            <div class="w-[50%] ml-[26%] flex justify-between">
                    <input type="text" placeholder="yourmail@email.com" 
                    class="px-4 py-2 border rounded-lg font-[400] text-[16px]"/>
                <button class="px-7 py-2 rounded-lg bg-[#EBFEF7] text-[#00826C] font-[600] text-[18px]">Get Started</button>
            </div>
        </div>
    
        <div class="w-full bg-[#00302A] pt-32 text-white">
            <div class="flex w-[90%] ml-11 justify-between">
                <div class="logo w-[70%]">
                    <img src="./assets/Images/logo.png" alt="">
                    <p class="text-[14px] font-[600] leading-[20px] mt-8">Address:</p>
                    <p class="text-[14px] font-[400] leading-[20px] text-[#F6F6F6] mb-8" >Level 1, 12 Santinagar St, Dhaka-1000, Bangladesh</p>
                    <p class="text-[14px] font-[600] leading-[21px]">Contact:</p>
                    <p class="text-[14px] font-[400] leading-[20px] text-[#F6F6F6]">+880 178 190 7745</p>
                    <p class="text-[14px] font-[400] leading-[20px] text-[#F6F6F6] underline mb-8">muntasir1710@gmail.com</p>
                    <div class="flex justify-between w-[20%]">
                        <img src="./assets/Images/circle.png" alt="">
                        <img src="./assets/Images/faceboo.png" alt="">
                        <img src="./assets/Images/x.png" alt="">
                        <img src="./assets/Images/Vector (5).png" alt="">
                        <img src="./assets/Images/linkdln.png" alt="">
                    </div>
                </div>

                <div class="flex w-[20%] justify-between">
                    <div class="">
                        <ul class=" text-[16px] font-[600] leading-[30px] text-[#F6F6F6]">
                            <li><a href="">Link 1</a></li>
                            <li><a href="">Link 2</a></li>
                            <li><a href="">Link 3</a></li>
                            <li><a href="">Link 4</a></li>
                            <li><a href="">Link 5</a></li>
                        </ul>
                    </div>
                    <div class="">
                        <ul class=" text-[16px] font-[600] leading-[30px] text-[#F6F6F6]">
                            <li><a href="">Link 6</a></li>
                            <li><a href="">Link 7</a></li>
                            <li><a href="">Link 8</a></li>
                            <li><a href="">Link 9</a></li>
                            <li><a href="">Link 10</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <img src="./assets/Images/Divider.png" alt="" class="w-[1250px] mt-20 ml-11">
            <div class=" flex w-[93%] ml-11 justify-between pt-7 pb-15">
                <p class="w-[80%] text-[14px] font-[400] leading-[20px] text-[#F6F6F6]">© 2023 MMahmud. All rights reserved.</p>

                <div class="flex w-[20%] justify-between">
                    <p class="underline text-[14px] font-[400] leading-[20px] text-[#F6F6F6]">Privacy Policy</p>
                    <p class="underline text-[14px] font-[400] leading-[20px] text-[#F6F6F6]">Terms of Service</p>
                </div>
            </div>

        </div>
    </footer>

</template>
<style scoped>

</style>
