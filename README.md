    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

</head>

<body>
@@ -28,7 +27,7 @@ <h1>What?</h1>
            <p>Alls wells definitely end well</p>
        </div>

        <img src="https://media.phillyvoice.com/media/images/072723-spotify-taylor-swift-eras.1b1911fa.fill-735x490.jpg" alt="Lover era!" class="image">
        <img src="https://media.phillyvoice.com/media/images/072723-spotify-taylor-swift-eras.1b1911fa.fill-735x490.jpg" alt="Lover era!" class="image image-animated">
        <div class="center">
            <p>Additional centered text.</p>
        </div>
@@ -62,15 +61,11 @@ <h3>Album Display</h3>
    <p>Favorite album: <span class="block">Lover</span> Display: block</p>

    <script>
        const img = document.querySelector('.ok');
        const img = document.querySelector('.image');
        img.addEventListener('click', () => {
            img.style.width = '800px';
        });
    </script>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</body>

</html>
