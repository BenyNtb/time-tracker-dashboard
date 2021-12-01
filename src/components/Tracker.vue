<template>
    <div>
        <p>{{report}}</p>
        <div class="name">{{nom}}</div>
        <div class="menu-link">{{freq}}</div>
        <div class="title">{{title}}</div>
        <div class="hours">{{hours}}</div>
        <div class="description">{{description}}</div>
    </div>
</template>

<script>
    
    export default {
        props: {
            report: String,
            nom: String,
            freq: String,
            title:String,
            hours: String,
            description:String,
        },
    }

</script>