<template>
    <div class="nav-bar">
            <div class="nav-logo">
                <img src="../assets/logo.png"/>
            </div>
            <div class="nav-navigation">
                <div class="nav-link">
                    <a href="http://">About Me</a>
                </div>
                <div class="nav-link">
                    <a href="http://">Projects</a>
                </div>
                <div class="nav-link">
                    <a href="http://">Links</a>
                </div>
                <div class="nav-link">
                    <a href="http://">Contact</a>
                </div>
            </div>
    </div>
    <div class="main-container">
        <div class="about-me">
            <div class="profile-pic">
                <img src="../assets/icons8-avatar-48.png" alt="">
                <p class="labels">Uppalapu Bala Bhuvan Varma</p>
            </div>
            <div class="about-me-description">
                <p class="section-header">
                    About Me
                </p>
                Software Developer
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Illo, fuga quis. Soluta earum error, voluptatibus debitis rerum fugit, vero nostrum pariatur quos, aperiam possimus repellat minima aliquid et beatae quibusdam?
            </div>
        </div>

        <div class="projects">
            <div class="project-card">
                project1
            </div>
            <div class="project-card">
                project2
            </div>
            <div class="project-card">
                project3
            </div>
        </div>

        <div class="hyper-links">
            <a href="http://">
                <img src="../assets/github-logo.png">
                <p class="labels">
                    GitHub
                </p>
            </a>
            <a href="http://">
                <img src="../assets/icons8-linkedin-logo-50.png">
                <p class="labels">
                    LinkedIn
                </p>
            </a>
            <a href="http://">
                <img src="../assets/icons8-resume-50.png">
                <p class="labels">
                    My Resume
                </p>
            </a>
        </div>

        <div class="contact">
            contact Info
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>


<style scoped >

    .about-me-description {
        padding-left: 10%;
        text-align: left;
    }
    .section-header {
        font-size: xx-large;
        font-weight: 900;
        
    }

    .profile-pic{
        width: 40%;
        border-right: 1px solid darkgreen;
    }
    .profile-pic > img {
        height: 15rem;
    }
    .labels {
        text-decoration: solid;
        font-size: large;
        font-weight: 600;
    }

    .profile-pic > .labels {
        color: black;
        font-size: x-large;
        font-weight: 900;
    }

    .nav-bar {
        display: flex;
        flex-direction: row;
        align-content: center;
        justify-content: space-between;
        background-color: rgb(0, 0, 0);
        border-bottom: 2rem;
        height: 2rem;
        position: fixed;
        top: 0;
        left: 0;
        padding-top: 1rem;
        padding-bottom: 1rem;
        width: 100%;
        overflow: hidden;
        z-index: 1;
    }

    .nav-logo > img {
        height: 90%;
    }

    .nav-navigation {
        display: flex;
        flex-direction: row;
        justify-content: right;
        align-items:center;
        align-content: flex-end;
        gap: 2rem;
    }

    .nav-link {
        width: 5rem;
        margin-right: 2rem;
    }

    .nav-link > a:link {
        color: rgb(22, 174, 123);
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        font-weight: bolder;
        text-transform: capitalize;
        text-decoration: solid;
    }

    .nav-link > a:hover {
        color: rgb(255, 255, 255);
        font-size: large;
        font-weight: 800;
    }

    .about-me{
        height: 100vh;
        margin-top: 4rem;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        background-color: rgb(47, 170, 129);
    }

    

</style>