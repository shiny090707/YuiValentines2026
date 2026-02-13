```javascript
// Basic Information
valentineName: "Yui"                    // Your Valentine's name
pageTitle: "Will You Be My Valentine? 🥺" // Browser tab title

// Floating Background Elements
floatingEmojis: {
    hearts: ['❤️', '💖', '💝', '👀', '🥺'],  // Heart emojis in background
    bears: ['🧸', '⚽']                       // Bear emojis in background
}

// Questions and Buttons
questions: {
    first: {
        text: "So theoretically if I asked you to be my totally platonic eValentine would you say yes 🫢",                   // First question
        yesBtn: "Yes",                             // Yes button text
        noBtn: "No",                               // No button text
        secretAnswer: "YOU WOULDDD? You're sweeter than chocolate 🤭"  // Hidden message
    },
    second: {
        text: "How sure are you...",          // Second question
        startText: "Show me how sure you are 😋",                   // Text before percentage
        nextBtn: "Next 🫶"                         // Next button text
    },
    third: {
        text: "Can we Timeskip to where you kyamo over and be my Valentine now? 😽",      // Final question
        yesBtn: "Omg yes TJ I will be your valentine!!!",                            // Yes button text
        noBtn: "Ew... no..."                                // No button text
    }
}

// Love Meter Messages
loveMessages: {
    extreme: "OKAY OKAYY I GET ITTT, you're making me blush stawpp 🤭",  // Shows above 5000%
    high: "I guess I'm just the best duo heh 😝",              // Shows above 1000%
    normal: "WOOOOW You're THAT sure? 😇💘"                           // Shows above 100%
}

// Final Celebration
celebration: {
    title: "I'M THE LUCKIEST PERSON EVERRRR!!!!",     // Celebration title
    message: "Now lemme know what kind of chocolate you want ☺️",          // Celebration message
    emojis: "🍫⚽🏐🛏️⚔️🫶💘💝"                        // Celebration emojis
}

// Website Colors
colors: {
    backgroundStart: "#ff0004",      // Background gradient start
    backgroundEnd: "#aa00ff",        // Background gradient end
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
    musicUrl: "[YOUR_CLOUDINARY_URL_HERE](https://res.cloudinary.com/djxxlpzh7/video/upload/v1770965109/Waiting_In_Vain_bhc44j.mp3)", // Paste your music URL here
    startText: "🎵 Play Music", // Button text to start music
    stopText: "🔇 Stop Music", // Button text to stop music
    volume: 0.5 // Volume level (0.0 to 1.0)
}
```
```javascript
music: {
    enabled: true,
    autoplay: true,
    musicUrl: "YOUR_CLOUDINARY_URL_HERE", // Paste your URL here
    startText: "🎵 Play Music",
    stopText: "🔇 Stop Music",
    volume: 0.5
}
```
