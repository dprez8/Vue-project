<template>
    <div>
        <b-col>
            <b-card
            :title="name"
            img-src="https://picsum.photos/600/300/?image=250"
            img-alt="Job-info"
            img-top
            tag="article"
            style="max-width:15rem"
            class="mb-2"
            footer="You will need to fill a form"
            >  
            <b-card-text>This is the oportunity you've been looking for</b-card-text>
            <b-button variant="primary">Apply</b-button>
            </b-card>
            </b-col>
    </div>
</template>

<script>
    export default {
        props: ['name']
    }
</script>

<style lang="scss" scoped>

</style>