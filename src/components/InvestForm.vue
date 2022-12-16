<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <!-- component -->
<div class="font-manrope   w-full items-center justify-center">
  <div class="mx-auto my-3 box-border w-[365px] border bg-white p-4">
    <div class="flex items-center justify-center">
      <span class="text-[#64748B]">Future Invest</span>
      <div class="cursor-pointer border rounded-[4px]">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-[#64748B]" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
        </svg>
      </div>
    </div>

    <div class="mt-6">
      <div class="font-semibold">How much would you like to invest?</div>
      <div><input class="mt-1 w-full rounded-[4px] border border-[#A0ABBB] p-2" value="" type="text" placeholder="Write the invest here" /></div>
      <div class="flex justify-center mt-5">
        <div class="mt-[14px] cursor-pointer truncate rounded-[4px] border border-[#E7EAEE] p-3 text-[#191D23]">$10</div>
        <div class="mt-[14px] cursor-pointer truncate rounded-[4px] border border-[#E7EAEE] p-3 text-[#191D23]">$15</div>
        <div class="mt-[14px] cursor-pointer truncate rounded-[4px] border border-green-700 p-3 text-[#191D23]">$20</div>
        <div class="mt-[14px] cursor-pointer truncate rounded-[4px] border border-[#E7EAEE] p-3 text-[#191D23]">$50</div>
      </div>


      <div class="font-semibold mt-5">Entry price</div>

      <div><input class="mt-1 w-full rounded-[4px] border border-[#A0ABBB] p-2" 
        value="" type="text" 
        placeholder="Write your entry" />
      </div>

      <div class="font-semibold mt-5">Exit price</div>

      <div><input class="mt-1 w-full rounded-[4px] border border-[#A0ABBB] p-2" 
        value="" type="text" 
        placeholder="Write your Exit" />
      </div>

      <div class="font-semibold mt-5">Liq price</div>

      <div><input class="mt-1 w-full rounded-[4px] border border-[#A0ABBB] p-2" 
        value="" type="text" 
        placeholder="Write your Liq" />
      </div>
    </div>

    <div class="mt-6">
      <div class="font-semibold">From</div>
      <div class="mt-2">
        <div class="flex w-full items-center justify-between bg-neutral-100 p-3 rounded-[4px]">
          <div class="flex items-center gap-x-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-[#299D37]" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
            <span class="font-semibold">Checking</span>
          </div>

          <div class="flex items-center gap-x-2">
            <div class="text-[#64748B]">card ending in 6678</div>
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 cursor-pointer" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7" />
            </svg>
          </div>
        </div>
      </div>
    </div>

    <div class="mt-6">
      <div class="flex justify-between">
        <span class="font-semibold text-[#191D23]">Receiving</span>
        <div class="flex cursor-pointer items-center gap-x-2">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-green-700" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>
          <div class="font-semibold text-green-700">Add recipient</div>
        </div>
      </div>

      <div class="flex items-center gap-x-[10px] bg-neutral-100 p-3 mt-2 rounded-[4px]">
        <img class="h-10 w-10 rounded-full" src="https://img.freepik.com/free-vector/mysterious-mafia-man-smoking-cigarette_52683-34828.jpg?w=740&t=st=1671195971~exp=1671196571~hmac=aa733a8d7f12f7b7ba2455f293374bde67422c99822a619acccb864e16e67178" alt="" />
        <div>
          <div class="font-semibold">Monz</div>
          <div class="text-[#64748B]">@monzcrypto</div>
        </div>
      </div>
    </div>

    <div class="mt-6">
      <div class="w-full cursor-pointer rounded-[4px] bg-green-700 px-3 py-[6px] text-center font-semibold text-white">Save the Trade</div>
    </div>
  </div>
</div>


</template>
