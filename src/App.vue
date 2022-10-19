<template>
  <div id="app">
    <header class="header">
      <div class="cont">
        <div class="top-header">
          <div class="logo">
            <a href="#">
              <img src="./img/log.svg" alt="">
            </a>
          </div>
          <nav class="menu">
            <ul class="menu__item">
              <li class="menu__list">
                <a href="" class="menu__link">
                  Какие плюсы?
                </a>
              </li>
              <li class="menu__list">
                <a href="" class="menu__link">
                  Что потребуется от тебя
                </a>
              </li>
              <li class="menu__list">
                <a href="" class="menu__link">
                  Наша миссия
                </a>
              </li>
              <li class="menu__list">
                <a href="" class="menu__link">
                  Присоединиться 
                </a>
              </li>
            </ul>
          </nav>
          <div class="gambuger">
            <input type="checkbox" id="active">
            <label for="active" class="menu-btn"><span></span></label>
            <label for="active" class="close"></label>
            <div class="wrapper">
              <ul>
                <li><a href="#">Какие плюсы?</a></li>
                <li><a href="#">Что потребуется от тебя</a></li>
                <li><a href="#">Наша миссия</a></li>
                <li><a href="#">Присоединиться</a></li>
            </ul>
          </div>
        </div>
        </div>
        <div class="bottom-header">
          <div class="bottom-header__left-block">
            <h1>Стань нашим 
  респондентом</h1>
            <p>Мы хотим услышать твое мнение, опыт 
  и боли общения с цифровыми продуктами  Beeline.</p>
            <div class="link">
              <a href="" class="link">Я готов!</a>
            </div>
          </div>
          <div class="fon">
            <img src="./img/fon.svg" alt="">
          </div>
        </div>
    </div>
    </header>
    <main>
      <div class="cont">
        <div class="first-main">
          <h2>Кто такой респондент?</h2>
          <p>
            Респондент - человек, принимающий участие в опросе, интервью или тестировании дизайна. Мы используем твои ответы в проектировании новых продуктов, чтобы сделать их понятнее, удобнее и приятнее для пользователей.
          </p>
        </div>
        <div class="two-main">
          <h2>Какие плюсы?</h2>
          <div class="banner">
            <div class="first__banner">
             <img src="./img/img1.svg" alt="">
              <h3>Будь первым</h3>
              <p>Ты первым увидишь наши новые продукты и поучаствуешь в их разработке </p>
            </div>
            <div class="second__banner">
                <img src="./img/img2.svg" alt="">
              <h3>Поделись опытом</h3>
              <p>Будем рады узнать о твоем опыте использования наших продуктов </p>
            </div>
            <div class="third__banner">
                <img src="./img/img3.svg" alt="">
              <h3>Получи уникальную ачивку</h3>
              <p>Блестящая, свеженькая и такая уникальная ачивка в приложении “Мой Билайн”</p>
            </div>
          </div>
        </div>
        <div class="third-main">
          <h2>Как принять участие?</h2>
          <div class="top">
            <div class="block">
              <div class="block__one blue">1</div>
              <p class="block__two">
                <a href="">Оставь <span>заявку</span></a>  
              </p>
              <p class="blcok__third">Заполни форму максимально честно, выбери продукты которые хочешь тестировать</p>
            </div>
            <div>
              <div class="block__one pink">2</div>
              <p class="block__two">
                Ожидай приглашения на интервью
              </p>
              <p class="blcok__third">Будь на связи :) Мы напишем тебе заранее и договоримся об удобном времени. Обычно интервью не занимает больше 30-40 минут. </p>
            </div>
          </div>
          <div class="bottom">
            <div>
              <div class="block__one green">3</div>
              <p class="block__two">
                Позаботься об окружении
              </p>
              <p class="blcok__third">Выбери спокойное, тихое место с хорошим интернетом. Обязательно приноси с собой хорошее настроение😉</p>
            </div>
            <div>
              <div class="block__one yellow">4</div>
              <p class="block__two">
                Получи клевую ачивку
              </p>
              <p class="blcok__third">После первого интервью, в приложении
Мой Билайн тебе откроется новая ачивка
«Яркий пиздюк». Спасибо, что ты с нами!
</p>
            </div>
          </div>
        </div>
      </div>
    </main>
    <footer class="footer">
      <div class="cont">
        <div class="flex">
          <div >
            <img src="./img/img4.svg" alt="" class="img">
          </div>
          <div class="footer__two">
            <h2>Наша миссия</h2>
            <p>Тебя тоже раздражает, когда ты пользуешься приложением или сайтом и непонятно куда нажать? Когда попадаешь на пустой экран после ввода данных?</p>
            <p>Нам тоже это не нравится!</p>
            <p>Мы хотим улучшать наши продукты, делать их проще и удобнее для пользователя. Присоединяйся, без тебя нам не обойтись!</p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
* {
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: Arial, Helvetica, sans-serif;
}
#app {
  position: relative;
}
.header {
  padding-top: 32px;
  padding-bottom:36px;
  background-color:#F1F1F4;
}

