<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="default">
    <meta name="apple-mobile-web-app-title" content="Formation Éso">
    <title>Formation Ésotérisme - Programme</title>
    <style>
        /* Palette douce et blocs bien séparés pour les profils TDA */
        :root {
            --bg-color: #f4f1ea;
            --card-bg: #ffffff;
            --block-bg: #f9f8f6;
            --primary: #4a3b5c;
            --primary-light: #efeaf6;
            --accent: #c59b27;
            --text-main: #2c2c2c;
            --text-muted: #666666;
            --border-color: #e6e2d8;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            padding: 20px 15px 110px 15px;
            line-height: 1.55;
        }

        .container {
            max-width: 580px;
            margin: 0 auto;
        }

        header {
            text-align: center;
            margin-bottom: 22px;
        }

        h1 {
            color: var(--primary);
            font-size: 1.55rem;
            margin: 0 0 4px 0;
        }

        .subtitle {
            color: var(--text-muted);
            font-size: 0.95rem;
            margin: 0;
        }

        /* Niveau 1 : Sélection des 4 Week-ends */
        .we-tabs {
            display: flex;
            gap: 8px;
            margin-bottom: 14px;
        }

        .we-btn {
            flex: 1;
            padding: 12px 6px;
            border: 2px solid var(--primary);
            background: #ffffff;
            color: var(--primary);
            border-radius: 12px;
            font-weight: 700;
            font-size: 0.95rem;
            cursor: pointer;
            transition: all 0.2s ease;
        }

        .we-btn.active {
            background: var(--primary);
            color: #ffffff;
        }

        /* Niveau 2 : Sélection Samedi / Dimanche */
        .day-tabs {
            display: flex;
            gap: 8px;
            margin-bottom: 20px;
            background: #e8e3d9;
            padding: 5px;
            border-radius: 12px;
        }

        .day-btn {
            flex: 1;
            padding: 10px;
            border: none;
            background: transparent;
            color: var(--text-main);
            border-radius: 9px;
            font-weight: 700;
            font-size: 0.95rem;
            cursor: pointer;
            transition: all 0.2s ease;
        }

        .day-btn.active {
            background: #ffffff;
            color: var(--primary);
            box-shadow: 0 2px 6px rgba(0,0,0,0.08);
        }

        /* Carte principale */
        .card {
            background: var(--card-bg);
            border-radius: 18px;
            padding: 22px;
            box-shadow: 0 4px 14px rgba(0,0,0,0.06);
            animation: fadeIn 0.25s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(4px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .badge {
            display: inline-block;
            background: var(--primary-light);
            color: var(--primary);
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 700;
            margin-bottom: 10px;
        }

        h2 {
            margin: 0 0 18px 0;
            color: var(--primary);
            font-size: 1.35rem;
            line-height: 1.3;
        }

        /* Blocs structurés */
        .section-block {
            background: var(--block-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 14px 16px;
            margin-bottom: 14px;
        }

        .section-title {
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            color: var(--primary);
            font-weight: 700;
            margin: 0 0 8px 0;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .info-line {
            margin: 4px 0;
            font-size: 0.95rem;
        }

        /* Boutons d'action rapides */
        .action-links {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 10px;
        }

        .btn-small {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            background: #ffffff;
            border: 1.5px solid var(--primary);
            color: var(--primary);
            text-decoration: none;
            padding: 7px 12px;
            border-radius: 8px;
            font-size: 0.88rem;
            font-weight: 600;
        }

        .btn-maps {
            background: var(--primary);
            color: #ffffff;
        }

        /* Liste du matériel */
        .materiel-list {
            margin: 0;
            padding-left: 20px;
            font-size: 0.95rem;
        }

        .materiel-list li {
            margin-bottom: 4px;
        }

        /* Boutons ressources */
        .btn-resource {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            background: var(--accent);
            color: #ffffff;
            text-decoration: none;
            padding: 13px 16px;
            border-radius: 10px;
            font-weight: 700;
            font-size: 0.95rem;
            margin-top: 8px;
        }

        /* Bannière discrète d'installation mobile */
        .install-banner {
            position: fixed;
            bottom: 12px;
            left: 12px;
            right: 12px;
            max-width: 556px;
            margin: 0 auto;
            background: var(--primary);
            color: #ffffff;
            padding: 12px 16px;
            border-radius: 14px;
            box-shadow: 0 6px 20px rgba(0,0,0,0.2);
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 12px;
            font-size: 0.85rem;
            z-index: 100;
        }

        .install-text strong {
            display: block;
            font-size: 0.9rem;
            margin-bottom: 2px;
            color: #f7d97e;
        }

        .close-banner {
            background: rgba(255,255,255,0.2);
            border: none;
            color: #ffffff;
            width: 28px;
            height: 28px;
            border-radius: 50%;
            font-weight: bold;
            cursor: pointer;
            flex-shrink: 0;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>✨ Formation Ésotérisme</h1>
        <p class="subtitle">Programme détaillé sur 4 week-ends</p>
    </header>

    <!-- Boutons des 4 Week-ends -->
    <div class="we-tabs">
        <button class="we-btn active" onclick="selectWeekend(1)">WE 1</button>
        <button class="we-btn" onclick="selectWeekend(2)">WE 2</button>
        <button class="we-btn" onclick="selectWeekend(3)">WE 3</button>
        <button class="we-btn" onclick="selectWeekend(4)">WE 4</button>
    </div>

    <!-- Boutons Samedi / Dimanche -->
    <div class="day-tabs">
        <button class="day-btn active" onclick="selectDay('samedi')">Samedi</button>
        <button class="day-btn" onclick="selectDay('dimanche')">Dimanche</button>
    </div>

    <!-- Contenu dynamique du jour sélectionné -->
    <div id="content-card" class="card"></div>
</div>

<!-- Bannière d'aide à l'installation sur téléphone -->
<div id="install-banner" class="install-banner">
    <div class="install-text">
        <strong>📲 Garder l'appli sur votre téléphone</strong>
        iPhone : appuyez sur <b>Partager</b> puis <b>Sur l'écran d'accueil</b>.<br>
        Android : appuyez sur <b>⋮</b> puis <b>Ajouter à l'écran d'accueil</b>.
    </div>
    <button class="close-banner" onclick="closeBanner()" aria-label="Fermer">✕</button>
</div>

<script>
    // PERSONNALISEZ VOS INFORMATIONS CI-DESSOUS POUR CHAQUE JOUR
    const programme = {
        1: {
            samedi: {
                titre: "Ancrage & Bases énergétiques",
                date: "Date à venir",
                horaires: "09h30 - 17h30",
                lieuNom: "Espace Lumière",
                adresse: "14 Rue des Lilas, 1000 Lausanne",
                lienMaps: "https://google.com",
                enseignantPrenom: "Claire",
                enseignantNom: "Martin",
                enseignantTel: "+41 79 123 45 67",
                enseignantMail: "claire.martin@exemple.ch",
                materiel: [
                    "Un cahier de notes et un stylo",
                    "Une bouteille d'eau",
                    "Des chaussettes chaudes ou chaussons",
                    "Un coussin de méditation (si vous en avez un)"
                ],
                description: "Accueil du groupe, compréhension des corps subtils, ressenti de l'énergie dans les mains et exercices pratiques d'ancrage à la Terre.",
                ressources: [
                    { titre: "Support de cours - WE 1 Samedi (PDF)", lien: "#" },
                    { titre: "Audio guidé : Méditation d'ancrage", lien: "#" }
                ]
            },
            dimanche: {
                titre: "Protection & Nettoyage de l'aura",
                date: "Date à venir",
                horaires: "09h30 - 17h00",
                lieuNom: "Espace Lumière",
                adresse: "14 Rue des Lilas, 1000 Lausanne",
                lienMaps: "https://google.com",
                enseignantPrenom: "Claire",
