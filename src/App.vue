<template>
  
  <div
    class="flex bg-gray-200 font-sans min-h-screen flex-col content-center justify-center text-2xl md:text-5xl"
  >
      <div class="fade-in text-orange-600 font-medium text-2xl md:text-5xl text-center px-4  py-2 mx-2 my-2"> Sathya Sai</div>
      <div class="fade-in text-orange-600 font-medium text-2xl md:text-5xl text-center px-4  py-2 mx-2 mb-2">International Organisation</div>
      <div class="fade-in text-orange-600 font-bold text-2xl md:text-6xl text-center px-4 py-2 mx-2 mb-2">Mauritius </div>
      <div class="fade-in text-center my-12">
        <img class="mx-auto h-full w-48 md:w-auto" src="http://saibabamauritius.org/sites/all/themes/surya/logo.png"/>
        </div>
        
      <div class="fade-in text-orange-600 font-medium text-2xl md:text-4xl text-center px-4 py-2 m-2">Coming soon...</div>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style lang="scss">
* {
  padding: 0;
  border: 0;
  margin: 0;
}

.fade-in {
  animation: fadeIn ease 5s;
  -webkit-animation: fadeIn ease 5s;
  -moz-animation: fadeIn ease 5s;
  -o-animation: fadeIn ease 5s;
  -ms-animation: fadeIn ease 5s;
}
@keyframes fadeIn {
  0% {
    opacity:0;
  }
  100% {
    opacity:1;
  }
}

@-moz-keyframes fadeIn {
  0% {
    opacity:0;
  }
  100% {
    opacity:1;
  }
}

@-webkit-keyframes fadeIn {
  0% {
    opacity:0;
  }
  100% {
    opacity:1;
  }
}

@-o-keyframes fadeIn {
  0% {
    opacity:0;
  }
  100% {
    opacity:1;
  }
}

@-ms-keyframes fadeIn {
  0% {
    opacity:0;
  }
  100% {
    opacity:1;
}
}
</style>
