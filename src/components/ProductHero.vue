<template>
        <div>
    <article>
<h1>Product1</h1>
<p>info1</p>
    </article>
    <article>
<h1>Product2</h1>
<p>info2</p>
    </article>
        </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
div{
    display: grid;
    grid-template-columns: 1fr 1fr;
}
</style>