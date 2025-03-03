<template>
    <div class="introduction">
        <header class="intro-header">
            <div class="avatar">
                <img src="/images/avatar.jpg" alt="avatar" />
            </div>
            <div class="intro-text">
                <h2>陳彥廷</h2>
                <p>
                    Hi there! 👋<br />I'm a Computer Science student at National
                    Yang Ming Chiao Tung University (NYCU) (formerly known as
                    NCTU), Taiwan.
                </p>
                <a class="contact-button" href="https://github.com/PikachuTW"
                    >聯絡我</a
                >
            </div>
        </header>
        <section class="about-section">
            <h3>💻 Technical Skills</h3>
            <ul>
                <li><p>Expert in: Javascript (Node.js)</p></li>
                <li>
                    <p>
                        Currently Learning: C++ (as part of university
                        curriculum)
                    </p>
                </li>
                <li><p>Also Familiar With: C, Python</p></li>
                <li>
                    <p>Self-Learning: Rust, Golang</p>
                </li>
            </ul>

            <h3>🔨 Main Focus</h3>
            <ul>
                <li>
                    <p>
                        I primarily work on Node.js projects, where I have the
                        most expertise and hands-on experience.
                    </p>
                </li>

                <li>
                    <p>
                        While focusing on my university studies, I'm also
                        passionate about expanding my programming horizons
                        through self-study of modern languages like Javascript,
                        Rust, and Golang.
                    </p>
                </li>
            </ul>

            <h3>🚀 Projects</h3>
            <ul>
                <li>
                    <p>
                        <strong>Tails Bot:</strong> My first programming project
                        - a feature-rich Discord bot built with Node.js. This
                        project has been my learning playground for JavaScript
                        and continues to evolve with new features and
                        architectural improvements. Running it on my Raspberry
                        Pi also helped me learn Linux.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>Frog Music:</strong> After the discontinuation
                        of popular music bots like Rythm, I created my ideal
                        Discord music bot - streamlined and efficient, without
                        unnecessary features.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>Tails SUS:</strong> A fun Discord bot that
                        mimics users through webhooks. While simple in
                        functionality, it's a community favorite in my Discord
                        server.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>betterE3:</strong> A Userscript enhancing the E3
                        learning platform with improved functionality and user
                        experience.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>discord-anime-notifier:</strong> A bot that
                        scrapes and notifies users about the latest anime
                        releases from major streaming platforms.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>FB-SAO-Random-Frame:</strong> An automated
                        Facebook page bot that scrapes and posts random anime
                        images from SAO.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>Face-Recognition:</strong> A simple face
                        recognition system built with Python for a school
                        project.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>Tails-SUS-in-Go:</strong> A Golang recreation of
                        my Tails SUS Discord bot, showcasing my journey into Go
                        programming.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>Discord-AI-Selfbot:</strong> A Python-based
                        Discord selfbot powered by Bing AI. This project helped
                        me expand my Python skills beyond my usual Node.js
                        comfort zone.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>my-rustling:</strong> Currently diving into Rust
                        programming language through the Rustlings exercise
                        project.
                    </p>
                </li>
                <li>
                    <p>
                        <strong>Discord.js-Command-Handler:</strong> A template
                        framework for Discord.js v14 bots, providing a solid
                        foundation for building Discord bots.
                    </p>
                </li>
            </ul>
        </section>
    </div>
</template>

<style scoped>
.avatar img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    margin: 0 auto 20px;
}

.introduction {
    padding: 40px 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.intro-header {
    background-color: #f5f5f5;
    padding: 40px;
    border-radius: 10px;
    display: flex;
    align-items: center;
    gap: 20px;
    @media (max-width: 800px) {
        flex-direction: column;
    }
}

.intro-text h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

.intro-text p {
    font-size: 1.1rem;
    margin-bottom: 20px;
}

.contact-button {
    padding: 10px 20px;
    background-color: #656d73;
    border: none;
    border-radius: 5px;
    color: #fff;
    cursor: pointer;
}

.contact-button:hover {
    background-color: #36383a;
}

.about-section {
    margin-top: 40px;
    padding: 0 40px;
}

.about-section h3 {
    font-size: 1.6rem;
    margin-top: 20px;
    margin-bottom: 10px;
}

.about-section p {
    font-size: 1.1rem;
    line-height: 1.6;
}
</style>
