<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionHome">
        <div class="bg-container d-flex flex-column justify-content-end">
            <div class="tourism-card">
                <h1 class="main-heading">Tourism</h1>
                <p class="paragraph">Plan your trip.</p>
                <button class="button" onclick="display('sectionFavouritePlaces')">
                    Get Started
                </button>
            </div>
        </div>
    </div>
    <div id="sectionFavouritePlaces">
        <div class="favourite-places-bg-container">
            <h1 class="favourite-places-heading">Favourite Places</h1>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionTajMahalDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">Taj Mahal</h1>
                    <p class="favourite-place-card-description">
                        If there was just one symbol to represent all of India, it would
                        be the Taj Mahal
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionGoldentempleDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">Golden Temple</h1>
                    <p class="favourite-place-card-description">
                        Amritsar is world-famous for the beautiful and highly revered
                        Golden Temple
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/golden-temple-img.png" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionMysorepalaceDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">Mysore Palace</h1>
                    <p class="favourite-place-card-description">
                        The Mysore Palace is a historical palace and the royal residence
                        at Mysore .
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace-img.png" class="favourite-place-card-image" />
            </div>
            <div class="favourite-place-card-container d-flex flex-row" onclick="display('sectionVaranasitempleDetailedView')">
                <div>
                    <h1 class="favourite-place-card-heading">Varanasi Temple</h1>
                    <p class="favourite-place-card-description">
                        Varanasi Temple is most famous Hindu temples dedicated to Lord
                        Shiva
                    </p>
                </div>
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi-temple-img.png" class="favourite-place-card-image" />
            </div>
            <button class="btn btn-dark" onclick="display('sectionHome')">
                back
            </button>
        </div>
    </div>
    <div id="sectionTajMahalDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="carouselExampleIndicators1" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#carouselExampleIndicators1" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#carouselExampleIndicators1" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Taj Mahal</h1>
                    <p class="detailed-view-card-description">
                        The Taj Mahal is considered to be the greatest architectural
                        achievement in the whole range of Indo-Islamic architecture. Its
                        recognised architectonic beauty has a rhythmic combination of
                        solids and voids, concave and convex and light shadow; such as
                        arches and domes further increases the aesthetic aspect. Not a
                        piece of architecture, as other buildings are, but the proud
                        passions of an emperor’s love wrought in living stones.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>

    <div id="sectionGoldentempleDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="goldenTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#goldenTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#goldenTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/goldentemple3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#goldenTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#goldenTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Golden Temple</h1>
                    <p class="detailed-view-card-description">
                        The Golden Temple, also known as Harmandir Sahib is a gurdwara
                        located in the city of Amritsar, Punjab, India. There are many
                        places to visit Near Golden Temple like Jallianwala Bagh, Wagah Border, Harike Wetland, Bathinda Fort.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>

    <div id="sectionMysorepalaceDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="mysorePalaceCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#mysorePalaceCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#mysorePalaceCarousel" data-slide-to="1"></li>
                        <li data-target="#mysorePalaceCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#mysorePalaceCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#mysorePalaceCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Mysore Palace</h1>
                    <p class="detailed-view-card-description">
                        Mysore Palace, also called Amba Vilas Palace, is one of the most magnificent and largest palaces in India. Situated in the southern state of Karnataka, it used to be the official residence of the Wodeyar Dynasty, the rulers of Mysore from 1399 to 1950. The grand palace stands tall in the heart of Mysore city and attracts visitors from across the world. Being one of the prime attractions in India after the Taj Mahal, it certainly deserves a place in every traveler’s bucket list.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>

    <div id="sectionVaranasitempleDetailedView">
        <div class="detailed-view-bg-container">
            <h1 class="detailed-view-heading">Detailed View</h1>
            <div class="detailed-view-card-container">
                <div id="varanasiTempleCarousel" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        <li data-target="#varanasiTempleCarousel" data-slide-to="0" class="active"></li>
                        <li data-target="#varanasiTempleCarousel" data-slide-to="1"></li>
                        <li data-target="#varanasiTempleCarousel" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi1-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi2-img.png" class="d-block w-100" alt="..." />
                        </div>
                        <div class="carousel-item">
                            <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi3-img.png" class="d-block w-100" alt="..." />
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#varanasiTempleCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#varanasiTempleCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
                <div class="detailed-view-card-text-container">
                    <h1 class="detailed-view-card-heading">Varanasi Temple</h1>
                    <p class="detailed-view-card-description">
                        Sri Kashi Vishwanath Temple also known as the Golden Temple, it is dedicated to Lord Shiva, the presiding deity of the city. Varanasi is Said to be the point at which the first jyotirlinga, the fiery pillar of light by which shiva manifested has supremacy over others gods, broke through the Earth’s crust and flared towards the heavens. More than the Gaths and even the Ganga, the Shivalinga installed in the temple remains the devotional focus of Varanasi.
                    </p>
                </div>
            </div>
            <button class="btn btn-dark" onclick="display('sectionFavouritePlaces')">
                back
            </button>
        </div>
    </div>

