<template>
    BUG：navbar里面添加的tabs展示不出来
    <nut-navbar @on-click-back="" @on-click-title="" @on-click-clear="" @on-click-send="" desc="编辑" icon="horizontal">
        <template v-slot:tabs>
            <nut-tab>
                <nut-tab-panel tab-title="商品"><p class="content">这里的tab展示不出来</p></nut-tab-panel>
                <nut-tab-panel tab-title="店铺"><p class="content">这里的tab展示不出来</p></nut-tab-panel>
            </nut-tab>
        </template>
    </nut-navbar>
</template>

<script setup>
</script>

<style>
    html, body {
        margin: 0;
        padding: 0;
    }

    #app {
    }
</style>
