<template>
    <div>
        <div class="container" style="margin-top:20px">
            <div class="row">
                <div class="col-lg-6 col-md-6 col-sm-12">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <div class="card-title">
                                <h3>Sign Up</h3>
                            </div>
                            <div class="form-group">
                                <label for="exampleInputEmail0">Full Name</label>
                                <input type="text" class="form-control" id="exampleInputEmail0" aria-describedby="emailHelp" placeholder="Enter full name">
                            </div>
                            <div class="form-group">
                                <label for="exampleInputEmail1">Email address</label>
                                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
                            </div>
                            <div class="form-group">
                                <label for="exampleInputPassword1">Password</label>
                                <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                            </div>
                            <button type="submit" class="btn btn-primary">Register</button>
                        </div>
                    </div>
                </div>
                <div class="col-lg-5 col-md-5">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <div class="card-title">
                                <h3>Sign In</h3>
                            </div>
                            <form @submit.prevent="signin">
                                <div class="form-group">
                                    <label for="exampleInputEmail1">Email address</label>
                                    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
                                </div>
                                <div class="form-group">
                                    <label for="exampleInputPassword1">Password</label>
                                    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
                                </div>
                                <button type="submit" class="btn btn-primary">Sign In</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    methods:{
        signin(){
            localStorage.setItem('login',true)
            location.href="/"
        }
    }
}
</script>

<style>

</style>