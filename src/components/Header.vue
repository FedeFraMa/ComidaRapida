<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <slot></slot>
        
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
            <slot name="grupo"></slot>
        </li>
    </ul>
    </div>
</nav>
</template>