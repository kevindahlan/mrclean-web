<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mr. Clean Laundry - Bersih, Wangi, Rapi!</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Poppins -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Custom colors and font family - Adjusted to match logo more closely */
        :root {
            --color-dark-blue: #003366; /* Slightly darker blue, richer */
            --color-bright-yellow: #FFC300; /* Richer yellow */
            --color-light-bg: #f0f5f9; /* Softer light background */
        }
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--color-light-bg);
        }
        .bg-dark-blue {
            background-color: var(--color-dark-blue);
        }
        .text-dark-blue {
            color: var(--color-dark-blue);
        }
        .bg-bright-yellow {
            background-color: var(--color-bright-yellow);
        }
        .text-bright-yellow {
            color: var(--color-bright-yellow);
        }
        .btn-primary {
            @apply bg-bright-yellow text-dark-blue font-semibold py-3 px-8 rounded-full shadow-lg hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1;
        }
        .btn-secondary {
            @apply bg-dark-blue text-white font-semibold py-3 px-8 rounded-full shadow-lg hover:shadow-xl transition-all duration-300 transform hover:-translate-y-1;
        }
        /* Enhanced animations */
        .fade-in-up {
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 0.8s ease-out forwards;
        }
        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .slide-in-left {
            opacity: 0;
            transform: translateX(-50px);
            animation: slideInLeft 0.8s ease-out forwards;
        }
        @keyframes slideInLeft {
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }
        .slide-in-right {
            opacity: 0;
            transform: translateX(50px);
            animation: slideInRight 0.8s ease-out forwards;
        }
        @keyframes slideInRight {
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }
        /* Testimonial carousel styles */
        .carousel-container {
            overflow: hidden;
            position: relative;
            width: 100%;
        }
        .carousel-track {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }
        .carousel-item {
            flex: 0 0 100%; /* Each item takes full width */
        }
        /* Parallax effect for hero image */
        .hero-image-parallax {
            background-image: url('https://placehold.co/600x400/003366/FFC300?text=Mesin+Cuci+%2B+Pakaian+Wangi+%2B+Orang+Senyum');
            background-size: cover;
            background-position: center;
            background-attachment: fixed; /* This creates the parallax effect */
            min-height: 400px; /* Ensure sufficient height for effect */
            width: 100%;
            border-radius: 0.75rem; /* rounded-lg */
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); /* shadow-xl */
        }

        /* Specific styles for card hover effects */
        .service-card, .advantage-card {
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
        }
        .service-card:hover, .advantage-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 25px -5px rgba(0, 0, 0, 0.15), 0 6px 10px -3px rgba(0, 0, 0, 0.08);
        }
    </style>
</head>
<body class="antialiased">
    <!-- Seluruh isi file menggunakan kode yang Anda kirimkan sebelumnya -->
    <!-- (Potong demi ringkas, silakan tempel seluruh kode Anda pada file ini) -->
</body>
</html>
