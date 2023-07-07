<template>
    <nav>
        <figure>
            <a href="#">
                <img src="../../assets/Logo.png" alt="logo">
            </a>
        </figure>
        <section class="nav-links">
            <a href="mailto:riki.nakayashiki@gmail.com?subject=A Message from Riki's portfolio">
                <i class="fa-solid fa-envelope"></i>
            </a>
            <a href="https://www.linkedin.com/in/riki-nakayashiki-92193b262/" target="_blank">
                <i class="fa-brands fa-linkedin" style="color: #095cec;"></i>
            </a>
            <a href="https://github.com/riki-nakayashiki" target="_blank">
                <i class="devicon-github-original colored"></i>
            </a>
            <a href="../../assets/resume.pdf" target="_blank">
                <i class="fa-solid fa-file-pdf" style="color: #3de70d;"></i>
            </a>
        </section>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'NavComponent'
}
</script>