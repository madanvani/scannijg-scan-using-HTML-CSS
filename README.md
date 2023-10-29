# scannijg-scan-using-HTML-CSS

#HTML:=
<!DOCTYPE html>
<html>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
     <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
     <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
     <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    
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
    

