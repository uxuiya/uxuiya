
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;700&family=Roboto&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="header center">
        <a class="header_link" href="#about">Обо мне</a>
        <a class="header_link" href="#skills">Навыки</a>
        <a class="header_link" href="#work">Мои работы</a>
        <a class="header_link" href="#contacts">Контакты</a>
    </div>
    <div class="top center">
        <h1 class="h1">Yuliya Anasovich</h1>
        <img class="topphoto" src="img/1.svg" alt="top photo">
    </div>
    <div class="about_me center" id="about">
        <h2 class="h2">Обо мне</h2>
        <div class="about_content">
            <img class="aboutphoto" src="img/2.svg" alt="about me">
            <p class="text_aboutme">Hi! I am a beginner UX/UI designer. She started her journey at the beginning of 2022. I have always been attracted to how you can make things around me, including on the Internet, both beautiful and convenient. 
                I have already managed to work on creating an application for a car, as well as a pet shelter website.
            </p>
        </div>
    </div>
    <div class="skills center" id="skills">
        <h2 class="h2">Навыки</h2>
        <div class="skills_content">
            <img class="skillsphoto" src="img/3.svg" alt="photoshop">
            <img class="skillsphoto" src="img/4.svg" alt="illustrator">
            <img class="skillsphoto" src="img/5.svg" alt="figma">
            <img class="skillsphoto" src="img//6.svg" alt="miro">
        </div>
    </div>
    <div class="works center" id="work">
        <h2 class="h2">Мои работы</h2>
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="true">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="img/7.jpg" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="img/8.jpg" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="img/9.jpg" class="d-block w-100" alt="...">
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
    </div>
    <div class="contacts_link center" id="contacts">
        <h2 class="h2">Контакты</h2>
        <div class="contacts_content">
            <div class="contacts_info">
                <a class="contacts" href="mailto:yuliya.anasovich@mail.ru">yuliya.anasovich@mail.ru</a>
                <a class="contacts" href="tel:+37544513**77">+375 44 513 ** 77</a>
            </div>
            <img class="planephoto" src="img/8.svg" alt="plane">
         </div>
    </div>
    <div class="footer center">
        <a class="sn" href="https://viber.com"><img width="32" src="img/viber.svg" alt="viber"></a>
        <a class="sn" href="https://instagram.com"><img width="32" src="img/instagram.svg" alt="instagram"></a>
        <a class="sn" href="https://vk.com"><img width="32" src="img/vk.svg" alt="vk"></a>    
    </div> 
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>    
</body>

</html>
