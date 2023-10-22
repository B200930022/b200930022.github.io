<html>
  <style>
    div{
      background-color: red;
      width: 200px;
      height: 200px;
      position: absolute;
      animation-name: boom;
      animation-timing-function: linear;
      animation-duration: infinity;
      animation-direction: alternate;
      }
      @keyframes boom{
      0%{
      transform: translate(0,0)
      }
      50%{
      transform: translate(40%, 40%)
      }
      100%{
      transform: translate(0,0)
      }
      }
      
  </style>
  <body>
    <div></div>
  </body>
</html>
