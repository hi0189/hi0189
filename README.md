- 👋 Hi, I’m @hi0189
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
hi0189/hi0189 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="pt-Br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Blog</title>
    <style>
        body {
            display: grid;
            margin: 0;
            height: 100vh;
            grid-template-areas:
                "header header"
                "header2 header2"
                "header3 header3"
                "main main2"
                "footer footer"
                "footer1 footer1"
                "footer2 footer2";

            grid-template-rows: 150px 450px 600px 0px 50px;
            grid-template-columns: 1fr 200px;
        }

        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap');

        .header1 {
            grid-area: header;
            background-color: #290742;
            color: white;
            padding: 40px 90px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-family: "Poppins", sans-serif;
        }

        .span1 {
            color: #4fff4b;
        }

        nav li {
            display: inline;
            margin: 5px 5px 5px 15px;
        }

        nav a {
            text-decoration: none;
            color: white;
            align-items: center;
            font-family: "Poppins", sans-serif;
        }

        .home {
            border-left: 3px solid;
            border-color: #4fff4b;
        }

        .search {
            border-top-left-radius: 5px;
            border-bottom-left-radius: 5px;
            background-color: #170027;
            border: none;
            width: 200px;
            height: 35px;
        }

        ::-webkit-input-placeholder {
            color: white;
            font-family: "Poppins", sans-serif;
        }

        .img1 {
            position: relative;
            top: 14px;
            right: 7px;
            background-color: #9e6dc2;
            box-sizing: border-box;
            width: 35px;
            height: 36px;
            border-top-right-radius: 5px;
            border-bottom-right-radius: 5px;

        }

        .img2 {
            position: relative;
        }

        .header2 {
            grid-area: header2;
            background-color: #290742;
            border-bottom: 5px solid;
            border-color: #4fff4b;
            display: flex;
            justify-content: space-between;
        }

        .p1 {
            color: #9e6dc2;
            font-family: "Poppins", sans-serif;
            font-size: 40px;
            padding: 0px 90px;
            line-height: 60px;
        }

        .img2 {
            position: relative;
            top: 50px;
            right: 80px;
            width: 550px;
            height: 320px;
        }

        .header3 {
            grid-area: header3;
            background-color: pink;
        }

        .p2 {
            position: relative;
            bottom: 250px;
            color: white;
            padding: 40px 90px;
            font-family: "Poppins", sans-serif;
        }

        .p3 {
            position: relative;
            bottom: 300px;
            padding: 40px 90px;
            font-family: "Poppins", sans-serif;
            color: #290742;
        }

        .a1 {
            text-decoration: none;
        }

        .img3 {
            position: relative;
            top: 7px;
        }

        .main1 {
            grid-area: main;
            display: grid;
            justify-content: space-between;
            align-items: center;
            position: relative;
            bottom: 630px;
            padding: 40px 40px;
        }

        .figcaption1 {
            position: relative;
            bottom: 15px;
            left: 42px;
            font-family: "Poppins", sans-serif;
            font-size: 12px;
        }

        .main2 {
            grid-area: main2;
            display: grid;
            justify-content: space-between;
            align-items: center;
            position: relative;
            bottom: 570px;
            right: 428px;
            color: #290742;
        }

        .figcaption2 {
            font-family: "Poppins", sans-serif;
            font-size: 12px;
        }

        .a2 {
            text-decoration: none;
            font-family: "Poppins", sans-serif;
            font-size: 23px;
            white-space: nowrap;
            position: relative;
            bottom: 10px;
            color: #290742;
        }

        .p4 {
            font-family: "Poppins", sans-serif;
            font-size: 14px;
            white-space: nowrap;
            position: relative;
            bottom: 28px;
            border-bottom: 1px solid;
            border-color: #d3d3d3;
            line-height: 20px;
        }

        .figcaption3 {
            position: relative;
            bottom: 25px;
            font-family: "Poppins", sans-serif;
            font-size: 12px;
            justify-content: space-between;
        }

        .a3 {
            color: #290742;
            text-decoration: none;
            font-size: 23px;
            font-family: "Poppins", sans-serif;
            white-space: nowrap;
            position: relative;
            bottom: 33px;
        }

        .p5 {
            font-family: "Poppins", sans-serif;
            font-size: 14px;
            position: relative;
            bottom: 45px;
        }

        .a4 {
            font-family: "Poppins", sans-serif;
            font-size: 23px;
            color: #290742;
            padding: 90px 40px;
            text-decoration: none;
            position: relative;
            bottom: 20px;
        }

        .p6 {
            font-family: "Poppíns", sans-serif;
            font-size: 14px;
            position: relative;
            padding: 90px 40px;
            bottom: 125px;
        }

        .footer1 {
            grid-area: footer;
            display: -webkit-flex;
            padding: 90px 40px;
            position: relative;
            bottom: 160px;
        }

        .figcaption4 {
            font-family: "Poppins", sans-serif;
            font-size: 12px;
        }

        .figcaption5 {
            font-family: "Poppins", sans-serif;
            font-size: 12px;
            position: relative;
            left: 18px;
        }

        .figcaption6 {
            font-family: "Poppins", sans-serif;
            font-size: 12px;
            position: relative;
            left: 35px;
        }

        .footer2 {
            grid-area: footer1;
            display: -webkit-flex;
            padding: 40px 80px;
            position: relative;
            bottom: 300px;
            align-items: center;

        }

        .img5 {
            position: relative;
            left: 18px;
        }

        .a5 {
            font-family: "Poppins", sans-serif;
            font-size: 20px;
            text-decoration: none;
            color: #290742;
            position: relative;
            top: 430px;
        }

        .img6 {
            position: relative;
            left: 30px;
        }

        .a6 {
            font-family: "Poppins", sans-serif;
            font-size: 20px;
            text-decoration: none;
            color: #290742;
            position: relative;
            left: 150px;
            top: 430px;
        }

        .a7 {
            font-family: "Poppins", sans-serif;
            font-size: 20px;
            text-decoration: none;
            color: #290742;
            position: relative;
            left: 300px;
            top: 430px;
        }

        .footer3 {
            grid-area: footer2;
            display: -webkit-flex;
            padding: 40px 90px;
        }

        .p9 {
            font-family: "Poppins", sans-serif;
            font-size: 14px;
            position: relative;
            top: 30px;
            right: 10px;
        }

        .p7 {
            font-family: "Poppins", sans-serif;
            font-size: 14px;
            position: relative;
            top: 30px;
            left: 147px;
        }

        .p8 {
            font-family: "Poppins", sans-serif;
            font-size: 14px;
            position: relative;
            top: 30px;
            left: 300px;
        }
    </style>
