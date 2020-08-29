<!--
 * @Descripttion: 
 * @version: 
 * @Author: suzhoayong
 * @Date: 2020-08-29 14:50:29
 * @LastEditors: suzhoayong
 * @LastEditTime: 2020-08-29 14:50:57
-->
<template>
    <div>
        <resumen-head />
        <resumen-body />
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