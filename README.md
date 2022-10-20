# Responsividade-inicial
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsividade</title>
    <link rel="stylesheet" href="./style.css"
  </head>
  <body>
    <img src="./01.jpg" alt="img-01" class="img-contet" />
    <h1 class="title-content">Titulo 1</h1>
    <p class="text-content">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nobis rem
      veritatis, a officia, molestias cumque vero incidunt doloremque reiciendis
      aliquid repudiandae vitae, et illum explicabo? Praesentium illum hic
      voluptatibus maxime esse numquam eius ad deleniti.
    </p>
    <img src="./02.jpg" alt="img-2" class="imag-contet" />
    <h1 class="title-content">Titulo 2</h1>
    <p class="text-content">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam,
      aspernatur. Deserunt excepturi vitae enim non nihil expedita, hic porro
      deleniti voluptatum quas quos tempora voluptatem.
    </p>
    <img src="./03.jpg" alt="img-2" class="img-contet" />
    <h1 class="title-content">Titulo 3</h1>style.css
    <p class="text-content">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa architecto
      mollitia libero nesciunt fugiat nihil?
    </p>
  </body>
</html>
////// Stylecss
.img-content {
  width: 765;
  height: 400px;
}

.text-content {
  font-size: 22px;
  font-family: Arial, Helvetica, sans-serif;
}
@media (max-width: 790px) {
  .img-content {
    width: 90%;
    height: auto;
  }
}
@media (max-width: 425px) {
  .img-content {
    width: 100%;
    height: auto;
  }
  .title-content {
    text-align: center;
  }
  .text-content {
    font-size: 18px;
    text-align: center;
  }
}
@media (max-width: 320px) {
  .text-content {
    font-size: 14px;
  }
}

