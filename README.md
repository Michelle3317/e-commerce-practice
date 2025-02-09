<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Library</title>
    <link rel="stylesheet" href="./style.css">
  </head>
  <body>
    <section id="landing">
      <nav>
        <div class="nav_container">
          <img class="logo" src="./E-commerce asstes/Library.svg" alt="" />
          <ul class="nav_links">
            <li><a href="#" class="nav_link">Home</a></li>
            <li><a href="#" class="nav_link">Contact</a></li>
            <li><a href="#" class="nav_link nav_link--primary">Books</a></li>
          </ul>
          <button class="btn_menu" onclick="openMenu()">
            <i class="fas fa-bars"></i>
          </button>
          <div class="menu_backdrop">
            <button class="btn_menu btn_menu--close" onclick="closeMenu ()">
              <i class="fas fa-times"></i>
            </button>
            <ul class="menu_links">
              <li class="menu_list">
                <a href="#" class="menu_link" onclick="closeMenu ()">Home</a>
              </li>
              <li class="menu_list">
                <a href="#features" class="menu_link" onclick="closeMenu ()"
                  >Books</a
                >
              </li>
              <li class="menu_list">
                <a class="menu_link no-cursor" onclick="closeMenu ()"
                  >Contacts</a
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <header>
        <div class="header_container">
          <div class="header_description">
            <h1>America's most awarded online library platform</h1>
            <h2>
              Find your dream book with <span class="purple">Library</span>
            </h2>
            <a href="#features">
              <button class="btn">Browse books</button>
            </a>
          </div>
          <figure class="header_img--wrapper">
            <img src="./E-commerce asstes/Undraw_Books.svg" alt="" />
          </figure>
        </div>
      </header>
    </section>

    <main>
      <section id="highlights">
        <div class="container">
          <div class="row">
            <h2 class="section_title">
              Why choose <span class="purple">Library</span>
            </h2>
            <div class="highlight_wrapper">
              <div class="highlight">
                <div class="highlight_img">
                 <i class="fas fa-bolt"></i>
                </div>
                <h3 class="highlight_subtitle">Easy and Quick</h3>
                <p class="highlight_para">
                Get access to the book your purchased online instantly.
                </p>
              </div>
              <div class="highlight">
                <div class="highlight_img">
                  <i class="fas fa-book-open"></i>
                </div>
                <h3 class="highlight_subtitle">10,000+ Books</h3>
                <p class="highlight_para">
                  Library has books in all your favorite categories.
                </p>
              </div>
              <div class="highlight">
                <div class="highlight_img">
                  <i class="fas fa-tags"></i>
                </div>
                <h3 class="highlight_subtitle">Affordable</h3>
                <p class="highlight_para">
                  Get your hands on popular books for as little as $10.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="features">
        <div class="container">
          <div class="row">
            <h2 class="section_title">
              Featured <span class="purple">Books</span>
            </h2>
            <div class="books">
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/crack the coding interview.png"
                    alt=""
                  />
                </figure>
                <div class="book_title">Cracking the Coding Interview

                </div>
                <div class="book_ratings">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/atomic habits.jpg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Atomic Habits</div>
                <div class="book_ratings">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/david goggins.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Can't Hurt Me</div>
                <div class="book_ratings">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/deep work.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Deep Work</div>
                <div class="book_ratings">
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star"></i>
                  <i class="fas fa-star-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="recent">
        <div class="container">
          <div class="row">
            <h2 class="section_title">
             Latest <span class="purple">Books</span>
            </h2>
            <div class="books">
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-1.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">The 10X Rule</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-2.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Be Obsessed Or Be Average</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-3.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Rich Dad Poor Dad</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-4.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Cashflow Quadrant"</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-5.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">48 Laws of Power</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-6.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">The 5 Second Rule</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-7.jpg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Your Next Five Moves</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
              <div class="book">
                <figure class="book_img--wrapper">
                  <img
                    class="book_img"
                    src="./E-commerce asstes/book-8.jpeg"
                    alt=""
                  />
                </figure>
                <div class="book_title">Mastery</div>
                <div class="book_ratings">
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start"></i>
                  <i class="fas fa-start-half-alt"></i>
                </div>
                <div class="book_price">
                  <span class="book_price--normal">$59.95</span> $14.95
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="explore">
        <div class="container">
            <div class="row row_column">
                <h2>Explore more <span class="purple">Books</span></h2>
                <a href="#features">
                    <button class="btn">Browse books</button>
                </a>
            </div>
        </div>
      </section>
    </main>

    <footer>
        <div class="container">
            <div class="row row_column">
                <a href="#">
                    <figure class="footer_logo">
                        <img src="./E-commerce asstes/Library.svg" class="footer_logo--img" alt="">
                    </figure>
                </a>
                <div class="footer_list">
                    <a href="#" class="footer_link">Home</a>
                    <a class="footer_link no-cursor">About</a>
                    <a href="#features" class="footer_link">Books</a>
                    <a class="footer_link no-cursor">Contact</a>
                </div>
                <div class="footer_copyright">Copyright &copy; 2025 Library</div>
            </div>
        </div>
    </footer>
  </body>
</html>
