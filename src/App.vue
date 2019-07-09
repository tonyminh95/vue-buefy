<template>
	<div id="app">
		<div class="main-content columns is-fullheight">
			<side-menu></side-menu>
			<!-- <div class="container column is-10">
				<router-view/>
			</div> -->
		</div>
	</div>
</template>

<script>
	import SideMenu from './layout/TheSideMenu'

	export default {
		name: 'app',

		components: {
			SideMenu
		}
	}
</script>
