<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Animé | BTS SIO</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/tsparticles-slim@2.0.6/tsparticles.slim.bundle.min.js"></script>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script src="https://unpkg.com/scrollreveal"></script>

    <style>
        :root {
            --bg-color: #0a0a0a;
            --surface-color: #111111;
            --primary-color: #00ffcc; 
            --text-color: #f0f0f0;
            --text-muted: #888888;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; scroll-behavior: smooth; }
        body { background-color: var(--bg-color); color: var(--text-color); overflow-x: hidden; }

        #tsparticles { position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1; }

        nav {
            position: fixed; top: 0; width: 100%; padding: 20px 50px; display: flex;
            justify-content: space-between; align-items: center; background: rgba(10, 10, 10, 0.8);
            backdrop-filter: blur(10px); z-index: 100; border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }

        .logo { font-size: 1.5rem; font-weight: 700; color: var(--text-color); }
        .logo span { color: var(--primary-color); }

        .nav-links a { color: var(--text-color); text-decoration: none; margin-left: 30px; font-weight: 600; transition: color 0.3s; }
        .nav-links a:hover { color: var(--primary-color); }

        section { min-height: 100vh; padding: 100px 10%; display: flex; flex-direction: column; justify-content: center; }

        .hero { align-items: flex-start; }
        .hero h1 { font-size: 4rem; margin-bottom: 10px; }
        .hero h2 { font-size: 2rem; color: var(--text-muted); margin-bottom: 20px; }
        .typed-cursor { color: var(--primary-color); font-size: 2rem; }

        .btn {
            display: inline-block; padding: 12px 30px; margin-top: 20px; background: transparent;
            color: var(--primary-color); border: 2px solid var(--primary-color); border-radius: 5px;
            text-decoration: none; font-weight: bold; transition: all 0.3s ease;
            box-shadow: 0 0 10px rgba(0, 255, 204, 0.1); cursor: pointer;
        }
        .btn:hover {
            background: var(--primary-color); color: var(--bg-color);
            box-shadow: 0 0 20px rgba(0, 255, 204, 0.6); transform: translateY(-3px);
        }

        .section-title { font-size: 2.5rem; margin-bottom: 50px; text-align: center; }
        .section-title span { color: var(--primary-color); }

        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
        .card { background: var(--surface-color); padding: 30px; border-radius: 10px; border: 1px solid rgba(255, 255, 255, 0.05); transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s; }
        .card:hover { transform: translateY(-10px); border-color: var(--primary-color); box-shadow: 0 10px 30px rgba(0, 255, 204, 0.15); }
        .card h3 { color: var(--text-color); margin-bottom: 15px; font-size: 1.5rem; }
        .card p { color: var(--text-muted); margin-bottom: 20px; font-size: 0.95rem; }
        
        .tech-stack span { display: inline-block; padding: 5px 10px; background: rgba(0, 255, 204, 0.1); color: var(--primary-color); border-radius: 4px; font-size: 0.8rem; margin-right: 10px; margin-bottom: 10px; }

        footer { text-align: center; padding: 30px; border-top: 1px solid rgba(255,255,255,0.05); margin-top: 50px; color: var(--text-muted); }
        
        /* STYLE DU MINI-JEU */
        #game-overlay { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(10,10,10,0.98); z-index: 9999; flex-direction: column; align-items: center; justify-content: center; }
        #game-area { position: relative; width: 80%; max-width: 800px; height: 60vh; border: 2px dashed var(--primary-color); border-radius: 10px; overflow: hidden; background: #000; }
        #the-bug { position: absolute; font-size: 2.5rem; cursor: crosshair; user-select: none; transition: top 0.2s linear, left 0.2s linear; }
        #secret-dot { cursor: pointer; color: var(--bg-color); transition: color 0.3s; }
        #secret-dot:hover { color: var(--primary-color); }
    </style>
</head>
<body>

    <div id="tsparticles"></div>

    <nav>
        <div class="logo">Roméo<span>.dev</span></div>
        <div class="nav-links">
            <a href="#accueil">Accueil</a>
            <a href="#projets">Projets</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section id="accueil" class="hero">
        <h1 class="reveal-left">Bonjour, je suis <span style="color: var(--primary-color);">Ton Prénom</span></h1>
        <h2 class="reveal-left delay-1">Je suis <span id="typed-text"></span></h2>
        <p class="reveal-up delay-2" style="max-width: 600px; color: var(--text-muted);">
            Étudiant en BTS SIO passionné par la création de solutions informatiques modernes.
        </p>
        <a href="#projets" class="btn reveal-up delay-3">Découvrir mon travail</a>
    </section>

    <section id="projets">
        <h2 class="section-title reveal-up">Mes <span>Projets E4</span></h2>
        <div class="grid">
            <div class="card reveal-up">
                <h3>Gestion des Frais (GSB)</h3>
                <p>Application web permettant aux visiteurs médicaux de saisir et de consulter leurs fiches de frais mensuelles.</p>
                <div class="tech-stack"><span>PHP</span><span>MySQL</span><span>Bootstrap</span></div>
            </div>
            <div class="card reveal-up delay-1">
                <h3>Application Mobile</h3>
                <p>Développement d'une application cross-platform pour la gestion de tâches collaboratives.</p>
                <div class="tech-stack"><span>React Native</span><span>Firebase</span></div>
            </div>
            <div class="card reveal-up delay-2">
                <h3>Refonte Réseau</h3>
                <p>Mise en place d'une architecture réseau sécurisée avec VLANs et serveurs de déploiement (MDT).</p>
                <div class="tech-stack"><span>Cisco</span><span>Windows Server</span></div>
            </div>
        </div>
    </section>

    <section id="contact" style="min-height: 60vh;">
        <h2 class="section-title reveal-up">Me <span>Contacter</span></h2>
        <div style="text-align: center;" class="reveal-up delay-1">
            <p style="color: var(--text-muted); margin-bottom: 30px;">Je suis actuellement à la recherche d'un stage ou d'une alternance.</p>
            <a href="mailto:ton.email@gmail.com" class="btn">Envoyer un message</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 - Ton Prénom Ton Nom | Portfolio BTS SIO<span id="secret-dot">.</span></p>
    </footer>

    <div id="game-overlay">
        <h2 style="color: var(--primary-color); margin-bottom: 10px;">🚨 Alerte Bug 🚨</h2>
        <p style="margin-bottom: 20px; color: var(--text-muted);">Attrape (clique sur) le bug 5 fois pour nettoyer le code !</p>
        
        <div id="game-area">
            <div id="the-bug">🐛</div>
        </div>
        
        <p style="margin-top: 20px; font-size: 1.5rem;">Bugs fixés : <span id="score" style="color: var(--primary-color); font-weight: bold;">0</span> / 5</p>
        <button id="close-game" class="btn" style="margin-top: 20px;">Fuir (Fermer)</button>
    </div>

    <script>
        /* 1. ANIMATIONS DE FOND ET TEXTE (Comme avant) */
        tsParticles.load("tsparticles", {
            particles: {
                number: { value: 40, density: { enable: true, value_area: 800 } },
                color: { value: "#00ffcc" },
                shape: { type: "circle" },
                opacity: { value: 0.3, random: true },
                size: { value: 3, random: true },
                line_linked: { enable: true, distance: 150, color: "#00ffcc", opacity: 0.2, width: 1 },
                move: { enable: true, speed: 1, out_mode: "out" }
            },
            interactivity: {
                detect_on: "canvas",
                events: { onhover: { enable: true, mode: "grab" }, resize: true },
                modes: { grab: { distance: 140, line_linked: { opacity: 0.8 } } }
            },
            retina_detect: true
        });

        new Typed('#typed-text', {
            strings: ['Étudiant en BTS SIO.', 'Développeur Web.', 'Chasseur de Bugs.'],
            typeSpeed: 50, backSpeed: 30, backDelay: 2000, loop: true
        });

        const sr = ScrollReveal({ distance: '50px', duration: 1000, easing: 'cubic-bezier(0.68, -0.55, 0.265, 1.55)' });
        sr.reveal('.reveal-up', { origin: 'bottom' });
        sr.reveal('.reveal-left', { origin: 'left' });
        sr.reveal('.delay-1', { delay: 200 });
        sr.reveal('.delay-2', { delay: 400 });
        sr.reveal('.delay-3', { delay: 600 });

        /* 2. LOGIQUE DU MINI-JEU CACHÉ */
        const trigger = document.getElementById('secret-dot');
        const overlay = document.getElementById('game-overlay');
        const bug = document.getElementById('the-bug');
        const scoreDisplay = document.getElementById('score');
        const closeBtn = document.getElementById('close-game');
        const gameArea = document.getElementById('game-area');

        let score = 0;
        let bugInterval;
        let currentSpeed = 900; // Vitesse de départ (millisecondes)

        // Fonction pour déplacer le bug aléatoirement
        function moveBug() {
            // Calcule l'espace disponible moins la taille du bug pour qu'il ne sorte pas
            const maxX = gameArea.clientWidth - 50;
            const maxY = gameArea.clientHeight - 50;
            const randomX = Math.floor(Math.random() * maxX);
            const randomY = Math.floor(Math.random() * maxY);
            
            bug.style.left = randomX + 'px';
            bug.style.top = randomY + 'px';
        }

        // Ouvrir le jeu
        trigger.addEventListener('click', () => {
            overlay.style.display = 'flex';
            score = 0;
            currentSpeed = 900;
            scoreDisplay.textContent = score;
            bug.style.display = 'block';
            moveBug();
            bugInterval = setInterval(moveBug, currentSpeed);
        });

        // Fermer le jeu
        closeBtn.addEventListener('click', () => {
            overlay.style.display = 'none';
            clearInterval(bugInterval);
        });

        // Cliquer sur le bug
        bug.addEventListener('click', () => {
            score++;
            scoreDisplay.textContent = score;
            
            if (score >= 5) {
                clearInterval(bugInterval);
                bug.style.display = 'none';
                alert('🎉 GÉANT ! Tu as fixé tous les bugs ! Ton code est maintenant parfait (pour l\'instant...).');
                setTimeout(() => { overlay.style.display = 'none'; }, 500);
            } else {
                // Si on a pas encore gagné, on accélère le bug
                clearInterval(bugInterval);
                currentSpeed -= 150; // Le bug devient plus rapide de 150ms à chaque clic
                moveBug(); 
                bugInterval = setInterval(moveBug, currentSpeed);
            }
        });
    </script>
</body>
</html>
