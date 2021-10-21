<template>
    <div>
        <form action="#">
            <input type="text" name="username" id="" v-model="username" placeholder="Username"><br><br>
            <input type="email" name="email" id="" v-model="email" placeholder="Email"><br><br>
            <input type="tel" name="phone" id="" v-model="phone" v-on="keyup" placeholder="Phone"><br><br>
            <input type="password" name="password" id="" v-model="password" placeholder="Password"><br><br>
        </form>
    </div>
</template>
<script>
export default {
    data: function(){
        return{
            
            username: "Joseph Njenga ",
            email:"kariuki.j.njenga2210@gmail.com",
            phone:"0713275451",
            password:"5 Potatoez",
        }
    },
    methods: ()=>{
        
    }
}
</script>
<style scoped>

</style>