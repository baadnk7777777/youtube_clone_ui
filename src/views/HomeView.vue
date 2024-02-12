<script setup lang="ts"></script>

<template>
  <div class="px-4 font-primary">
    <div
      class="inline-flex pt-4 w-full flex-nowrap items-center justify-between sticky top-0 z-50 bg-white"
    >
      <div class="flex gap-4">
        <div class="">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            viewBox="0 0 24 24"
            width="24"
            focusable="false"
            style="pointer-events: none; display: block; width: 100%; height: 100%"
          >
            <path d="M21 6H3V5h18v1zm0 5H3v1h18v-1zm0 6H3v1h18v-1z"></path>
          </svg>
        </div>
        <!-- <q-img :src="youtubeLogo" style="height: 20px; width: 97px; max-width: 97px" /> -->
        <div class="flex items-center">
          <div class="h-6 flex items-center">
            <div class="w-24">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="external-icon"
                viewBox="0 0 97 20"
                style="width: 100%; pointer-events: none; display: block; height: 100%"
                focusable="false"
              >
                <svg
                  viewBox="0 0 97 20"
                  preserveAspectRatio="xMidYMid meet"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <g>
                    <path
                      d="M27.9704 3.12324C27.6411 1.89323 26.6745 0.926623 25.4445 0.597366C23.2173 2.24288e-07 14.2827 0 14.2827 0C14.2827 0 5.34807 2.24288e-07 3.12088 0.597366C1.89323 0.926623 0.924271 1.89323 0.595014 3.12324C-2.8036e-07 5.35042 0 10 0 10C0 10 -1.57002e-06 14.6496 0.597364 16.8768C0.926621 18.1068 1.89323 19.0734 3.12324 19.4026C5.35042 20 14.285 20 14.285 20C14.285 20 23.2197 20 25.4468 19.4026C26.6769 19.0734 27.6435 18.1068 27.9727 16.8768C28.5701 14.6496 28.5701 10 28.5701 10C28.5701 10 28.5677 5.35042 27.9704 3.12324Z"
                      fill="#FF0000"
                    ></path>
                    <path
                      d="M11.4275 14.2854L18.8475 10.0004L11.4275 5.71533V14.2854Z"
                      fill="white"
                    ></path>
                  </g>
                  <g>
                    <path
                      d="M40.0566 6.34524V7.03668C40.0566 10.4915 38.5255 12.5118 35.1742 12.5118H34.6638V18.5583H31.9263V1.42285H35.414C38.6078 1.42285 40.0566 2.7728 40.0566 6.34524ZM37.1779 6.59218C37.1779 4.09924 36.7287 3.50658 35.1765 3.50658H34.6662V10.4727H35.1365C36.6064 10.4727 37.1803 9.40968 37.1803 7.10253L37.1779 6.59218Z"
                    ></path>
                    <path
                      d="M46.5336 5.8345L46.3901 9.08238C45.2259 8.83779 44.264 9.02123 43.836 9.77382V18.5579H41.1196V6.0391H43.2857L43.5303 8.75312H43.6337C43.9183 6.77288 44.8379 5.771 46.0232 5.771C46.1949 5.7757 46.3666 5.79687 46.5336 5.8345Z"
                    ></path>
                    <path
                      d="M49.6567 13.2456V13.8782C49.6567 16.0842 49.779 16.8415 50.7198 16.8415C51.6182 16.8415 51.8228 16.1501 51.8439 14.7178L54.2734 14.8613C54.4568 17.5565 53.0481 18.763 50.6586 18.763C47.7588 18.763 46.9004 16.8627 46.9004 13.4126V11.223C46.9004 7.58707 47.8599 5.80908 50.7409 5.80908C53.6407 5.80908 54.3769 7.32131 54.3769 11.0984V13.2456H49.6567ZM49.6567 10.6703V11.5687H51.7193V10.675C51.7193 8.37258 51.5547 7.71172 50.6821 7.71172C49.8096 7.71172 49.6567 8.38669 49.6567 10.675V10.6703Z"
                    ></path>
                    <path
                      d="M68.4103 9.09902V18.5557H65.5928V9.30834C65.5928 8.28764 65.327 7.77729 64.7132 7.77729C64.2216 7.77729 63.7724 8.06186 63.4667 8.59338C63.4832 8.76271 63.4902 8.93439 63.4879 9.10373V18.5605H60.668V9.30834C60.668 8.28764 60.4022 7.77729 59.7884 7.77729C59.2969 7.77729 58.8665 8.06186 58.5631 8.57456V18.5628H55.7456V6.03929H57.9728L58.2221 7.63383H58.2621C58.8947 6.42969 59.9178 5.77588 61.1219 5.77588C62.3072 5.77588 62.9799 6.36854 63.288 7.43157C63.9418 6.34973 64.9225 5.77588 66.0443 5.77588C67.7564 5.77588 68.4103 7.00119 68.4103 9.09902Z"
                    ></path>
                    <path
                      d="M69.8191 2.8338C69.8191 1.4862 70.3106 1.09814 71.3501 1.09814C72.4132 1.09814 72.8812 1.54734 72.8812 2.8338C72.8812 4.22373 72.4108 4.57181 71.3501 4.57181C70.3106 4.56945 69.8191 4.22138 69.8191 2.8338ZM69.9837 6.03935H72.6789V18.5629H69.9837V6.03935Z"
                    ></path>
                    <path
                      d="M81.891 6.03955V18.5631H79.6849L79.4403 17.032H79.3792C78.7466 18.2573 77.827 18.7677 76.684 18.7677C75.0095 18.7677 74.2522 17.7046 74.2522 15.3975V6.0419H77.0697V15.2352C77.0697 16.3382 77.3002 16.7874 77.867 16.7874C78.3844 16.7663 78.8477 16.4582 79.0688 15.9902V6.0419H81.891V6.03955Z"
                    ></path>
                    <path
                      d="M96.1901 9.09893V18.5557H93.3726V9.30825C93.3726 8.28755 93.1068 7.7772 92.493 7.7772C92.0015 7.7772 91.5523 8.06177 91.2465 8.59329C91.263 8.76027 91.2701 8.9296 91.2677 9.09893V18.5557H88.4502V9.30825C88.4502 8.28755 88.1845 7.7772 87.5706 7.7772C87.0791 7.7772 86.6487 8.06177 86.3453 8.57447V18.5627H83.5278V6.0392H85.7527L85.9973 7.63139H86.0372C86.6699 6.42725 87.6929 5.77344 88.8971 5.77344C90.0824 5.77344 90.755 6.3661 91.0631 7.42913C91.7169 6.34729 92.6976 5.77344 93.8194 5.77344C95.541 5.77579 96.1901 7.0011 96.1901 9.09893Z"
                    ></path>
                    <path
                      d="M40.0566 6.34524V7.03668C40.0566 10.4915 38.5255 12.5118 35.1742 12.5118H34.6638V18.5583H31.9263V1.42285H35.414C38.6078 1.42285 40.0566 2.7728 40.0566 6.34524ZM37.1779 6.59218C37.1779 4.09924 36.7287 3.50658 35.1765 3.50658H34.6662V10.4727H35.1365C36.6064 10.4727 37.1803 9.40968 37.1803 7.10253L37.1779 6.59218Z"
                    ></path>
                  </g>
                </svg>
              </svg>
            </div>
          </div>
          <div class="flex items-start text-[10px] ml-2">
            <p class="font-light">TH</p>
          </div>
        </div>
      </div>

      <div class="flex gap-4 items-center">
        <div class="w-6 h-6">
          <q-img class="mr-4" :src="searchLogo" style="height: 24px; max-width: 24px" />
        </div>
        <div class="">
          <q-img class="mr-4" :src="micLogo" style="height: 24px; max-width: 24px" />
        </div>
        <div class="">
          <q-img class="mr-4" :src="video_callLogo" style="height: 24px; max-width: 24px" />
        </div>
        <div class="">
          <q-img class="mr-4" :src="notificationsLogo" style="height: 24px; max-width: 24px" />
        </div>
        <div class="">
          <q-avatar size="32px">
            <img src="https://cdn.quasar.dev/img/avatar.png" />
          </q-avatar>
        </div>
      </div>
    </div>
    <!-- END: Navbar -->

    <!-- Start: main content -->
    <!-- v-for="index in 20" :key="index" -->
    <div class="flex-row justify-start mt-4">
      <!-- Start: Sidebar -->
      <div hidden class="w-64 h-full fixed left-0 lg:flex">
        <div class="w-full px-2">
          <button
            class="justify-start items-center flex bg-[#f0f0f0] font-[500] text-[14px] leading-8 text-black px-3 rounded-lg w-full"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              enable-background="new 0 0 24 24"
              height="24"
              viewBox="0 0 24 24"
              width="24"
              focusable="false"
              style="pointer-events: none; display: block; width: 24px; height: 24px"
            >
              <g><path d="M4 21V10.08l8-6.96 8 6.96V21h-6v-6h-4v6H4z"></path></g>
            </svg>
            <div class="ml-2 font-bold">Home</div>
          </button>
          <button
            class="justify-start items-center flex bg-[#00000] hover:bg-[#f0f0f0] font-[500] text-[14px] leading-8 text-black px-3 rounded-lg w-full"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              height="24"
              viewBox="0 0 24 24"
              width="24"
              focusable="false"
              style="pointer-events: none; display: block; width: 24px; height: 24px"
            >
              <path
                d="M10 14.65v-5.3L15 12l-5 2.65zm7.77-4.33-1.2-.5L18 9.06c1.84-.96 2.53-3.23 1.56-5.06s-3.24-2.53-5.07-1.56L6 6.94c-1.29.68-2.07 2.04-2 3.49.07 1.42.93 2.67 2.22 3.25.03.01 1.2.5 1.2.5L6 14.93c-1.83.97-2.53 3.24-1.56 5.07.97 1.83 3.24 2.53 5.07 1.56l8.5-4.5c1.29-.68 2.06-2.04 1.99-3.49-.07-1.42-.94-2.68-2.23-3.25zm-.23 5.86-8.5 4.5c-1.34.71-3.01.2-3.72-1.14-.71-1.34-.2-3.01 1.14-3.72l2.04-1.08v-1.21l-.69-.28-1.11-.46c-.99-.41-1.65-1.35-1.7-2.41-.05-1.06.52-2.06 1.46-2.56l8.5-4.5c1.34-.71 3.01-.2 3.72 1.14.71 1.34.2 3.01-1.14 3.72L15.5 9.26v1.21l1.8.74c.99.41 1.65 1.35 1.7 2.41.05 1.06-.52 2.06-1.46 2.56z"
              ></path>
            </svg>
            <div class="ml-2 font-normal">Shorts</div>
          </button>
          <button
            class="justify-start items-center flex bg-[#00000] hover:bg-[#f0f0f0] font-[500] text-[14px] leading-8 text-black px-3 rounded-lg w-full"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              enable-background="new 0 0 24 24"
              height="24"
              viewBox="0 0 24 24"
              width="24"
              focusable="false"
              style="pointer-events: none; display: block; width: 24px; height: 24px"
            >
              <path
                d="M10 18v-6l5 3-5 3zm7-15H7v1h10V3zm3 3H4v1h16V6zm2 3H2v12h20V9zM3 10h18v10H3V10z"
              ></path>
            </svg>
            <div class="ml-2 font-normal">Subscriptions</div>
          </button>
          <button
            class="justify-start items-center flex bg-[#00000] hover:bg-[#f0f0f0] font-[500] text-[14px] leading-8 text-black px-3 rounded-lg w-full"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              height="24"
              viewBox="0 0 24 24"
              width="24"
              focusable="false"
              style="pointer-events: none; display: block; width: 24px; height: 24px"
            >
              <path
                d="M10 9.35 15 12l-5 2.65zM12 7a5 5 0 105 5 5 5 0 00-5-5m0-1a6 6 0 11-6 6 6 6 0 016-6zm0-3a9 9 0 109 9 9 9 0 00-9-9m0-1A10 10 0 112 12 10 10 0 0112 2z"
              ></path>
            </svg>
            <div class="ml-2 font-normal">YouTube Music</div>
          </button>
        </div>
      </div>
      <!-- End: Sidebar -->
      <div class="px-2 lg:w-[calc(100% - 256px)] lg:ml-64">
        <!-- Start: menuLists -->

        <div class="inline-flex flex-nowrap gap-2 items-center h-14 overflow-hidden">
          <div class="">
            <button
              class="bg-[#030303] font-[500] text-[14px] leading-8 text-white px-3 rounded-lg"
            >
              All
            </button>
          </div>
          <div class="">
            <button
              class="bg-[#e9e9e9] font-[500] text-[14px] leading-8 text-black px-3 rounded-lg"
            >
              Mixes
            </button>
          </div>
          <div class="">
            <button
              class="bg-[#e9e9e9] font-[500] hover:bg-[#f0f0f0] text-[14px] leading-8 text-black px-3 rounded-lg"
            >
              Gaming
            </button>
          </div>
          <div class="">
            <button
              class="bg-[#e9e9e9] font-[500] hover:bg-[#f0f0f0] text-[14px] leading-8 text-black px-3 rounded-lg"
            >
              JavaScript
            </button>
          </div>
          <div class="">
            <button
              class="bg-[#e9e9e9] font-[500] hover:bg-[#f0f0f0] text-[14px] leading-8 text-black px-3 rounded-lg"
            >
              Live
            </button>
          </div>
          <div v-for="index in 15" :key="index" class="">
            <button
              class="bg-[#e9e9e9] font-[500] hover:bg-[#f0f0f0] text-[14px] leading-8 text-black px-3 rounded-lg"
            >
              Movie
            </button>
          </div>
          <div class="w-10 h-10">
            <button
              class="bg-[#00000] w-10 h-10 font-medium hover:bg-[#f0f0f0] text-sm text-black py-1 px-2 rounded-full"
            >
              <q-img class="mr-4" :src="arrow_forwardLogo" style="height: 24px; max-width: 24px" />
            </button>
          </div>
        </div>
        <!-- END -->
        <!-- Start: content -->
        <div class="w-full flex gap-4">
          <div v-for="index in 20" :key="index" class="flex max-w-[350px] min-w-[450px]">
            <q-img
              class="rounded-xl"
              src="https://i.ytimg.com/vi/RRUIZFbVWKE/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCexD52wEFcvIInBTBaKQpfeJ5P0w"
            ></q-img>
            <div class="inline-flex gap-2 mt-2">
              <div class="w-11">
                <q-img
                  src="https://yt3.ggpht.com/vhhwIJzbT4hY38VV0yGnn8R6Do9eZfg7h22UHcpWiMMSSy1dnasLIQpmxgthYeYBpoLqTgyM2A=s68-c-k-c0x00ffffff-no-rj"
                ></q-img>
              </div>
              <div class="flex-grow">
                <span class="font-bold text-[16px]"
                  >Werewolf <span class="font-normal text-[16px]">คืนหอนหลอนหมาป่า </span>
                  <span>EP.7</span>
                  <span class="font-normal text-[16px]">
                    | เทพลีลา x @ <span class="font-bold text-[16px]">TattooColourTV</span></span
                  ></span
                >
                <div class="text-[#606060] font-normal">Thepleela</div>
                <div class="text-[#606060] font-normal">850K views * 2 months ago</div>
              </div>
            </div>
          </div>

          <!-- <div class="flex">
            <q-img
              class="rounded-xl"
              src="https://i.ytimg.com/vi/RRUIZFbVWKE/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCexD52wEFcvIInBTBaKQpfeJ5P0w"
            ></q-img>
            <div class="inline-flex gap-2 mt-2">
              <div class="w-11">
                <q-img
                  src="https://yt3.ggpht.com/vhhwIJzbT4hY38VV0yGnn8R6Do9eZfg7h22UHcpWiMMSSy1dnasLIQpmxgthYeYBpoLqTgyM2A=s68-c-k-c0x00ffffff-no-rj"
                ></q-img>
              </div>
              <div class="flex-grow">
                <span class="font-bold text-[16px]"
                  >Werewolf <span class="font-normal text-[16px]">คืนหอนหลอนหมาป่า </span>
                  <span>EP.7</span>
                  <span class="font-normal text-[16px]">
                    | เทพลีลา x @ <span class="font-bold text-[16px]">TattooColourTV</span></span
                  ></span
                >
                <div class="text-[#606060] font-normal">Thepleela</div>
                <div class="text-[#606060] font-normal">850K views * 2 months ago</div>
              </div>
            </div>
          </div> -->
        </div>

        <!-- <div v-for="index in 10" :key="index" class="flex bg-red-300 w-full">
          <q-img
            class="rounded-xl"
            src="https://i.ytimg.com/vi/RRUIZFbVWKE/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCexD52wEFcvIInBTBaKQpfeJ5P0w"
          ></q-img>
          <div class="inline-flex gap-2 mt-2">
            <div class="w-11">
              <q-img
                src="https://yt3.ggpht.com/vhhwIJzbT4hY38VV0yGnn8R6Do9eZfg7h22UHcpWiMMSSy1dnasLIQpmxgthYeYBpoLqTgyM2A=s68-c-k-c0x00ffffff-no-rj"
              ></q-img>
            </div>
            <div class="flex-grow">
              <span class="font-bold text-[16px]"
                >Werewolf <span class="font-normal text-[16px]">คืนหอนหลอนหมาป่า </span>
                <span>EP.7</span>
                <span class="font-normal text-[16px]">
                  | เทพลีลา x @ <span class="font-bold text-[16px]">TattooColourTV</span></span
                ></span
              >
              <div class="text-[#606060] font-normal">Thepleela</div>
              <div class="text-[#606060] font-normal">850K views * 2 months ago</div>
            </div>
          </div>
        </div> -->
        <!-- End: content -->
      </div>
    </div>
    <!-- End: main content -->
  </div>
</template>

<script setup lang="ts">
import menuLogo from '/src/assets/icons/menu.png'
import youtubeLogo from '/src/assets/icons/youtube.png'
import searchLogo from '/src/assets/icons/search.png'
import micLogo from '/src/assets/icons/mic.png'
import video_callLogo from '/src/assets/icons/video_call.png'
import notificationsLogo from '/src/assets/icons/notifications.png'

import arrow_forwardLogo from '/src/assets/icons/arrow_forward.png'
</script>
