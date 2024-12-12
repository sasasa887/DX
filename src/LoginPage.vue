<template>
	<div>
    <Header></Header>
	メールアドレス		<input type="text">
	<br>
	パスワード		<input type="text">
		<br>
	<button>新規登録</button>
	<br>
	<button>ログイン</button>
	<Footer></Footer>
	</div>
</template>

<script setup>
import Header from "./components/AppHeader.vue";
import Footer from "./components/AppFooter.vue";
</script>

<style>
.div{
	background-color: #FFFFFF;
}

.input{
	
}
</style>