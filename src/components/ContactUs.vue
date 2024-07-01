<template>
    <div>

        <p>{{ message }}</p>
            <v-text-field v-model="userData.name" label="Name"></v-text-field>
            <v-text-field v-model="userData.email"></v-text-field>
            <v-text-field v-model="userData.phNumber"></v-text-field>
            <v-textarea
            label="User Text Area"
             rows="8"
            >
    
    
            </v-textarea>
    
    
        <!-- <input v-model="userData.email">
        <input v-model="userData.phNumber"> -->
    
        <button v-on:click="logUserData()">Send Data</button>
    </div>
    </template>
    <script>
export default {
name:'ContactUs',


data(){
    return {
       userData:{
        name:'',
        email:'',
        phNumber:''
       }
        
    }
},
methods: {
logUserData(){
console.log(this.userData);    
}

}
}

    
    </script>