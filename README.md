
Here's what you can customize in `config.js`:
```javascript
// Basic Information
valentineName: "Louise"                    // Your Valentine's name
pageTitle: "Você quer ser minha Valentine? 💗" // Browser tab title

// Floating Background Elements
floatingEmojis: {
    hearts: ['❤️', '💖', '💝', '💗', '💓'],  // Heart emojis in background
    bears: ['🧸', '🐻']                       // Bear emojis in background
}

// Questions and Buttons
questions: {
    first: {
        text: "Você gosta de mim?",                   // First question
        yesBtn: "SIIIII",                             // Yes button text
        noBtn: "No.",                               // No button text
        secretAnswer: "Eu não gosto de você, eu te amo! ❤️"  // Hidden message
    },
    second: {
        text: "O quanto você me ama?",          // Second question
        startText: "Tudo isso!",                   // Text before percentage
        nextBtn: "Next ❤️"                         // Next button text
    },
    third: {
        text: "Você quer ser minha Valentine? 💗",      // Final question
        yesBtn: "SIM ",                            // Yes button text
        noBtn: "No, te odio"                                // No button text
    }
}

// Love Meter Messages
loveMessages: {
    extreme: "AYAYAYAYAY AHORA SI CREO QUE ME PODRIAS ESTAR EMPATANDO",  // Shows above 5000%
    high: "IMPOSIBLE PERO ENTONCES POR QUE NO NO CASAMOS",              // Shows above 1000%
    normal: "ENSERIO TANTO??? PUES YO MAS JIJIIII 🥰"                           // Shows above 100%
}

// Final Celebration
celebration: {
    title: "JIJIIIII YO LA PERSONA MAS AFORTUNADA DEL MUNDO",     // Celebration title
    message: "AHORA ESTAS SENTENCIADA A UN 14 DE FEBRERO CONMIGO",          // Celebration message
    emojis: "💕"                        // Celebration emojis
}

// Website Colors
colors: {
    backgroundStart: "#ffafbd",      // Background gradient start
    backgroundEnd: "#ffc3a0",        // Background gradient end
    buttonBackground: "#ff6b6b",     // Button color
    buttonHover: "#ff8787",          // Button hover color
    textColor: "#ff4757"            // Text color
}

// Animation Settings
animations: {
    floatDuration: "15s",           // How long hearts float (10-20s)
    floatDistance: "50px",          // Sideways movement (30-70px)
    bounceSpeed: "0.5s",            // Bounce animation speed (0.3-0.7s)
    heartExplosionSize: 1.5         // Final heart explosion size (1.2-2.0)
}

// Music Settings
music: {
    enabled: true, // Music feature is enabled
    autoplay: true, // Try to autoplay (note: some browsers may block this)
    musicUrl: "YOUR_CLOUDINARY_URL_HERE", // Paste your music URL here
    startText: "🎵 Play Music", // Button text to start music
    stopText: "🔇 Stop Music", // Button text to stop music
    volume: 0.5 // Volume level (0.0 to 1.0)
}
```


MIT License - Feel free to use this for your Valentine! 
