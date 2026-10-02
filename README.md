<!-- ================= HEADER ================= -->

<header>
    <nav class="navbar">

        <div class="logo">
            Marcha♡
        </div>

        <ul class="nav-menu" id="nav-menu">

            <li>
                <a href="#beranda">Home</a>
            </li>

            <li>
                <a href="#tentang">About</a>
            </li>

            <li>
                <a href="#proyek">Projects</a>
            </li>

            <li>
                <a href="#kontak">Contact</a>
            </li>

        </ul>

        <div>

            <button
                class="theme-button"
                id="theme-button">
                🌙
            </button>

            <button
                class="menu-button"
                id="menu-button">
                ☰
            </button>

        </div>

    </nav>
</header>


<!-- ================= HOME ================= -->

<section class="hero" id="beranda">

    <div class="hero-text">

        <p class="small-title">
            ✨ Hello, everyone!
        </p>

        <h1>
            Marcha Nabila
        </h1>

        <h2>
            Welcome to my portfolio ♡
        </h2>

        <p>
            I am a student of X RPL 3 who is interested
            in programming, UI/UX design,
            and website development.
        </p>

        <a
            href="#proyek"
            class="main-button">
            View Projects
        </a>

    </div>


    <div class="hero-photo">

        <div class="photo-frame">

            <img
                src="https://uploads.onecompiler.io/45447qjvv/1790334519966/WhatsApp%20Image%202026-09-25%20at%2003.59.33.jpeg"
                alt="Marcha Nabila's Photo">

        </div>

    </div>

</section>


<!-- ================= ABOUT ================= -->

<section id="tentang">

    <h2 class="section-title">
        ABOUT ME ♡
    </h2>


    <div class="about-card">

        <h3>
            Hi, I'm Marcha! 🌷
        </h3>

        <p>
            I am a student at SMK Krian 1 Sidoarjo,
            majoring in Software Engineering.
            I enjoy learning coding, creating websites,
            and exploring attractive and
            user-friendly designs.
        </p>

    </div>


    <!-- BIODATA -->

    <div class="biodata">

        <h3>
            Biodata
        </h3>

        <p>
            <strong>Name</strong> :
            Marcha Nabila Alfatuz Zahra
        </p>

        <p>
            <strong>Class</strong> :
            X RPL 3
        </p>

        <p>
            <strong>Student No.</strong> :
            41
        </p>

    </div>


    <!-- EDUCATION -->

    <div class="education">

        <h3>
            Education 🎓
        </h3>

        <div class="education-item">

            <strong>Elementary School</strong>

            <p>
                SDN Kepunten
            </p>

        </div>


        <div class="education-item">

            <strong>Junior High School</strong>

            <p>
                MTs 4 Sidoarjo
            </p>

        </div>


        <div class="education-item">

            <strong>Vocational High School</strong>

            <p>
                SMK Krian 1 Sidoarjo
            </p>

        </div>

    </div>

</section>


<!-- ================= PROJECTS ================= -->

