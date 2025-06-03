// config.js

module.exports = {
  // Informations de base
  botName: 'IVORYX MD',
  ownerName: 'abdias dev / denki dev',
  ownerNumber: ['2250715370638'], // Numéros autorisés (sans le "+")

  // Messages par défaut
  messages: {
    success: '✅ Terminé !',
    admin: '❌ Cette commande est réservée aux admins.',
    botAdmin: '❌ Le bot doit être admin pour faire ça.',
    owner: '❌ Cette commande est réservée au propriétaire.',
    group: '❌ Utilisable uniquement dans un groupe.',
    private: '❌ Utilisable uniquement en message privé.',
    bot: '❌ Cette fonction est réservée au bot.',
    wait: '⏳ En cours, patiente un peu...',
    error: '❌ Une erreur est survenue.',
    endLimit: '🚫 Tu as atteint ta limite quotidienne.',
  },

  // Limites par utilisateur
  limitInitial: {
    premium: "Infini",
    gratuit: 20
  },

  // Messages d'accueil / départ
  welcomeMessage: '👋 Bienvenue, @user !',
  goodbyeMessage: '😢 Au revoir, @user !',

  // Auto-lecture de messages
  autoRead: true,

  // Anti-lien, anti-fake, etc.
  antiLink: false,
  antiFake: false,
  antiSpam: true,

  // Préfixes valides pour appeler les commandes
  prefixes: ['!', '.', '/', '#'],

  // Message personnalisé du menu
  menuMessage: `
🤖 *IVORYX MD - MENU PRINCIPAL*
╭─────────────◆
│👑 Propriétaire : Abdias dev and denki dev
│📱 Numéro : wa.me/2250715370638
│📆 Date : %date
╰─────────────◆

🔍 Tape une commande pour commencer !
`,

  // Clé API (si utilisée)
  openaiKey: process.env.OPENAI_KEY || '',

  // Configuration avancée
  sessionName: 'session',
  language: 'fr', // ou 'en'
}

