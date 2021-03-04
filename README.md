# goit-markup-hw-08

<!-- <!DOCTYPE html>  
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>WebStudio</title>
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.0.0/modern-normalize.min.css"
    />
    <link rel="stylesheet" href="./css/main.min.css" />
  </head>

  <body>
    <!--====== ШАПКА ======-->

    <header class="page-header">
      <div class="container">
        <nav class="main-nav">
          <a href="./index.html" class="logo header-logo"
            ><span class="web-logo">Web</span>Studio</a
          >
          <button
            type="button"
            class="mobile-menu"
            aria-expanded="false"
            aria-controls="menu-container"
            data-menu-button
          >
            <svg
              class="mobile-menu-icon"
              aria-label="Переключатель мобильного меню"
            >
              <use
                class="burger-icon"
                href="./images/sprite.svg#icon-burger"
              ></use>
              <use
                class="burger-close-icon"
                href="./images/sprite.svg#icon-burger-close"
              ></use>
            </svg>
          </button>
          <div class="menu-container" id="menu-container" data-menu>
            <ul class="menu-container-list list">
              <li class="menu-container-item item">
                <a
                  href="./index.html"
                  class="menu-container-link link mobile-current"
                  >Студия</a
                >
              </li>
              <li class="menu-container-item item">
                <a href="./portfolio.html" class="menu-container-link link"
                  >Портфолио</a
                >
              </li>
              <li class="menu-container-item item">
                <a href="" class="menu-container-link link">Контакты</a>
              </li>
            </ul>
            <ul class="mobile-contacts-list list">
              <li class="mobile-contacts-item item">
                <a href="mailto:info@devstudio.com" class="contacts-link link">
                  <svg class="contact-icon envelope">
                    <use href="./images/sprite.svg#envelope"></use>
                  </svg>
                  info@devstudio.com</a
                >
              </li>
              <li class="mobile-contacts-item item">
                <a href="tel:+380961111111" class="contacts-link link">
                  <svg class="contact-icon smartphone">
                    <use href="./images/sprite.svg#smartphone"></use>
                  </svg>
                  +38 096 111 11 11</a
                >
              </li>
            </ul>
          </div>
          <ul class="site-nav list">
            <li class="item">
              <a href="./index.html" class="link current">Студия</a>
            </li>
            <li class="item">
              <a href="./portfolio.html" class="link">Портфолио</a>
            </li>
            <li class="item">
              <a href="" class="link">Контакты</a>
            </li>
          </ul>
        </nav>
        <ul class="contacts list">
          <li class="item">
            <a href="mailto:info@devstudio.com" class="contacts-link">
              <svg class="contact-icon envelope">
                <use href="./images/sprite.svg#envelope"></use>
              </svg>
              info@devstudio.com</a
            >
          </li>
          <li class="item">
            <a href="tel:+380961111111" class="contacts-link">
              <svg class="contact-icon smartphone">
                <use href="./images/sprite.svg#smartphone"></use>
              </svg>
              +38 096 111 11 11</a
            >
          </li>
        </ul>
      </div>
    </header>

    <main>
      <!--====== ГЕРОЙ ======-->

      <section class="hero">
        <div class="container">
          <h1 class="hero-title title">
            Эффективные решения для вашего бизнеса
          </h1>
          <button type="button" class="button" data-modal-open>
            Заказать услугу
          </button>
        </div>
      </section>

      <!--====== ХАРАКТЕРИСТИКИ ======-->

      <section class="section features-section">
        <div class="container">
          <h2 class="title visually-hidden">Характеристики</h2>
          <ul class="list features-list">
            <li class="item">
              <div class="thumb-features">
                <svg class="features-decoration">
                  <use href="./images/sprite.svg#antenna"></use>
                </svg>
              </div>
              <h3 class="title sub-title features-title">Внимание к деталям</h3>
              <p class="features-text">
                Идейные соображения, а также начало повседневной работы по
                формированию позиции.
              </p>
            </li>
            <li class="item">
              <div class="thumb-features">
                <svg class="features-decoration">
                  <use href="./images/sprite.svg#clock"></use>
                </svg>
              </div>
              <h3 class="title sub-title features-title">Пунктуальность</h3>
              <p class="features-text">
                Задача организации, в особенности же рамки и место обучения
                кадров влечет за собой.
              </p>
            </li>
            <li class="item">
              <div class="thumb-features">
                <svg class="features-decoration">
                  <use href="./images/sprite.svg#diagram"></use>
                </svg>
              </div>
              <h3 class="title sub-title features-title">Планирование</h3>
              <p class="features-text">
                Равным образом консультация с широким активом в значительной
                степени обуславливает.
              </p>
            </li>
            <li class="item">
              <div class="thumb-features">
                <svg class="features-decoration">
                  <use href="./images/sprite.svg#astronaut"></use>
                </svg>
              </div>
              <h3 class="title sub-title features-title">
                Современные технологии
              </h3>
              <p class="features-text">
                Значимость этих проблем настолько очевидна, что реализация
                плановых заданий.
              </p>
            </li>
          </ul>
        </div>
      </section>

      <!--====== ЧЕМ МЫ ЗАНИМАЕМСЯ ======-->

      <section class="section services-section">
        <div class="container">
          <h2 class="title services-title">Чем мы занимаемся</h2>
          <ul class="list services-list">
            <li class="item">
              <picture>
                <source
                  srcset="
                    ./images/services/desctop.webp    1x,
                    ./images/services/desctop@2x.webp 2x
                  "
                  media="(min-width: 1200px)" type="image/webp"
                />
                <source
                  srcset="
                    ./images/services/desctop.jpg    1x,
                    ./images/services/desctop@2x.jpg 2x
                  "
                  media="(min-width: 1200px)"
                />
                <img
                  src="./images/services/desctop.jpg"
                  alt="Человек печатает на клавиатуре"
                />
              </picture>
              <p class="text">Десктопные приложения</p>
            </li>
            <li class="item">
              <picture>
                <source
                  srcset="
                    ./images/services/mobile.webp    1x,
                    ./images/services/mobile@2x.webp 2x
                  "
                  media="(min-width: 1200px)" type="image/webp"
                />
                <source
                  srcset="
                    ./images/services/mobile.jpg    1x,
                    ./images/services/mobile@2x.jpg 2x
                  "
                  media="(min-width: 1200px)"
                />
                <img
                  src="./images/services/mobile.jpg"
                  alt="Человек с телефоном в руках"
                />
              </picture>
              <p class="text">Мобильные приложения</p>
            </li>
            <li class="item">
              <picture>
                <source
                  srcset="
                    ./images/services/tablet.webp    1x,
                    ./images/services/tablet@2x.webp 2x
                  "
                  media="(min-width: 1200px)" type="image/webp"
                />
                <source
                  srcset="
                    ./images/services/tablet.jpg    1x,
                    ./images/services/tablet@2x.jpg 2x
                  "
                  media="(min-width: 1200px)"
                />
                <img
                  src="./images/services/tablet.jpg"
                  alt="Человек с планшетом в руках"
                />
              </picture>
              <p class="text">Дизайнерские решения</p>
            </li>
          </ul>
        </div>
      </section>

      <!--====== НАША КОМАНДА ======-->

      <section class="team-section section">
        <div class="container">
          <h2 class="title team-title">Наша команда</h2>
          <ul class="list team-list">
            <li class="item team-list-item">
                <picture>
                    <source 
                    srcset="./images/team/desctop-pro-des.webp 1x, ./images/team/desctop-pro-des@2x.webp 2x"
                    media="(min-width: 1200px)" type="image/webp">
                    <source 
                    srcset="./images/team/desctop-pro-des.jpg 1x, ./images/team/desctop-pro-des@2x.jpg 2x"
                    media="(min-width: 1200px)">

                    <source 
                    srcset="./images/team/tablet-pro-des.webp 1x, ./images/team/tablet-pro-des@2x.webp 2x" 
                    media="(min-width: 768px)" type="image/webp">
                    <source 
                    srcset="./images/team/tablet-pro-des.jpg 1x, ./images/team/tablet-pro-des@2x.jpg 2x" 
                    media="(min-width: 768px)">

                    <source 
                    srcset="./images/team/mobile-pro-des.webp 1x, ./images/team/mobile-pro-des@2x.webp 2x"
                    media="(min-width: 480px)" type="image/webp">
                    <source 
                    srcset="./images/team/mobile-pro-des.jpg 1x, ./images/team/mobile-pro-des@2x.jpg 2x" 
                    media="(min-width: 480px)">

                    <img 
                    class="img-team-section" 
                    src="./images/team/mobile-pro-des.jpg" 
                    alt="Мужчина в очках и в бордовой рубашке" />
                </picture>
              <div class="team-subsection">
                <h3 class="title sub-title team-subtitle">Игорь Демьяненко</h3>
                <p lang="en" class="team-text">Product Designer</p>
                <ul class="list social-list">
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#instagram"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#twitter"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#facebook"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#linkedin"></use>
                      </svg>
                    </a>
                  </li>
                </ul>
              </div>
            </li>
            <li class="item team-list-item">
                <picture>
                    <source 
                    srcset="./images/team/desctop-dev.webp 1x, ./images/team/desctop-dev@2x.webp 2x" 
                    media="(min-width: 1200px)" 
                    type="image/webp">
                    <source 
                    srcset="./images/team/desctop-dev.jpg 1x, ./images/team/desctop-dev@2x.jpg 2x" 
                    media="(min-width: 1200px)">

                    <source 
                    srcset="./images/team/tablet-dev.webp 1x, ./images/team/tablet-dev@2x.webp 2x" 
                    media="(min-width: 768px)" 
                    type="image/webp">
                    <source 
                    srcset="./images/team/tablet-dev.jpg 1x, ./images/team/tablet-dev@2x.jpg 2x" 
                    media="(min-width: 768px)">

                    <source 
                    srcset="./images/team/mobile-dev.webp 1x, ./images/team/mobile-dev@2x.webp 2x" 
                    media="(min-width: 480px)"
                     type="image/webp">
                    <source 
                    srcset="./images/team/mobile-dev.jpg 1x, ./images/team/mobile-dev@2x.jpg 2x" 
                    media="(min-width: 480px)">

                    <img 
                    class="img-team-section" 
                    src="./images/team/mobile-dev.jpg" 
                    alt="Девушка в очках и в черном пиджаке" />
                </picture>
                <div class="team-subsection">
                <h3 class="title sub-title team-subtitle">Ольга Репина</h3>
                <p lang="en" class="team-text">Frontend Developer</p>
                <ul class="list social-list">
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#instagram"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#twitter"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#facebook"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#linkedin"></use>
                      </svg>
                    </a>
                  </li>
                </ul>
              </div>
            </li>
            <li class="item team-list-item">
                <picture>
                    <source 
                    srcset="./images/team/desctop-marketing.webp 1x, ./images/team/desctop-marketing@2x.webp 2x" 
                    media="(min-width: 1200px)"
                    type="image/webp">
                    <source srcset="./images/team/desctop-marketing.jpg 1x, ./images/team/desctop-marketing@2x.jpg 2x" 
                    media="(min-width: 1200px)">

                    <source srcset="./images/team/tablet-marketing.webp 1x, ./images/team/tablet-marketing@2x.webp 2x" 
                    media="(min-width: 768px)"
                    type="image/webp">
                    <source srcset="./images/team/tablet-marketing.jpg 1x, ./images/team/tablet-marketing@2x.jpg 2x" 
                    media="(min-width: 768px)">

                    <source 
                    srcset="./images/team/mobile-marketing.webp 1x, ./images/team/mobile-marketing@2x.webp 2x" 
                    media="(min-width: 480px)"
                    type="image/webp">
                    <source 
                    srcset="./images/team/mobile-marketing.jpg 1x, ./images/team/mobile-marketing@2x.jpg 2x" 
                    media="(min-width: 480px)">
                    <img 
                    class="img-team-section"
                    src="./images/team/mobile-marketing.jpg" 
                    alt="Мужчина в белой рубашке">
                </picture>
              <div class="team-subsection">
                <h3 class="title sub-title team-subtitle">Николай Тарасов</h3>
                <p lang="en" class="teame-text">Marketing</p>
                <ul class="list social-list">
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#instagram"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#twitter"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#facebook"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#linkedin"></use>
                      </svg>
                    </a>
                  </li>
                </ul>
              </div>
            </li>
            <li class="item team-list-item">
                <picture>
                    <source 
                    srcset="./images/team/desctop-ui-des.webp 1x, ./images/team/desctop-ui-des@2x.webp 2x" 
                    media="(min-width: 1200px)" type="image/webp">
                    <source 
                    srcset="./images/team/desctop-ui-des.jpg 1x, ./images/team/desctop-ui-des@2x.jpg 2x" 
                    media="(min-width: 1200px)">

                    <source 
                    srcset="./images/team/tablet-ui-des.webp 1x, ./images/team/tablet-ui-des@2x.webp 2x" 
                    media="(min-width: 768px)" type="image/webp">
                    <source 
                    srcset="./images/team/tablet-ui-des.jpg 1x, ./images/team/tablet-ui-des@2x.jpg 2x" 
                    media="(min-width: 768px)">

                    <source 
                    srcset="./images/team/mobile-ui-des.webp 1x, ./images/team/mobile-ui-des@2x.webp 2x" 
                    media="(min-width: 480px)" type="image/webp">
                    <source 
                    srcset="./images/team/mobile-ui-des.jpg 1x, ./images/team/mobile-ui-des@2x.jpg 2x" 
                    media="(min-width: 480px)">

                    <img 
                    class="img-team-section"
                    src="./images/team/mobile-ui-des.jpg" 
                    alt="Мужчина в очках и в черной футболке" />
                </picture>
              <div class="team-subsection">
                <h3 class="title sub-title team-subtitle">Михаил Ермаков</h3>
                <p lang="en" class="teame-text">UI Designer</p>
                <ul class="list social-list">
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#instagram"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#twitter"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#facebook"></use>
                      </svg>
                    </a>
                  </li>
                  <li class="item social-item">
                    <a class="link social-link team-social-link" href="">
                      <svg class="social-icons">
                        <use href="./images/sprite.svg#linkedin"></use>
                      </svg>
                    </a>
                  </li>
                </ul>
              </div>
            </li>
          </ul>
        </div>
      </section>

      <!-- ====== ПОСТОЯННЫЕ КЛИЕНТЫ -->

      <section class="clients-section section">
            <div class="container">
                <h2 class="title clients-title">Постоянные клиенты</h2>
                <ul class="list clients-list">
                    <li class="item clients-item">
                        <a class="clients-link" href="">
                            <svg class="clients-icon icon-logo-1">
                                <use href="./images/sprite.svg#logo-1"></use>
                            </svg>
                        </a>
                    </li>
                    <li class="item clients-item">
                        <a class="clients-link" href="">
                            <svg class="clients-icon icon-logo-2">
                                <use href="./images/sprite.svg#logo-2"></use>
                            </svg>
                        </a>
                    </li>
                    <li class="item clients-item">
                        <a class="clients-link" href="">
                            <svg class="clients-icon icon-logo-3">
                                <use href="./images/sprite.svg#logo-3"></use>
                            </svg>
                        </a>
                    </li>
                    <li class="item clients-item">
                        <a class="clients-link" href="">
                            <svg class="clients-icon icon-logo-4">
                                <use href="./images/sprite.svg#logo-4"></use>
                            </svg>
                        </a>
                    </li>
                    <li class="item clients-item">
                        <a class="clients-link" href="">
                            <svg class="clients-icon icon-logo-5">
                                <use href="./images/sprite.svg#logo-5"></use>
                            </svg>
                        </a>
                    </li>
                    <li class="item clients-item">
                        <a class="clients-link" href="">
                            <svg class="clients-icon icon-logo-6">
                                <use href="./images/sprite.svg#logo-6"></use>
                            </svg>
                        </a>
                    </li>
                </ul>
            </div>
        </section>
    </main>

    <!--====== ФУТЕР ======-->

    <footer class="footer">
        <div class="container">
            <div>
                <a href="./index.html" class="logo footer-logo"><span class="web-logo">Web</span>Studio</a>
                <address class="footer-address">
                    <p class="footer-text">г. Киев, пр-т Леси Украинки, 26</p>
                    <a href="mailto:info@devstudio.com" class="footer-link link">info@devstudio.com</a>
                    <a href="tel:+380961111111" class="footer-link link">+38 096 111 11 11</a>
                </address>  
            </div>
            <div class="social-item-container">
                <b class="footer-subtitle">Присоединяйтесь</b>
                <ul class="footer-list list">
                    <li class="social-item item">
                        <a class="social-link footer-item-link" href="">
                            <svg class="footer-social-item">
                                <use href="./images/sprite.svg#instagram"></use>
                            </svg>
                        </a>
                    </li>
                    <li class="social-item item">
                        <a class="social-link footer-item-link" href="">
                            <svg class="footer-social-item">
                                <use href="./images/sprite.svg#twitter"></use>
                            </svg>
                        </a>
                    </li>
                    <li class=" social-item item">
                        <a class="social-link footer-item-link" href="">
                            <svg class="footer-social-item">
                                <use href="./images/sprite.svg#facebook"></use>
                            </svg>
                        </a>
                    </li>
                    <li class=" social-item item">
                        <a class="social-link footer-item-link" href="">
                            <svg class="footer-social-item">
                                <use href="./images/sprite.svg#linkedin"></use>
                            </svg>
                        </a>
                    </li>
                </ul>
            </div>
            <div class="footer-modal-wrapper">
                <b class="footer-subtitle">Подпишитесь на рассылку</b>
                <form class="footer-form" action="#">
                    <input class="footer-modal-input" name="user-subscribe" type="email" placeholder="E-mail" required>
                    <button class="button footer-modal-form-btn" type="submit">
                        Подписаться
                        <svg class="footer-modal-icon">
                            <use href="./images/sprite.svg#icon-telegram"></use>
                        </svg>
                    </button>
                </form>
            </div>
        </div>
    </footer>

    <!-- ====== MODAL BTN ====== -->

    <div class="backdrop is-hidden" data-modal>
      <div class="modal-window">
        <button class="modal-close-button" type="button" data-modal-close>
          <svg class="modal-close-svg">
            <use href="./images/sprite.svg#modalclose"></use>
          </svg>
        </button>
        <form action="#" class="modal-form">
          <b class="title modal-form-title">
            Оставьте свои данные, мы вам перезвоним
          </b>
          <label class="modal-form-input-label" for="user-name"> Имя </label>
          <div class="modal-form-input-wrapper">
            <input
              class="modal-form-input"
              type="text"
              name="user-name"
              id="user-name"
              required
            />
            <svg class="modal-form-icon">
              <use href="./images/sprite.svg#icon-modal-name"></use>
            </svg>
          </div>

          <label class="modal-form-input-label" for="user-tel"> Телефон </label>
          <div class="modal-form-input-wrapper">
            <input
              class="modal-form-input"
              type="tel"
              name="user-phone"
              id="user-tel"
              required
            />
            <svg class="modal-form-icon">
              <use href="./images/sprite.svg#icon-modal-phone"></use>
            </svg>
          </div>

          <label class="modal-form-input-label" for="user-mail"> Почта </label>
          <div class="modal-form-input-wrapper">
            <input
              class="modal-form-input"
              type="email"
              name="user-mail"
              id="user-mail"
              required
            />
            <svg class="modal-form-icon">
              <use href="./images/sprite.svg#icon-modal-mail"></use>
            </svg>
          </div>

          <label class="modal-form-input-label" for="user-message">
            Комментарий
          </label>
          <textarea
            class="modal-form-message"
            name="user-message"
            id="user-message"
            placeholder="Введите текст"
          ></textarea>

          <input
            class="visually-hidden modal-form-check-policy"
            value="success"
            name="user-policy"
            type="checkbox"
            id="policy"
            required
          />
          <label class="modal-form-label-policy" for="policy">
            Соглашаюсь с рассылкой и принимаю
            <a class="policy-link" href="">Условия договора</a>
          </label>

          <button class="button" type="submit">Отправить</button>
        </form>
      </div>
    </div>
    <script src="./js/modal.js"></script>
    <script src="./js/menu.js"></script>
  </body>
</html>/
 