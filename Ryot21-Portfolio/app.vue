
<script setup lang="ts">
  useHead(
    {
      title: "Ryot21-Portfolio | WEBエンジニア",
      // link: [
        // {rel: "stylesheet", href: "https://fonts.googleapis.com/css2?family=Kanit:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap"}
      // ]
    }
  )
  // const { data: users } = await useFetch('')// 非同期データ取得
  // const { params } = useRoute();
  // definePageMeta({// 数字以外のパラメーターは「404エラー」を表示。
	// 	validate: async(route) => {
	// 		return /^\d+$/.test(route.params.id)
	// 	}
	// })
  
</script>

<template>
  <Header />
  <PartsHamburgerNavi />
  <div>
    <NuxtPage />
  </div>
  <Footer />
</template>

<style lang="scss">
body{
  background: url('/body_bg.png') repeat center top;
}
</style>