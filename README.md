<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Informace o chovu králíků beranů - péče, výživa a tipy pro začátečníky.">
    <title>Chov králíků beranů</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #4caf50;
            color: white;
            padding: 20px 10px;
            text-align: center;
            border-bottom: 5px solid #3e8e41;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            text-transform: uppercase;
        }

        nav {
            text-align: center;
            margin: 20px 0;
        }

        nav a {
            text-decoration: none;
            color: #4caf50;
            font-weight: bold;
            margin: 0 15px;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #3e8e41;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            flex: 1 1 calc(50% - 20px);
            overflow: hidden;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            height: auto;
            display: block;
        }

        .card h2 {
            font-size: 1.5rem;
            margin: 10px;
            color: #4caf50;
        }

        .card p {
            font-size: 1rem;
            margin: 10px;
            line-height: 1.6;
        }

        footer {
            text-align: center;
            padding: 10px;
            background: #4caf50;
            color: white;
            margin-top: 20px;
            border-top: 5px solid #3e8e41;
        }
    </style>
</head>
<body>
    <header>
        <h1>Chov králíků beranů</h1>
        <p>Průvodce péčí a chovem tohoto úžasného plemene.</p>
    </header>

    <nav>
        <a href="#o-plemenu">O plemenu</a>
        <a href="#pece">Péče</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <div class="container">
        <section class="content">
            <div class="card">
                <img src="https://example.com/kralik1.jpg" alt="Králík beran v trávě">
                <h2>O plemenu</h2>
                <p>Králíci berani jsou známí svými dlouhými převislými ušima a klidnou povahou. Jsou skvělou volbou pro chovatele hledající mazlíčka.</p>
            </div>

            <div class="card">
                <img src="https://example.com/kralik2.jpg" alt="Králík beran v králíkárně">
                <h2>Péče</h2>
                <p>Péče o králíky berany zahrnuje několik klíčových oblastí:
                    <ul>
                        <li><strong>Výživa:</strong> Krmte králíky kvalitním senem, granulemi pro králíky a čerstvou zeleninou. Vyvarujte se škodlivých potravin, jako je čokoláda nebo pečivo.</li>
                        <li><strong>Čistota:</strong> Pravidelně čistěte kotec a zajistěte čerstvé stelivo. Hygiena je důležitá pro prevenci nemocí.</li>
                        <li><strong>Zdraví:</strong> Sledujte zdravotní stav svého králíka. Pravidelné kontroly u veterináře jsou důležité, zejména očkování a odčervení.</li>
                        <li><strong>Pohyb:</strong> Poskytněte králíkům dostatek prostoru pro pohyb, ideálně výběh na zahradě nebo bezpečné místo uvnitř.</li>
                        <li><strong>Socializace:</strong> Králíci jsou společenská zvířata, a pokud nemají jiného králíka, věnujte jim dostatek času.</li>
                    </ul>
                </p>
                <p>Dodržováním těchto pravidel zajistíte svému králíkovi šťastný a zdravý život.</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Chov králíků beranů. Všechna práva vyhrazena.</p>
    </footer>
</body>
</html>
