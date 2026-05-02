```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>IB_OS | Ignacio Bermúdez</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@300;500&family=Inter:wght@400;800&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #050505; color: #e5e5e5; }
        .mono { font-family: 'Fira Code', monospace; }
        .gradient-text { background: linear-gradient(90deg, #fff, #666); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .terminal-box { border: 1px solid #222; background: rgba(10, 10, 10, 0.8); }
    </style>
</head>
<body class="p-4 md:p-12">

    <header class="max-w-4xl mx-auto mb-20 flex justify-between items-end border-b border-zinc-800 pb-4">
        <div>
            <h1 class="text-4xl font-extrabold tracking-tighter gradient-text uppercase">IB_OS v.2026</h1>
            <p class="mono text-xs text-zinc-500 mt-2">ESTADO: GHOSTWRITING / INVESTIGACIÓN / VIGILANCIA</p>
        </div>
        <nav class="mono text-[10px] space-x-4 uppercase tracking-widest text-zinc-400">
            <a href="#manifiesto" class="hover:text-white">Manifiesto</a>
            <a href="#promis" class="hover:text-white">PROMIS</a>
            <a href="#archivo" class="hover:text-white">Archivo</a>
        </nav>
    </header>

    <section id="manifiesto" class="max-w-3xl mx-auto mb-32">
        <h2 class="mono text-red-600 text-sm mb-8 uppercase tracking-widest">// Manifiesto de Escritura</h2>
        <div class="space-y-8 text-lg leading-relaxed text-zinc-300">
            <p>
                La narrativa no es un refugio sino un sistema de procesamiento de datos. Escribo bajo la sombra de arquitecturas maximalistas donde la frase corta es un golpe de cursor y el párrafo largo un panóptico. En mi laboratorio literario la precisión léxica se funde con el código binario. No busco la trama sencilla. Busco la redundancia sistémica que revela la verdad oculta tras el software de vigilancia.
            </p>
            <p class="italic text-zinc-500 border-l border-zinc-800 pl-6">
                El autor desaparece en el sistema. No hay diálogos marcados por guiones porque la voz es una corriente continua. Matías Webb observa el monitor mientras Clara Rembrandt espera una señal que no llega. El silencio es el único dato que no se puede cifrar.
            </p>
        </div>
    </section>

    <section id="promis" class="max-w-4xl mx-auto mb-32">
        <div class="terminal-box p-8 rounded-lg">
            <h2 class="text-2xl font-bold mb-6">PROYECTO: PROMIS (Novela)</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="text-sm text-zinc-400 space-y-4">
                    <p>Un thriller técnico sobre la genealogía del espionaje moderno. Siete libros publicados bajo el anonimato del ghostwriter convergen aquí.</p>
                    <ul class="mono text-xs space-y-2">
                        <li>> STACK: ESP32 / PYTHON / FASTAPI</li>
                        <li>> FOCUS: OSINT / CRIPTOGRAFÍA</li>
                        <li>> STATUS: EN DESARROLLO (KDP)</li>
                    </ul>
                </div>
                <div class="border border-zinc-800 p-4 bg-zinc-950 flex items-center justify-center">
                    <span class="mono text-zinc-600 animate-pulse text-[10px]">DATOS_CIFRADOS_05.02.26</span>
                </div>
            </div>
        </div>
    </section>

    <footer id="archivo" class="max-w-4xl mx-auto border-t border-zinc-800 pt-12 flex flex-col md:flex-row justify-between items-center space-y-6 md:space-y-0">
        <div class="text-[10px] mono text-zinc-600 uppercase">
            Mendoza, AR | Florencia, IT | 43.0N - 74.0W
        </div>
        <div class="flex space-x-6">
            <a href="mailto:ignacio@ib-os.com" class="text-white font-bold hover:underline">SOLICITAR ACCESO</a>
            <span class="text-zinc-800">|</span>
            <span class="mono text-[10px] text-zinc-500">SIGNAL_ONLY</span>
        </div>
    </footer>

</body>
</html>


```
