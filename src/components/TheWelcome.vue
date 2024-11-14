<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import BookIcon from './icons/IconBook.vue'
import IconHardDrive from './icons/IconHardDrive.vue'
import ProjectIcon from './icons/IconProject.vue'
import IconConnect from './icons/IconConnect.vue'
import stylex from '@stylexjs/stylex'
</script>
<script lang="ts">
let s = stylex.create({})
</script>

<template>
    <WelcomeItem>
        <template #icon>
            <BookIcon />
        </template>
        <template #heading>History</template>

        US Navy for 20 years. Now retired and waisting time writeing a power fanatasy.
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <IconHardDrive />
        </template>
        <template #heading>Languages</template>

        I can use Vue, Javascript, Typescript, CSS, Sass, StyleX, HTML, MySQL, and Java to help get
        your website off paper and onto the web.

        <br />
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <ProjectIcon />
        </template>
        <template #heading>People I Have Helped</template>

        <a href="https://N0PR.org" target="_blank">NOPR Macon County Amature Radio Club</a>
    </WelcomeItem>

    <WelcomeItem>
        <template #icon>
            <IconConnect />
        </template>
        <template #heading>Lets Connect</template>
        <a href="mailto:ira.m.huff@gmail.com">Ira Huff</a>
    </WelcomeItem>
</template>
