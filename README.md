<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmet AI | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { background-color: #050505; color: white; font-family: sans-serif; }
        .hero-glow {
            background: radial-gradient(circle at center, rgba(59, 130, 246, 0.2) 0%, transparent 70%);
        }
    </style>
</head>
<body class="hero-glow min-h-screen flex flex-col items-center justify-center p-6">

    <header class="text-center">
        <div class="mb-4 inline-block px-3 py-1 bg-blue-500/20 border border-blue-500/50 rounded-full text-blue-400 text-xs font-bold uppercase tracking-widest">
            Ahmet's AI Project
        </div>
        <h1 class="text-5xl md:text-7xl font-extrabold mb-6 tracking-tighter">
            The Future is <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-600">Intelligence.</span>
        </h1>
        <p class="text-gray-400 text-lg max-w-xl mx-auto mb-10">
            Welcome to my website hosted on GitHub. This is a demonstration of a modern AI landing page interface.
        </p>
    </header>

    <div class="w-full max-w-4xl bg-white/5 border border-white/10 rounded-2xl p-8 backdrop-blur-md shadow-2xl">
        <div class="flex items-center gap-2 mb-6">
            <div class="w-3 h-3 rounded-full bg-red-500"></div>
            <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
            <div class="w-3 h-3 rounded-full bg-green-500"></div>
            <span class="ml-4 text-gray-500 text-sm italic">ai-engine-active...</span>
        </div>
        <div class="space-y-4">
            <div class="h-4 bg-white/10 rounded w-3/4"></div>
            <div class="h-4 bg-white/10 rounded w-1/2"></div>
            <div class="h-32 bg-blue-500/10 rounded-xl border border-blue-500/20 flex items-center justify-center">
                <span class="text-blue-400 font-mono animate-pulse">Processing Data at ahmetwebsite.io...</span>
            </div>
        </div>
    </div>

    <footer class="mt-12 text-gray-500 text-sm">
        <p>Built by Ahmet &bull; Hosted on GitHub Pages</p>
    </footer>

</body>
</html>
