<template>
  <html lang="en">
    <div class="container-nobackground">
      <div class="fixed-part">
        <nav>
          <div class="top">
            <div class="top-left">г. Ростов-на-Дону</div>
            <div class="top-right">
              <div class="buttom-top-right">Вакансии</div>
              <div class="buttom-top-right">Доставка</div>
              <div class="buttom-top-right">FAQ</div>
              <div class="buttom-top-right">Отзывы о магазине</div>
              <div class="buttom-top-right">Цены</div>
              <div class="buttom-top-right">Оплата</div>
              <div class="buttom-top-right">Контакты</div>
            </div>
          </div>
        </nav>
        <div class="header-menu">
          <div class="header">
            <div class="border-header">
              <div class="sections">
                <a href="main.html"
                  ><div class="sections-hover">Главная {{ name }}</div></a
                >
                <a href="catalog.html"
                  ><div class="sections-hover">Коталог товаров</div>
                </a>
                <a href="info.html"><div class="sections-hover">О нас</div></a>
                <a href="toppings.html"
                  ><div class="sections-hover">Начинки</div></a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="main-top">
        <div class="main-logo">
          <a href="main.html"
            ><img
              class="main-pic"
              :src="require('@/assets/images/morocco.png')"
            />
            /></a
          >
          <img src="" />
        </div>
        <div class="main-centr">
          <div class="phone-number">
            <div class="main-number">+7 (988) 258-98-11</div>
            <div class="call-order">Заказать звонок</div>
          </div>
          <div class="main-search-line">
            <input type="text" placeholder="Поиск" class="main-imput-line" />
          </div>
        </div>
        <a class="basket-color" href="ordering.html">
          <div class="main-top-right">
            <img class="main-right-pic" src="images/main/korzina_cool.png" />
            <div class="basket">Корзина</div>
          </div>
        </a>
      </div>
    </div>
    <div class="container-main">
      <div></div>
      <div class="field-1">
        <div class="container-f1">
          <div class="f1-card">
            <div class="f1-icon"><i class="fab fa-pagelines fa-6x"></i></div>
            <div class="f1-text">Экологически чистые продукты</div>
          </div>
          <div class="f1-card">
            <div class="f1-icon"><i class="fas fa-ruble-sign fa-6x"></i></div>
            <div class="f1-text">Лояльные цены, удобная система оплаты</div>
          </div>
          <div class="f1-card">
            <div class="f1-icon"><i class="fas fa-dolly fa-6x"></i></div>
            <div class="f1-text">Надёжные поставщики сырья и упаковки</div>
          </div>
          <div class="f1-card">
            <div class="f1-icon"><i class="fas fa-award fa-6x"></i></div>
            <div class="f1-text">
              Контроль качества на всех этапах производства
            </div>
          </div>
        </div>
      </div>
      <div class="field-2">
        <img class="img-field-2" src="images/main/s3.jpg" alt="" />
      </div>
      <div class="field-3">
        <div class="container-f3">
          <div class="f3text-con">
            <div class="heading-f3text-con">
              ИП «Лебортиани» — производитель и поставщик тортов и кондитерских
              изделий
            </div>
            <div class="body-f3text-con">
              Сладкие мучные кондитерские изделия прочно вошли в ассортимент
              большинства магазинов и торговых сетей. При огромном выборе
              производителей и оптовых поставщиков кондитерских изделий,
              особенно важным становится выбор компаний, продукция которых
              пользуется спросом у покупателей.
            </div>
            <div class="miniheading-f3">
              Продажа кондитерки оптом от производителя
            </div>
            <div class="body-f3text-con">
              Ростовская компания ИП «Лебортиани» более 5 лет поставляет на
              российский рынок продукцию собственного производства. Мы работаем
              с ведущими поставщиками сырья и стремимся обеспечить клиентам
              возможность широкого выбора по-настоящему качественных
              кондитерских изделий. В нашем каталоге более 100 различных видов
              кексов, печенья и других сладких мучных изделий. Благодаря
              лояльным ценам, удобной системе оплаты, контролю качества
              производства и расширению мощностей и ассортимента у наших
              клиентов всегда есть выгодная возможность заказать и купить
              высококачественную кондитерку оптом напрямую от надежного
              производителя!
            </div>
          </div>
          <a href="info.html">
            <div class="main-button">Подробнее</div>
          </a>
        </div>
      </div>
      <footer>
        <img class="povarimg" src="images/main/povar.png" alt="" />
        <div class="foot-form">
          <!-- <img class="povarimg" src="images/main/povar.png" alt=""> -->
          <div class="ff-con">
            <div class="header-ff">У Вас есть вопросы?</div>
            <div class="text-ff">
              Отправьте нам заявку и наш специалист свяжется с Вами!
            </div>
            <div class="forma-ff">
              <span>
                <input
                  type="email"
                  placeholder="Ваше имя"
                  class="main-imput-mail"
                />
                <input
                  type="email"
                  placeholder="Номер телефона"
                  class="main-imput-mail"
                />
              </span>
            </div>
          </div>
        </div>
        <div class="pod-povar"></div>
      </footer>
    </div>
  </html>
</template>

<script lang="js" src="./index.js" />
<style lang="css" src="./index.css" scoped />
