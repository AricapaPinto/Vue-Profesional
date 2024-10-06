<template>
    <div class="post-card">
        <h3>Titulo</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique magnam iusto iste sapiente. Voluptas dolorem exercitationem assumenda, consequuntur, a non ducimus amet quo mollitia cupiditate quod? Reiciendis laboriosam placeat unde?</p>
        <PostButton/>
    </div>
</template>
<script lang="ts" setup>
    import PostButton from './PostButton.vue';

</script>

<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    border: 1px solid #ccc;
    margin: 5px;
}
</style>