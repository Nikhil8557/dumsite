# My Site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DINO RUNNER // README</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap');
        body { font-family: 'Space Mono', monospace; }
        
        /* Subtle scanline effect for that retro feel */
        .scanlines {
            background: linear-gradient(to bottom, rgba(255,255,255,0), rgba(255,255,255,0) 50%, rgba(0,0,0,0.1) 50%, rgba(0,0,0,0.1));
            background-size: 100% 4px;
        }
    </style>
</head>
<body class="bg-zinc-950 text-zinc-300 min-h-screen flex items-center justify-center p-4 sm:p-8 relative">
    
    <!-- Background Overlay -->
    <div class="absolute inset-0 scanlines pointer-events-none opacity-50"></div>

    <div class="max-w-2xl w-full bg-zinc-900 border border-zinc-800 rounded-xl p-8 sm:p-12 shadow-2xl relative overflow-hidden z-10">
        <!-- Top neon accent bar -->
        <div class="absolute top-0 left-0 w-full h-1 bg-gradient-to-r from-emerald-500 via-cyan-500 to-purple-500"></div>

        <header class="mb-12">
            <h1 class="text-4xl sm:text-6xl font-bold text-white tracking-tighter mb-4">DINO_RUNNER</h1>
            <p class="text-zinc-400 text-lg sm:text-xl leading-relaxed">
                An endless desert.<br>
                Prehistoric speed.<br>
                Survive the pixelated wasteland.
            </p>
        </header>

        <section class="space-y-6">
            <h2 class="text-emerald-400 font-bold uppercase tracking-widest text-sm flex items-center">
                <span class="w-8 h-[1px] bg-emerald-400 mr-4"></span>
                Controls
            </h2>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                <!-- Jump -->
                <div class="bg-zinc-950/50 p-4 rounded-lg border border-zinc-800 flex items-center space-x-4 hover:border-emerald-500/30 transition-colors">
                    <div class="flex space-x-2">
                        <kbd class="bg-zinc-800 text-zinc-100 px-3 py-1 rounded shadow border-b-2 border-zinc-700 text-sm">W</kbd>
                        <kbd class="bg-zinc-800 text-zinc-100 px-3 py-1 rounded shadow border-b-2 border-zinc-700 text-sm">I</kbd>
                    </div>
                    <span class="text-sm font-bold tracking-wide">JUMP / START</span>
                </div>

                <!-- Duck -->
                <div class="bg-zinc-950/50 p-4 rounded-lg border border-zinc-800 flex items-center space-x-4 hover:border-emerald-500/30 transition-colors">
                    <div class="flex space-x-2">
                        <kbd class="bg-zinc-800 text-zinc-100 px-3 py-1 rounded shadow border-b-2 border-zinc-700 text-sm">S</kbd>
                        <kbd class="bg-zinc-800 text-zinc-100 px-3 py-1 rounded shadow border-b-2 border-zinc-700 text-sm">K</kbd>
                    </div>
                    <span class="text-sm font-bold tracking-wide">DUCK / DROP</span>
                </div>

                <!-- Restart -->
                <div class="bg-zinc-950/50 p-4 rounded-lg border border-zinc-800 flex items-center space-x-4 sm:col-span-2 hover:border-emerald-500/30 transition-colors">
                    <kbd class="bg-zinc-800 text-zinc-100 px-3 py-1 rounded shadow border-b-2 border-zinc-700 text-sm">J</kbd>
                    <span class="text-sm font-bold tracking-wide">RESTART SEQUENCE</span>
                </div>
            </div>
        </section>

        <!-- Footer status -->
        <div class="mt-16 pt-6 border-t border-zinc-800 flex justify-between items-center">
            <span class="text-xs text-zinc-600 tracking-widest uppercase">System.Ready</span>
            <div class="flex items-center space-x-2">
                <span class="text-xs text-emerald-500 tracking-widest uppercase">Online</span>
                <span class="animate-pulse block w-2 h-2 bg-emerald-500 rounded-full shadow-[0_0_8px_rgba(16,185,129,0.8)]"></span>
            </div>
        </div>
    </div>

</body>
</html>

## Preview

![Website Preview](https://cdn.hackclub.com/019de7eb-e1a4-7759-9be0-6eb1ee5ff553/screenshot.png)
