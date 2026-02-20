<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Internship Task 1 - Level 2</title>
    <!-- Bulma CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.3/css/bulma.min.css">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --pastel-pink: #ffd6e0;
            --pastel-blue: #c1e7ff;
            --pastel-green: #d4f1d4;
            --pastel-purple: #e6d4ff;
            --pastel-yellow: #fff5c1;
            --pastel-peach: #ffdfd1;
        }

        body {
            background-color: #fafafa;
            font-family: 'Nunito', sans-serif;
            padding: 2rem 0;
        }

        .header {
            text-align: center;
            margin-bottom: 3rem;
        }

        .title {
            color: #6b6b6b;
            font-weight: 700;
            margin-bottom: 1rem;
        }

        .subtitle {
            color: #9b9b9b;
            max-width: 600px;
            margin: 0 auto;
        }

        .card {
            border-radius: 12px;
            overflow: hidden;
            transition: all 0.3s ease;
            height: 100%;
            border: none;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }

        .card-image {
            height: 180px;
            overflow: hidden;
        }

        .card-image img {
            object-fit: cover;
            width: 100%;
            height: 100%;
            transition: transform 0.5s ease;
        }

        .card:hover .card-image img {
            transform: scale(1.05);
        }

        .card-content {
            padding: 1.5rem;
        }

        .card-title {
            font-size: 1.25rem;
            font-weight: 600;
            margin-bottom: 0.75rem;
            color: #5a5a5a;
        }

        .card-text {
            color: #7a7a7a;
            margin-bottom: 1rem;
            line-height: 1.5;
        }

        .card-footer-item {
            font-weight: 500;
            color: #6b6b6b;
            transition: color 0.3s ease;
        }

        .card-footer-item:hover {
            color: #4a4a4a;
        }

        /* Pastel color classes */
        .bg-pastel-pink {
            background-color: var(--pastel-pink);
        }

        .bg-pastel-blue {
            background-color: var(--pastel-blue);
        }

        .bg-pastel-green {
            background-color: var(--pastel-green);
        }

        .bg-pastel-purple {
            background-color: var(--pastel-purple);
        }

        .bg-pastel-yellow {
            background-color: var(--pastel-yellow);
        }

        .bg-pastel-peach {
            background-color: var(--pastel-peach);
        }

        .footer {
            margin-top: 3rem;
            padding: 2rem 0;
            background-color: #f5f5f5;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="header">
            <h1 class="title is-2">Pastel Card Collection</h1>
            <p class="subtitle is-5">Beautiful responsive cards in soothing pastel colors</p>
        </div>

        <div class="columns is-multiline">
            <!-- Card 1 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-pink">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="Mountain landscape">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Mountain Retreat</h3>
                        <p class="card-text">Escape to the serene mountains where the air is fresh and the views are
                            breathtaking. Perfect for relaxation and adventure alike.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-blue">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1505142468610-359e7d316be0?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="Beach sunset">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Beach Paradise</h3>
                        <p class="card-text">Feel the sand between your toes and watch the sunset over the ocean. Our
                            beach destinations offer the ultimate relaxation.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-green">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1470114716159-e389f8712fda?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="Forest path">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Forest Walk</h3>
                        <p class="card-text">Immerse yourself in nature with our guided forest walks. Discover hidden
                            waterfalls and ancient trees in their natural habitat.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>

            <!-- Card 4 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-purple">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1483729558449-99ef09a8c325?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="City skyline">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">City Lights</h3>
                        <p class="card-text">Experience the vibrant energy of the city that never sleeps. From rooftop
                            bars to underground jazz clubs, we've got you covered.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>

            <!-- Card 5 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-yellow">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1506260408121-e353d10b87c7?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="Desert dunes">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Desert Adventure</h3>
                        <p class="card-text">Explore the vast golden dunes on camelback or try sandboarding for an
                            adrenaline rush. Camp under the stars in luxury tents.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>

            <!-- Card 6 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-peach">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1476514525535-07fb3b4ae5f1?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="Countryside">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Countryside Escape</h3>
                        <p class="card-text">Slow down and enjoy the simple pleasures of rural life. Farm-to-table
                            dining, cycling routes, and charming cottages await.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>

            <!-- Card 7 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-blue">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1532339142463-fd0a8979791a?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="Island getaway">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Island Getaway</h3>
                        <p class="card-text">Private beaches, crystal clear waters, and luxury villas. Your perfect
                            island vacation is just a click away.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>

            <!-- Card 8 -->
            <div class="column is-one-third-tablet is-one-quarter-desktop">
                <div class="card bg-pastel-green">
                    <div class="card-image">
                        <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
                            alt="Lakeside view">
                    </div>
                    <div class="card-content">
                        <h3 class="card-title">Lakeside Serenity</h3>
                        <p class="card-text">Wake up to misty mornings on the lake. Perfect for fishing, kayaking, or
                            simply enjoying the peaceful surroundings.</p>
                    </div>
                    <footer class="card-footer">
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-heart"></i></span>
                            <span>Save</span>
                        </a>
                        <a href="#" class="card-footer-item">
                            <span class="icon"><i class="fas fa-share-alt"></i></span>
                            <span>Share</span>
                        </a>
                    </footer>
                </div>
            </div>
        </div>
    </div>

    <footer class="footer">
        <div class="content has-text-centered">
            <p>
                <strong>Pastel Card Grid</strong> by <a href="#">Creative Designs</a>.
                The source code is licensed <a href="#">MIT</a>.
            </p>
        </div>
    </footer>

    <script>
        // Add some interactive effects
        document.addEventListener('DOMContentLoaded', () => {
            // Get all cards
            const cards = document.querySelectorAll('.card');

            // Add click effect
            cards.forEach(card => {
                card.addEventListener('click', function () {
                    this.style.transform = 'scale(0.98)';
                    setTimeout(() => {
                        this.style.transform = 'translateY(-5px)';
                    }, 150);
                });

                // Add mouse enter/leave effects for the footer items
                const footerItems = this.querySelectorAll('.card-footer-item');
                footerItems.forEach(item => {
                    item.addEventListener('mouseenter', () => {
                        const icon = item.querySelector('.icon i');
                        icon.style.transform = 'scale(1.2)';
                    });

                    item.addEventListener('mouseleave', () => {
                        const icon = item.querySelector('.icon i');
                        icon.style.transform = 'scale(1)';
                    });
                });
            });

            // Randomly assign pastel colors if you want more variety
            // const pastelColors = ['pink', 'blue', 'green', 'purple', 'yellow', 'peach'];
            // cards.forEach(card => {
            //     const randomColor = pastelColors[Math.floor(Math.random() * pastelColors.length)];
            //     card.classList.add(`bg-pastel-${randomColor}`);
            // });
        });
    </script>
</body>

</html>
