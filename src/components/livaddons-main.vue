<script setup lang="ts">
import { Icon } from "@iconify/vue"
</script>
<template>
    <div class="mainclass">
        <div class="discord">
            <a href="https://discord.gg/">
                <span>Join our official Discord server</span>
            </a>
        </div>
        <div class="navbar">
            <div class="title">
                <span>LivvyaAddons</span>
            </div>
        </div>
        <div class="hero">
            <span class="bigass-text">Livvya Addons.</span>
            <span class="subtitle">More than dungeons. More than cosmetics. A journey worth remembering.</span>
            <div class="sources">
                <a href="https://modrinth.com/mod/livaddons">Download on Modrinth (soon)</a>
                <a href="https://modrinth.com/mod/livaddons">Download on GitHub</a>
            </div>
        </div>
        <div class="content">

        </div>
        <div class="footer">

        </div>
    </div>
</template>
<style scoped>
.discord {
    background-color: #252a66;
    text-align: center;
    padding: 10px;
    box-sizing: border-box;
    a {
        color: white;
        text-decoration: none;
    }
}
.sources {
    display: flex;
    flex-direction: row;
    gap: 5px;
    margin-top: 10px;
    a {
        color: white;
        background-color: rgb(26, 26, 26);
        text-decoration: none;
        padding: 5px;
        border-radius: 5px;
    }
}
.mainclass {
    width: 100%;
    height: 100vh;
    background-color: rgb(0, 0, 0);
    display: flex;
    flex-direction: column;
}
.navbar {
    width: 80%;
    padding: 10px;
    margin: 20px auto;
    border-radius: 5px;
    justify-content: center;
    align-items: center;
    display: flex;
}
    .title {
        display: flex;
        flex-direction: row;
        align-items: center;
        gap: 10px;
        img {
            width: 32px;
        }
        span {
            color: white;
            font-size: 1.2rem;
        }
    }
.hero {
    width: 80%;
    margin: 0 auto;
    align-items: center;
    display: flex;
    flex-direction: column;

    .bigass-text {
        color: rgb(255, 255, 255);
        font-size: 5rem;
        font-weight: 300;
        letter-spacing: 10px;
    }
    .subtitle {
        color: white;
        font-size: 1.2rem;
        font-style: italic;
    }
}
</style>