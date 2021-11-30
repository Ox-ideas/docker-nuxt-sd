<template>
    <div id='mypage'>
        <h1>My Own Page</h1>
        <h2>MyPage.vue in src/views/</h2>
        <MyComp />
    </div>
</template>

<script>
import MyComp from '@/components/MyComp'
export default {
    components: {
        MyComp
    }
}
</script>