</head>

<body>
    <header class="header header1">
        <h1>The Blog<span class="span span1">.</span></h1>
        <nav>
            <ul>
                <li class="home"><a href=""><strong>Home</strong></a></li>
                <li><a href="">Sobre</a></li>
                <li><a href="">Categorias</a></li>
                <li><a href="">Contato</a></li>
            </ul>
        </nav>
        <div class="div div1">
            <input class="search" type="search" placeholder="Buscar...">
            <img class="img img1" src="search.svg" alt="search">
        </div>
    </header>
    <header class="header header2">
        <p class="p p1"><strong>Veja o guia definitivo para <br>conquistar seus objetivos <br>como DEV em 2022 </strong>
        </p>
        <img class="img img2" src="featured-image.png" alt="codding" title="codding">

    </header>
    <header class="header header 3">
        <p class="p p2">Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br>
            Nibh nibh eu in aliquet ut adipisicing neque. Sed volupat <br> aenean sit vitae, sed tristique placerat hac
        </p>
        <p class="p p3"><strong><a class="a a1" href="">Veja Mais <img class="img img3" src="arrow-right.svg"
                        alt="arrow-right"></a></strong></p>
    </header>
    <main class="main main1">
        <figure class="figure figure1"><img src="post-1.png" alt="compute"></figure>
        <figcaption class="figcaption figcaption1">Janeiro 04, 2022</figcaption>
        <p><strong><a class="a a4" href="">Começando no ReactJS em 2022</a></strong></p>
        <p class="p p6">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nibh nibh eu in aliquet <br> ut
            adipisicing neque. Sed volutpat aenean sit vitae, sed tristique nibh nibh eu in <br> aliquet ut adipisicing
            neque. Sede volutpat aenean sit vitae, sed tristique. Sed <br> volutpat aenean</p>
    </main>
    <main class="main main2">
        <figcaption class="figcaption figcaption2">Janeiro 04, 2022</figcaption>
        <p><strong><a class="a a2" href="">Conheça as principais técnicas para <br> conseguir uma vaga internacional
                    <br>
                    em
                    programação</a></strong></p>
        <p class="p p4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nibh nibh <br> eu in aliquet ut
            adipisicing neque. Sed volupt aenean sit vitae, <br> sed tristique.</p>
        <figcaption class="figcaption figcaption3">Janeiro 04, 2022</figcaption>
        <p><strong><a class="a a3" href="">Veja a solução do Front-end na prática</a></strong></p>
        <p class="p p5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nibh nibh <br> eu in aliquet ut
            adipisicing neque.</p>
    </main>
    <footer class="footer footer1">
        <figure><img class="img img4" src="post-2.png" alt="computer">
            <figcaption class="figcaption figcaption4">Janeiro 04, 2022</figcaption>
        </figure>
        <figure><img class="img img5" src="post-3.png" alt="codding01">
            <figcaption class="figcaption figcaption5">Janeiro 04, 2022</figcaption>
        </figure>
        <figure><img class="img img6" src="post-4.png" alt="phone">
            <figcaption class="figcaption figcaption6">Janeiro 04, 2022</figcaption>
        </figure>
    </footer>
    <footer class="footer footer2">
        <p><strong><a class="a a5" href="">10 dicas para conseguir uma vaga <br>desejada</a></strong></p>
        <p><strong><a class="a a6" href="">Deixe seu código mais semântico <br>com essas dicas</a></strong></p>
        <p><strong><a class="a a7" href="">Use essas dicas nas suas <br>aplicações mobile</a></strong></p>
    </footer>
    <footer class="footer footer3">
        <p class="p p9">Lorem ipsum dolor sit amet, consectetur adipisicing <br> elit. Nibh eu in aliquet ut adipisicing
            neque. Sed <br> volupat aenean sit vitae, sed tristique</p>
        <p class="p p7">Lorem ipsum dolor sit amet, consectetur adipisicing <br> elit. Nibh eu in aliquet ut adipisicing
            neque. Sed <br> volupat aenean sit vitae, sed tristique</p>
        <p class="p p8">Lorem ipsum dolor sit amet, consectetur adipisicing <br> elit. Nibh eu in aliquet ut adipisicing
            neque. Sed <br> volupat aenean sit vitae, sed tristique</p>
    </footer>
</body>

</html>
