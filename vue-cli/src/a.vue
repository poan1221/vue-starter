// .vue 파일 싱글파일 컴포넌트 - 한 파일에 html / script / css 을 모두 다 넣음

// 기존에 이렇게 썻던걸 아래처럼 쓰면 됨
// var appHeader = {
//     template: '<div>header</div>',
//     methods: {
//         addNum: function() {

//         }
//     }
// }

<template>
<!-- Html -->
  <div>header</div>
</template>

<script>
export default {
    //script - 인스턴스 옵션
    methods: {
        addNum: function() {

        }
    }
}
</script>

<style>
/* css */
</style>