<script>
import PageTitle from "./PageTitle.vue"

export default {
    name: "Contact",
    components : {
        PageTitle
    }
}
</script>


<template>
    <div id="contact">
        <PageTitle title="CONTACT ME"/>
    </div>
</template>


<style scoped>
#contact {
    grid-gap: 20px;
    grid-template-rows: 50px 1fr;
}
</style>
