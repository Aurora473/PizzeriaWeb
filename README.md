# PizzeriaWeb
progetto di gruppo A-B-C
ogni sviluppatore deve aggiungere due portate nel proprio menu':
-sviluppatore a: assegnato al menu' pizze
-sviluppatore b:assegnato al menu' dolci 
-sviluppatore c:assegnato al menu' bevande
idex.html 
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PizzeriaWeb - Il nostro menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
        <h1>🍕 PizzeriaWeb</h1>
        <p>Il sapore della tradizione italiana</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="menu/pizze.html">Pizze</a>
        <a href="menu/dolci.html">Dolci</a>
        <a href="menu/bevande.html">Bevande</a>
    </nav>

    <main>
        <h2>Benvenuti nella nostra pizzeria!</h2>
        <p>Scoprite le nostre proposte preparate con passione.</p>

        <section class="categorie">
            <article class="card">
                <h3>🍕 Menu pizze</h3>
                <p>Le nostre pizze, classiche e gustose.</p>
                <a class="bottone" href="menu/pizze.html">Scopri le pizze</a>
            </article>

            <article class="card">
                <h3>🍰 Menu dolci</h3>
                <p>Un finale dolce per ogni pasto.</p>
                <a class="bottone" href="menu/dolci.html">Scopri i dolci</a>
            </article>

            <article class="card">
                <h3>🥤 Menu bevande</h3>
                <p>Bevande per accompagnare ogni portata.</p>
                <a class="bottone" href="menu/bevande.html">Scopri le bevande</a>
            </article>
        </section>
    </main>

    <footer>
        <p>Progetto di gruppo A-B-C | PizzeriaWeb</p>
    </footer>

</body>
</html>


<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Pizze - PizzeriaWeb</title>
    <link rel="stylesheet" href="../style.css">
</head>
<body>
    <header>
        <h1>🍕 Menu Pizze</h1>
        <p>Sviluppatore A</p>
    </header>

    <nav>
        <a href="../index.html">Home</a>
        <a href="pizze.html">Pizze</a>
        <a href="dolci.html">Dolci</a>
        <a href="bevande.html">Bevande</a>
    </nav>

<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Dolci - PizzeriaWeb</title>
    <link rel="stylesheet" href="../style.css">
</head>
<body>
    <header>
        <h1>🍰 Menu Dolci</h1>
        <p>Sviluppatore B</p>
    </header>

    <nav>
        <a href="../index.html">Home</a>
        <a href="pizze.html">Pizze</a>
        <a href="dolci.html">Dolci</a>
        <a href="bevande.html">Bevande</a>
        </nav>

    <main>
        <h2>I nostri dolci</h2>

        <section class="categorie">
            <article class="card">
                <h3>Tiramisù</h3>
                <p>Savoiardi, caffè, mascarpone e cacao.</p>
                <p class="prezzo">€ 5,00</p>
            </article>

            <article class="card">
                <h3>Cheesecake</h3>
                <p>Crema al formaggio e base croccante di biscotti.</p>
                <p class="prezzo">€ 5,50</p>
            </article>
        </section>
    </main>
    
    <footer>
        <a href="../index.html">Torna alla home</a>
    </footer>
</body>
</html>
