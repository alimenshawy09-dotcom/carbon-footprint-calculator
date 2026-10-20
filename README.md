# carbon-footprint-calculator
My Computer Science project: a Carbon Footprint Calculator website built using HTML, CSS, and Bootstrap.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carbon Footprint Calculator</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f8f5;
            color: #222;
        }

        .hero {
            padding: 45px 20px;
            text-align: center;
        }

        h1 {
            color: #247a43;
            font-weight: bold;
        }

        h2 {
            margin-top: 15px;
            color: #333;
        }

        .environment-image {
            width: 100%;
            max-height: 400px;
            object-fit: cover;
            border-radius: 10px;
        }

        .content {
            padding: 25px;
        }

        .calculate-link {
            color: #0d6efd;
            font-size: 20px;
            font-weight: bold;
        }
    </style>
</head>

<body>
    <div class="container-fluid">
        <div class="row">
            <div class="col-12 hero">
                <h1>Carbon Footprint Calculator</h1>
                <h2>Climate change is real!!</h2>
            </div>
        </div>

        <div class="row align-items-center content">
            <div class="col-md-6">
                <p>
                    Climate change is one of the biggest challenges facing
                    our planet. Our daily activities can release greenhouse
                    gases into the atmosphere and contribute to global warming.
                    We can all take steps to protect the environment.
                </p>

                <h4>Discover your carbon footprint!</h4>

                <p>
                    Find out how your lifestyle affects the environment.
                    Assess your carbon footprint and learn how small changes
                    can help create a cleaner and greener future.
                </p>

                <a href="#calculator" class="calculate-link">Calculate</a>
            </div>

            <div class="col-md-6 mt-4 mt-md-0">
                <img
                    src="https://images.unsplash.com/photo-1448375240586-882707db888b"
                    alt="Green forest representing a healthy environment"
                    class="environment-image"
                >
            </div>
        </div>

        <div class="row content" id="calculator">
            <div class="col-12 text-center">
                <h3>Start Thinking Green</h3>
                <p>
                    Every small action matters. Save energy, reduce waste,
                    and make environmentally friendly choices.
                </p>
            </div>
        </div>
    </div>
</body>
</html>
