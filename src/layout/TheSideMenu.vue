<template>
    <aside class="column is-2 has-background-dark">
        <h1 class="title has-text-primary">Vue Buefy</h1>

        <ul class="menu-list">
            <li>
                <a href="#" :class="{ 'is-active': activeNum == 0 }" @click="changeActiveLink(0)">
                <span class="icon"><i class="fa fa-home"></i></span> Home
                </a>
            </li>
            <li>
                <a href="#" :class="{ 'is-active': activeNum == 1 }" @click="changeActiveLink(1)">
                <span class="icon"><i class="fa fa-book"></i></span> Other
                </a>
                <ul>
                <li>
                    <a href="#" :class="{ 'is-active': activeNum == 10 }" @click="changeActiveLink(10)">
                    <span class="icon is-small"><i class="fa fa-link"></i></span> Twitter
                    </a>
                </li>
                <li>
                    <a href="#" :class="{ 'is-active': activeNum == 11 }" @click="changeActiveLink(11)">
                    <span class="icon is-small"><i class="fa fa-link"></i></span> Qiita
                    </a>
                </li>
                </ul>
            </li>
            <li>a
                <a href="#" :class="{ 'is-active': activeNum == 13 }" @click="changeActiveLink(13)">
                <span class="icon"><i class="fa fa-info"></i></span> About
                </a>
            </li>
        </ul>
    </aside>
</template>

<script>
export default {

}
</script>