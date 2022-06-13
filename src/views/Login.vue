<template>

   <div class="row">
        <div class="col-7">
          <img width="100%" height="100%" src="src/assets/images/truck.png">
        </div>
        <div class="col-5 d-flex justify-content-center">
          <div class="card p-4 pt-0">
            <div class="d-flex justify-content-center">
            <img class="mt-3" width="200px" height="150px" src="src/assets/images/signin.svg">
            </div>
            <h2>
              Sign In
            </h2>
            <div class="form">
              <div class="form-outline mb-4">
              <label class="form-label" for="email">Email</label>
              <input type="email" id="email" class="form-control" />
              </div>

              <div class="form-outline mb-4">
                <label class="form-label" for="pass">Password</label>
              <input type="password" id="pass" class="form-control" />
              </div>
              <div class="form-check d-flex justify-content-start mb-4">
                <input class="form-check-input" type="checkbox" value="" id="form1Example3" />
                <label class="form-check-label" for="form1Example3"><small class="remPass"> Remember password </small></label>
              </div>

              <button type="submit" class="btn btn-primary signinbtn">Sign in</button>
              <a class="forget-pass">Forgot Password</a>
            </div>
            <div>

            </div>
          </div>
        </div>
   </div>

</template>

<style>
.form-control{
  border-radius: 20px;
}
.card{
  box-shadow: 0px 1px 2px #0000000F;
  border-radius: 12px;
  margin-top: 200px;
  margin-bottom: 300px;
  width: 50%;
}
.remPass{
  margin-left: 15px;
  color: #9A9A9A;
}
.signinbtn{
  width: 100%;
  border-radius: 19px;
  background-color: black;
}
.forget-pass{
  margin-left: 100px;
  margin-top: 15px;
  text-decoration: none;
  color: #9A9A9A;
}
</style>