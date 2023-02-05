<script setup >
import { ref } from 'vue'


</script>

<template>
    <div class="">
        <div class="mb-5">
            <lable>
                <slot>請輸入文字</slot>
            </lable>
            <div class="flex w-full">
                <select class="w-1/6 border border-solid border-gray-300 rounded-l-lg px-2">
                    <option>思兔閱讀</option>
                    <option>小說王</option>
                </select>
                <input type="text"
                    class="w-4/6 form-control block  px-3 py-1.5 text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 transition ease-in-outm-0 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none"
                    id="exampleFormControlInput1" placeholder="Example label" />
                <button class="w-1/6 border border-solid border-gray-300 rounded-r-lg px-2s">搜尋</button>
            </div>
        </div>
    </div>
</template>

<style scoped>

</style>
