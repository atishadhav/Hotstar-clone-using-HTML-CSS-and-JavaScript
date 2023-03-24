# Hotstar-clone-using-HTML-CSS-and-JavaScript

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>Disney+ clone</title>
    <link rel="stylesheet" href="styles.css" />
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  </head>
  <body>
    <nav class="navbar">
      <img src="images/Hotstar.png" class="brand-logo" alt="" />
      <ul class="nav-links">
        <li class="nav-items"><a href="#">TV</a></li>
        <li class="nav-items"><a href="#">Movies</a></li>
        <li class="nav-items"><a href="#">Sports</a></li>
        <li class="nav-items"><a href="#">Disney+</a></li>
      </ul>
      <div class="right-container">
        <input type="text" class="search-box" placeholder="search" />
        <button class="sub-button">subscribe</button>
        <a href="a" class="login-link"> Login </a>
      </div>
    </nav>
    <div class="carousel-container">
      <div class="carousel">
        <!--<div class="slider">
          <div class="slide-content">
            <h1 class="movie-title">Loki</h1>
            <p class="movie-des">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita
              eos adipisci vitae. Nemo repellendus cupiditate neque recusandae
              quae, fugit quisquam doloribus saepe, architecto, hic accusamus
              incidunt maiores culpa sit facilis?
            </p>
          </div>
          <img src="images/slider 1.png" alt="" />
        </div> -->
      </div>
    </div>
    <div class="video-card-container">
      <div class="video-card">
        <img src="images/disney.png" class="video-card-image" alt="" />
        <video src="videos/disney.mp4" muted loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/pixar.png" class="video-card-image" alt="" />
        <video src="videos/pixar.mp4" muted loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/marvel.png" class="video-card-image" alt="" />
        <video src="videos/marvel.mp4" muted loop class="card-video"></video>s
      </div>
      <div class="video-card">
        <img src="images/star-wars.png" class="video-card-image" alt="" />
        <video src="videos/star-war.mp4" muted loop class="card-video"></video>
      </div>
      <div class="video-card">
        <img src="images/geographic.png" class="video-card-image" alt="" />
        <video
          src="videos/geographic.mp4"
          muted
          loop
          class="card-video"
        ></video>
      </div>
    </div>

    <!-- Latest & Trending -->

    <h1 class="title">Latest & Trending</h1>
    <div class="movies-list">
        <button class="pre-btn" title="btn"><img src="images/pre.png" alt=""></button>
        <button class="nxt-btn" title="btn"><img src="images/nxt.png" alt=""></button>
        <div class="card-container">

            <div class="card">
                <img src="images/poster 13.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Pop Kaun</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 17.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Night Manager</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 15.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Mandalodrian</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 14.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Run Baby Run</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 30.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Kaun Pravin Tambe?</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 16.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Gulmohar</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 7.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">movie name</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 8.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">movie name</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 9.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">movie name</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 1.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Loki</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 2.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Mulan</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 3.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">The Falcon and The Winter Soldier</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 4.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Avengers Endgame</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 5.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">THOR Ragnarok/h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 6.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Avengers</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
              </div>
              <div class="card">
                  <img src="images/poster 10.png" alt="" class="card-img">
                  <div class="card-body">
                      <h2 class="name">Luka</h2>
                      <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                      <button class="watchlist-btn">add to watchlist</button>
                  </div>
                </div>
                <div class="card">
                    <img src="images/poster 11.png" alt="" class="card-img">
                    <div class="card-body">
                        <h2 class="name">Ford vs Ferrari</h2>
                        <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                        <button class="watchlist-btn">add to watchlist</button>
                    </div>
                  </div>
                  <div class="card">
                      <img src="images/poster 12.png" alt="" class="card-img">
                      <div class="card-body">
                          <h2 class="name">Dark Phonix</h2>
                          <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                          <button class="watchlist-btn">add to watchlist</button>
                      </div>
                    </div>

        </div>
    </div>

    <!-- Best Of Superheros -->

    <h1 class="title">Best Of superheros</h1>
    <div class="movies-list">
        <button class="pre-btn"><img src="images/pre.png" alt=""></button>
        <button class="nxt-btn"><img src="images/nxt.png" alt=""></button>
        <div class="card-container">

            <div class="card">
                <img src="images/poster 1.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Loki</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 4.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Avengers Endgame</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 5.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">THOR Ragnarok</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 25.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Deadpool</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 26.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Iron Man 3</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 24.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Spider Man - No Way Home</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 23.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Spider-Man</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 19.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Ant Man-Wasp</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish.</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

            <div class="card">
                <img src="images/poster 20.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Black Panther</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 22.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">She Hulk</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 21.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">THOR-Love Thunder</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 18.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Wakanda Forever</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 3.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">The Falcon and The Winter Soldier</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 7.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Pirets-Caribbean</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 15.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Mandalodrian</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

          </div>
        </div>


            <!--Exclusive Indian Movies-->

    <h1 class="title">Exclusive Indian Movies</h1>
    <div class="movies-list">
        <button class="pre-btn"><img src="images/pre.png" alt=""></button>
        <button class="nxt-btn"><img src="images/nxt.png" alt=""></button>
        <div class="card-container">

            <div class="card">
                <img src="images/poster 27.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Atrangi Re</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 28.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Sanak</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 29.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Shiddat</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 30.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Kaun Pravin Tambe</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 31.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Maestro</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 33.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Adbhutam</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 32.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Paramapadham Vilayattu</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 17.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">The Night Manager</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 13.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Pop Kaun</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 16.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Gulmohar</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 34.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Run Baby Run</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 35.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Good Luck Jerry</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 36.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">19(1)(a)</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 37 .png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">A Thursday</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 38.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Bhoot Police</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 39.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Bhuj</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 40.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Hungama 2</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 41.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">sadak 2</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 42.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Laxmii</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 43.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Bhoomi</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
              </div>
  
        </div>
    </div>


    <!--Best Of Kids-->

    <h1 class="title">Best Of Kids</h1>
    <div class="movies-list">
        <button class="pre-btn"><img src="images/pre.png" alt=""></button>
        <button class="nxt-btn"><img src="images/nxt.png" alt=""></button>
        <div class="card-container">

            <div class="card">
                <img src="images/poster 61.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Dabangg</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 62.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Selfie With Bajrangi</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 63.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">VIR - The Robot Boy</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 64.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Chacha Bhatija</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 65.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Bhagam-Bhag</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 66.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Eena Meena Deeka</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 67.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Frozen II</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

          </div>
        </div>
    

            <!--Popular Shows-->

            <h1 class="title">Popular Shows</h1>
    <div class="movies-list">
        <button class="pre-btn"><img src="images/pre.png" alt=""></button>
        <button class="nxt-btn"><img src="images/nxt.png" alt=""></button>
        <div class="card-container">

            <div class="card">
                <img src="images/poster 44.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Ye Rishta Kya Kahelata Hai</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 45.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Anupama</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 46.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Gum Hai Kisi Ke Pyar Me?</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 47.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Aashiquana</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 48.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Na Umr Ki Sima Ho</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 49.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Radha_Krishna</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 50.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Aai Kuthe Kay Karte?</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 51.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Shinchan</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 52.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Doraemon</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 53.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Mahadev</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 54.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Saathiya 2</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 55.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Tharal Tar mag</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 56.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Pratigya</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 57.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Rajjo</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 58.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Sukh Mhnje Nakki Kay Aste?</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 59.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Thipkyanchi Rangoli</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>
            <div class="card">
                <img src="images/poster 60.png" alt="" class="card-img">
                <div class="card-body">
                    <h2 class="name">Lagnachi Bedi</h2>
                    <h6 class="des">This websites (Disney+ hotstar clone) created by Atish</h6>
                    <button class="watchlist-btn">add to watchlist</button>
                </div>
            </div>

          </div>
        </div>
  

    <script src="index.js"></script>
</body>
</html>
