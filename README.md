# 🌌 STELLAR EVOLUTION — Gargantua V-1

![Stellar Evolution Preview](STELLAR EVOLUTION%20%E2%80%94%20Gargantua%20V-1.gif)

---

## 🌐 Choose Language / Выберите язык / Оберіть мову
* [🇬🇧 English](#-english)
* [🇺🇦 Українська](#-українська)
* [🇷🇺 Русский](#-русский)

---

## 🇬🇧 English

> **Stellar Evolution** is an interactive, cinematic web experience that visualizes the full life cycle of a massive star: from its stable state to a catastrophic supernova explosion, leading to the birth of a supermassive black hole inspired by *Gargantua*.

This portfolio pet-project demonstrates advanced creative coding. All animations and visual effects are bound to the user's scroll position, delivering an immersive space cinematic directly in the browser.

### ✨ Key Phases
1. **Phase 01: Blue Supergiant** — A massive star running out of fuel. Features a live plasma surface animated with convection cells via procedural noise.
2. **Phase 02: Core Collapse & Supernova** — The core collapses in a fraction of a second, triggering a shockwave that violently ejects 3D particle systems into space.
3. **Phase 03: Accretion Disk** — Fallback matter circularizes, spinning at differential speeds and forming a glowing, high-temperature plasma disk.
4. **Phase 04: Event Horizon & Jets** — The final monster is born, showcasing a bright photon ring, gravitational lensing distortion, and relativistic plasma jets.

### 🛠️ Tech Stack
* **Three.js** — 3D scene orchestration, buffer geometries, custom lighting.
* **GLSL (Shaders)** — Custom vertex and fragment shaders for image-space gravitational lensing simulation, Doppler boosting, and procedural plasma FBM noise.
* **GSAP + ScrollTrigger** — Precise scroll-driven timeline management.
* **Vanilla JS / CSS3** — Responsive lightweight HUD overlay.

### 🚀 Optimization Highlights
* **Dynamic Device Profiling:** Automatically lowers particle count on mobile (from 6200+ down to safe GPU limits) to guarantee 60 FPS.
* **Zero Allocation in Render Loop:** Pre-allocated colors and vectors avoid memory thrashing and entirely eliminate Garbage Collector micro-stutters.
* **GPU-Driven Effects:** Heavy math for light deflection and plasma movement is offloaded entirely to the GPU via custom shaders.
* **Asynchronous Bloom Fallback:** Cinematic glow (`UnrealBloomPass`) loads dynamically. If CDN fails, the website gracefully falls back to the native WebGL renderer.

### 💻 Local Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/WebBit-Ro/STELLAR-EVOLUTION-Gargantua-V-1
   ```
2. Open `index.html` via a local server (e.g., Live Server in VS Code) for correct CDN script resolution.

[🔼 Back to Top](#-stellar-evolution--gargantua-v-1)

---

## 🇺🇦 Українська

> **Stellar Evolution** — це інтерактивний кінематографічний веб-інтерфейс, який візуалізує повний життєвий цикл масивної зірки: від її стабільного стану до катастрофічного вибуху наднової та фінального народження надмасивної чорної діри, натхненної моделлю *Gargantua*.

Це демонстраційний пет-проєкт для портфоліо, створений на стику веб-розробки та комп'ютерної графіки. Усі анімації та візуальні ефекти прив'язані до плавного скролінгу сторінки, що занурює користувача в атмосферу космічного синематика прямо в браузері.

### ✨ Ключові фази історії
1. **Фаза 01: Голубий надгігант (Blue Supergiant)** — Масивна зірка на порозі вичерпання палива. Візуалізовано живу плазмову поверхню з конвекційними комірками через процедурний шум.
2. **Фаза 02: Колапс ядра та Наднова (Supernova)** — Ядро схлопується за частку секунди, породжуючи потужну ударну хвилю, яка викидає тривимірні системи частинок у простір.
3. **Фаза 03: Аккреційний диск (Accretion Disk)** — Речовина падає назад і закручується з диференціальною швидкістю, формуючи гарячий обертовий диск.
4. **Фаза 04: Горизонт подій та Джети (Event Horizon)** — Народження гравітаційного монстра. Фінал історії з демонстрацією фотонного кільця, релятивістських струменів плазми та ефекту лінзування.

### 🛠️ Технологічний стек
* **Three.js** — побудова 3D-сцени, робота з буферною геометрією, кастомними матеріалами та освітленням.
* **GLSL (Шейдери)** — унікальні вершинні та фрагментні шейдери для симуляції гравітаційного лінзування світла, ефекту Допплера та процедурного шуму плазми (FBM).
* **GSAP + ScrollTrigger** — оркестровка таймлайну анімації та прив'язка фаз до позиції скролу.
* **Vanilla JS / CSS3** — адаптивний та легкий інтерфейс (HUD) поверх WebGL-конвасу.

### 🚀 Оптимізація та продуктивність
* **Адаптивний профайлінг пристроїв:** Кількість важких частинок автоматично зменшується на смартфонах (з 6200+ на десктопі), забезпечуючи стабільні 60 FPS.
* **Zero Allocation у рендер-лупі:** Усі об'єкти кольорів та векторів виділяються в пам'яті один раз при ініціалізації. Відсутність створення об'єктів у кадрі повністю виключає мікро-фризи від Garbage Collector.
* **GPU-Driven обчислення:** Математика викривлення світла біля горизонту подій та рух плазми повністю перенесені з процесора на відеокарту.
* **Асинхронний Bloom-fallback:** Кінематографічне світіння (`UnrealBloomPass`) підвантажується динамічно. Якщо CDN недоступний, проєкт м'яко перемикається на стандартний рендеринг.

### 💻 Локальний запуск
1. Склонуйте репозиторій:
   ```bash
   git clone https://github.com/WebBit-Ro/STELLAR-EVOLUTION-Gargantua-V-1
   ```
2. Відкрийте `index.html` через локальний сервер (наприклад, Live Server у VS Code) для коректної роботи CDN-скриптів.

[🔼 Нагору](#-stellar-evolution--gargantua-v-1)

---

## 🇷🇺 Русский

> **Stellar Evolution** — это интерактивный кинематографический веб-интерфейс, который визуализирует полный жизненный цикл массивной звезды: от её стабильного состояния до катастрофического взрыва сверхновой и финального рождения сверхмассивной чёрной дыры, вдохновленной моделью *Gargantua*.

Это демонстрационный пет-проект для портфолио, созданный на стыке веб-разработки и компьютерной графики (Creative Coding). Все анимации и визуальные эффекты привязаны к плавному скроллингу страницы, погружая пользователя в атмосферу космического синематика прямо в браузере.

### ✨ Ключевые фазы истории
1. **Фаза 01: Голубой сверхгигант (Blue Supergiant)** — Массивная звезда на пороге истощения топлива. Визуализирована живая плазменная поверхность с конвекционными ячейками на процедурном шуме.
2. **Фаза 02: Колапс ядра и Сверхновая (Supernova)** — Ядро схлопывается за доли секунды, порождая мощную ударную волну и выбрасывая трехмерные системы частиц в окружающее пространство.
3. **Фаза 03: Аккреционный диск (Accretion Disk)** — Вещество падает обратно и закручивается с дифференциальной скоростью, формируя горячий вращающийся диск плазмы.
4. **Фаза 04: Горизонт событий и Джети (Event Horizon)** — Рождение гравитационного монстра. Финал истории с формированием фотонного кольца, релятивистских струй плазмы и эффекта линзирования.

### 🛠️ Технологический стек
* **Three.js** — построение 3D-сцены, работа с буферной геометрией, кастомными материалами и освещением.
* **GLSL (Шейдеры)** — уникальные вершинные и фрагментные шейдеры для симуляции гравитационного линзирования света, эффекта Допплера и процедурного шума плазмы (FBM).
* **GSAP + ScrollTrigger** — оркестровка таймлайна анимации и привязка фаз симуляции к позиции скролла.
* **Vanilla JS / CSS3** — адаптивный и легкий интерфейс (HUD) поверх WebGL-канваса.

### 🚀 Оптимизация и производительность
* **Динамический профайлинг устройств:** Количество тяжелых частиц автоматически снижается на смартфонах (с 6200+ на десктопе до безопасных лимитов), сохраняя стабильные 60 FPS.
* **Zero Allocation в рендер-лупе:** Все цветовые объекты и векторы выделяются в памяти один раз при инициализации. Внутри циклов анимации нет создания новых объектов, что исключает фризы от Garbage Collector.
* **GPU-Driven вычисления:** Сложная математика искривления света у горизонта и симуляция плазмы перенесены из CPU на видеокарту с помощью кастомных шейдеров.
* **Умный Bloom-fallback:** Кинематографическое свечение (`UnrealBloomPass`) подгружается асинхронно через CDN. Если сеть нестабильна, проект мягко переключается на стандартный пайплайн рендеринга.

### 💻 Локальный запуск
1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/WebBit-Ro/STELLAR-EVOLUTION-Gargantua-V-1
   ```
2. Откройте файл `index.html` через локальный сервер (например, Live Server в VS Code) для корректной работы всех CDN-скриптов.

[🔼 Наверх](#-stellar-evolution--gargantua-v-1)
