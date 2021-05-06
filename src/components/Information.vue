<template>
<li>
    <span>
    <input type="checkbox">
    <strong>{{Con.id}}</strong>
    {{Con.title}}
        </span>
</li>
</template>

<script>
export default {
    props: {
        Con: {
            type: Object,
            required: true
        }
    }
}
</script>
