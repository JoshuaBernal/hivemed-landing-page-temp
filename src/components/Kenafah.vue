<template> <!-- HOW IT WORKS PART -->
  <div class="pt-56 md:pt-96 pb-40 flex flex-col lg:flex-row justify-between items-center container mx-auto">

      <div class="px-7 md:px-0 md:w-[450px]">

          <div class="flex items-center mb-5">
          <div class="w-[45px] border border-[#FC881D]"></div>
          <p class="font-title font-semibold text-[#FC881D] ml-3">HOW DOES IT WORK?</p>
          </div>

          <p class="text-3xl font-dmsans font-bold">As a patient, it connects you to doctors and pharmacies. <br>As a doctor, it connects you to patients and pharmacies. <br>And as a pharmacy, it connects you to doctors and patients.</p>
          <p class="font-title text-base py-8">HiveMed makes use of a variety of tools to make this possible. Databases, chatrooms, artificial intelligence, and electronic health records are key tools.</p>
          
          <button class="py-4 px-6 bg-[#0D0E25] rounded-full text-white font-dmsans flex items-center shadow-lg hover:bg-[#212238] transition-all">Learn More <img src="/arrow.png" class="ml-3" ></button>
      </div>


    <div id="hiw" class="grid grid-cols-1 md:grid-cols-2 lg:mt-0 mt-28">

        <div class="w-[290px] bg-[#0D0E25] text-white rounded-lg p-9">
            <div class="flex items-center">
                <img src="/icon-database.png" alt="">
                <p class="font-title font-semibold ml-5">Databases</p>
            </div>
            <p class="font-title mt-7">
                HiveMed's databases store a variety of information such as pharmacies' medicine inventory, user profiles, and medicine information to allow users to access relevant 
                information at any time to help in their medical tasks.
            </p>
        </div>

        <div class="w-[290px] rounded-lg p-9">
            <div class="flex items-center">
                <img src="/server.png" alt="">
                <p class="font-title font-semibold ml-5">Chatrooms</p>
            </div>
            <p class="font-title mt-7">
                HiveMed's chatrooms will allow patients to contact doctors and set-up appointments with them.
            </p>
        </div>

                <div class="w-[290px] rounded-lg p-9">
            <div class="flex items-center">
                <img src="/listrik.png" alt="">
                <p class="font-title font-semibold ml-5">AI</p>
            </div>
            <p class="font-title mt-7">
                HiveMed uses artificial intelligence to automatically sort pharmacies' inventory datasets and add appropriate images and descriptions for each medicine.
            </p>
        </div>

            <div class="w-[290px] border-t border-l p-9">
            <div class="flex items-center">
                <img src="/lingkungan.png" alt="">
                <p class="font-title font-semibold ml-5">Electronic Health Records</p>
            </div>
            <p class="font-title mt-7">
                HiveMed uses Electronic Health Records integration to allow doctors and patients to access relevant and updated patient information. Naturally, patients may only access their
                own patient information to promote confidentiality. 
            </p>
        </div>


    </div>
  </div>
</template>

<script>
export default {

}
</script>
