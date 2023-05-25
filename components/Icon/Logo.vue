<template>
	<nav 
        flex="~ row" px5 py5 lg:px44 xl:px64 justify-between items-center transition  
        :class="'lg:py32'"
    >
        <NuxtLink to="/" tag="a">
            <img 
                h6 transition-height duration-400
                :src=" '/triple-helix-logo2.png'" 
                alt="Triple Helix Logo"
                :class=" 'lg:h24' "
            >
        </NuxtLink>
		</nav>
	 
</template>
