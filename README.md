
<html lang="hu">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Health and Fitness Cards</title>  
    <script src="https://cdn.tailwindcss.com"></script>  
    <style>  
        .card {  
            perspective: 1000px;  
        }  
        .card-inner {  
            position: relative;  
            width: 100%;  
            height: 100%;  
            transition: transform 0.6s;  
            transform-style: preserve-3d;  
        }  
        .card-front, .card-back {  
            position: absolute;  
            width: 100%;  
            height: 100%;  
            backface-visibility: hidden;  
            border-radius: 10px;  
        }  
        .card-front {  
            background-size: cover;  
            background-position: center;  
            display: flex;  
            align-items: flex-end;  
            justify-content: center;  
            padding: 20px;  
            color: white;  
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7);  
        }  
        .card-back {  
            background-color: #f7fafc;  
            transform: rotateY(180deg);  
            padding: 20px;  
            display: flex;  
            flex-direction: column;  
            justify-content: center;  
        }  
        .card:hover .card-inner {  
            transform: rotateY(180deg);  
        }  
    </style>  
</head>  
<body class="bg-gray-200 p-10">  
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">  
        <div class="card h-64">  
            <div class="card-inner">  
                <div class="card-front" style="background-image: url('https://i.postimg.cc/87JwmL5F/health-fitness.jpg');">  
                    <h2 class="text-xl font-bold">Health and Fitness</h2>  
                </div>  
                <div class="card-back">  
                    <h3 class="text-lg font-semibold">Tips:</h3>  
                    <ul class="list-disc pl-5">  
                        <li>Exercise regularly (e.g., 3-4 times a week).</li>  
                        <li>Eat more fruits and vegetables.</li>  
                        <li>Drink more water daily.</li>  
                        <li>Get at least 7-8 hours of sleep each night.</li>  
                    </ul>  
                </div>  
            </div>  
        </div>  
        <div class="card h-64">  
            <div class="card-inner">  
                <div class="card-front" style="background-image: url('https://i.postimg.cc/DWYjTFzN/personal-development.jpg');">  
                    <h2 class="text-xl font-bold">Personal Development</h2>  
                </div>  
                <div class="card-back">  
                    <h3 class="text-lg font-semibold">Tips:</h3>  
                    <ul class="list-disc pl-5">  
                        <li>Read a certain number of books each month.</li>  
                        <li>Learn a new skill or hobby.</li>  
                        <li>Take a course to advance your career.</li>  
                        <li>Practice mindfulness or meditation regularly.</li>  
                    </ul>  
                </div>  
            </div>  
        </div>  
        <div class="card h-64">  
            <div class="card-inner">  
                <div class="card-front" style="background-image: url('https://i.postimg.cc/dhVjtXgc/financial-goals.jpg');">  
                    <h2 class="text-xl font-bold">Financial Goals</h2>  
                </div>  
                <div class="card-back">  
                    <h3 class="text-lg font-semibold">Tips:</h3>  
                    <ul class="list-disc pl-5">  
                        <li>Create and stick to a budget.</li>  
                        <li>Save a certain percentage of your income.</li>  
                        <li>Pay off debt or reduce unnecessary expenses.</li>  
                        <li>Start investing or increase contributions to a retirement fund.</li>  
                    </ul>  
                </div>  
            </div>  
        </div>  
        <div class="card h-64">  
            <div class="card-inner">  
                <div class="card-front" style="background-image: url('https://i.postimg.cc/F1m4Cg2J/professional-growth.jpg');">  
                    <h2 class="text-xl font-bold">Professional Growth</h2>  
                </div>  
                <div class="card-back">  
                    <h3 class="text-lg font-semibold">Tips:</h3>  
                    <ul class="list-disc pl-5">  
                        <li>Set specific career goals, such as a promotion or new role.</li>  
                        <li>Network more within your industry.</li>  
                        <li>Enhance your skills with training or certifications.</li>  
                        <li>Improve work-life balance.</li>  
                    </ul>  
                </div>  
            </div>  
        </div>  
        <div class="card h-64">  
            <div class="card-inner">  
                <div class="card-front" style="background-image: url('https://i.postimg.cc/YhKmsVtz/social-relationships.jpg');">  
                    <h2 class="text-xl font-bold">Social and Relationships</h2>  
                </div>  
                <div class="card-back">  
                    <h3 class="text-lg font-semibold">Tips:</h3>  
                    <ul class="list-disc pl-5">  
                        <li>Spend more quality time with family and friends.</li>  
                        <li>Volunteer for a cause you care about.</li>  
                        <li>Meet new people or join a club or group.</li>  
                        <li>Improve communication skills.</li>  
                    </ul>  
                </div>  
            </div>  
        </div>  
        <div class="card h-64">  
            <div class="card-inner">  
                <div class="card-front" style="background-image: url('https://i.postimg.cc/4KSYb28t/environmental-lifestyle-changes.jpg');">  
                    <h2 class="text-xl font-bold">Environmental and Lifestyle Changes</h2>  
                </div>  
                <div class="card-back">  
                    <h3 class="text-lg font-semibold">Tips:</h3>  
                    <ul class="list-disc pl-5">  
                        <li>Reduce waste and recycle more.</li>  
                        <li>Use public transportation or cycle more often.</li>  
                        <li>Declutter and organize your living space.</li>  
                        <li>Travel to a new place or explore local attractions.</li>  
                    </ul>  
                </div>  
            </div>  
        </div>  
    </div>  
</body>  
</html>
