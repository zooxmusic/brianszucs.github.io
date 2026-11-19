<!DOCTYPE html>
<html lang="en">
<head>
    <title>{{ page.title }} | Brian Szucs</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://googleapis.com" rel="stylesheet">
    <script defer src="{{ '/assets/fontawesome/js/all.min.js' | relative_url }}"></script>
    <link rel="stylesheet" href="{{ '/assets/plugins/bootstrap/css/bootstrap.min.css' | relative_url }}">
    <link id="theme-style" rel="stylesheet" href="{{ '/assets/css/orbit-6.css' | relative_url }}">
</head>
<body>
    <header>
        <nav class="site-nav" aria-label="Main navigation">
            <a class="nav-tab" href="{{ '/' | relative_url }}">← Back to Resume / Articles</a>
        </nav>
    </header>
    <div class="wrapper mt-lg-5">
        {% include sidebar.html %}
        <div class="main-wrapper">
            <section class="section">
                <h1 class="section-title">{{ page.title }}</h1>
                {% if page.date %}
                <div class="text-muted mb-3">{{ page.date | date: "%B %-d, %Y" }}</div>
                {% endif %}
                {% if page.image %}
                <img class="img-fluid rounded mb-4" src="{{ page.image | relative_url }}" alt="{{ page.title | escape }}">
                {% endif %}
                <div class="post-content">
                    {{ content }}
                </div>
            </section>
        </div>
    </div>
</body>
</html>
