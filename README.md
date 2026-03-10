<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>AI Nexus Immersive</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        /* Immersive glass texture with a broader neon haze */
        .glass {
            background: rgba(255, 255, 255, 0.02);
            backdrop-filter: blur(15px);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }

        /* The extended and broadened neon shading effect */
        .neon-shaded {
            box-shadow: 
                0 0 20px rgba(129, 140, 248, 0.2), /* Softer inner haze */
                30px 0 60px -10px rgba(129, 140, 248, 0.6); /* Extended and stronger right-side shading */
        }

        /* Essential reset for full immersion */
        html, body {
            height: 100%;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #0b0e14;
        }
    </style>
</head>
<body class="text-gray-200 font-sans flex justify-center items-center">

    <div class="w-full h-screen max-w-[420px] max-h-[850px] bg-[#0d1017] rounded-[48px] shadow-2xl border-[1px] border-gray-900 p-0 flex flex-col relative overflow-hidden">
        
        <header class="h-10 w-full flex justify-center items-center">
            </header>

        <div class="flex-1 flex flex-col items-center justify-center relative px-6">
            
            <div class="glass w-full max-w-[340px] p-12 rounded-[40px] flex flex-col items-center gap-10 relative neon-shaded">
                
                <h1 class="text-7xl text-white font-serif tracking-tight" style="font-family: 'Brush Script MT', cursive; transform: rotate(-5deg);">
                    hello
                </h1>

                <div class="w-28 h-28 text-indigo-100 opacity-90">
                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.2" stroke-linecap="round" stroke-linejoin="round">
                        <circle cx="12" cy="12" r="10"></circle>
                        <line x1="8" y1="13.5" x2="16" y2="13.5"></line>
                    </svg>
                </div>
            </div>

        </div>

        <div class="absolute bottom-12 left-0 right-0 w-full px-6 flex flex-col items-center gap-6">
            
            <button class="w-full max-w-[340px] h-16 glass rounded-full flex items-center justify-center px-8 gap-3 group hover:border-indigo-500 transition-all shadow-md">
                <i class="fa-solid fa-search text-gray-400 group-hover:text-indigo-400"></i>
                <span class="text-gray-300 font-medium text-lg">Tap to Search</span>
            </button>
            
            <div class="flex justify-between w-full max-w-[340px] px-8 text-gray-500 text-2xl">
                <i class="fa-regular fa-check-circle hover:text-white cursor-pointer"></i>
                <i class="fa-solid fa-microphone hover:text-white cursor-pointer"></i>
                <i class="fa-solid fa-pencil hover:text-white cursor-pointer"></i>
                <i class="fa-solid fa-plus-circle hover:text-white cursor-pointer"></i>
            </div>
        </div>

    </div>
    </body>
</html>
