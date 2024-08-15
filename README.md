<html lang="pt-BR">

<head>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="stylesheet">
    <title>muliruflix</title>
</head>

<body>
    <header>MULIRUFLIX</header>

    <section class="chamada">
        <div class="chamada-texto">
            <h1>KIMRTSU NO YAIBA E O DESTRITO DO DRIP</h1>
            <p>#kimetsu</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/ZPGwxahIdds?si=H500ptexTzzjQyDd" 
            title="YouTube video player" frameborder="0" 
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
            referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            
        </div>
    </section>

    <section class="categoria">
        <h2>Animes Resumos</h2>
        <div class="categoria-videos">
            <a href="https://www.youtube.com/watch?v=H-MJIg9CfU4&list=PLkmMLmC12qnyswkcd8TQlnQNlHEbX-mL6">
                <img src="https://img.youtube.com/vi/H-MJIg9CfU4&list=PLkmMLmC12qnyswkcd8TQlnQNlHEbX-mL6/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=vfNSvQ9CYi4">
                <img src="https://img.youtube.com/vi/vfNSvQ9CYi4/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=J-ZjDtSESJM&t=329s">
                <img src="https://img.youtube.com/vi/J-ZjDtSESJM&t=329s/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=4SGDiyjjJIg">
                <img src="https://img.youtube.com/vi/4SGDiyjjJIg/maxresdefault.jpg" />
            </a>
            <a href="https://www.youtube.com/watch?v=3ABbjeRgDJ4">
                <img src="https://img.youtube.com/vi/3ABbjeRgDJ4/maxresdefault.jpg" />
            </a>
        </div>
    </section>

</body>

</html>















CSS
body {
    color: rgb(53, 40, 20);
    background: rgb(0, 0, 0);
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
}

header {
    border-bottom: solid 2px rgb(42, 122, 228);
    padding: 20px;
    font-size: 32px;
    color: rgb(42, 122, 228);
}

.chamada {
    background: rgb(42, 87, 138);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 5%;
}

h1 {
    font-size: 40px;
}

p {
    font-size: 20px;
}

.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
}

.categoria {
    padding-left: 20px;
    padding-right: 20px;
    margin-top: 50px;
}

.categoria-videos img {
    opacity: 0.5;
    height: 200px;
}

.categoria-videos img:hover {
    opacity: 1.0;
    border: 3px solid green;
}

.categoria h2 {
    color: rgb(42, 122, 228);
}
