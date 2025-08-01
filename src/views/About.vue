<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Le Dang Vinh</strong>, a senior full-stack game developer with 7 years of experience.<br/>
        I specialize in Unity, Cocos Creator, and .NET Core, building both client and server-side systems for engaging and scalable games.
      </div>

      <div style="margin-top: 20px;">
        I've worked on game projects, tools and systems, and contributed to various teams and roles over the years.
      </div>

      <div style="margin-top: 40px;">
        I'm <strong>currently open to new opportunities</strong> in game development or backend engineering. You can reach me at <a href="mailto:ldvinhx@gmail.com">ldvinhx@gmail.com</a> or <router-link to="/contact">through this page</router-link>.
      </div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of Le Dang Vinh" /> 
    </div>

    <div style="clear:both"></div>
  </div>
</template>


<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>