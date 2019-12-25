<template>
  <div style="background-color: rgb(244,244,244);font-family: Rubik, sans-serif;min-height:100vh">
    <div class="shadow">
        <nav class="navbar navbar-light navbar-expand-md navigation-clean bg-white">
            <div class="container">
              <nuxt-link to="/" class="navbar-brand" href="#" style="font-family: Muli, sans-serif;font-weight: bold;">XSEED Resturant Directory</nuxt-link><button class="navbar-toggler" data-toggle="collapse" data-target="#navcol-1"><span class="sr-only">Toggle navigation</span><span class="navbar-toggler-icon"></span></button>
                <div
                    class="collapse navbar-collapse" id="navcol-1">
                    <ul class="nav navbar-nav ml-auto">
                        <li class="nav-item" role="presentation"><nuxt-link to="/login" class="nav-link">Sign In</nuxt-link></li>
                        <li class="nav-item" role="presentation"><a class="nav-link" href="https://app.enhancv.com/share/54986e24?utm_medium=growth&utm_campaign=share-resume&utm_source=dynamic" target="_blank">My Portfolio&nbsp;<i class="fa fa-external-link"></i></a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </div>
    <nuxt />
  </div>
</template>