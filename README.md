<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Greek Phrasebook (Green Edition)</title>
    <style>
        /* Base Styles and Colors */
        :root {
            --primary-green: #2ecc71; /* A bright, fresh green */
            --dark-green: #27ae60;    /* For headers and strong elements */
            --bg-color: #f0faf4;      /* Very pale green background */
            --text-color: #2c3e50;    /* Dark gray/blue for text */
            --border-color: #e0e0e0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            line-height: 1.6;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 10px; /* Reduced padding for mobile */
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(46, 204, 113, 0.1); /* Subtle green shadow */
        }

        h1 {
            color: var(--dark-green);
            text-align: center;
            border-bottom: 2px solid var(--primary-green);
            padding-bottom: 15px;
            margin-top: 0;
            font-size: 1.8rem;
        }

        h2 {
            color: var(--dark-green);
            margin-top: 25px;
            margin-bottom: 10px;
            font-size: 1.2rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 25px;
            background-color: white;
        }

        /* Desktop Table Styling */
        th, td {
            text-align: left;
            padding: 15px;
            border-bottom: 1px solid var(--border-color);
        }

        th {
            background-color: var(--primary-green);
            color: white;
            font-weight: 600;
        }

        /* Interacting Styles */
        tr:nth-child(even) {
            background-color: #fbfdfc; /* Alternate row color */
        }

        tr:hover {
            background-color: #f0fdf4; /* Row hover highlight */
        }

        /* Column specific styling */
        .col-english {
            width: 40%;
            color: #7f8c8d; /* Muted gray for English */
        }
        .col-greek {
            width: 60%;
        }

        .greek-text {
            font-weight: bold;
            color: var(--dark-green);
            font-size: 1.1rem;
            display: block; /* Ensures Greek is on its own line in card view */
        }

        .pronunciation {
            color: #666;
            font-style: italic;
            font-size: 0.95rem;
            display: block; /* Ensures Pronunciation is on its own line in card view */
            margin-top: 4px;
        }

        /* =========================================
           MOBILE RESPONSIVE STYLING (The Magic)
           ========================================= */
        @media screen and (max-width: 650px) {
            
            h1 { font-size: 1.5rem; }

            /* Hide table headers (but keep accessible) */
            table thead {
                display: none;
            }

            table, table tbody, table tr, table td {
                display: block;
                width: 100%;
            }

            /* Style each row like a separate 'card' */
            table tr {
                margin-bottom: 20px;
                background-color: white;
                border: 1px solid var(--border-color);
                border-radius: 8px;
                box-shadow: 0 2px 5px rgba(0,0,0,0.05);
                overflow: hidden; /* Fixes border radius */
            }

            /* Make alternate row coloring work as alternate card coloring instead */
            table tr:nth-child(even) {
                background-color: #fcfdfd;
            }

            /* Style the 'cells' (TDs) within the card */
            table td {
                padding: 15px;
                border-bottom: none;
                position: relative;
            }

            /* Top 'cell' of the card (the English phrase) */
            table td:first-child {
                border-bottom: 1px solid var(--border-color);
                background-color: #fafafa;
                font-size: 1rem;
                font-weight: 600;
                color: #555;
            }

            /* The Greek text (already has green color, just need to align) */
            .greek-text {
                margin-bottom: 5px;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>🇬🇷 Greek Phrasebook</h1>

    <h2>Daily Interactions & Logistics</h2>
    <table>
        <thead>
            <tr>
                <th>English</th>
                <th>Greek</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="col-english">Can you help me, please?</td>
                <td class="col-greek">
                    <span class="greek-text">Μπορείτε να με βοηθήσετε, παρακαλώ;</span>
                    <span class="pronunciation">(Bo-ree-te na me vo-ee-thee-se-te, pa-ra-ka-lo?)</span>
                </td>
            </tr>
            <tr>
                <td class="col-english">Excuse me, where’s the bathroom?</td>
                <td class="col-greek">
                    <span class="greek-text">Με συγχωρείτε, πού είναι η τουαλέτα;</span>
                    <span class="pronunciation">(Me sin-ho-ree-te, poo ee-ne ee toa-le-ta?)</span>
                </td>
            </tr>
            <tr>
                <td class="col-english">What time is it?</td>
                <td class="col-greek">
                    <span class="greek-text">Τι ώρα είναι;</span>
                    <span class="pronunciation">(Tee o-ra ee-ne?)</span>
                </td>
            </tr>
            <tr>
                <td class="col-english">Directions to the gas station?</td>
                <td class="col-greek">
                    <span class="greek-text">Οδηγίες για το βενζινάδικο;</span>
                    <span class="pronunciation">(O-thee-yee-es ya to ven-zee-na-thee-ko?)</span>
                </td>
            </tr>
            <tr>
                <td class="col-english">See you later / Goodbye</td>
                <td class="col-greek">
                    <span class="greek-text">Τα λέμε αργότερα / Αντίο</span>
                    <span class="pronunciation">(Ta le-me ar-go-te-ra / An-thee-o)</span>
                </td>
            </tr>
        </tbody>
    </table>

    <h2>Dining & Communication</h2>
    <table>
        <thead>
            <tr>
                <th>English</th>
                <th>Greek</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="col-english">The bill, please.</td>
                <td class="col-greek">
                    <span class="greek-text">Τον λογαριασμό, παρακαλώ.</span>
                    <span class="pronunciation">(Ton lo-ga-rya-smo, pa-ra-ka-lo)</span>
                </td>
            </tr>
            <tr>
                <td class="col-english">Can you tell me a joke?</td>
                <td class="col-greek">
                    <span class="greek-text">Μπορείς να μου πεις ένα ανέκδοτο;</span>
                    <span class="pronunciation">(Bo-rees na moo pees e-na a-nek-tho-to?)</span>
                </td>
            </tr>
            <tr>
                <td class="col-english">How was your day?</td>
                <td class="col-greek">
                    <span class="greek-text">Πώς ήταν η μέρα σου;</span>
                    <span class="pronunciation">(Pos ee-tan ee me-ra soo?)</span>
                </td>
            </tr>
            <tr>
                <td class="col-english">What’s the weather like?</td>
                <td class="col-greek">
                    <span class="greek-text">Τι καιρό κάνει;</span>
                    <span class="pronunciation">(Tee ke-ro ka-nee?)</span>
                </td>
            </tr>
        </tbody>
    </table>

</div>

</body>
</html>
