<template>
   <div>
      <div
         class="absolute right-0 z-20 invisible text-right text-white xl:visible xl:mt-12 xl:mr-20 xl:text-6xl font-primary"
      >
         <p>{{ $t('title') }}</p>
         <p>Box</p>
      </div>
      <div class="absolute z-10 w-full">
         <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
            <path
               fill="#333"
               d="M0 192l48-16c48-16 144-48 240-53.3C384 117 480 139 576 160c96 21 192 43 288 53.3 96 10.7 192 10.7 288 26.7s192 48 240 64l48 16V0H0z"
            />
         </svg>
      </div>
   </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
