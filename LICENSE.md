<!DOCTYPE html>
<html lang="en">
<head><meta name="viewport" content= "width=device-width, initial-scale=1.0">
  
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-8588456481282424"

     crossorigin="anonymous"></script>
  <!-- Google tag (gtag.js) -->

<script async src="https://www.googletagmanager.com/gtag/js?id=G-XQ386GTBB3"></script>

<script>

  window.dataLayer = window.dataLayer || [];

  function gtag(){dataLayer.push(arguments);}

  gtag('js', new Date());

  gtag('config', 'G-XQ386GTBB3');

</script>
  <!-- Google Tag Manager -->

<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':

new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],

j=d.createElement(s),dl=l!='dataLayer'?'a![android-chrome-192x192](https://github.com/Sohail1088/Webp-converter-/assets/136848019/3b289b9a-f377-4a3e-ad6c-f70a6e60aa9d)
mp='+l:'';j.async=true;j.src=

'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);

})(window,document,'script','dataLayer','GTM-W2HC7LR');</script>

<!-- End Google Tag Manager -->

  
  
<meta name="msapplication-TileColor" content="#da532c">

<meta name="theme-color" content="#ffffff">

<meta name="google-site-verification" content="q0a-hvl4dug2PaiwND5tuSKT5I040cZRu4u36-MuQYw" />
  <meta charset="utf-8">
    <meta name="theme-color" content="#317EFB"/>
  <title>WebP Converter optimizer your image</title>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <meta name="description" content=

"A WebP converter converts images to the WebP format, optimizing web content with smaller file sizes and faster loading times.">
  <link rel="icon" type="image/png" href="favicon.png">
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">

<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">

<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">

<link rel="manifest" href="/site.webmanifest">

<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">


<link rel=” canonical” href= “https://webpconvertertips.blogspot.com”/>
<link rel="alternate" href="https://webpconvertertips.blogspot.com/en-us" hreflang="en-us" />



  <style>
    body{
      
background-color: blue green;

      font-family:sans-serif;

      font-size:20px;

      font-weight:15px;
}

    container {
  max-width:  100%;
  margin: 40px;
  padding: 20px;
    }

    h1 {

  font-size: 30px;

  font-weight:bold ;

  margin: 30px;

}



    

    form {

      ,display: flex;

      flex-direction:grid ;

      align-items: center;

    }
input {
  width: 100%;
  padding: 10px;
  border-radius: 1px;
  border: 5px solid #fffff;
    }
    .input-field {

      margin-bottom: 15px;

    }

    .input-field label {

      display: block;

      margin-bottom: 20px;

    }

button {

  width: 80px;

  height: 48px;

background-color: white;

}

    .input-field input[type="file"] {

      display: block;

    }
    @ media all and (max-device-width: 812px)
    .input-field input[type="text"] {
      
      width: 100%;

      padding: 12px;

      border-radius: 20px;

    }
    </style>
 <script type="application/ld+json">

    {

      "@context": "https://schema.org",

      "@type": "SoftwareApplication",

      "name": "WebP Converter",

      "description": "A tool to convert images to the WebP format",

      "url": "https://webpconvertertips.blogspot.com/webp-converter",

      "applicationCategory": "Image Conversion",

      "operatingSystem": "All",

      "offers": {

        "@type": "Offer",

        "price": "0.00",

        "priceCurrency": "USD"

      },

      "creator": {

        "@type": "Organization",

        "name": "webp converter"

      }

    }

  </script>
</head>
  
   <body>
  <!-- Google Tag Manager (noscript) -->

<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-W2HC7LR"

height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>

<!-- End Google Tag Manager (noscript) --> 
  <div class="container">
    <h1>Free WebP Converter</h1> 
      
    <form>
      <div class="form-group"><label for="imageFile">Select Image File:</label>
       

 
         <input type="file" id="imageFile" accept="image/*">
      <div class="input-field">
        <label for="outputName">Output Filename:</label>

      
        <input type="text" id="outputName" placeholder="Enter output filename">
      </div>
     
      <div class=button>
         <button type="button" onclick="convertToWebP()">Convert</button>
      </div>
    </div>
  </form>

  <script>
    function convertToWebP() {
      var inputFile = document.getElementById("imageFile");
      var outputName = document.getElementById("outputName").value;

      if (inputFile.files.length > 0 && outputName.trim() !== "") {
        var file = inputFile.files[0];
        var reader = new FileReader();

        reader.onload = function (e) {
          var img = new Image();
          img.onload = function () {
            var canvas = document.createElement("canvas");
            canvas.width = img.width;
            canvas.height = img.height;
            var ctx = canvas.getContext("2d");
            ctx.drawImage(img, 0, 0);
            var webpData = canvas.toDataURL("image/webp");

            var a = document.createElement("a");
            a.href = webpData;
            a.download = outputName + ".webp";
            a.click();
          };
          img.src = e.target.result;
        };



        reader.readAsDataURL(file);
      }
    }
  </script>

</div>



</body>
</html>
