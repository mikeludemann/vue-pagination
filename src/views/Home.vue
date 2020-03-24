<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
		<!--<pagination-numbers/>-->
		<pagination :data='[
      { content: "Element 1"},
      { content: "Element 2"},
      { content: "Element 3"},
      { content: "Element 4"},
      { content: "Element 5"},
      { content: "Element 6"},
      { content: "Element 7"},
      { content: "Element 8"},
      { content: "Element 9"},
      { content: "Element 10"},
      { content: "Element 11"},
      { content: "Element 12"},
      { content: "Element 13"},
      { content: "Element 14"},
      { content: "Element 15"},
      { content: "Element 16"}
    ]'></pagination>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
//import paginationNumbers from '@/components/pagination-numbers.vue';
import pagination from '@/components/pagination.vue';

export default {
	name: 'Home',
	components: {
		HelloWorld,
		//paginationNumbers,
		pagination
	}
}
</script>
