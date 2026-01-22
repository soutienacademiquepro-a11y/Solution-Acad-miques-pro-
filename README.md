git clone https://github.com/Soutien Académie pro/soutien-academique-pro.git
cd soutien-academique-pro
cat > index.html << 'EOF'
<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Soutien Académique Pro+ | Réussite Garantie pour Étudiants Béninois</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
</head>
<body class="bg-gray-50 text-gray-800 font-sans antialiased">

  <!-- Hero Section -->
  <header class="bg-gradient-to-br from-blue-900 to-indigo-900 text-white">
    <div class="container mx-auto px-6 py-20 md:py-32 text-center">
      <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6">
        Votre Réussite Académique<br/><span class="text-yellow-400">Notre Priorité Absolue</span>
      </h1>
      <p class="text-xl md:text-2xl mb-10 max-w-3xl mx-auto">
        Résumés de cours, protocoles de recherche, mémoires corrigés, CV pro... Accompagnement 100% personnalisé et confidentiel pour étudiants au Bénin.
      </p>
      <a href="https://wa.me/22944218514?text=Bonjour%20!%20Je%20souhaite%20un%20accompagnement%20académique" 
         class="inline-block bg-yellow-400 text-blue-900 font-bold text-lg px-10 py-5 rounded-full shadow-lg hover:bg-yellow-300 transition transform hover:-translate-y-1">
        <i class="fab fa-whatsapp mr-2"></i> Commencer sur WhatsApp maintenant
      </a>
      <p class="mt-6 text-lg">+500 étudiants satisfaits • Note 4.9/5 • Paiement Mobile Money flexible</p>
    </div>
  </header>

  <!-- Stats Rapides -->
  <section class="py-16 bg-white">
    <div class="container mx-auto px-6 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
      <div>
        <p class="text-5xl font-bold text-indigo-700">500+</p>
        <p class="text-gray-600">Étudiants aidés</p>
      </div>
      <div>
        <p class="text-5xl font-bold text-indigo-700">1000+</p>
        <p class="text-gray-600">Projets réalisés</p>
      </div>
      <div>
        <p class="text-5xl font-bold text-indigo-700">4.9/5</p>
        <p class="text-gray-600">Note moyenne</p>
      </div>
      <div>
        <p class="text-5xl font-bold text-indigo-700">Bénin</p>
        <p class="text-gray-600">Partout au pays</p>
      </div>
    </div>
  </section>

  <!-- Packs en Cartes -->
  <section class="py-20 bg-gray-100">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Nos Packs Adaptés à Vos Besoins</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <!-- Pack Essentiel -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden transform hover:scale-105 transition">
          <div class="bg-indigo-600 text-white py-6 text-center">
            <h3 class="text-2xl font-bold">Pack Essentiel</h3>
            <p class="text-4xl font-extrabold mt-2">6 000 FCFA</p>
            <span class="inline-block bg-yellow-400 text-blue-900 px-4 py-1 rounded-full mt-2 text-sm font-bold">Populaire</span>
          </div>
          <ul class="p-8 space-y-4 text-center">
            <li>Résumé cours (10-20 pages)</li>
            <li>Fiche de révision simple</li>
            <li>Création / optimisation CV</li>
          </ul>
          <div class="p-6 border-t">
            <a href="https://wa.me/22944218514?text=Bonjour,%20je%20veux%20le%20Pack%20Essentiel" class="block bg-indigo-600 text-white py-4 rounded-lg text-center font-bold hover:bg-indigo-700">Choisir ce pack</a>
          </div>
        </div>

        <!-- Pack Standard -->
        <div class="bg-white rounded-2xl shadow-2xl overflow-hidden transform hover:scale-105 transition border-4 border-yellow-400 relative">
          <div class="absolute top-4 right-4 bg-yellow-400 text-blue-900 px-4 py-1 rounded-full font-bold">Meilleur choix</div>
          <div class="bg-indigo-700 text-white py-6 text-center">
            <h3 class="text-2xl font-bold">Pack Standard</h3>
            <p class="text-4xl font-extrabold mt-2">12 000 FCFA</p>
          </div>
          <ul class="p-8 space-y-4 text-center">
            <li>Protocole recherche complet</li>
            <li>Résumé cours détaillé (20-40p)</li>
            <li>Correction partielle mémoire</li>
          </ul>
          <div class="p-6 border-t">
            <a href="https://wa.me/22944218514?text=Bonjour,%20je%20veux%20le%20Pack%20Standard" class="block bg-indigo-700 text-white py-4 rounded-lg text-center font-bold hover:bg-indigo-800">Choisir ce pack</a>
          </div>
        </div>

        <!-- Pack Premium -->
        <div class="bg-white rounded-2xl shadow-xl overflow-hidden transform hover:scale-105 transition">
          <div class="bg-indigo-800 text-white py-6 text-center">
            <h3 class="text-2xl font-bold">Pack Premium</h3>
            <p class="text-4xl font-extrabold mt-2">24 000 FCFA</p>
          </div>
          <ul class="p-8 space-y-4 text-center">
            <li>Accompagnement mémoire A→Z</li>
            <li>Mise en forme pro</li>
            <li>Résumés illimités (1 mois)</li>
            <li>Conseils + protocole</li>
          </ul>
          <div class="p-6 border-t">
            <a href="https://wa.me/22944218514?text=Bonjour,%20je%20veux%20le%20Pack%20Premium" class="block bg-indigo-800 text-white py-4 rounded-lg text-center font-bold hover:bg-indigo-900">Choisir ce pack</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Pourquoi Nous Choisir -->
  <section class="py-20">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Pourquoi des Milliers d'Étudiants Nous Font Confiance ?</h2>
      <div class="grid md:grid-cols-3 gap-10">
        <div class="text-center">
          <i class="fas fa-clock text-6xl text-indigo-600 mb-6"></i>
          <h3 class="text-2xl font-bold mb-4">Livraison Rapide</h3>
          <p>24-48h pour résumés, jusqu'à 2 semaines pour mémoires complets.</p>
        </div>
        <div class="text-center">
          <i class="fas fa-lock text-6xl text-indigo-600 mb-6"></i>
          <h3 class="text-2xl font-bold mb-4">Confidentialité 100%</h3>
          <p>Vos documents et infos jamais partagés. Garanti.</p>
        </div>
        <div class="text-center">
          <i class="fas fa-sync-alt text-6xl text-indigo-600 mb-6"></i>
          <h3 class="text-2xl font-bold mb-4">Révisions Gratuites</h3>
          <p>Modifications jusqu'à satisfaction totale.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Témoignages (simplifié, tu peux ajouter photos plus tard) -->
  <section class="py-20 bg-indigo-50">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Ce Que Disent Nos Étudiants</h2>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-xl shadow">
          <p class="italic mb-4">"Grâce à eux, j'ai bouclé mon mémoire à temps. Professionnel et réactif !"</p>
          <p class="font-bold">Jean Dupont – Droit, UAC</p>
        </div>
        <!-- Ajoute les autres témoignages de la même façon -->
      </div>
    </div>
  </section>

  <!-- CTA Final + Contact -->
  <section class="py-20 bg-gradient-to-br from-indigo-900 to-blue-900 text-white text-center">
    <div class="container mx-auto px-6">
      <h2 class="text-4xl md:text-5xl font-bold mb-8">Prêt à Booster Vos Notes ?</h2>
      <p class="text-xl mb-10">Contactez-nous en 30 secondes via WhatsApp</p>
      <a href="https://wa.me/22944218514?text=Bonjour%20Soutien%20Académique%20Pro+,%20je%20veux%20de%20l'aide%20pour..." 
         class="inline-block bg-white text-indigo-900 font-bold text-xl px-12 py-6 rounded-full shadow-2xl hover:bg-gray-100 transition">
        <i class="fab fa-whatsapp text-2xl mr-3"></i> Discutons de ton projet !
      </a>
      <p class="mt-8">Email : soutienacademiquepro@gmail.com | Tous les jours 8h-22h</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-10 text-center">
    <p>&copy; 2026 Soutien Académique Pro+ – Tous droits réservés | Bénin</p>
  </footer>

</body>
</html>
EOF
