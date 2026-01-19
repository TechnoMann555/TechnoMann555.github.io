<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Teodor Šešum | teodor1125@its.edu.rs">
    <title>EasyFit patike</title>
    <link rel="stylesheet" href="./css/bootstrap.min.css">
    <link rel="stylesheet" href="./css/index-style.css">
</head>
<body style="background-color: #b3d3ff;">
    <!-- Header i navigacija -->
    <header style="background-color: #334B71;">
        <nav class="py-2 text-white">
            <div class="container d-flex flex-wrap">
                <span class="d-flex flex-column justify-content-center me-5"><img src="./img/logo.png" height="35px"/></span>
                <ul class="nav me-auto">
                    <li class="nav-item"><a href="#staNudimo" class="nav-link link-light px-2">Šta nudimo</a></li>
                    <li class="nav-item"><a href="#procesIzradePatika" class="nav-link link-light px-2">Proces izrade patika</a></li>
                    <li class="nav-item"><a href="#kontakt" class="nav-link link-light px-2">Kontakt</a></li>
                </ul>
                <ul class="nav">
                    <li class="nav-item"><a href="#vazno" class="nav-link link-light px-2">Login</a></li>
                    <li class="nav-item"><a href="#vazno" class="nav-link link-light px-2">Registracija</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main role="main">
        <!-- Hero i CTA -->
        <section class="d-flex justify-content-center text-white py-4" style="background-color: #4c71aa;">
            <div class="row d-flex flex-row justify-content-center w-75">
                <div class="col-6 p-4 d-flex flex-column justify-content-evenly" style="width:450px;">
                    <div>
                        <h1 class="mb-4 fw-bold" style="text-shadow: 0px 3px 10px black">
                            Udobne i atraktivne<br>
                            patike po Vašoj meri
                        </h1>
                        <p class="fs-5" style="color: yellow">
                            <i><b>EasyFit</b></i> je biznis sa ciljem da
                            <u>pojednostavi, pojeftini i približi</u>
                            proces kreiranja kalupa patika
                            po meri Vaših stopala.
                        </p>
                        <p class="fs-5" style="color: rgb(255, 168, 37)">
                            Imate <u>osetljiva stopala, ravna stopala, visok ris</u>...?
                            <b><i>EasyFit</i></b> je rešenje za Vas!
                        </p>
                    </div>
                    <div class="text-center">
                        <a href="#vazno" class="btn btn-warning border-light fs-6">Kreirajte kalup</a>
                        <p class="fw-lighter my-3">- ili, ako ste ga kreirali -</p>
                        <a href="#vazno" class="btn btn-info border-light fs-6">Izaberite dizajn patika</a>
                    </div>
                </div>
                <div class="col-6 text-center" style="width:fit-content">
                    <img src="./img/hero-shoe.png" style="height: 500px"/>
                </div>
            </div>
        </section>
        <!-- Šta nudimo? -->
        <section id="staNudimo" class="py-5 d-flex flex-column justify-content-center align-items-center" style="background-color: #6892d3">
            <div style="width: 85%">
                <div class="text-center mb-5">
                    <h2 class="section-heading text-white fw-bold" style="text-shadow: 0 3px 10px black">Šta nudimo?</h2>
                </div>
                <div class="row text-center d-flex align-items-stretched">
                    <div class="col-md-4">
                        <div class="card ponuda-card bg-light h-100" style="border: none;">
                            <img src="./img/ponuda_1.png" class="card-img-top" style="border: none;">
                            <div class="card-body" style="color: #032a69">
                                <h4 class="card-title text-center">🔍 Kraj beskrajnom traganju za patikama</h5>
                                <p class="card-text text-center fs-5">Zaboravite isprobavanje brojnih modela patika i razočarenja zbog neudobnosti. Sa <i><b>EasyFit</b></i>, kreiran kalup se primenjuje na svaki naručeni par.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card ponuda-card bg-light h-100" style="border: none;">
                            <img src="./img/ponuda_2.png" class="card-img-top" style="border: none;">
                            <div class="card-body" style="color: #032a69">
                                <h4 class="card-title text-center">🦶 Izrada personalizovanog kalupa</h5>
                                <p class="card-text text-center fs-5">Kreiramo jedinstven kalup patika po merama Vaših stopala. Rezultat su patike koje pružaju maksimalnu udobnost pri svakom koraku.</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="card ponuda-card bg-light h-100" style="border: none;">
                            <img src="./img/ponuda_3.png" class="card-img-top" style="border: none;">
                            <div class="card-body" style="color: #032a69">
                                <h4 class="card-title text-center">👟 Jedan kalup – više modela patika</h5>
                                <p class="card-text text-center fs-5">Izaberite bilo koji <i><b>EasyFit</b></i> dizajn, bez kompromisa po pitanju udobnosti. Imaćete osećaj se kao da nosite svoj omiljeni par patika.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Proces izrade patika -->
        <section id="procesIzradePatika" class="py-5" style="background-color: #81aae7;">
            <div class="container d-flex flex-column justify-content-center align-items-center">
                <div class="text-center mb-5">
                    <h2 class="section-heading text-white fw-bold" style="text-shadow: 0 3px 10px black">Proces izrade patika</h2>
                </div>
                <div id="carouselExampleCaptions" class="carousel slide w-75 rounded" data-bs-ride="carousel" data-bs-interval="false">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active bg-dark" aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" class="bg-dark" aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" class="bg-dark" aria-label="Slide 3"></button>
                        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" class="bg-dark" aria-label="Slide 4"></button>
                    </div>
                    <div class="carousel-inner rounded">
                        <div class="carousel-item active">
                            <img src="./img/korak_1.png" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block text-dark rounded px-2" style="background-color: rgba(255, 255, 255, 0.7); bottom: 3rem;">
                                <h4 class="text-decoration-underline" style="color: #032a69;">1. Kreiranje kalupa</h4>
                                <p class="mb-0 fs-5" style="color: #032a69;"> U <i><b>EasyFit</b></i> lokalima ili ovlašćenim prodavnicama patika merimo Vaša stopala i kreiramo kalup. Kalup se po potrebi dodatno prilagođava, kako bi pristajanje bilo savršeno.</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="./img/korak_2.png" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block text-dark rounded px-2" style="background-color: rgba(255, 255, 255, 0.7); bottom: 3rem;">
                                <h4 class="text-decoration-underline" style="color: #032a69;">2. Izbor dizajna</h4>
                                <p class="mb-0 fs-5" style="color: #032a69;">Vi birate željeni dizajn patika putem sajta. Vaš kalup se primenjuje na izabrani dizajn, bez brige o udobnosti.</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="./img/korak_3.png" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block text-dark rounded px-2" style="background-color: rgba(255, 255, 255, 0.7); bottom: 3rem;">
                                <h4 class="text-decoration-underline" style="color: #032a69;">3. Proizvodnja</h4>
                                <p class="mb-0 fs-5" style="color: #032a69;">Nakon poručivanja, započinje proizvodnja patika po Vašem kalupu i izabranom dizajnu. Svaki par se proizvodi sa posvećenošću i pažnjom, kako bi zadržao kvalitet i udobnost.</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <img src="./img/korak_4.png" class="d-block w-100" alt="...">
                            <div class="carousel-caption d-none d-md-block text-dark rounded px-2" style="background-color: rgba(255, 255, 255, 0.7); bottom: 3rem;">
                                <h4 class="text-decoration-underline" style="color: #032a69;">4. Dostava i preuzimanje patika</h4>
                                <p class="mb-0 fs-5" style="color: #032a69;">Patike izrađene po merama Vaših stopala, spremne za udobno nošenje od prvog koraka, dostavljamo na Vašu adresu ili u izabranu prodavnicu.</p>
                            </div>
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon bg-dark" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                        <span class="carousel-control-next-icon bg-dark" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
        </section>
        <!-- Kontakt i ostale informacije -->
        <section class="p-0" style="background-color: #AAC5EE;">
            <div class="w-100 d-flex flex-column justify-content-center align-items-center" style="position: relative;">
                <div id="kontakt" class="rounded-3 py-3 w-50" style="position: absolute; background-color: rgba(255, 255, 255, 0.8);">
                    <div class="text-center mb-5 mt-3">
                        <img src="./img/logo.png" style="height: 175px"/>
                    </div>
                    <div class="text-center fs-5" style="color: #032a69">
                        <p>
                            Telefon: +381 61 123 1234<br>
                            Email: support@easyfit.com
                        </p>
                    </div>
                    <div class="text-center fs-3 mx-3" style="color: red;">
                        <p id="vazno">Sajt je deo projekta planiranog Nastavnog plana i programa za predmet Preduzetništvo u IT, prve godine master strukovnih studija na Visokoj školi strukovnih studija za informacione tehnologije (ITS).
Kao takav, predstavlja imaginarni biznis u prethodno navedenu svrhu.</p>
                    </div>
                </div>
                <img src="./img/footer_image.png" class="w-100"/>
            </div>
        </section>
    </main>
    <script type="text/javascript" src="./js/bootstrap.min.js"></script>
</body>
</html>
