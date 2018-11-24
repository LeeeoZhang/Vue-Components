<template>
    <div class="divider">
        <span class="divider-title">{{title}}</span>
    </div>
</template>

<script>
    export default {
      props:['title'],
    }
</script>

<style>
    .divider {
        font-size: 16px;
        font-weight: 500;
        display: flex;
    }
    .divider > .divider-title {
        padding: 0 10px;
    }
    .divider:before,
    .divider:after {
        content: ' ';
        display: block;
        padding-bottom: 23px;
        border-top: 1px solid #e8e8e8;
        transform: translateY(50%);
    }
    .divider:before {
        width: 1em;
    }
    .divider:after {
        flex: 1;
    }
</style>