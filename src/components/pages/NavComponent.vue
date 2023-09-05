<template>
    <nav>
        <figure>
            <a href="#">
                <img src="../../assets/Logo.png" alt="logo">
            </a>
        </figure>
        <ul class="bigger-menu">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <section class="nav-links">
            <a href="mailto:riki.nakayashiki@gmail.com?subject=A Message from the portfolio">
                <i class="fa-solid fa-envelope" style="color: #0E7EBD;"></i>
            </a>
            <a href="https://www.linkedin.com/in/riki-nakayashiki-92193b262/" target="_blank">
                <i class="fa-brands fa-linkedin" style="color: #0E7EBD;"></i>
            </a>
            <a href="https://github.com/riki-nakayashiki" target="_blank">
                <i class="devicon-github-original" style="color: #0E7EBD;"></i>
            </a>
            <a href="https://drive.google.com/file/d/1rTlhGE22EVmRtgYfpiIsRmwIz5HJohij/view?usp=sharing" target="_blank">
                <i class="fa-regular fa-file-lines" style="color: #0E7EBD;"></i>
            </a>
        </section>
    </nav>
    <details class="smaller-menu">
        <!-- <summary class="fa-solid fa-bars"></summary> -->
        <summary></summary>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </details>
</template>

<script>
export default {
    name: 'NavComponent'
}
</script>