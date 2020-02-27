<template>
    <div>
        <div class="container" style="padding:10%">
            <h2>Contact Me</h2>
            <form action="mailto:alloyking1@gmail.com" method="post" enctype="text/plain">
                <div class="form-group">
                    <input type="email" class="form-control" v-model="contact.eamil" placeholder="Enter email">
                </div>
                <div class="form-group">
                    <textarea class="form-control" v-model="contact.message" rows="3" placeholder="write message"></textarea>
                </div>
            </form>
            
            <button type="button" @click="submit" class="btn btn-primary btn-lg">Contact</button>
        </div>
    </div>
</template>

<script lang="ts">
export default {
    data(){
        return {
            contact:{
                email:'',
                message:''
            }
        }
    },
    
    methods:{
        submit(){
            if(this.contact.eamil !="" && this.contact.message != ""){
                // send details to email
            }else{
                alert("All fields are required");
            }
        }
    }
}


</script>