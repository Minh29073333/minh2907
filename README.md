<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="website icon" type="png" href="image/traitym.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css" integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Gửi em!</title>
</head>
<body>
    <div class="wrapper">
        <div class="crile-1"></div>
        <div class="crile-2"></div>
        <div class="crile-3"></div>
        <div class="crile-4"></div>
        <div class="heart">
            <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                viewBox="0 0 323.47 305.1" style="enable-background:new 0 0 323.47 305.1;" xml:space="preserve">
            <path class="st0" d="M263.95,161.72c-0.79,0.79-1.59,1.55-2.4,2.28l0.06,0.06l-99.88,99.88l-99.87-99.88l0.05-0.05
                c-0.81-0.74-1.61-1.5-2.4-2.29c-13.79-13.79-20.68-31.86-20.68-49.94c0-18.07,6.89-36.15,20.69-49.94
                c13.79-13.79,31.86-20.68,49.94-20.68c18.07,0,36.14,6.89,49.93,20.68c0.79,0.79,1.55,1.59,2.28,2.4c0.03,0.02,0.05,0.04,0.07,0.06
                c0.01-0.02,0.03-0.04,0.05-0.06c0.74-0.81,1.5-1.61,2.29-2.4c13.79-13.79,31.86-20.68,49.94-20.68c18.07,0,36.14,6.89,49.93,20.68
                C291.53,89.42,291.53,134.14,263.95,161.72z"/>
            </svg>
        </div>
        <div class="traitym">
            <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
                viewBox="0 0 323.47 305.1" style="enable-background:new 0 0 323.47 305.1;" xml:space="preserve">
            <path class="st1" d="M0,152.55h53.28l13.76-29.86c0,0,8.87,57.48,9.78,57.48s15.59-70.01,15.59-70.01l11.62,59.01l9.17-43.11
                l11.31,26.49h79.8l14.06-24.66l8.87,42.19l11.62-34.85l9.17,42.19l10.7-63.59l9.48,38.72h55.26"/>
            <path class="st2" d="M196.74,116.91l0.01,0.01l-35.02,35.02l-35.02-35.02c-4.43-4.47-7.16-10.62-7.16-17.42
                c0-6.83,2.77-13.03,7.25-17.51c4.48-4.48,10.67-7.25,17.51-7.25c6.8,0,12.95,2.73,17.42,7.16c4.47-4.43,10.63-7.16,17.41-7.16
                c6.84,0,13.03,2.77,17.51,7.25c4.49,4.48,7.26,10.68,7.26,17.51C203.91,106.29,201.18,112.44,196.74,116.91z"/>
            </svg>
        </div>
        <div class="avt">
            <img src="image/truongan.jpg" alt="">
        </div>

        <div class="heart-item1">
            <img src="image/heart.png" alt="">
        </div>
        <div class="heart-item2">
            <img src="image/heart2.png" alt="">
        </div>
        <div class="box-heart">
            <div class="heart1">
                <i class="fa-solid fa-heart"></i>
            </div>
            <div class="heart2">
                <i class="fa-solid fa-heart"></i>
            </div>
            <div class="heart3">
                <i class="fa-solid fa-heart"></i>
            </div>
            <div class="heart4">
                <i class="fa-solid fa-heart"></i>
            </div>
        </div>
        <div class="box-big_clouds">
            <div class="big_clouds1">
                <img src="image/big-clouds1.png" alt="">
            </div>
            <div class="big_clouds2">
                <img src="image/big-clouds2.png" alt="">
            </div>
            <div class="big_clouds3">
                <img src="image/big-clouds3.png" alt="">
            </div>
        </div>
        <div class="mail">
            <button><i class="fa-regular fa-envelope"></i></button>
            <span class="heartMail"><i class="fa-solid fa-heart"></i></span>
        </div>
        <div class="icon">
            <i class="fa-solid fa-chevron-left"></i>
        </div>
        <div class="gift"></div>
        <div class="gift1"></div>
        <div class="gift2"></div>
        <div class="gift3"></div>
        <div class="textLove">
            <p>I</p>
            <p>Love</p>
            <p>You</p>
        </div>
    </div>
</body>
<script>
    var mail = document.querySelector(".mail")
    mail.addEventListener("click", ()=>{
        window.location.href = "mail.html"
    })
</script>
</html>
