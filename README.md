# WebsiteLoader
Simple HTML, CSS, JS Website gif loading screen



Put the script and the style elements inside the end of the <head> div.

```<script>
    $(window).on('load', function () {
      $(".containerr").fadeOut("slow");
    });
  </script>
  <style>
    .containerr {
      position: fixed;
      left: 0px;
      top: 0px;
      width: 100%;
      height: 100%;
      z-index: 9999;
      justify-items: center;
    }
    
    /*This centers the loading gif*/
    .centered {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      transform: -webkit-translate(-50%, -50%);
      transform: -moz-translate(-50%, -50%);
      transform: -ms-translate(-50%, -50%);
    }
  </style>
```

  
  ## Put all the Div elements inside the beginning of the <body> Div>


```<div class="containerr" style="background: /*Background color you want*/;">
    <img class="centered" src="Path/To/Gif" alt="">
  </div>
```



![example](https://i.ibb.co/6t6m7Sj/chrome-3o5-EZcih-WT.gif)
