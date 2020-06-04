<template>
<div class="min-h-screen" style="background-image: url(images/flower2.jpg)" >
  <div class="flex flex-wrap">
    <div class="w-full lg:w-1/2 py-8 lg:py-0">

      <div class="lg:flex flex-wrap">
        <div class="flex-1 lg:relative bg-white w-full lg:w-4/5">
          <div class="relative  lg:flex lg:justify-center items-center md:justify-center justify-center lg:min-h-screen"> 
            <div class="relative lg:min-h-full py-12">
                  <div class="flex flex-col text-gray-700 text-center">
                    <div class="fade-in-1  animation-delay text-orange-600 text-center text-xl md:text-4xl lg:text-5xl lg:px-4 lg:pt-8 lg:mx-2 lg:mt-8" style="--delay: 500ms" >Sathya Sai</div>
                    <div class="fade-in-1 animation-delay text-orange-600 text-center text-xl md:text-4xl lg:text-5xl lg:px-4 lg:mb-2 lg:mb-4" style="--delay: 500ms">International Organisation</div>
                  </div>
                    <div class="fade-in-1 animation-delay text-orange-600 text-center font-bold text-3xl md:text-6xl lg:text-6xl lg:px-4 lg:py-2 pt-8 md:pt-8 lg:mx-2"  style="--delay:1000ms">Mauritius</div>
                    <div class="fade-in-1  animation-delay text-orange-600 text-center px-4 py-8 m-2 " style="--delay: 1500ms">
                        <img class="mx-auto h-full w-48 md:w-auto" src="http://saibabamauritius.org/sites/all/themes/surya/logo.png"/>
                    </div>    
                    <div class="fade-in-1 animation-delay text-orange-600 font-medium text-xl md:text-4xl lg:text-5xl text-center lg:px-4 lg:py-2 lg:md:py-8 lg:mx-2 mb-2" style="--delay: 2s">Coming soon...</div>             
            </div>
          </div>
        </div>
        <div class="w-0 lg:w-1/5 bg--200 hidden -ml-2 lg:block lg:overflow-hidden min-h-screen">
           <div class="relative text-center -ml-2 mr-2 lg:h-1200 lg:w-100">
              <svg class="absolute top-0 left-0 md:overflow-hidden" viewBox="0 0 100 1200" fill="#FFFFFF" xmlns="http://www.w3.org/2000/svg">
                <polygon points="0,0 100,0 0,1200"/>
              </svg>
            </div>
        </div>
      </div>  
    
    </div>
   
  </div>

</div>
</template>

<script>
export default {
  components: {},
};
</script>

<style lang="scss">

.fade-in-1 {
  opacity:0;
  animation: fadeIn ease 1s forwards;
}

.animation-delay {
  animation-delay: var(--delay, 0.5s); 
}


@keyframes fadeIn {
  0% {
    opacity:0;
  }
  100% {
    opacity:1;
  }
}


</style>
