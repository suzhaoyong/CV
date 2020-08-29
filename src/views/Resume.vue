<!--
 * @Descripttion: 
 * @version: 
 * @Author: suzhoayong
 * @Date: 2020-08-29 14:50:29
 * @LastEditors: suzhoayong
 * @LastEditTime: 2020-08-29 14:50:57
-->
<template>
    <div class="resume">
        <resumen-head class="resume__head" />
        <resumen-body class="resume__body" />
    </div>
</template>
<script>
import { ResumenHead, ResumenBody } from '@/components/resumen'
export default {
    components: {
        ResumenHead,
        ResumenBody
    }
}
</script>
<style lang="stylus" scoped>
.resume
    background #fff
    width 1000px
    min-height calc(100vh - 40px)
    padding: 10px 20px
    margin 20px auto
    box-shadow 0 1px 10px #ccc
    display flex
    flex-wrap wrap
    flex-direction column
    transition box-shadow 1.5s
    &:hover
        box-shadow 0 1px 10px #000
    &__head
        margin-bottom 20px
    &__body
        flex-grow 1
        
</style>