.cont {
  max-width:1200px;
  margin:0 auto;
  padding: 0 36px;
}

.top-header {
  display: flex;
  justify-content: space-between;
}

.logo, .img {
  max-width: 100%;
}

@media(max-width:865px) {
  .menu {
    display: none;
  }
}

.menu__item {
  display: flex;
  list-style: none;
}

.menu__link {
  display: block;
  margin-right: 36px;
  text-decoration: none;
  color: #10083F;
  font-weight: bold;
  font-size: 16px;
  line-height: 22px;
}

.bottom-header {
  display: flex;
  padding-top: 70px;
  justify-content: space-between;
}

@media (max-width:768px) {
  .bottom-header {
    display: block;
  }
  .bottom-header__left-block {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}

.bottom-header__left-block {
  margin-bottom: 50px;
}

h1 {
  font-weight: 700;
  font-size: 40px;
  line-height: 48px;
  color: #10083F;
  margin-bottom: 24px;
  max-width: 300px;
}

@media (max-width:765px) {
  h1 {
    font-size: 30px;
    line-height: 36px;
  }
}

.bottom-header p {
  font-size: 18px;
  line-height: 24px;
  color: #504D64;
  margin-bottom: 24px;
  max-width: 340px;
}

@media (max-width:765px) {
  .bottom-header p {
    font-size: 18px;
    line-height: 24px;
  }
}

.fon img {
    max-width:100% !important;
    height:auto;
    display:block;
}

.link {
  display: block;
  padding-top:8px;
  padding-bottom: 8px;
  padding-left: 15px;
  padding-right: 15px;
  color: #10083F;
  text-decoration: none;
  background: #FFE14D;
  border-radius: 12px;
  width: fit-content;
}

.gambuger {
  display: none;
}

@media (max-width:865px) {
    .gambuger {
      display: block;
    }
}

.wrapper{
  position: fixed;
  top: 0;
  /*left: -100%;*/
  right: -100%;
  height: 100%;
  width: 100%;
  background: #fff;
  /*background: linear-gradient(90deg, #f92c78, #4114a1);*/
  /* background: linear-gradient(375deg, #1cc7d0, #2ede98); */
 /* background: linear-gradient(-45deg, #e3eefe 0%, #efddfb 100%);*/
  transition: all 0.6s ease-in-out;
}
#active:checked ~ .wrapper{
  /*left: 0;*/
  right:0;
}
.menu-btn{
  position: absolute;
  z-index: 2;
  right: 20px;
  /*left: 20px; */
  top: 20px;
  height: 50px;
  width: 50px;
  text-align: center;
  line-height: 50px;
  border-radius: 50%;
  font-size: 20px;
  cursor: pointer;
  /*color: #fff;*/
  /*background: linear-gradient(90deg, #f92c78, #4114a1);*/
  /* background: linear-gradient(375deg, #1cc7d0, #2ede98); */
 /* background: linear-gradient(-45deg, #e3eefe 0%, #efddfb 100%); */
  transition: all 0.3s ease-in-out;
}
.menu-btn span,
.menu-btn:before,
.menu-btn:after{
	content: "";
	position: absolute;
	top: calc(50% - 1px);
	left: 30%;
	width: 40%;
	border-bottom: 2px solid #000;
	transition: transform .6s cubic-bezier(0.215, 0.61, 0.355, 1);
}
.menu-btn:before{
  transform: translateY(-8px);
}
.menu-btn:after{
  transform: translateY(8px);
}

.close {
	z-index: 1;
	width: 100%;
	height: 100%;
	pointer-events: none;
	transition: background .6s;
}

/* closing animation */
#active:checked + .menu-btn span {
	transform: scaleX(0);
}
#active:checked + .menu-btn:before {
	transform: rotate(45deg);
  border-color: #202020;
}
#active:checked + .menu-btn:after {
	transform: rotate(-45deg);
  border-color: #202020;
}
.wrapper ul{
  position: absolute;
  top: 60%;
  left:60%;
  height: 90%;
  transform: translate(-50%, -50%);
  list-style: none;
  text-align: center;
}

@media(max-width:630px) {
  .wrapper ul {
    left:70%
  }
}
.wrapper ul li{
  height: 10%;
  margin: 15px 0;
}
.wrapper ul li a{
  text-decoration: none;
  font-size: 24px;
  font-weight: 500;
  color: #10083F;
  border-radius: 50px;
  line-height: 32px;  
  display: block;
  opacity: 0;
  transition: all 0.3s ease;
  transition: transform .6s cubic-bezier(0.215, 0.61, 0.355, 1);
}

