<script></script>
<template>
    <div class="navbar">
        <a href="" class="navbar-opener">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-three-dots"
                viewBox="0 0 16 16">
                <path
                    d="M3 9.5a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3m5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3m5 0a1.5 1.5 0 1 1 0-3 1.5 1.5 0 0 1 0 3" />
            </svg>
        </a>    
    </div>
</template>
<style>
    .navbar {
        top: 0em;
        position: absolute;
        display: inline-block;
        background-color: var(--pico-background-color);
        border: 1px solid var(--pico-form-element-border-color);             
        width: 80%;
        left: 0;
        height: 2em;
        /* opacity: 0; */
        transform: translateY(-10px);
        transition: all 0.3s;
    }
    .navbar-opener {
        top: 15pt;
        left: 5pt;
        position: absolute;
        border-radius: var(--pico-border-radius);
        border: 1px solid var(--pico-form-element-border-color);        
        background-color: var(--pico-background-color);
        padding-left: .5em;
        padding-right: .5em;        
        padding-bottom: 0;        
        vertical-align: bottom;
    }
    .navbar-opener svg {
        position: relative;
        top: 5px;
    }
</style>