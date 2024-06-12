<template>
  <div class="w-full min-h-screen">
    <head
      class="w-full px-6 py-2 bg-white fixed flex justify-between items-center"
    >
      <div class="flex items-center">
        <button class="mr-2">
          <svg
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="w-8 h-8"
          >
            <path
              d="M4 7L7 7M20 7L11 7"
              stroke="#1C274C"
              stroke-width="1.5"
              stroke-linecap="round"
            />
            <path
              d="M20 17H17M4 17L13 17"
              stroke="#1C274C"
              stroke-width="1.5"
              stroke-linecap="round"
            />
            <path
              d="M4 12H7L20 12"
              stroke="#1C274C"
              stroke-width="1.5"
              stroke-linecap="round"
            />
          </svg>
        </button>
        <span class="text-2xl">FreeTube</span>
      </div>
      <div>
        <div class="border-2 rounded-full flex items-center">
          <input
            type="text"
            placeholder="Search"
            class="w-96 px-4 py-2 border-r rounded-l-full focus:outline-none"
          />
          <button class="px-6 py-2">
            <svg
              viewBox="0 0 32 32"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:xlink="http://www.w3.org/1999/xlink"
              xmlns:sketch="http://www.bohemiancoding.com/sketch/ns"
              fill="#000000"
              class="w-5 h-5"
            >
              <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
              <g
                id="SVGRepo_tracerCarrier"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></g>
              <g id="SVGRepo_iconCarrier">
                <title>search</title>
                <desc>Created with Sketch Beta.</desc>
                <defs></defs>
                <g
                  id="Page-1"
                  stroke="none"
                  stroke-width="1"
                  fill="none"
                  fill-rule="evenodd"
                  sketch:type="MSPage"
                >
                  <g
                    id="Icon-Set"
                    sketch:type="MSLayerGroup"
                    transform="translate(-256.000000, -1139.000000)"
                    fill="#000000"
                  >
                    <path
                      d="M269.46,1163.45 C263.17,1163.45 258.071,1158.44 258.071,1152.25 C258.071,1146.06 263.17,1141.04 269.46,1141.04 C275.75,1141.04 280.85,1146.06 280.85,1152.25 C280.85,1158.44 275.75,1163.45 269.46,1163.45 L269.46,1163.45 Z M287.688,1169.25 L279.429,1161.12 C281.591,1158.77 282.92,1155.67 282.92,1152.25 C282.92,1144.93 276.894,1139 269.46,1139 C262.026,1139 256,1144.93 256,1152.25 C256,1159.56 262.026,1165.49 269.46,1165.49 C272.672,1165.49 275.618,1164.38 277.932,1162.53 L286.224,1170.69 C286.629,1171.09 287.284,1171.09 287.688,1170.69 C288.093,1170.3 288.093,1169.65 287.688,1169.25 L287.688,1169.25 Z"
                      id="search"
                      sketch:type="MSShapeGroup"
                    ></path>
                  </g>
                </g>
              </g>
            </svg>
          </button>
        </div>
      </div>
      <div class="flex gap-10 items-center">
        <button>
          <svg
            fill="#000000"
            viewBox="0 0 512 512"
            version="1.1"
            xml:space="preserve"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            class="w-5 h-5"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <g id="_x37_04_-video__x2C__media__x2C__mp4__x2C_">
                <g>
                  <g>
                    <path
                      d="M486.25,436.599H26.7c-3.705,0-6.708-3.003-6.708-6.708V83.063c0-3.705,3.003-6.708,6.708-6.708h459.55 c3.705,0,6.708,3.003,6.708,6.708v346.828C492.958,433.596,489.955,436.599,486.25,436.599z M33.408,423.183h446.134V89.771 H33.408V423.183z"
                    ></path>
                  </g>
                  <g>
                    <path
                      d="M154.69,378.506c-1.167,0-2.335-0.304-3.378-0.912c-2.062-1.202-3.33-3.409-3.33-5.796V141.155 c0-2.387,1.269-4.594,3.331-5.796c2.061-1.203,4.607-1.218,6.685-0.041l203.569,115.35c2.103,1.191,3.402,3.421,3.401,5.838 c0,2.416-1.3,4.646-3.402,5.836l-203.57,115.293C156.97,378.216,155.83,378.506,154.69,378.506z M161.398,152.667v207.622 l183.251-103.785L161.398,152.667z"
                    ></path>
                  </g>
                </g>
              </g>
              <g id="Layer_1"></g>
            </g>
          </svg>
        </button>
        <button>
          <svg
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="w-5 h-5"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <g clip-path="url(#clip0_15_159)">
                <rect width="24" height="24" fill="white"></rect>
                <path
                  d="M9.5 19C8.89555 19 7.01237 19 5.61714 19C4.87375 19 4.39116 18.2177 4.72361 17.5528L5.57771 15.8446C5.85542 15.2892 6 14.6774 6 14.0564C6 13.2867 6 12.1434 6 11C6 9 7 5 12 5C17 5 18 9 18 11C18 12.1434 18 13.2867 18 14.0564C18 14.6774 18.1446 15.2892 18.4223 15.8446L19.2764 17.5528C19.6088 18.2177 19.1253 19 18.382 19H14.5M9.5 19C9.5 21 10.5 22 12 22C13.5 22 14.5 21 14.5 19M9.5 19C11.0621 19 14.5 19 14.5 19"
                  stroke="#000000"
                  stroke-linejoin="round"
                ></path>
                <path
                  d="M12 5V3"
                  stroke="#000000"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                ></path>
              </g>
              <defs>
                <clipPath id="clip0_15_159">
                  <rect width="24" height="24" fill="white"></rect>
                </clipPath>
              </defs>
            </g>
          </svg>
        </button>
        <div
          class="w-8 h-8 text-white bg-gray-500 rounded-full flex justify-center items-center"
        >
          R
        </div>
      </div>
    </head>
    <main class="pt-14">
      <slot></slot>
    </main>
  </div>
</template>