@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
    height: 100vh;
    background-size: cover;
}

.tourism-card {
    text-align: center;
    background-color: white;
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
    padding: 5px;
}

.button {
    color: white;
    background-color: #25b1cc;
    width: 138px;
    height: 36px;
    border-width: 0px;
    border-radius: 20px;
}

.main-heading {
    font-family: "Roboto";
}

.paragraph {
    font-family: "Roboto";
}

.favourite-places-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/towerbg.png");
    height: 100vh;
    background-size: cover;
    padding: 24px;
}

.favourite-places-heading {
    color: white;
    font-family: "Roboto";
    font-size: 28px;
    font-weight: bold;
}

.favourite-place-card-container {
    background-color: white;
    border-radius: 8px;
    padding: 16px;
    margin-bottom: 15px;
}

.favourite-place-card-heading {
    color: #0f0e46;
    font-family: "Roboto";
    font-size: 23px;
    font-weight: bold;
}

.favourite-place-card-description {
    color: #6c6b70;
    font-family: "Roboto";
    font-size: 13px;
}

.favourite-place-card-image {
    width: 80px;
    height: 100px;
}

.favourite-place-card-text-container {
    margin-right: 15px;
}

.detailed-view-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/seabg.png");
    height: 100vh;
    background-size: cover;
}

.detailed-view-heading {
    color: white;
    font-family: "Roboto";
    font-size: 28px;
    font-weight: bold;
    padding: 24px;
}

.detailed-view-card-container {
    background-color: white;
    border-bottom-right-radius: 8px;
    border-bottom-left-radius: 8px;
    margin: 24px;
}

.detailed-view-card-heading {
    color: #0f0e46;
    font-family: "Roboto";
    font-size: 23px;
    font-weight: bold;
}

.detailed-view-card-description {
    color: #6c6b70;
    font-family: "Roboto";
    font-size: 13px;
}

.detailed-view-card-text-container {
    padding: 16px;
}

.detailed-view-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/seabg.png");
    height: 100vh;
    background-size: cover;
}

.detailed-view-heading {
    color: white;
    font-family: "Roboto";
    font-size: 28px;
    font-weight: bold;
    padding: 24px;
}

.detailed-view-card-container {
    background-color: white;
    border-bottom-right-radius: 8px;
    border-bottom-left-radius: 8px;
    margin: 24px;
}

.detailed-view-card-heading {
    color: #0f0e46;
    font-family: "Roboto";
    font-size: 23px;
    font-weight: bold;
}

.detailed-view-card-description {
    color: #6c6b70;
    font-family: "Roboto";
    font-size: 13px;
}

.detailed-view-card-text-container {
    padding: 16px;
}

.detailed-view-bg-container {
    background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/seabg.png");
    height: 100vh;
    background-size: cover;
}

.detailed-view-heading {
    color: white;
    font-family: "Roboto";
    font-size: 28px;
    font-weight: bold;
    padding: 24px;
}

.detailed-view-card-container {
    background-color: white;
    border-bottom-right-radius: 8px;
    border-bottom-left-radius: 8px;
    margin: 24px;
}

.detailed-view-card-heading {
    color: #0f0e46;
    font-family: "Roboto";
    font-size: 23px;
    font-weight: bold;
}

.detailed-view-card-description {
    color: #6c6b70;
    font-family: "Roboto";
    font-size: 13px;
}

.detailed-view-card-text-container {
    padding: 16px;
}



















    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>
