<template>
    <div>
        <b-nav tabs fill >
            <b-nav-item>
                <b-link :to="{ path: '/' }">top</b-link>
            </b-nav-item>
            <b-nav-item>
                <b-link :to="{ path: 'about' }" exact>prof</b-link>
            </b-nav-item>
            <b-nav-item>skill</b-nav-item>
            <b-nav-item>contact</b-nav-item>
        </b-nav>
    </div>
</template>


