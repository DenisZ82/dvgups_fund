<script>
    import logo from '../image/logo.svg'
    
</script>

<header class="flex flex-row items-center justify-center z-999 absolute inset-x-0 top-0">
    <div class="flex items-center justify-center gap-8 mx-auto px-[70px] py-[24px] max-w-[1440px]">
        <img src={logo} alt='logo_DVGUPS' class="w-[392px] h-[36px]"/>        
        <div class="header-nav">
            <ul class="relative flex items-center flex-wrap pr-[41px]
            after:content-[''] after:absolute after:top-[50%] after:transform after:-translate-y-1/2 
            after:right-[20px] after:w-[1px] after:h-[16px]  after:bg-white">
                <div>
                    <ul class="flex justify-center items-center flex-wrap">
                        <li class="nav-item font-600"><a href="https://abiturient.dvgups.ru/" tabindex="0">Абитуриенту</a></li>
                        <li class="nav-item font-600"><a href="/studtopmenu" tabindex="0">Студенту</a></li>
                        <li class="nav-item font-600"><a href="/spectopmenu" tabindex="0">Специалисту</a></li>
                        <li class="nav-item font-600"><a href="/asptopmenu" tabindex="0">Аспиранту</a></li>
                        <li class="nav-item font-600"><a href="/spectopmenu/ido" tabindex="0">Доп. образование</a></li>
                        <li class="nav-item font-600"><a href="/" class="accessibility-link" tabindex="0">Версия сайта для слабовидящих</a></li>
                    </ul>
                </div>
            </ul>

            <ul class="pr-0 shrink-0">
                <div>
                    <ul class="flex justify-center items-center flex-wrap">
                        <li class="nav-item font-700"><a href="https://dvgups.ru/" tabindex="0">RU</a></li>
                        <li class="nav-item font-700"><a href="/en/" tabindex="0">ENG</a></li>
                        <li class="nav-item font-700"><a href="/ch/" tabindex="0">汉语</a></li>
                    </ul>
                </div>
            </ul>
        </div>
    </div>

</header>

<style lang="postcss">
    @reference "tailwindcss";

    .header-nav {
        @apply flex items-center px-[20px] py-[12px] rounded-[16px] bg-zinc-700/45;
    }

    .nav-item {
        @apply p-[4px] text-white hover:text-[#181818]/80 transition-colors duration-200;
    }

    .font-600 {
        @apply font-semibold;
    }

    .font-700 {
        @apply font-bold;
    }

</style>