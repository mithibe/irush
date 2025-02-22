<script setup lang="ts">
</script>
<template>
    <nav>
        <ul>
            <li><a href="#Home">1</a></li>
            <li><a href="#About">2</a></li>
            <li><a href="#Services">3</a></li>
            <li><a href="#Contact">4</a></li>
        </ul>
    </nav>
    <div class="Page Hero" id="Home">
        <div class="MajorSection first">
            <h1>Graphics, Animation and Web Development --- Fast & Flawless!</h1>
            <p>
                Everyone is always in a rush, but that doesn't mean you should compromise on quality. At I-Rush, we specialize in delivering stunning graphic design, highquality animation and cutting-edge web development quickly and efficiently. Whether it's your project, your boss's deadline or your friend's request, we make it happen.
            </p>
            <button>CONTACT US</button>
        </div>
        <div class="MajorSection  second">
            <img src="../assets/I-Rush-Logo.svg" alt="">
        </div>
    </div>
    <div class="Page About" id="About">
        <div class="MajorSection first">
            <img src="../assets/About-Us-Graphics.svg" alt="">
        </div>
        <div class="MajorSection second">
            <h1>ABOUT US</h1>
            <p>
                At I-Rush, we are a team of skilled professionals with extensive experience in graphic design, animation and web development. We have successfully executed numerous project, bringing creative visions to life with precision and expertise. Our commitement to excellence and efficiency ensures that every project we undertake meets the highest standards of quality. We thrive on innovation and delivering results that leave a lasting impact.
            </p>
        </div>
    </div>
    <div class="Page Services" id="Services">
        <div class="MajorSection first">
            <h1>SERVICES</h1>
            <ul>
                <li>Graphic Design - Stunning visuals that capture your brand's identity, from logos and branding to marketing materials and UI/UX design.</li>
                <li>Animation - Bring ideas to life with high-quality 2D & 3D animations, motion graphics and explainer videos.</li>
                <li>Web Development - Custom-built websites, e-commerce platforms and web application designed for performance and user experience.</li>
            </ul>
        </div>
        <div class="MajorSection second"></div>
    </div>
    <!-- <div class="Page Projects">
        <div class="MajorSection first"></div>
        <div class="MajorSection second"></div>
    </div>
    <div class="Page Testimonials">
        <div class="MajorSection first"></div>
        <div class="MajorSection second"></div>
    </div> -->
    <div class="Page Contact" id="Contact"></div>
</template>

<style scoped>
    html, body{
        height: 100%;
        margin: 0;
        padding: 0;
    }
    template{
        min-height: 100%;
        overflow:hidden;
        scroll-behavior: smooth;
        /* scroll-snap-type: mandatory; */
    }

    nav{
        position: fixed;
        right: 100px;
        min-height: 100vh;
        border: none;
    }

    nav ul{
        position: relative;
        height: 100vh;
        /* border: 1px solid #aaa; */
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
    }

    ul a{
        /* padding: 10px; */
        height: 50px;
        width: 50px;
        display: flex;
        align-items: center;
        justify-content: center;
        border: 2px solid #333;
        border-radius: 50%;
        transition: 1000ms ease-in-out;
    }

    ul a:hover{
        background: #c6d728;
        color: #333;
    }

    /* li{
        padding: 10px 20px;
        position: relative;
    }

    li::after {
        content: "";
        position: absolute;
        top: 50%;
        right: -12px;
        width: 24px;
        height: 2px;
        background: white;
        transform: translateY(-50%);
    }

    li:last-child::after{
        display: none;
    } */

    /* ul::before{
        content: "";
        position: absolute;
        width: 100%;
        height: 2px;
        background:white;
        bottom: 0;
        left: 0;
    } */

    .Page{
        min-height: 100vh;
        display: flex;
        border: 2px solid #c6d728;
    }

    .MajorSection{
        /* position: relative; */
        max-width: 50%;
        /* height: 100%; */
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        border: 2px solid #aaa;
        flex-grow: 1;
        margin: 0;
        padding: 0;
    }

    img{
        max-width: 100%;
        width: auto;
        display: block;
    }

    h1{
        color: #c6d728;
        font-weight: 700;
    }

    button{
        background: #c6d728;
        color: #333;
        height: 50px;
        width: 150px;
        font-size: 20px;
        font-weight: 700;
        border-radius: 10px;
        border: none;
    }
</style>