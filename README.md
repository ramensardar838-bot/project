<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SEO project</title>
</head>

<style>
    /* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

/* Body */
body {
    background: linear-gradient(135deg, #0f4c81, #c1121f);
    color: #ffffff;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
}

/* Header */
header {
    background: rgba(0, 0, 0, 0.25);
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

/* Logo */
header div:first-child {
    font-size: 1.6rem;
    font-weight: bold;
    color: #ffeb3b;
}

/* Navigation */
header a {
    margin-left: 20px;
    color: #ffffff;
    text-decoration: none;
    font-weight: bold;
    position: relative;
    transition: 0.3s;
}

/* Hover underline */
header a::after {
    content: "";
    position: absolute;
    width: 0;
    height: 2px;
    background: #ff4d4d;
    left: 0;
    bottom: -5px;
    transition: 0.3s;
}

header a:hover::after {
    width: 100%;
}

/* Main */
main {
    flex: 1;
    display: flex;
    align-items: center;
    justify-content: center;
}

main h4 {
    font-size: 2rem;
    background: rgba(255, 255, 255, 0.15);
    padding: 20px 40px;
    border-radius: 12px;
}

/* Footer */
footer {
    background: rgba(0, 0, 0, 0.3);
    padding: 20px 40px;
    font-size: 0.9rem;
    line-height: 1.6;
    text-align: center;
    color: #e0e0e0;
}

</style>
<body>
    <header>
        <div>Logic</div>
        <div>
            <a href="/Home" target="_main">Home</a>
            <a href="/Product" target="_main">Product</a>
            <a href="/Contact" target="_main">Contact</a>
        </div>
    </header>

    <main>
        <h4>Hi !</h4>
    </main>

    <footer>
        Welcome all of you to my website , Logic!
        Hey! Let's fun together with coding!
    </footer>
</body>
</html>
