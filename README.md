# scannijg-scan-using-HTML-CSS

#HTML:=
<!DOCTYPE html>
<html>

<head>
      <link rel="stylesheet" href="madan.css">
</head>
<body>
    <div class="scanner">
    <h1>
        Scanning...
    </h1>
    </div>
  </body>



    </html>
    
    #CSS:=
      
               .scanner h1{
    color: #252839;
    font-size: 4rem;
    position: absolute;
}
.scanner h1:before{
    content: "Scanning...";
    position: absolute;
    top: 0;
    left: 0;
    width: 0;
    height: 100%;
    border-right: 4px solid red;
    box-shadow: 0 0 10px  #ff0000;
    overflow: hidden;
    color: red;
    animation: scan 4s linear infinite;
}
@keyframes scan{
    0%, 10%, 100%{
        width: 0;
    }
    60%, 80%{
        width: 100%;
    }
}
    

