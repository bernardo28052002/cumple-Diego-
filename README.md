<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Feliz Cumpleaños Diego🎉!</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Quicksand:wght@400;700&display=swap');
        body {
            font-family: 'Quicksand', sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            overflow-x: hidden;
            min-height: 100vh;
            /* Fondo optimizado */
            background: #0a043c url('https://losresumenes.com/wp-content/uploads/2023/10/Antoine-de-Saint-Exupery-El-Principito.-Resumen-y-analisisx.jpg') no-repeat center center;
            background-size: cover;
            background-attachment: fixed;
            position: relative;
        }
        body {
            font-family: 'Quicksand', sans-serif;
            margin: 0;
            padding: 0;
            color: #fff;
            overflow-x: hidden;
            background-color: #534d8a;
            background-image: url('https://losresumenes.com/wp-content/uploads/2023/10/Antoine-de-Saint-Exupery-El-Principito.-Resumen-y-analisisx.jpg');
            background-size: cover;
            background-attachment: fixed;
            min-height: 100vh;
        }
        
        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
        
        .star {
            position: absolute;
            background-color: #fff;
            border-radius: 50%;
            animation: twinkle var(--duration) infinite ease-in-out;
        }
        
        @keyframes twinkle {
            0%, 100% { opacity: 0.2; }
            50% { opacity: 1; }
        }
        
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 30px;
            background: rgba(10, 4, 60, 0.7);
            box-shadow: 0 0 30px rgba(212, 175, 55, 0.4);
            border-radius: 15px;
            position: relative;
            overflow: hidden;
            border: 2px solid #d4af37;
            backdrop-filter: blur(5px);
        }
        
        h1 {
            font-family: 'Dancing Script', cursive;
            color: #d4af37;
            font-size: 3.5em;
            margin-bottom: 20px;
            text-shadow: 0 0 10px rgba(212, 175, 55, 0.7);
            position: relative;
        }
        
        h1::after {
            content: "★";
            position: absolute;
            right: -40px;
            top: -15px;
            font-size: 1.2em;
            animation: float 3s ease-in-out infinite;
            color: #f9d423;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }
        
        .carousel {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin: 30px auto;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.5);
            border: 3px solid #d4af37;
        }
        
        .carousel-inner {
            display: flex;
            transition: transform 0.5s ease;
        }
        
        .carousel-item {
            min-width: 100%;
            position: relative;
        }
        
        .carousel-item img {
            width: 100%;
            height: 400px;
            object-fit: cover;
            display: block;
        }
        
        .carousel-caption {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(0,0,0,0.7);
            padding: 15px;
            color: #fff;
            font-size: 1.1em;
        }
        
        .carousel-control {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background: rgba(212, 175, 55, 0.7);
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            font-size: 1.5em;
            z-index: 10;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
        }
        
        .carousel-control:hover {
            background: rgba(212, 175, 55, 0.9);
        }
        
        .carousel-control.prev {
            left: 15px;
        }
        
        .carousel-control.next {
            right: 15px;
        }
        
        .message {
            text-align: center;
            line-height: 1.7;
            font-size: 1.1em;
            padding: 20px;
            margin: 20px 0;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            border-left: 4px solid #d4af37;
            position: relative;
        }
        
        .message::before {
            content: '"';
            font-family: 'Dancing Script', cursive;
            font-size: 5em;
            position: absolute;
            left: 10px;
            top: -20px;
            color: rgba(212, 175, 55, 0.3);
            line-height: 1;
        }
        
        .principito-quote {
            font-style: italic;
            color: #f9d423;
            margin: 20px 0;
            font-size: 1.2em;
            text-shadow: 0 0 5px rgba(0,0,0,0.5);
        }
        
        .signature {
            font-family: 'Dancing Script', cursive;
            margin-top: 30px;
            font-size: 1.8em;
            color: #d4af37;
            text-shadow: 0 0 5px rgba(212, 175, 55, 0.5);
        }
        
        .veterinary-icon {
            font-size: 2em;
            margin: 0 10px;
            vertical-align: middle;
            color: #2ecc71;
        }
        
        @media (max-width: 600px) {
            h1 {
                font-size: 2.5em;
            }
            
            .carousel-item img {
                height: 300px;
            }
            
            .container {
                margin: 20px 15px;
                padding: 20px;
            }
        }
    </style>
    <style>
        /* Estilos mejorados para el carrusel */
        .carousel {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin: 30px auto;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.5);
            border: 3px solid #d4af37;
            aspect-ratio: 16/9; /* Proporción fija para todas las pantallas */
        }
        
        .carousel-inner {
            display: flex;
            transition: transform 0.5s ease;
            height: 100%;
        }
        
        .carousel-item {
            min-width: 100%;
            position: relative;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }
        
        .carousel-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
            display: block;
        }
        
        .carousel-caption {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
            background: rgba(0,0,0,0.7);
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            font-size: 1.2em;
            white-space: nowrap;
            z-index: 10;
            text-align: center;
            max-width: 80%;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        
        /* Efecto de overlay para mejor legibilidad */
        .carousel-item::after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            height: 30%;
            background: linear-gradient(to top, rgba(0,0,0,0.7), transparent);
            z-index: 1;
        }
        
        /* Controles del carrusel */
        .carousel-control {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background: rgba(212, 175, 55, 0.7);
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            font-size: 1.5em;
            z-index: 20;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .carousel-control:hover {
            background: rgba(212, 175, 55, 0.9);
        }
        
        .carousel-control.prev {
            left: 10px;
        }
        
        .carousel-control.next {
            right: 10px;
        }
        
        /* Responsive para móviles */
        @media (max-width: 600px) {
            .carousel {
                max-width: 100%;
                border-radius: 0;
                border-left: none;
                border-right: none;
            }
            
            .carousel-caption {
                font-size: 1em;
                bottom: 10px;
                padding: 8px 15px;
            }
        }
    </style>
    
</head>
<body>
    <div class="stars" id="stars-container"></div>
    
    <div class="container">
        <h1>Feliz Cumpleaños Diego</h1>
        
        <div class="principito-quote">
            "Todas las personas mayores fueron al principio niños, aunque pocas de ellas lo recuerdan"<br>
            - El Principito
        </div>
        
        <div class="carousel">
            
            <div class="carousel-inner" id="carousel-inner">
                <div class="carousel-item">
                    <img src="image5.jpeg" alt="Diego Trabajando">
                    <div class="carousel-caption">Diego </div>
                </div>
                <div class="carousel-item">
                    <img src="image3.jpg" alt="Diego veterinario">
                    <div class="carousel-caption">Diego </div>
                </div>
                <div class="carousel-item">
                    <img src="image2.jpg" alt="Diego siendo Diego">
                    <div class="carousel-caption">Diego </div>
                </div>
                <div class="carousel-item">
                    <img src="image1.jpg" alt="Diego siendo Diego">
                    <div class="carousel-caption">Diego </div>
                </div>
                <div class="carousel-item">
                    <img src="image4.jpeg" alt="Diego siendo Diego">
                    <div class="carousel-caption">Diego </div>
                </div>
            </div>
            <button class="carousel-control prev" onclick="prevSlide()">❮</button>
            <button class="carousel-control next" onclick="nextSlide()">❯</button>
        </div>
        
        <div class="message">
            <p>Hoy celebramos a un hombre trabajador, luchador y con un corazón enorme para construir no solo sueños, sino también un hogar lleno de amor y esfuerzo. ¡Esa dedicación que pones en cada detalle para tu casa y tu familia es admirable!</p>
            <p>¡<span class="highlight">Diegoooo!</span> Hoy celebramos que existes porque eres de esa <span class="gold-text">gente rara</span> que lo hace todo a su manera,con su propio estilo:</p>
            
            <p>👉 Como <span class="highlight">veterinario</span> <span class="veterinary-icon">🐾</span> eres un <span class="gold-text">crack</span>, no solo por lo profesional, sino por ese amor que le pones hasta al perrito más gruñón.</p>
            
            <p>👉 En tu <span class="highlight">casa</span> <span class="home-icon">✨</span> te transformas en un mil usos: pintas, reparas, decoras... ¡Hasta pareces que siempre lo haces, aun que sea la primera vez!</p>
            
            <p>👉 Y en el <span class="highlight">trabajo</span> <span class="work-icon">💼</span>, aunque a veces te estreses (como todos), siempre <span class="gold-text">le pones alma</span> y sacas adelante todo como campeón.</p>
            
            <p>Que este año te llene de <span class="highlight">logros</span>, de esos <span class="gold-text">momentos chidos</span> con tu gente, de paz en tu casa y de muchos animalitos agradecidos. ¡Te mereces todo lo bueno!</p>
            
            <p>PD: No importa cuántos años cumplas, para mi siempre serás el <span class="highlight">Principito</span> de este cuento... aunque con una bata balanca y unas geringas 😉</p>
        </div>
        <style>
            /* Estilos mejorados para el carrusel */
            .carousel {
                position: relative;
                width: 100%;
                max-width: 600px;
                margin: 30px auto;
                overflow: hidden;
                border-radius: 10px;
                box-shadow: 0 10px 25px rgba(0,0,0,0.5);
                border: 3px solid #d4af37;
                aspect-ratio: 16/9; /* Proporción fija para todas las pantallas */
            }
            
            .carousel-inner {
                display: flex;
                transition: transform 0.5s ease;
                height: 100%;
            }
            
            .carousel-item {
                min-width: 100%;
                position: relative;
                display: flex;
                justify-content: center;
                align-items: center;
                overflow: hidden;
            }
            
            .carousel-item img {
                width: 100%;
                height: 100%;
                object-fit: cover;
                object-position: center;
                display: block;
            }
            
            .carousel-caption {
                position: absolute;
                bottom: 20px;
                left: 50%;
                transform: translateX(-50%);
                background: rgba(0,0,0,0.7);
                color: white;
                padding: 10px 20px;
                border-radius: 20px;
                font-size: 1.2em;
                white-space: nowrap;
                z-index: 10;
                text-align: center;
                max-width: 80%;
                overflow: hidden;
                text-overflow: ellipsis;
            }
            
            /* Efecto de overlay para mejor legibilidad */
            .carousel-item::after {
                content: "";
                position: absolute;
                bottom: 0;
                left: 0;
                right: 0;
                height: 30%;
                background: linear-gradient(to top, rgba(0,0,0,0.7), transparent);
                z-index: 1;
            }
            
            /* Controles del carrusel */
            .carousel-control {
                position: absolute;
                top: 50%;
                transform: translateY(-50%);
                background: rgba(212, 175, 55, 0.7);
                color: white;
                border: none;
                padding: 10px;
                cursor: pointer;
                font-size: 1.5em;
                z-index: 20;
                border-radius: 50%;
                width: 40px;
                height: 40px;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            
            .carousel-control:hover {
                background: rgba(212, 175, 55, 0.9);
            }
            
            .carousel-control.prev {
                left: 10px;
            }
            
            .carousel-control.next {
                right: 10px;
            }
            
            /* Responsive para móviles */
            @media (max-width: 600px) {
                .carousel {
                    max-width: 100%;
                    border-radius: 0;
                    border-left: none;
                    border-right: none;
                }
                
                .carousel-caption {
                    font-size: 1em;
                    bottom: 10px;
                    padding: 8px 15px;
                }
            }
        </style>
        
        
        <div class="signature">
            Con todo el cariño del universo ★<br>
            [Bernardo]
        </div>
    </div>
    <script>
        
        // Crea confeti
        function createConfetti() {
            const colors = ['#e74c3c', '#3498db', '#2ecc71', '#f1c40f', '#9b59b6'];
            for (let i = 0; i < 50; i++) {
                const confetti = document.createElement('div');
                confetti.className = 'confetti';
                confetti.style.left = Math.random() * 100 + 'vw';
                confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
                confetti.style.animationDuration = (Math.random() * 3 + 2) + 's';
                confetti.style.width = (Math.random() * 10 + 5) + 'px';
                confetti.style.height = confetti.style.width;
                document.body.appendChild(confetti);
            }
        }
        
        // Ejecuta al cargar
        window.onload = createConfetti;
    </script>
    

    <script>
        // Crear estrellas twinkle
        function createStars() {
            const container = document.getElementById('stars-container');
            const starCount = 200;
            
            for (let i = 0; i < starCount; i++) {
                const star = document.createElement('div');
                star.classList.add('star');
                
                // Tamaño aleatorio entre 1 y 3px
                const size = Math.random() * 2 + 1;
                star.style.width = `${size}px`;
                star.style.height = `${size}px`;
                
                // Posición aleatoria
                star.style.left = `${Math.random() * 100}%`;
                star.style.top = `${Math.random() * 100}%`;
                
                // Duración de animación aleatoria
                star.style.setProperty('--duration', `${Math.random() * 5 + 3}s`);
                
                // Retraso aleatorio
                star.style.animationDelay = `${Math.random() * 5}s`;
                
                container.appendChild(star);
            }
        }
        
        // Carrusel de imágenes
        let currentSlide = 0;
        const carousel = document.getElementById('carousel-inner');
        const items = document.querySelectorAll('.carousel-item');
        const totalItems = items.length;
        
        function updateCarousel() {
            carousel.style.transform = `translateX(-${currentSlide * 100}%)`;
        }
        
        function nextSlide() {
            currentSlide = (currentSlide + 1) % totalItems;
            updateCarousel();
        }
        
        function prevSlide() {
            currentSlide = (currentSlide - 1 + totalItems) % totalItems;
            updateCarousel();
        }
        
        // Auto avanzar el carrusel cada 5 segundos
        setInterval(nextSlide, 5000);
        
        // Crear estrellas al cargar
        window.onload = function() {
            createStars();
            updateCarousel();
        };
    </script>
    <script>
        // Crear estrellas twinkle
        function createStars() {
            const container = document.getElementById('stars-container');
            const starCount = 200;
            
            for (let i = 0; i < starCount; i++) {
                const star = document.createElement('div');
                star.classList.add('star');
                
                const size = Math.random() * 2 + 1;
                star.style.width = `${size}px`;
                star.style.height = `${size}px`;
                
                star.style.left = `${Math.random() * 100}%`;
                star.style.top = `${Math.random() * 100}%`;
                
                star.style.setProperty('--duration', `${Math.random() * 5 + 3}s`);
                star.style.animationDelay = `${Math.random() * 5}s`;
                
                container.appendChild(star);
            }
        }
    
</script>
<script>
    // Crea confeti que se muestra sobre el fondo pero bajo el contenido
    function createConfetti() {
        const colors = ['#e74c3c', '#3498db', '#2ecc71', '#f1c40f', '#9b59b6', '#d4af37'];
        const confettiContainer = document.createElement('div');
        confettiContainer.style.position = 'fixed';
        confettiContainer.style.top = '0';
        confettiContainer.style.left = '0';
        confettiContainer.style.width = '100%';
        confettiContainer.style.height = '100%';
        confettiContainer.style.pointerEvents = 'none'; // Permite hacer clic a través del confeti
        confettiContainer.style.zIndex = '1'; // Mayor que el fondo (0) pero menor que el contenido (2+)
        
        for (let i = 0; i < 100; i++) { // Aumenté a 100 partículas
            const confetti = document.createElement('div');
            confetti.className = 'confetti';
            confetti.style.position = 'absolute';
            confetti.style.left = Math.random() * 100 + 'vw';
            confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
            confetti.style.animationDuration = (Math.random() * 3 + 2) + 's';
            confetti.style.width = (Math.random() * 10 + 5) + 'px';
            confetti.style.height = confetti.style.width;
            confetti.style.borderRadius = '50%';
            confettiContainer.appendChild(confetti);
        }
        
        document.body.appendChild(confettiContainer);
    }

    // Asegúrate que el contenedor principal tenga z-index mayor
    document.addEventListener('DOMContentLoaded', function() {
        createConfetti();
        document.querySelector('.container').style.position = 'relative';
        document.querySelector('.container').style.zIndex = '2';
    });
</script>

<style>
    /* Agrega esto a tu CSS existente */
    .confetti {
        animation: fall linear infinite;
    }
    
    @keyframes fall {
        0% { 
            transform: translateY(-100vh) rotate(0deg); 
            opacity: 1; 
        }
        100% { 
            transform: translateY(100vh) rotate(360deg); 
            opacity: 0; 
        }
    }
    
    /* Asegura que el fondo tenga z-index bajo */
    body {
        position: relative;
    }
    
    /* Si tienes un elemento de fondo específico */
    .background-image {
        position: fixed;
        z-index: 0;
    }
</style>
    
</body>
</html>
