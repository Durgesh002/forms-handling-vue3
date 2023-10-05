<template>
    <div class="container">
        <div class="row">
            <div class="col-md-3">
                <div class="card shadow-lg">
                    <div class="card-header">
                        <p class="h3">Register Here!!</p>
                    </div>
                    <div class="card-body bg-light">
                        <form @submit.prevent="register">
                            <div class="mb-2">
                                <input type="text" class="form-control" placeholder="Name goes here..." v-model="user.name">
                            </div>
                            <div class="mb-2">
                                <input type="email" class="form-control" placeholder="e.g. example@gmail.com" v-model="user.email">
                            </div>
                            <div class="mb-2">
                                <input type="password" class="form-control" placeholder="Password goes here..." v-model="user.password">
                            </div>
                            <div class="mb-2">
                                <input class="btn btn-success" type="submit" value="Register">
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Register',
        data: function(){
            return{
                user: {
                    name: '',
                    email: '',
                    password: '',
                }
            }
        },
        methods: {
            register: function(){
                console.log(this.user)
            }
        }
    }
</script>

<style scoped>

</style>