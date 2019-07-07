<template>
    <div>
        <!-- <side-bar></side-bar>
        <nav-bar></nav-bar> -->
        <Footer/>
    </div>
</template>

<script>
    import SideBar from './TheSideBar'
    import NavBar from './TheNavBar'
    import Footer from './TheFooter'

    export default {
        components: {
            SideBar,
            NavBar,
            Footer
        }
    }
</script>
