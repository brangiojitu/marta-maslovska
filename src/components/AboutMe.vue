<template>
    <div>
        <ul>
            <Information 
            v-for="Con of Contacts"
            :Contacts="Contacts"
            :key="Con.id"
            v-bind:Con="Con"/>
            <Indormation 
            v-for="Ab of Aboutme"
            :Aboutme="Aboutme"
            :key="Ab.id"
            v-bind:Ab="Ab"
            />
            <Indormation 
            v-for="t of to"
            :to="to"
            :key="t.id"
            v-bind:Ab="Ab"
            />
            <Indormation 
            v-for="f of from"
            :from="from"
            :key="f.id"
            v-bind:Ab="Ab"
            />
            <Indormation 
            v-for="sp of savedPosition"
            :savedPosition="savedPosition"
            :key="sp.id"
            v-bind:Ab="Ab"
            />
            </ul>
        </div>
</template>

<script>
import Information from '@/components/Information'
export default {
    props: ['Contacts','About me'],
    components: {
        Information
    }
}
</script>

<style scoped>
ul {
    height: 7px;
    text-align: center;
    list-style: none;
    margin: 0;
    padding: 0;
}
</style>
