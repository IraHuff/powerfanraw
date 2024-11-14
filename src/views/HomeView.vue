<script setup lang="ts">
import stylex from '@stylexjs/stylex'
</script>
<script lang="ts">
const s = stylex.create({
    text: {
        color: 'lightblue',
        'text-align': 'center',
        'font-size': '3rem'
    },
    flex: {
        display: 'flex',
        'justify-content': 'center',
        'align-items': 'center'
    },
    media: {
        '@media (max-width: 1024px)': {
            display: 'flex',
            'justify-content': 'center'
        }
    }
})
</script>

<template>
    <main :class="stylex(s.flex, s.media)">
        <p :class="stylex(s.text)">I am writeing a litRPG power fantasy that I will be posting and updateing here</p>
    </main>
</template>
