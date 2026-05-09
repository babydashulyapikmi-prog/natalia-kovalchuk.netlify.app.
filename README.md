<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Наталия Ковальчук | Психолог</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@300;400;500&display=swap');

        body {
            font-family: 'Inter', system_ui, sans-serif;
        }
        
        .heading-font {
            font-family: 'Playfair Display', sans-serif;
        }

        .hero-bg {
            background: linear-gradient(rgba(0, 0, 0, 0.18), rgba(0, 0, 0, 0.28)), 
                        url('2https://picsum.photos/id/1015/2000/100') center/cover no-repeat;
        }

        .btn-primary {
            background-color: #8a7d6e;
            transition: all 0.4s cubic-bezier(0.4, 0.0, 0.2, 1);
        }
        
        .btn-primary:hover {
            background-color: #6f6458;
            transform: translateY(-3px);
            box-shadow: 0 20px 25px -5px rgb(138 125 110 / 0.2);
        }

        .soft-card {
            transition: all 0.4s cubic-bezier(0.4, 0.0, 0.2, 1);
        }
        
        .soft-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.15);
        }
    </style>
</head>
<body class="bg-[#f8f4ed] text-[#5c5348]">

    <!-- HERO SCREEN -->
    <section class="hero-bg min-h-screen flex items-center relative">
        <div class="absolute inset-0 bg-gradient-to-b from-transparent via-[#f8f4ed]/30 to-[#f8f4ed]/75"></div>
        
        <div class="max-w-7xl mx-auto px-6 md:px-12 relative z-10 pt-20">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                
                <!-- Левая колонка -->
                <div class="space-y-8">
                    <div class="inline-flex items-center gap-3 bg-white/80 backdrop-blur-md px-5 py-2 rounded-3xl border border-[#e8d9c7]">
                        <div class="w-3 h-3 bg-emerald-500 rounded-full animate-pulse"></div>
                        <span class="text-sm font-medium tracking-widest">САМОЗАНЯТАЯ • КОВАЛЬЧУК Н.А.</span>
                    </div>

                    <h1 class="heading-font text-6xl md:text-7xl leading-none text-[#3f372f] font-light">
                        Наталия<br>Ковальчук
                    </h1>

                    <!-- Обновлённые строки — теперь чёрные -->
                    <div class="space-y-1">
                        <p class="text-2xl md:text-3xl font-light text-pink">
                            Психолог • Магистр психологии
                        </p>
                        <p class="text-lg md:text-xl font-light text-black">
                           Кандидат на получение статуса СТА в области психотерапии(контракт в EATA)
                           А так же член EATA, ОСТА И СОТА
                        </p>
                    </div>

                    <!-- Цитата — тоже чёрная -->
                    <div class="max-w-md">
                        <p class="text-2xl md:text-3xl leading-tight font-light italic text-black">
                            «Пространство, где становятся возможными изменения и возвращается ощущение собственной Окейности»
                        </p>
                    </div>

                    <!-- Кнопки -->
                    <div class="flex flex-wrap gap-4 pt-6">
                        <a href="https://wa.me/79282858720" target="_blank" 
                           class="btn-primary text-white px-10 py-5 rounded-3xl flex items-center gap-3 text-lg font-medium">
                            <i class="fa-brands fa-whatsapp text-2xl"></i>
                            Записаться на консультацию
                        </a>
                        
                        <a href="https://t.me/Nataliya_Kovalchuk" target="_blank" 
                           class="bg-white hover:bg-[#f8f4ed] border border-[#d4c3b0] px-8 py-5 rounded-3xl flex items-center gap-3 text-lg font-medium transition-all">
                            <i class="fa-brands fa-telegram text-2xl text-[#229ED9]"></i>
                            Telegram
                        </a>
                    </div>

                    <div class="flex items-center gap-8 text-sm pt-4">
                        <a href="https://instagram.com/kovalchuk_harmonyscript" target="_blank" 
                           class="flex items-center gap-2 hover:text-[#8a7d6e] transition-colors">
                            <i class="fa-brands fa-instagram"></i>
                            <span>@kovalchuk_harmonyscript</span>
                        </a>
                        <a href="https://t.me/Nataliya_Kovalchuk" target="_blank" 
                           class="flex items-center gap-2 hover:text-[#8a7d6e] transition-colors">
                            <i class="fa-brands fa-telegram"></i>
                            <span>@Nataliya_Kovalchuk</span>
                        </a>
                    </div>
                </div>

                <!-- Правая колонка — фото -->
                <div class="relative">
                    <div class="aspect-[4/5] md:aspect-square max-w-md mx-auto relative">
                        <img src="Natalia.jpg" 
                             alt="Наталия Ковальчук — психолог"
                             class="w-full h-full object-cover rounded-[3.5rem] shadow-2xl border border-white/60">
                    </div>
                </div>
            </div>
        </div>

        <div class="absolute bottom-12 left-1/2 -translate-x-1/2 flex flex-col items-center gap-2 text-xs tracking-widest opacity-70">
            <span>Прокрутить</span>
            <i class="fa-solid fa-chevron-down animate-bounce"></i>
        </div>
    </section>

    <!-- Интерактивный блок -->
    <section class="py-20 bg-white">
        <div class="max-w-4xl mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="heading-font text-4xl mb-4">Как я принимаю решение о начале работы</h2>
                <p class="text-[#8a7d6e]">Честный и бережный подход к каждому запросу</p>
            </div>

            <div onclick="toggleSomatization()" id="decision-btn"
                 class="soft-card bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl p-8 cursor-pointer group">
                <div class="flex items-center justify-between">
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-2xl bg-[#d4c3b0]/20 flex items-center justify-center text-3xl">🤝</div>
                        <div>
                            <p class="text-2xl font-light">Как я принимаю решение о начале сотрудничества</p>
                            <p class="text-[#8a7d6e] text-sm mt-1">включая работу с соматизацией</p>
                        </div>
                    </div>
                    <i id="arrow" class="fa-solid fa-chevron-down text-2xl transition-transform duration-300"></i>
                </div>
                
                <div id="somatization-content" class="hidden mt-10 pt-10 border-t border-[#e8d9c7]">
                    <div class="grid md:grid-cols-2 gap-10">
                        <div>
                            <h4 class="font-medium mb-4 text-lg">Критерии начала работы:</h4>
                            <ul class="space-y-4 text-[#5c5348]">
                                <li class="flex gap-3"><span class="text-emerald-600">✓</span> Готовность к регулярным встречам</li>
                                <li class="flex gap-3"><span class="text-emerald-600">✓</span> Мотивация к изменениям</li>
                                <li class="flex gap-3"><span class="text-emerald-600">✓</span> Понимание границ терапии</li>
                                <li class="flex gap-3"><span class="text-emerald-600">✓</span> Отсутствие острых психиатрических состояний</li>
                            </ul>
                        </div>
                        
                        <div>
                            <h4 class="font-medium mb-4 text-lg">Работа с соматизацией</h4>
                            <p class="text-[#6b6458] leading-relaxed">
                                При телесных проявлениях тревоги и психосоматических симптомах я работаю особенно мягко и постепенно, 
                                уделяя большое внимание чувству безопасности.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <script>
        function toggleSomatization() {
            const content = document.getElementById('somatization-content');
            const arrow = document.getElementById('arrow');
            
            if (content.classList.contains('hidden')) {
                content.classList.remove('hidden');
                arrow.style.transform = 'rotate(180deg)';
            } else {
                content.classList.add('hidden');
                arrow.style.transform = 'rotate(0deg)';
            }
        }
    </script>
</body>
</html>
<!-- ====================== БЛОК 2: ОБО МНЕ ====================== -->
<section id="about" class="py-24 bg-[#f8f4ed]">
    <div class="max-w-7xl mx-auto px-6 md:px-12">
        <div class="grid md:grid-cols-12 gap-16 items-center">
            
            <!-- Фото слева -->
            <div class="md:col-span-5">
                <div class="sticky top-12">
                    <div class="aspect-square max-w-md mx-auto md:mx-0 rounded-[3rem] overflow-hidden shadow-2xl border border-white/70">
                        <img src="фото2.jpg" 
                             alt="Наталия Ковальчук"
                             class="w-full h-full object-cover">
                    </div>
                    <div class="mt-8 text-center md:text-left">
                        <p class="text-sm uppercase tracking-widest text-[#8a7d6e]">Транзактный анализ</p>
                        <p class="text-[#6b6458] mt-2">МИП • Международный уровень</p>
                    </div>
                </div>
            </div>

            <!-- Текстовая часть -->
            <div class="md:col-span-7 space-y-10">
                <div>
                    <span class="inline-block px-5 py-2 bg-white rounded-3xl text-sm tracking-widest border border-[#e8d9c7]">Обо мне</span>
                    <h2 class="heading-font text-5xl md:text-6xl text-[#3f372f] mt-6 leading-none">
                        Путь в профессию
                    </h2>
                </div>

                <p class="text-2xl text-[#5c5348] font-light leading-tight">
                    Магистр психологии с глубокой специализацией в Транзактном Анализе (МИП)
                </p>

                <ul class="space-y-6 text-lg">
                    <li class="flex gap-4">
                        <span class="text-2xl text-[#8a7d6e] mt-0.5">→</span>
                        <span>4 года углублённого обучения (курс ТА-202)</span>
                    </li>
                    <li class="flex gap-4">
                        <span class="text-2xl text-[#8a7d6e] mt-0.5">→</span>
                        <span>Практика с 2019 года: более 3000 часов индивидуальной и групповой работы</span>
                    </li>
                    <li class="flex gap-4">
                        <span class="text-2xl text-[#8a7d6e] mt-0.5">→</span>
                        <span>Куратор обучающих программ и супервизор для коллег</span>
                    </li>
                </ul>

                <div class="pt-8 border-t border-[#d4c3b0]/60">
                    <p class="text-xl italic leading-relaxed text-[#4a4339]">
                        «Я постоянно инвестирую в свою устойчивость: прохожу личную терапию и регулярные супервизии, 
                        чтобы оставаться для вас надежным проводником».
                    </p>
                </div>

                <div class="pt-6">
                    <a href="https://t.me/Nataliya_Kovalchuk" target="_blank"
                       class="inline-flex items-center gap-3 text-[#8a7d6e] hover:text-[#6f6458] transition-colors text-lg group">
                        Записаться на консультацию 
                        <span class="text-2xl group-hover:translate-x-1 transition-transform">→</span>
                    </a>
                </div>
            </div>
        </div>
    </div>
</section
<!-- ====================== БЛОК 3: С ЧЕМ Я РАБОТАЮ ====================== -->
<section id="requests" class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-6 md:px-12">
        
        <div class="text-center mb-16">
            <span class="inline-block px-5 py-2 bg-[#f8f4ed] rounded-3xl text-sm tracking-widest border border-[#e8d9c7]">Работаем вместе</span>
            <h2 class="heading-font text-5xl md:text-6xl text-[#3f372f] mt-6 leading-none">
                С чем мы можем поработать?
            </h2>
            <p class="mt-4 text-[#8a7d6e] max-w-md mx-auto">
                Создаю безопасное пространство для изменений
            </p>
        </div>

        <div class="grid md:grid-cols-2 gap-8">
            
            <!-- Карточка 1 -->
            <div class="soft-card group bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl overflow-hidden hover:border-[#d4c3b0] transition-all duration-300">
                <div class="h-56 bg-cover bg-center relative" 
                     style="background-image: url('тупик.jpg');">
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#f8f4ed]/90"></div>
                </div>
                <div class="p-10">
                    <div class="text-4xl mb-6">⟳</div>
                    <h3 class="text-2xl font-light mb-4">Жизненные тупики</h3>
                    <p class="text-[#6b6458] leading-relaxed">
                        Когда кажется, что вы ходите по кругу одного и того же сценария жизни.
                    </p>
                </div>
            </div>

            <!-- Карточка 2 -->
            <div class="soft-card group bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl overflow-hidden hover:border-[#d4c3b0] transition-all duration-300">
                <div class="h-56 bg-cover bg-center relative" 
                     style="background-image: url('отн.jpg');">
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#f8f4ed]/90"></div>
                </div>
                <div class="p-10">
                    <div class="text-4xl mb-6">❤️</div>
                    <h3 class="text-2xl font-light mb-4">Сложности в отношениях</h3>
                    <p class="text-[#6b6458] leading-relaxed">
                        Зависимость, конфликты, страх близости, трудности с установкой границ.
                    </p>
                </div>
            </div>

            <!-- Карточка 3 -->
            <div class="soft-card group bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl overflow-hidden hover:border-[#d4c3b0] transition-all duration-300">
                <div class="h-56 bg-cover bg-center relative" 
                     style="background-image: url('фото7.jpg');">
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#f8f4ed]/90"></div>
                </div>
                <div class="p-10">
                    <div class="text-4xl mb-6">🌫️</div>
                    <h3 class="text-2xl font-light mb-4">Эмоциональные состояния</h3>
                    <p class="text-[#6b6458] leading-relaxed">
                        Тревога, выгорание, самокритика, чувство вины и стыда.
                    </p>
                </div>
            </div>

            <!-- Карточка 4 -->
            <div class="soft-card group bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl overflow-hidden hover:border-[#d4c3b0] transition-all duration-300">
                <div class="h-56 bg-cover bg-center relative" 
                     style="background-image: url('хуй.jpg');">
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#f8f4ed]/90"></div>
                </div>
                <div class="p-10">
                    <div class="text-4xl mb-6">🛡️</div>
                    <h3 class="text-2xl font-light mb-4">Личностные особенности</h3>
                    <p class="text-[#6b6458] leading-relaxed">
                        Работа с ПРЛ, БАР, ПТСР — бережно и в тандеме с врачом при необходимости.
                    </p>
                </div>
            </div>

        </div>

        <div class="text-center mt-16">
            <a href="https://t.me/Nataliya_Kovalchuk" target="_blank"
               class="inline-flex items-center gap-3 bg-[#8a7d6e] text-white px-10 py-6 rounded-3xl text-lg hover:bg-[#6f6458] transition-all">
                Обсудить ваш запрос
                <span>→</span>
            </a>
        </div>
    </div>
</section>
<!-- ====================== БЛОК 4: МОЙ МЕТОД ====================== -->
<section id="method" class="py-24 bg-[#f8f4ed]">
    <div class="max-w-7xl mx-auto px-6 md:px-12">
        
        <div class="text-center mb-16">
            <span class="inline-block px-5 py-2 bg-white rounded-3xl text-sm tracking-widest border border-[#e8d9c7]">Подход</span>
            <h2 class="heading-font text-5xl md:text-6xl text-[#3f372f] mt-6 leading-none">
                Метод: Транзактный Анализ
            </h2>
        </div>

        <div class="max-w-3xl mx-auto text-center mb-20">
            <p class="text-2xl leading-relaxed font-light text-[#4a4339]">
                «Мой подход основан на вере в то, что каждый человек изначально Окей и способен принимать новые решения. 
                Мы будем исследовать ваши эго-состояния, распутывать игры и переписывать жизненный сценарий ради обретения подлинной автономии».
            </p>
        </div>

        <!-- Интерактивные карточки Эго-состояний -->
        <div class="grid md:grid-cols-3 gap-8">
            
            <!-- Родитель -->
            <div class="soft-card group bg-white rounded-3xl overflow-hidden border border-[#e8d9c7] hover:border-[#d4c3b0] transition-all">
                <div class="h-64 bg-cover bg-center relative" 
                     style="background-image: url('roditel.jpg');">
                    <!-- Замените ссылку на своё фото Родителя -->
                </div>
                <div class="p-8">
                    <h3 class="text-2xl font-light mb-3 text-[#3f372f]">Родитель</h3>
                    <p class="text-[#6b6458]">
                        Внутренние правила, убеждения, критика и забота. 
                        Мы работаем с тем, какие голоса из прошлого до сих пор управляют вашей жизнью.
                    </p>
                </div>
            </div>

            <!-- Взрослый -->
            <div class="soft-card group bg-white rounded-3xl overflow-hidden border border-[#e8d9c7] hover:border-[#d4c3b0] transition-all">
                <div class="h-64 bg-cover bg-center relative" 
                     style="background-image: url('взрослый\ \(2\).jpg');">
                    <!-- Замените ссылку на своё фото Взрослого -->
                </div>
                <div class="p-8">
                    <h3 class="text-2xl font-light mb-3 text-[#3f372f]">Взрослый</h3>
                    <p class="text-[#6b6458]">
                        Здесь и сейчас. Рациональность, осознанность и способность принимать здесь-и-сейчас решения.
                        Цель терапии — укрепить именно это состояние.
                    </p>
                </div>
            </div>

            <!-- Ребёнок -->
            <div class="soft-card group bg-white rounded-3xl overflow-hidden border border-[#e8d9c7] hover:border-[#d4c3b0] transition-all">
                <div class="h-64 bg-cover bg-center relative" 
                     style="background-image: url('reb.jpg');">
                    <!-- Замените ссылку на своё фото Ребёнка -->
                </div>
                <div class="p-8">
                    <h3 class="text-2xl font-light mb-3 text-[#3f372f]">Ребёнок</h3>
                    <p class="text-[#6b6458]">
                        Эмоции, потребности, спонтанность и творчество. 
                        Помогаю исцелить раны и освободить  естественную Окейность внутреннего Ребёнка.
                    </p>
                </div>
            </div>

        </div>

        <div class="text-center mt-16">
            <a href="https://t.me/Nataliya_Kovalchuk" target="_blank"
               class="inline-flex items-center gap-3 bg-[#8a7d6e] text-white px-10 py-6 rounded-3xl text-lg hover:bg-[#6f6458] transition-all">
                Узнать, как ТА поможет именно вам
                <span>→</span>
            </a>
        </div>
    </div>
</section>
<!-- ====================== БЛОК 5: УСЛУГИ И СТОИМОСТЬ ====================== -->
<section id="pricing" class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-6 md:px-12">
        
        <div class="text-center mb-16">
            <span class="inline-block px-5 py-2 bg-[#f8f4ed] rounded-3xl text-sm tracking-widest border border-[#e8d9c7]">Форматы работы</span>
            <h2 class="heading-font text-5xl md:text-6xl text-[#3f372f] mt-6 leading-none">
                Услуги и стоимость
            </h2>
        </div>

        <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
            
            <!-- Карточка 1: Индивидуальная терапия -->
            <div class="soft-card bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl overflow-hidden hover:border-[#d4c3b0] transition-all duration-300">
                <div class="h-64 bg-cover bg-center relative" 
                     style="background-image: url('индивидуалочка.jpg');">
                    <!-- ← Замени ссылку на своё фото для индивидуальной терапии -->
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#f8f4ed]/80"></div>
                </div>
                <div class="p-10">
                    <h3 class="text-2xl font-light mb-4">Индивидуальная терапия</h3>
                    <p class="text-[#8a7d6e] mb-1">Онлайн / Офлайн</p>
                    <p class="text-4xl font-light text-[#3f372f] mb-8">100$ <span class="text-base font-normal text-[#8a7d6e]">/ 50 мин.</span></p>
                    <p class="text-[#6b6458] leading-relaxed">
                        Краткосрочный запрос или глубокая работа.
                    </p>
                </div>
            </div>

            <!-- Карточка 2: Групповая терапия -->
            <div class="soft-card bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl overflow-hidden hover:border-[#d4c3b0] transition-all duration-300">
                <div class="h-64 bg-cover bg-center relative" 
                     style="background-image: url('груповаятерапияjpg.jpg');">
                    <!-- ← Замени ссылку на своё фото для групповой терапии -->
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#f8f4ed]/80"></div>
                </div>
                <div class="p-10">
                    <h3 class="text-2xl font-light mb-4">Групповая терапия</h3>
                    <p class="text-4xl font-light text-[#3f372f] mb-8">50$ <span class="text-base font-normal text-[#8a7d6e]">/ сессия</span></p>
                    <p class="text-[#6b6458] leading-relaxed">
                        Развитие через взаимодействие с другими.
                    </p>
                </div>
            </div>

            <!-- Карточка 3: Супервизия -->
            <div class="soft-card bg-[#f8f4ed] border border-[#e8d9c7] rounded-3xl overflow-hidden hover:border-[#d4c3b0] transition-all duration-300">
                <div class="h-64 bg-cover bg-center relative" 
                     style="background-image: url('коллеги.jpg');">
                    <!-- ← Замени ссылку на своё фото для супервизии -->
                    <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-[#f8f4ed]/80"></div>
                </div>
                <div class="p-10">
                    <h3 class="text-2xl font-light mb-4">Супервизия для коллег</h3>
                    <p class="text-4xl font-light text-[#3f372f] mb-8">5000 ₽ <span class="text-base font-normal text-[#8a7d6e]">/ 50 мин.</span></p>
                    <p class="text-[#6b6458] leading-relaxed">
                        Профессиональная поддержка вашей практики.
                    </p>
                </div>
            </div>

        </div>

        <div class="text-center mt-16 text-sm text-[#8a7d6e]">
            <p>Оплата в рублях по курсу ЦБ на день оплаты</p>
            <p class="mt-1">Возможна рассрочка на долгосрочную терапию</p>
        </div>
    <!-- ====================== БЛОК 6: ГРАНИЦЫ И ЭТИКА ====================== -->
<section id="ethics" class="py-24 bg-[#f8f4ed]">
    <div class="max-w-7xl mx-auto px-6 md:px-12">
        
        <div class="grid md:grid-cols-12 gap-16 items-center">
            
            <!-- Левая колонка — фото -->
            <div class="md:col-span-5">
                <div class="sticky top-12">
                    <div class="aspect-[4/5] rounded-[3rem] overflow-hidden shadow-2xl border border-white/70 bg-[#e8d9c7]">
                        <img src="херня.jpg" 
                             alt="Наталия Ковальчук"
                             class="w-full h-full object-cover transition-all duration-700 hover:scale-105">
                        <!-- Замени ссылку выше на свою -->
                    </div>
                </div>
            </div>

            <!-- Правая колонка — принципы -->
            <div class="md:col-span-7">
                <span class="inline-block px-5 py-2 bg-white rounded-3xl text-sm tracking-widest border border-[#e8d9c7]">Этика и границы</span>
                
                <h2 class="heading-font text-5xl md:text-6xl text-[#3f372f] mt-6 leading-none">
                    Мои принципы
                </h2>

                <p class="mt-8 text-2xl font-light leading-tight text-[#4a4339]">
                    Я работаю в соответствии с Этическим кодексом Транзактного Анализа.
                </p>

                <div class="mt-12 space-y-10">
                    <div class="flex gap-6">
                        <div class="w-12 h-12 flex-shrink-0 bg-white rounded-2xl flex items-center justify-center text-3xl shadow-sm">🔒</div>
                        <div>
                            <h3 class="text-xl font-medium">Полная конфиденциальность</h3>
                            <p class="mt-2 text-[#6b6458]">Всё, о чём мы говорим на сессиях, остаётся строго между нами.</p>
                        </div>
                    </div>

                    <div class="flex gap-6">
                        <div class="w-12 h-12 flex-shrink-0 bg-white rounded-2xl flex items-center justify-center text-3xl shadow-sm">🛡️</div>
                        <div>
                            <h3 class="text-xl font-medium">Чёткие границы</h3>
                            <p class="mt-2 text-[#6b6458]">Не работаю с близкими знакомыми / родственниками.</p>
                        </div>
                    </div>

                    <div class="flex gap-6">
                        <div class="w-12 h-12 flex-shrink-0 bg-white rounded-2xl flex items-center justify-center text-3xl shadow-sm">🧬</div>
                        <div>
                            <h3 class="text-xl font-medium">Безопасность прежде всего</h3>
                            <p class="mt-2 text-[#6b6458]">При необходимости работаю в тандеме с психиатром.</p>
                        </div>
                    </div>
                </div>

                <div class="mt-16 pt-10 border-t border-[#d4c3b0]/60">
                    <p class="italic text-[#5c5348]">
                        Эти правила помогают создать по-настоящему безопасное пространство для вашей работы.
                    </p>
                </div>
            </div>
        </div>
    </div>
</section>
