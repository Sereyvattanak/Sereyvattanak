<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Template</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/owl-carousel/1.3.3/owl.carousel.min.css">
    <style>
        :root {
            --primary: #00B87B;
            --secondary: #314355;
            --light: #F2F2F2;
            --dark: #2C3E50;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: var(--light);
        }

        #spinner {
            opacity: 0;
            visibility: hidden;
            transition: opacity .5s ease-out, visibility 0s linear .5s;
            z-index: 99999;
        }

        #spinner.show {
            transition: opacity .5s ease-out, visibility 0s linear 0s;
            visibility: visible;
            opacity: 1;
        }

        .fw-semi-bold {
            font-weight: 600;
        }

        .fw-medium {
            font-weight: 500;
        }

        .btn-square {
            width: 40px;
            height: 40px;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .btn-primary {
            background: var(--primary);
            color: #FFFFFF;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        .title {
            position: relative;
        }

        .title::before {
            position: absolute;
            content: "";
            width: 10px;
            height: 10px;
            bottom: -4px;
            left: 0;
            border: 2px solid var(--light);
            border-radius: 10px;
        }

        .title::after {
            position: absolute;
            content: "";
            width: 50px;
            height: 2px;
            bottom: 0;
            left: 15px;
            border-radius: 2px;
            background: var(--light);
        }

        .service-item {
            padding: 30px;
            text-align: center;
            background: var(--secondary);
        }

        .service-item i {
            width: 75px;
            height: 75px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: var(--light);
            color: var(--primary);
            transition: .5s;
        }

        .service-item:hover i {
            background: var(--primary);
            color: var(--light);
        }
    </style>
</head>
<body>
    <div id="spinner" class="show">Loading...</div>
    
    <header>
        <h1 class="title">Welcome to the Styled Template</h1>
    </header>

    <section class="service-item">
        <i class="fas fa-cog"></i>
        <h2>Service Title</h2>
        <p>Service description goes here.</p>
    </section>

    <button class="btn-primary">Click Me</button>

    <script>
        document.addEventListener("DOMContentLoaded", function() {
            setTimeout(() => {
                document.getElementById("spinner").classList.remove("show");
            }, 2000);
        });
    </script>
</body>
</html>
