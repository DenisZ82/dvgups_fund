<script>
    import coin from '../image/3d_icon_coin.png'
    import moneybox from '../image/3d_icon_moneybox.png'
    import case_ic from '../image/3d_icon_case.png'
    import arrow_up from '../image/3d_icon_rub_and_arrow_up.png'
    import bank from '../image/3d_icon_bank.png'
    // import banner_footer from '../image/banner__footer.jpg'

</script>

<div class="pt-[130px] px-[70px] mx-auto max-w-[1440px]">
    <main class="p-[20px] mx-auto my-0 max-w-[1300px] container__main">
        <section class="fund_form flex items-center justify-between">
            <div class="flex flex-col w-[613px] h-[287] gap-[32px] leading-[1.2]">
                <h1 class="text-[2.5rem] text-teal-800 font-[750]">Фонд целевого капитала ДВГУПС</h1>
                <p class="text-[0.9rem] tracking-wide">Мы привлекаем ресурсы для реализации значимых проектов и программ, направленных на повышение качества образования, развитие научных исследований и улучшение социального благополучия.</p>
                <button class="
                    bg-teal-800 
                    text-white 
                    border-none 
                    w-[215px] h-[56] 
                    text-[1rem] 
                    rounded-[16px] 
                    tracking-wider 
                    cursor-pointer 
                    transition-colors duration-300 
                    hover:bg-green-600 ">
                    Внести свой вклад
                </button>
            </div>
            <div class="fund-banner bg-cover bg-center w-[502px] h-[352px] rounded-[20px]"></div>
        </section>

        <section class="fund_form info__block fund__form">
          <div class="mb-[20px]">
            <div class="flex justify-between items-start mb-[20px] about__header">
              <h2 class="w-[400px] text-[2rem] font-[600] about__fund-title">О Фонде</h2>
              <div class="flex-1 text-[1rem] text-start max-w-[802px] about__promotes">
                <h3 class="text-[1.25rem] font-[600] leading-[1.2]">
                  Фонд способствует развитию университета, направляя ресурсы на важные образовательные и научные проекты
                </h3>
                <p class="tracking-wide">Наш фонд привлекает целевые средства для реализации образовательных, научных и социальных проектов.</p>
                <p class="tracking-wide">Фонд не имеет основной целью своей деятельности извлечение прибыли и не распределяет полученную прибыль учредителем Фонда и лицами, занимающими должности в органах управления Фонда.</p>
              </div>
            </div>

            <div class="grid grid-cols-[repeat(auto-fit,minmax(280px,1fr))] gap-[20px] about__cards">
              <div class="about_info">
                <h3 class="about__info-title">Миссия Фонда</h3>
                <p class="about__info-paragraph">Содействовать устойчивому развитию университета, привлекая ресурсы для реализации значимых проектов и программ, направленных на повышение качества образования, научных исследований и социального благополучия.</p>
              </div>

              <div class="about_info">
                <h3 class="about__info-title">Цель Фонда</h3>
                <ul class="about__info-paragraph">
                  <li class="info-paragraph__li">Формирование и пополнение целевого капитала</li>
                  <li class="info-paragraph__li">Использование целевого капитала</li>
                  <li class="info-paragraph__li">Распределение доходов в пользу ДВГУПС и некоммерческих организаций для его развития</li>
                </ul>
              </div>

              <div class="about_info">
                <h3 class="about__info-title">Задачи Фонда</h3>
                <ul class="about__info-paragraph">
                  <li class="info-paragraph__li">Модернизация материально-технической базы университета</li>
                  <li class="info-paragraph__li">Финансирование инвестиционных и научных проектов студентов и преподавателей</li>
                  <li class="info-paragraph__li">Развитие кадрового потенциала ДВГУПС</li>
                </ul>
              </div>
            </div>
          </div>

          <div class="mt-[40px] how__it__works">
            <h2 class="mb-[20px] text-left text-[2rem] font-[600] how__title">Как это работает?</h2>
            <div class="flex gap-[20px] how__cards-container">
              <div class="how__card">
                <img src={coin} alt="Средства дарителя" class="how__ico" loading="lazy">
                <span class="absolute top-[16px] right-[16px] font-bold text-[#D1D1D1]">1</span>
                <h3>Средства дарителя</h3>
                <p>Фонд формируется из благотворительных пожертвований меценатов и выпускников ДВГУПС</p>
              </div>
              <div class="how__card">
                <img src={moneybox} alt="Фонд целевого капитала ДВГУПС" class="how__ico" loading="lazy">
                <span class="absolute top-[16px] right-[16px] font-bold text-[#D1D1D1]">2</span>
                <h3>Фонд целевого капитала ДВГУПС</h3>
                <p>Фонд формирует целевой капитал из пожертвований и передаёт его УК</p>
              </div>
              <div class="how__card">
                <img src={case_ic} alt="Управляющая компания" class="how__ico" loading="lazy">
                <span class="absolute top-[16px] right-[16px] font-bold text-[#D1D1D1]">3</span>
                <h3 >Управляющая компания</h3>
                <p>Деньги фонда передаются в доверительное управление управляющей компании</p>
              </div>
              <div class="how__card">
                <img src={arrow_up} alt="Получение дохода" class="how__ico" loading="lazy">
                <span class="absolute top-[16px] right-[16px] font-bold text-[#D1D1D1]">4</span>
                <h3>Получение дохода</h3>
                <p>Университет получает доход от управления средствами фонда каждый год</p>
              </div>
              <div class="how__card">
                <img src={bank} alt="Финансирование проектов" class="how__ico" loading="lazy">
                <span class="absolute top-[16px] right-[16px] font-bold text-[#D1D1D1]">5</span>
                <h3>Финансирование проектов</h3>
                <p>Полученные доходы направляются на развитие проектов ДВГУПС</p>
              </div>
            </div>
          </div>

          <div class="grid grid-cols-[1fr_2fr] gap-[20px] items-start bg-white mt-[56px] mb-[40px] rounded-[20px] 
              text-left info__graduates">
            <h2 class="text-[2rem] font-semibold">Выпускники ДВГУПС</h2>
            <div>
              <h3 class="mb-[10px] text-[1.25rem] font-semibold leading-[1.2]">Ассоциация выпускников – важная часть успеха и развития нашего университета</h3>
              <p class="mb-[20px] text-[1rem]">Выпускники играют ключевую роль в поддержке университета, объединяя всех, кто хочет внести свой вклад в его развитие.</p>
              <div class="info__btns">
                <button class="bg-[#0D635A] 
                    text-white 
                    text-[100%] 
                    leading-[1.15] 
                    border-none 
                    rounded-[12px] 
                    px-[20px] py-[10px] mr-[10px] 
                    transition-colors duration-300 
                    hover:bg-[#1F9C60] 
                    cursor-pointer 
                    open-modal-btn">Внести вклад</button>
                <button class="bg-white 
                    text-[100%] 
                    leading-[1.15] 
                    border
                    border-[#0D635A] 
                    rounded-[12px] 
                    px-[20px] py-[10px] mr-[10px] 
                    transition-colors duration-300 
                    hover:bg-[#d9eee6] 
                    cursor-pointer
                details__button" id="detailsButton">Подробнее</button>
              </div>
            </div>
          </div>
        </section>

        <section class="text-left fund_form fund__board fund__form">
          <h2 class="mb-[20px] text-[2rem] font-semibold management__title">Правление Фонда</h2>
          <div class="mb-[30px] board__management">
            <h3 class="text-[#888888] mb-[10px] text-[1.25rem] font-semibold leading-[1.2]">Высший коллегиальный орган управления</h3>
            <div class="management__item">
              <p><strong>Буровцев Владимир Викторович</strong></p>
              <p>Ректор ФГБОУ ВО «ДВГУПС»</p>
            </div>
            <div class="management__item">
              <p><strong>Пляскин Артем Константинович</strong></p>
              <p>Проректор по учебной работе ФГБОУ ВО «ДВГУПС»</p>
            </div>
            <div class="management__item">
              <p><strong>Говорин Александр Анатольевич</strong></p>
              <p>Главный инженер Дальневосточной железной дороги – филиала ОАО «РЖД»</p>
            </div>
          </div>
          <div class="mb-[30px] board__management">
            <h3 class="text-[#888888] mb-[10px] text-[1.25rem] font-semibold leading-[1.2]">Единоличный исполнительный орган управления</h3>
            <div class="management__item">
              <p><strong>Едигарян Аркадий Рудольфович</strong></p>
              <p>Первый проректор ФГБОУ ВО «ДВГУПС», исполнительный директор фонда</p>
            </div>
          </div>
          <div class="mb-[30px] board__management">
            <h3 class="text-[#888888] mb-[10px] text-[1.25rem] font-semibold leading-[1.2]">Попечительский совет</h3>
            <div class="management__item">
              <p><strong>Говорин Александр Анатольевич</strong></p>
              <p>Главный инженер Дальневосточной железной дороги – филиала ОАО «РЖД»</p>
            </div>
            <div class="management__item">
              <p><strong>Агранат Юлия Владимировна</strong></p>
              <p>Проректор по молодежной политике и воспитательной деятельности ФГБОУ ВО «ДВГУПС»</p>
            </div>
            <div class="management__item">
              <p><strong>Смирнова Елена Викторовна</strong></p>
              <p>Начальник Финансово-экономического управления ФГБОУ ВО «ДВГУПС»</p>
            </div>
          </div>
        </section>

        <section class="bg-[#F7F7F7] mb-[40px]">
          <div class="mx-auto my-[0px] max-w-[1300px] flex flex-row gap-[24px]">
           <div class="contacts__blocks fund_form w-[100%] p-[40px]">
            <h2 class="mb-[20px] text-[2rem] font-semibold">Контакты</h2>
            <address><b>Адрес фонда:</b> 680021, г. Хабаровск, ул. Серышева, 47, ауд. 209</address>
            <b>Телефон:</b> <a class="footer__address-link" href="tel:+74212407775">+7 (4212) 40-77-75</a>
            <br><b>Email:</b> <a class="footer__address-link" href="mailto:fond@festu.khv.ru">fond@festu.khv.ru</a>
            <h4 class="font-bold tracking-wide">Реквизиты Фонда</h4>
            <p>
              ОГРН 1232700019958<br>
              ИНН 2700023102<br>
              КПП 270001001
            </p>
           </div>

           <div class="contacts__blocks fund_form fund__docs w-[100%] p-[40px]">
            <h2 class="mb-[20px] text-[2rem] font-semibold">Документы</h2>
            <p><a href="/">Устав фонда</a></p>
            <p><a href="/">Лист записи фонда</a></p>
            <p><a href="/">Свидетельство о постановке на налог.учет</a></p>
            <p><a href="/">Свидетельство Фонда Целевого Капитала</a></p>
            <p><a href="/">Документы образовательной организации</a></p>
           </div>
          </div>
        </section>

        <section class="banner__foot fund__form 
            bg-no-repeat bg-center bg-cover
            flex justify-between
            px-14 py-8
            rounded-[20px]
            mb-10
            text-white
            min-h-[394px]">
          <div class="flex flex-col max-w-[61%] gap-[20px] leading-[1.3] banner__text-block">
            <h2 class="text-[2rem] font-semibold">Станьте частью нашей инициативы – вместе мы сможем внести значимый вклад в будущее образования и науки!</h2>
            <p class="tracking-wider">Каждый вклад, независимо от его размера, помогает нам создавать новые возможности для студентов и преподавателей.</p>
            <button class="banner__btn open-modal-btn
                w-[215px] h-[56px]
                bg-white
                text-[#0D635A]
                border-none
                rounded-[12px]
                text-[1rem]
                cursor-pointer
                transition-colors duration-300
                hover:bg-[#ebf3f0]
            ">Внести свой вклад</button>
          </div>
          <div class="flex flex-col items-end banner__qr-block">
            <div class="w-[250px] h-[250px] bg-white bg-cover bg-center rounded-[24px] mb-[20px] qr-image">
              <!--<img src="/images/main/files/FUND/QR_IMG_02.jpg" class="qr-image_mobile">-->
            </div>
          <div class="w-[250px] text-left qr-text">
              <h3 class="text-[1.25rem] font-semibold leading-[1.2]">Взнос по QR</h3>
              <p class="text-[#D1D1D1] text-[1rem] tracking-wide">Сканируйте приложением банка ВТБ, чтобы внести вклад</p>
            </div>
          </div>
        </section>
  </main>

</div>


<style lang="postcss">
    @reference "tailwindcss";

    .fund_form {
        @apply bg-white p-[40px] mb-[40px] rounded-[20px];
    }

    /* .about__info {
        @apply flex flex-col bg-[#097C6E] p-[15px] rounded-[20px] text-[1rem] min-h-[230px] 
            transition-colors duration-300 
            hover:bg-[#1F9C60] 
            hover:bg-gradient-to-tr from-[#1F9C60] from-55% to-[#097C6E];
    } */

    .about_info {
        @apply flex flex-col bg-[#097C6E] p-[15px] rounded-[20px] text-[1rem] min-h-[230px] 
              transition-colors duration-300 hover:bg-[#1F9C60];
    }

    .about__info-title {
        @apply text-white mb-[20px] text-[1.25rem] font-[600] leading-[1.2];
    }

    .about__info-paragraph {
        @apply text-white text-[0.9rem] tracking-wider my-[0.2em] mx-[0px] leading-[1.2];
    }

    .info-paragraph__li {
        @apply relative pl-[12px] before:absolute before:content-['\2022'] 
            before:left-0 before:top-0 before:text-base before:leading-none before:inline-block;
    }

    .how__card {
        @apply w-[236px] h-[280px] bg-[#F4F4F4] rounded-[20px] relative p-[16px] 
            flex flex-col transition-all duration-300;
    }

    .how__card h3 {
        @apply text-[1.1rem] mt-[100px] mb-[5px] leading-[1] font-[600];
    }

    .how__card p {
        @apply text-[0.8rem] m-[0px] mb-[5px] leading-[1.2] text-[#888888] font-medium
            transition-colors duration-300 flex-1;
    }

    .how__card:hover p {
        @apply font-medium text-[#181818];
    }

    .how__ico {
        @apply absolute top-[16px] left-[16px] mb-[16px] transition-transform duration-300;
    }

    .how__card:hover .how__ico {
        @apply scale-105;
    }

    .fund-banner {
        background-image: url('../image/banner__cover.jpg');
    }

    .management__item {
        @apply grid grid-cols-[1fr_1fr] items-center gap-x-[30px] border-b border-[#888888] 
            px-[0px] py-[10px] mb-[5px];
    }

    .contacts__blocks address, .contacts__blocks p, .contacts__blocks a {
        @apply not-italic text-[1rem] mb-[10px];
    }

    .fund__docs a {
        @apply underline text-[#0D635A] hover:text-[#1F9C60] transition-colors duration-300;
    }

    .footer__address-link {
        @apply no-underline text-[#181818] text-nowrap;
    }

    .banner__foot {
        background-image: url('../image/banner__footer.jpg');
    }
</style>