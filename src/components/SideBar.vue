<template>
    <div>
        <Formcontrol />
        <b-container class="bv-example-row">
            <b-row align-h="start">
                <b-col cols="4">
                    <b-list-group>
                        <b-list-group-item>Piyush pandit</b-list-group-item>
                        <b-list-group-item>Sohan Honakeri </b-list-group-item>
                        <b-list-group-item>Kiran Begari</b-list-group-item>
                        <b-list-group-item>Chirag Shah</b-list-group-item>
                        <b-list-group-item>Chintan Shah</b-list-group-item>
                    </b-list-group>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
import Formcontrol from './Formcontrol.vue'

export default {
    name: "SideBar",
    component:{
        Formcontrol
    }
}
</script>

<style scoped>

</style>