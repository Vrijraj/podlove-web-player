<template>
  <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
    viewBox="0 0 36 31" xml:space="preserve" width="43" height="38">
    <g>
      <g transform="translate(-143.000000, -9.000000)">
        <g transform="translate(144.000000, 10.000000)">
          <path :fill="color || 'currentColor'" d="M30.6,13.2h-3.1l-0.1-0.9C26.5,5.9,20.8,1,14.3,1C7,1,1,7,1,14.3c0,7,5.4,12.7,12.3,13.2v-2.1
            C7.6,24.9,3.1,20.1,3.1,14.3c0-6.2,5-11.2,11.2-11.2c5.3,0,9.9,3.8,11,9l0.2,1.2h-3.1l4.1,5.5L30.6,13.2z"/>
          <g>
            <path :fill="color || 'currentColor'" d="M10.7,11c-1,0-1.8,0.3-2.5,1L9,12.9c0.5-0.5,1-0.7,1.6-0.7c0.7,0,1.2,0.4,1.2,1.1c0,0.8-0.5,1.2-1.3,1.2
              h-0.4l-0.2,1.1h0.6c0.9,0,1.5,0.3,1.5,1.3c0,0.8-0.6,1.4-1.4,1.4c-0.6,0-1.2-0.2-1.7-0.8L8,18.2c0.6,0.8,1.5,1.2,2.6,1.2
              c1.8,0,2.9-1.1,2.9-2.5c0-1.2-0.8-1.9-1.8-2c0.9-0.3,1.6-0.9,1.6-1.9C13.3,11.9,12.4,11,10.7,11z M17.4,11
              c1.9,0,2.9,1.5,2.9,4.2c0,2.7-1,4.2-2.9,4.2c-1.9,0-2.9-1.5-2.9-4.2C14.6,12.5,15.5,11,17.4,11z M17.4,12.2
              c-0.9,0-1.3,0.8-1.3,3c0,2.3,0.4,3,1.3,3c0.9,0,1.3-0.8,1.3-3C18.8,12.9,18.3,12.2,17.4,12.2z"/>
          </g>
        </g>
      </g>
    </g>
  </svg>
</template>

<script>
  export default {
    props: ['color']
  }
</script>
