<template>
    <div></div>
    <center>
    <h1 class="font-extrabold">Public Beta 6 </h1>
    
    <NuxtLink></NuxtLink>
  </center>
</template>
<style>

@tailwind base;
@tailwind components;
@tailwind utilities;

:root {
  --foreground-rgb: 0, 0, 0;
  --background-start-rgb: 214, 219, 220;
  --background-end-rgb: 255, 255, 255;
}

@media (prefers-color-scheme: dark) {
  :root {
    --foreground-rgb: 255, 255, 255;
    --background-start-rgb: 0, 0, 0;
    --background-end-rgb: 0, 0, 0;
  }
}

body {
  color: rgb(var(--foreground-rgb));
  background: rgb(0,0,0);
  background: linear-gradient(90deg, rgba(0,0,0,1) 0%, rgba(2,0,36,1) 66%, rgba(0,85,244,1) 100%);
}

h1 {
  padding-top: 5rem;
  padding-bottom: 5rem;
  font-size: 3.75rem;
line-height: 1rem;
}


    </style>