<template>
   <div class="header_section header_bg">
      <div class="collapse" id="navbarToggleExternalContent">
         <div class="bg-dark p-4">
            <h5 class="text-white h4">Collapsed content</h5>
            <span class="text-muted">Toggleable via the navbar brand.</span>
         </div>
      </div>
      <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
         <a class="logo"><router-link to="/Cycle"><img src="images/logo.png"></router-link></a>

         <form class="form-inline my-2 my-lg-0">
            <ul class="navbar-nav mr-auto">
               <li v-for="item, index in navItems" :key="index" class="nav-item active">
                  <a class="nav-link"><router-link :to="item.path">{{ item.text }}</router-link></a>
               </li>
            </ul>
            <div class="login_menu">
               <ul>
                  <li><a><router-link to="/Shop"><img src="images/trolly-icon.png"></router-link></a></li>
               </ul>
            </div>
         </form>
         <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent"
            aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
         </button>
      </nav>
   </div>
</template>

<script>
export default {
   name: "NavComponent",
   props: ["navItems"],
   mounted() {


   }
};

</script>