<html>
  <head>
  <style>
    .div{
      background-color: red;
      width: 200px;
      height: 200px;
      position: absolute;
      animation-name: boom;
      animation-timing-function: linear;
      animation-duration: 10s;
      animation-direction: alternate;
      }
      @keyframes boom{
      0%{
         background-color: red;
      transform: translateX(0)
      }
      50%{
         background-color: blue;
      transform: translateX(40%)
      }
      100%{
         background-color: yellow;
      transform: translateX(50%)
      }
      }
      }
  </style>
  </head>
  <body>
    <div class="div">0</div>
  </body>
</html>