<section id="proyek">

    <h2 class="section-title">
        My Projects 💻
    </h2>


    <div class="project-grid">


        <!-- PROJECT 1 -->

        <article class="project-card">

            <div class="project-image">
                🌸
            </div>


            <div class="project-content">

                <span class="project-number">
                    01
                </span>

                <h3>
                    To-Do List Website
                </h3>

                <p>
                    A simple application for recording
                    tasks and daily activities.
                </p>

                <button
                    class="demo-button"
                    onclick="openDemo('todo-demo')">
                    Use Project →
                </button>


                <div
                    class="demo-area"
                    id="todo-demo">

                    <h4>
                        🌸 To-Do List
                    </h4>

                    <div class="todo-input">

                        <input
                            type="text"
                            id="todo-input"
                            placeholder="Write a task...">

                        <button onclick="addTodo()">
                            Add
                        </button>

                    </div>

                    <ul id="todo-list"></ul>

                </div>

            </div>

        </article>


        <!-- PROJECT 2 -->

        <article class="project-card">

            <div class="project-image">
                🎨
            </div>


            <div class="project-content">

                <span class="project-number">
                    02
                </span>

                <h3>
                    Mini Calculator
                </h3>

                <p>
                    A simple calculator that can
                    perform basic mathematical operations.
                </p>

                <button
                    class="demo-button"
                    onclick="openDemo('calculator-demo')">
                    Use Project →
                </button>


                <div
                    class="demo-area"
                    id="calculator-demo">

                    <h4>
                        🎨 Mini Calculator
                    </h4>

                    <div class="calculator">

                        <input
                            type="text"
                            id="calc-display"
                            readonly>


                        <div class="calc-buttons">

                            <button
                                onclick="clearCalc()">
                                C
                            </button>

                            <button
                                onclick="deleteCalc()">
                                ⌫
                            </button>

                            <button
                                onclick="appendCalc('%')">
                                %
                            </button>

                            <button
                                onclick="appendCalc('/')">
                                ÷
                            </button>


                            <button
                                onclick="appendCalc('7')">
                                7
                            </button>

                            <button
                                onclick="appendCalc('8')">
                                8
                            </button>

                            <button
                                onclick="appendCalc('9')">
                                9
                            </button>

                            <button
                                onclick="appendCalc('*')">
                                ×
                            </button>


                            <button
                                onclick="appendCalc('4')">
                                4
                            </button>

                            <button
                                onclick="appendCalc('5')">
                                5
                            </button>

                            <button
                                onclick="appendCalc('6')">
                                6
                            </button>

                            <button
                                onclick="appendCalc('-')">
                                −
                            </button>


                            <button
                                onclick="appendCalc('1')">
                                1
                            </button>

                            <button
                                onclick="appendCalc('2')">
                                2
                            </button>

                            <button
                                onclick="appendCalc('3')">
                                3
                            </button>

                            <button
                                onclick="appendCalc('+')">
                                +
                            </button>


                            <button
                                onclick="appendCalc('0')">
                                0
                            </button>

                            <button
                                onclick="appendCalc('.')">
                                .
                            </button>

                            <button
                                class="calc-equal"
                                onclick="calculate()">
                                =
                            </button>

                        </div>

                    </div>

                </div>

            </div>

        </article>


        <!-- PROJECT 3 -->

        <article class="project-card">

            <div class="project-image">
                📚
            </div>


            <div class="project-content">

                <span class="project-number">
                    03
                </span>

                <h3>
                    Class Schedule App
                </h3>

                <p>
                    An application for recording
                    school class schedules.
                </p>

                <button
                    class="demo-button"
                    onclick="openDemo('schedule-demo')">
                    Use Project →
                </button>


                <div
                    class="demo-area"
                    id="schedule-demo">

                    <h4>
                        📚 Class Schedule
                    </h4>


                    <div class="schedule-form">

                        <select id="schedule-day">

                            <option value="Monday">
                                Monday
                            </option>

                            <option value="Tuesday">
                                Tuesday
                            </option>

                            <option value="Wednesday">
                                Wednesday
                            </option>

                            <option value="Thursday">
                                Thursday
                            </option>

                            <option value="Friday">
                                Friday
                            </option>

                        </select>


                        <input
                            type="text"
                            id="schedule-subject"
                            placeholder="Subject name">


                        <input
                            type="text"
                            id="schedule-time"
                            placeholder="Time, example: 07:00 - 08:30">


                        <button onclick="addSchedule()">
                            Add Schedule
                        </button>

                    </div>


                    <div id="schedule-list"></div>

                </div>

            </div>

        </article>

    </div>

</section>


<!-- ================= CONTACT ================= -->

<section id="kontak">

    <h2 class="section-title">
        Contact Me 💌
    </h2>


    <div class="contact-box">

        <p>
            📧 Email:
            <a
                href="mailto:nabilamarcha5567@gmail.com">
                nabilamarcha5567@gmail.com
            </a>
        </p>


        <p>
            📷 Instagram:
            <a
                href="https://instagram.com/mrcha.aja"
                target="_blank">
                @mrcha.aja
            </a>
        </p>

    </div>

</section>


<!-- ================= FOOTER ================= -->

<footer>

    <p>
        © 2026 Marcha Nabila Alfatuz Zahra
    </p>

    <p>
        Made with ♡ using HTML, CSS & JavaScript
    </p>

</footer>


<!-- BACK TO TOP BUTTON -->

<button id="scroll-top">
    ↑
</button>