.wrapper ul li a:after{
  position: absolute;
  content: "";
  background: #fff;
   /*background: linear-gradient(#14ffe9, #ffeb3b, #ff00e0);*/
  /*background: linear-gradient(375deg, #1cc7d0, #2ede98);*/
  width: 100%;
  height: 100%;
  left: 0;
  top: 0;
  border-radius: 50px;
  transform: scaleY(0);
  z-index: -1;
  transition: transform 0.3s ease;
}
.wrapper ul li a:hover:after{
  transform: scaleY(1);
}
.wrapper ul li a:hover{
  color: #1a73e8;
}
input[type="checkbox"]{
  display: none;
}
.content{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: -1;
  text-align: center;
  width: 100%;
  color: #202020;
}
.content .title{
  font-size: 40px;
  font-weight: 700;
}
.content p{
  font-size: 35px;
  font-weight: 600;
}

#active:checked ~ .wrapper ul li a{
  opacity: 1;
}
.wrapper ul li a{
  transition: opacity 1.2s, transform 1.2s cubic-bezier(0.215, 0.61, 0.355, 1);
  transform: translateX(100px);
}
#active:checked ~ .wrapper ul li a{
	transform: none;
	transition-timing-function: ease, cubic-bezier(.1,1.3,.3,1); /* easeOutBackを緩めた感じ */
   transition-delay: .6s;
  transform: translateX(-100px);
}

.first-main {
  padding-top:110px;
  text-align: center;
  padding-bottom: 110px;
}

@media (max-width:765px) {
  .first-main {
    padding-top:64px;
    padding-bottom: 64px;
  }
}

.first-main h2 {
  font-weight: 700;
  font-size: 40px;
  line-height: 48px;
  color: #10083F;
  margin-bottom:36px;
}

@media (max-width:765px) {
  .first-main h2 {
    font-size: 30px;
    line-height: 36px;
  }
}

.first-main p {
  font-size: 18px;
  line-height: 24px;
  color: #504D64;
  max-width: 642px;
  margin: 0 auto;
}

.two-main h2 {
  font-size: 40px;
  line-height: 48px;
}

@media(max-width:765px) {
  .two-main h2 {
    font-size: 30px;
    line-height: 36px;
  }
}

.banner {
  padding-top: 40px;
  display: flex;
  justify-content: space-around;
  gap:28px;
}

@media (max-width:950px) {
    .banner {
      flex-direction: column;
      justify-content: space-between;
    }

}

.banner div {
  text-align: center;
  padding: 100px 36px 85px 36px;
  min-width:293px;
  cursor: pointer;
}


.banner div p {
  max-width: 290px;
  font-size: 0;
  transition: 0.5s;
  margin: 0 auto;
}

.banner div:hover p{
  transition: 0.5s;
  font-size: 18px;
  line-height: 24px;
  color: #78735E;
}


.third__banner:hover p{
  color: #FFFFFF !important;
}

@media(max-width:950px) {
  .banner div p {
    font-size: 18px;
    line-height: 24px;
  }
}

.banner h3 {
  font-size: 20px;
  line-height: 26px;
  margin-bottom: 12px;
}

.first__banner {
  background: #FFF6CC;
  border-radius: 16px;
}

.second__banner {
  background: #EAF4FF;
  border-radius: 16px;
}

.third__banner {
  background: #000000;
  border-radius: 16px;
  color:white;
}

.third-main {
  padding-top:80px;
  max-width: 958px;
}


.third-main h2 {
  margin-bottom: 30px;
}

.top {
  margin-bottom: 50px;
}

.top, .bottom {
  display: flex;
  justify-content: space-between;
}

@media(max-width:865px) {
  .top, .bottom {
    align-items: center;
    flex-direction: column;
    gap:50px
  }
}

.block__one {
  padding:18px 22px;
  font-weight: 700;
  font-size: 36px;
  line-height: 26px;
  margin-bottom: 24px;
  width: fit-content;
}

.block__two {
  font-size: 20px;
  line-height: 26px;
  margin-bottom: 12px;
}

.block__two a {
  color:black;
  text-decoration: none;
}

.block__two a span {
  color:#0183D4 !important;
  text-decoration: underline;
}

.blcok__third {
  font-size: 18px;
  line-height: 24px;
  color: #858295;
  max-width: 400px;
}

.blue {
  background: #EAF4FF;
  border-radius: 16px;
  color: #0183D4;
}

.pink {
  color: #9E66FF;
  background: #F3ECFF;
  border-radius: 16px;
}

.green {
  background: #DFF7D9;
  border-radius: 16px;
  color: #61CA45;
}

.yellow {
  background: #FFF7E2;
  border-radius: 16px;
  color: #FFBD12;
}

.footer {
  padding-top: 120px;
}

.footer h2 {
  font-weight: 700;
  font-size: 30px;
  line-height: 36px;
  color: #10083F;
}

.footer p {
  max-width: 400px;
  font-size: 18px;
  line-height: 24px;
  color: #504D64;
}

.flex {
  display: flex;
  row-gap: 50px;
  flex-wrap: wrap;
  justify-content: space-around;
}
@media (max-width:1100px) {
  .flex {
    flex-direction: column-reverse;
    align-items: center;
  }
}

.footer__two {
  display: flex;
  flex-direction: column;
  gap:40px;
}
</style>

<script>

</script>