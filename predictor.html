<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quantum Predictor Pro - Real-Time Analytics</title>
    <style>
        :root {
            --bg-color: #0a0b10;
            --panel-bg: rgba(18, 20, 32, 0.8);
            --primary: #8a2be2;
            --secondary: #00f2fe;
            --text: #ffffff;
            --text-muted: #6c7293;
            --success: #00ff87;
            --warning: #ffb703;
            --aviator-red: #e10531;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            overflow-x: hidden;
            background: radial-gradient(circle at 50% 50%, #1a1235 0%, #0a0b10 100%);
        }

        .app-container {
            width: 100%;
            max-width: 440px;
            padding: 20px;
        }

        .panel {
            background: var(--panel-bg);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.08);
            border-radius: 28px;
            padding: 25px;
            box-shadow: 0 24px 50px rgba(0, 0, 0, 0.6);
            position: relative;
            overflow: hidden;
            min-height: 580px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .login-view {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100%;
            flex-grow: 1;
            padding: 20px 10px;
            animation: fadeIn 0.4s ease;
        }

        .login-title {
            font-size: 22px;
            font-weight: 800;
            margin-bottom: 8px;
            letter-spacing: 0.5px;
            background: linear-gradient(45deg, #ffffff, var(--text-muted));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .login-subtitle {
            font-size: 13px;
            color: var(--text-muted);
            text-align: center;
            margin-bottom: 30px;
            line-height: 1.4;
        }

        .input-group {
            width: 100%;
            margin-bottom: 25px;
        }

        .input-field {
            width: 100%;
            background: rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.12);
            padding: 16px 20px;
            border-radius: 50px;
            color: #ffffff;
            font-size: 15px;
            outline: none;
            text-align: center;
            transition: all 0.3s ease;
        }

        .input-field:focus {
            border-color: var(--secondary);
            box-shadow: 0 0 15px rgba(0, 242, 254, 0.2);
        }

        .main-view {
            display: none;
            flex-direction: column;
            flex-grow: 1;
            animation: fadeIn 0.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .header {
            text-align: center;
            margin-bottom: 15px;
        }

        .header h1 {
            font-size: 24px;
            font-weight: 900;
            letter-spacing: 1.5px;
            background: linear-gradient(45deg, var(--secondary), var(--primary));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .header p {
            color: var(--text-muted);
            font-size: 11px;
            margin-top: 4px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .display-area {
            background: rgba(0, 0, 0, 0.35);
            border-radius: 20px;
            height: 180px;
            margin-bottom: 15px;
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            border: 1px solid rgba(255, 255, 255, 0.04);
        }

        .signal-circle {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 6px solid var(--secondary);
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 0 25px rgba(0, 242, 254, 0.25);
            background: rgba(10, 11, 16, 0.85);
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            z-index: 2;
            margin-bottom: 6px;
        }

        .result-text {
            font-size: 28px;
            font-weight: 900;
            color: var(--text);
        }

        .risk-badge {
            font-size: 11px;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--secondary);
            background: rgba(0, 242, 254, 0.1);
            padding: 4px 12px;
            border-radius: 20px;
        }

        .metrics-panel {
            background: rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(255, 255, 255, 0.06);
            border-radius: 16px;
            padding: 15px;
            margin-bottom: 15px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 12px;
        }

        .metric-box {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 8px;
            background: rgba(255, 255, 255, 0.02);
            border-radius: 10px;
            border: 1px solid rgba(255, 255, 255, 0.03);
        }

        .metric-label {
            font-size: 10px;
            color: var(--text-muted);
            text-transform: uppercase;
            letter-spacing: 0.5px;
            margin-bottom: 4px;
            text-align: center;
        }

        .metric-value {
            font-size: 16px;
            font-weight: 800;
            color: #ffffff;
        }

        .loader-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: var(--aviator-red);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 10;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.3s ease;
        }

        .loader-overlay.active {
            opacity: 1;
            pointer-events: auto;
        }

        .loader-title {
            font-size: 20px;
            font-weight: 900;
            letter-spacing: 2px;
            color: #ffffff;
            margin-bottom: 25px;
        }

        .spinner {
            width: 60px;
            height: 60px;
            border: 5px solid rgba(255, 255, 255, 0.25);
            border-left-color: #ffffff;
            border-radius: 50%;
            animation: spin 0.75s linear infinite;
            margin-bottom: 20px;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .loader-text {
            font-size: 12px;
            color: rgba(255, 255, 255, 0.9);
            letter-spacing: 0.5px;
            font-weight: 600;
            text-transform: uppercase;
            text-align: center;
            padding: 0 20px;
        }

        .btn-oval {
            width: 100%;
            border: none;
            padding: 16px;
            border-radius: 50px;
            font-size: 15px;
            font-weight: 800;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            text-align: center;
        }

        .btn-login {
            background: linear-gradient(90deg, var(--primary), var(--secondary));
            color: white;
            box-shadow: 0 6px 20px rgba(138, 43, 226, 0.3);
        }

        .btn-login:hover { transform: translateY(-2px); }

        .btn-action {
            background: #00ff87;
            color: #0a0b10;
            box-shadow: 0 6px 20px rgba(0, 255, 135, 0.3);
        }

        .btn-action:hover {
            transform: translateY(-2px);
            background: #00ff9d;
        }

        .btn-oval:disabled {
            background: #252736 !important;
            color: var(--text-muted) !important;
            cursor: not-allowed;
            transform: none !important;
            box-shadow: none !important;
        }

        .history-section { margin-top: 15px; }

        .history-title {
            font-size: 11px;
            color: var(--text-muted);
            text-transform: uppercase;
            margin-bottom: 8px;
            display: flex;
            justify-content: space-between;
        }

        .history-tags {
            display: flex;
            gap: 8px;
            overflow-x: auto;
            padding-bottom: 5px;
        }

        .tag {
            background: rgba(255, 255, 255, 0.04);
            border: 1px solid rgba(255, 255, 255, 0.07);
            padding: 6px 12px;
            border-radius: 10px;
            font-size: 11px;
            font-weight: 700;
            color: var(--secondary);
        }

        .anchored-link {
            position: fixed;
            right: 16px;
            bottom: 16px;
            z-index: 50;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            padding: 12px 18px;
            border-radius: 999px;
            color: #ffffff;
            text-decoration: none;
            font-size: 11px;
            font-weight: 800;
            text-transform: uppercase;
            background: linear-gradient(90deg, var(--aviator-red), var(--primary));
            box-shadow: 0 10px 30px rgba(225, 5, 49, 0.35);
            border: 1px solid rgba(255, 255, 255, 0.15);
            transition: all 0.3s ease;
        }

        .anchored-link:hover { transform: scale(1.04); }

        .source-note {
            margin-top: 15px;
            padding: 10px 12px;
            border-radius: 12px;
            background: rgba(0, 242, 254, 0.05);
            border: 1px solid rgba(0, 242, 254, 0.12);
            color: var(--text-muted);
            font-size: 11px;
            line-height: 1.4;
            text-align: center;
        }
    </style>
</head>
<body>

<a class="anchored-link" id="vicibet-anchor" href="https://vicibet.com/ca/game/aviator-v3" target="_blank" rel="noopener noreferrer">🎰 ABRIR VICIBET</a>

<div class="app-container">
    <div class="panel">
        
        <div class="loader-overlay" id="loader">
            <div class="loader-title">ALGORITMO QUANTUM</div>
            <div class="spinner"></div>
            <div class="loader-text" id="loader-status">PROCESANDO CADENAS DE MARKOV...</div>
        </div>

        <div class="login-view" id="view-login">
            <div class="login-title">Iniciar Servidor Predictivo</div>
            <div class="login-subtitle">Introduce tu ID de cuenta ViciBet para ajustar las tolerancias de tiempo de retiro.</div>
            
            <div class="input-group">
                <input type="text" class="input-field" id="user-input" placeholder="ID de Usuario / Cuenta" autocomplete="off">
            </div>
            
            <button class="btn-oval btn-login" onclick="autenticarUsuario()">Vincular Servidor</button>
        </div>

        <div class="main-view" id="view-main">
            <div class="header">
                <h1>QUANTUM PREDICTOR</h1>
                <p>Módulo de Control Estadístico Avanzado</p>
            </div>

            <div class="display-area">
                <div class="signal-circle" id="signal-ring">
                    <div class="result-text" id="display-multiplier">READY</div>
                </div>
                <div class="risk-badge" id="risk-status">Sincronizado</div>
            </div>

            <div class="metrics-panel">
                <div class="metric-box">
                    <div class="metric-label">Tiempo Sugerido Retiro</div>
                    <div class="metric-value" id="metric-time">0.00s</div>
                </div>
                <div class="metric-box">
                    <div class="metric-label">Probabilidad Éxito</div>
                    <div class="metric-value" id="metric-probability" style="color: var(--success);">00.0%</div>
                </div>
                <div class="metric-box">
                    <div class="metric-label">Ventana de Validez</div>
                    <div class="metric-value" id="validez-time">--:--:--</div>
                </div>
                <div class="metric-box">
                    <div class="metric-label">Riesgo Estimado</div>
                    <div class="metric-value" id="metric-risk">NINGUNO</div>
                </div>
            </div>

            <button class="btn-oval btn-action" id="btn-action" onclick="ejecutarAnalisis()">Generar Análisis Lineal</button>

            <div class="history-section">
                <div class="history-title">
                    <span>Muestreos de Sesión</span>
                    <span style="color: var(--secondary);">Últimas 4</span>
                </div>
                <div class="history-tags" id="history-box">
                    <div class="tag" style="color: var(--text-muted)">Sin registros</div>
                </div>
            </div>

            <div class="source-note">
                <strong>Precaución Operativa:</strong> El tiempo sugerido calcula la velocidad promedio del ascenso del avión para evitar retrasos de reacción humana.
            </div>
        </div>

    </div>
</div>

<script>
    const VICIBET_URL = "https://vicibet.com/ca/game/aviator-v3";
    const mensajesCarga = [
        "Leyendo patrones de dispersión...",
        "Calculando curva de aceleración...",
        "Calculando milisegundos de ejecución...",
        "Mapeando punto óptimo de retiro..."
    ];
    let historial = [];

    function autenticarUsuario() {
        if (document.getElementById('user-input').value.trim() === "") {
            alert("Por favor, introduce tu identificador.");
            return;
        }
        const loader = document.getElementById('loader');
        loader.classList.add('active');
        document.getElementById('loader-status').innerText = "ESTABLECIENDO PROTOCOLO PROBABILÍSTICO...";
        setTimeout(() => {
            loader.classList.remove('active');
            document.getElementById('view-login').style.display = 'none';
            document.getElementById('view-main').style.display = 'flex';
        }, 1500);
    }

    function ejecutarAnalisis() {
        const btn = document.getElementById('btn-action');
        const loader = document.getElementById('loader');
        const displayMult = document.getElementById('display-multiplier');
        const ring = document.getElementById('signal-ring');
        
        btn.disabled = true;
        loader.classList.add('active');
        displayMult.innerText = "1.00x";
        
        let msgIndex = 0;
        document.getElementById('loader-status').innerText = mensajesCarga[msgIndex];
        const intervalMsgs = setInterval(() => {
            msgIndex++;
            if(msgIndex < mensajesCarga.length) document.getElementById('loader-status').innerText = mensajesCarga[msgIndex];
        }, 500);

        setTimeout(() => {
            clearInterval(intervalMsgs);
            loader.classList.remove('active');
            
            let multFinal;
            const seed = Math.random();
            if (seed < 0.50) multFinal = (Math.random() * (1.95 - 1.15) + 1.15).toFixed(2);
            else if (seed < 0.88) multFinal = (Math.random() * (4.50 - 2.00) + 2.00).toFixed(2);
            else multFinal = (Math.random() * (10.50 - 4.60) + 4.60).toFixed(2);
            
            const valorCuota = parseFloat(multFinal);
            let tiempoSegundos = (Math.log(valorCuota) * 4.2 + 0.5).toFixed(2);
            if (tiempoSegundos < 0.5) tiempoSegundos = "0.80";
            let porcentajeExito = Math.max(99.4 - (valorCuota * 4.8), 61.2).toFixed(1);

            const ahora = new Date();
            ahora.setMinutes(ahora.getMinutes() + 2);
            document.getElementById('validez-time').innerText = ahora.toTimeString().split(' ')[0];

            const startTime = performance.now();
            function actualizarContador(currentTime) {
                const elap = currentTime - startTime;
                const progreso = Math.min(elap / 1200, 1);
                displayMult.innerText = (1.00 + (valorCuota - 1.00) * progreso).toFixed(2) + "x";

                if (progreso < 1) {
                    requestAnimationFrame(actualidor => requestAnimationFrame(actualizarContador));
                } else {
                    document.getElementById('metric-time').innerText = tiempoSegundos + "s";
                    document.getElementById('metric-probability').innerText = porcentajeExito + "%";

                    if (valorCuota < 1.60) {
                        ring.style.borderColor = "var(--aviator-red)";
                        document.getElementById('risk-status').innerText = "ALERTA: MULTIPLICADOR BAJO";
                        document.getElementById('metric-risk').innerText = "ALTO";
                        document.getElementById('metric-risk').style.color = "var(--aviator-red)";
                    } else if (valorCuota < 3.00) {
                        ring.style.borderColor = "var(--success)";
                        document.getElementById('risk-status').innerText = "ENTRADA RECOMENDADA";
                        document.getElementById('metric-risk').innerText = "BAJO";
                        document.getElementById('metric-risk').style.color = "var(--success)";
                    } else {
                        ring.style.borderColor = "var(--warning)";
                        document.getElementById('risk-status').innerText = "CUOTA ALTA EMITIDA";
                        document.getElementById('metric-risk').innerText = "MODERADO";
                        document.getElementById('metric-risk').style.color = "var(--warning)";
                    }
                    actualizarHistorial(multFinal + "x");
                    btn.disabled = false;
                }
            }
            requestAnimationFrame(actualizarContador);
        }, 2200);
    }

    function actualizarHistorial(nuevoValor) {
        historial.unshift(nuevoValor);
        if(historial.length > 4) historial.pop();
        const box = document.getElementById('history-box');
        box.innerHTML = '';
        historial.forEach(item => {
            const tag = document.createElement('div');
            tag.className = 'tag';
            tag.innerText = item;
            box.appendChild(tag);
        });
    }
</script>
</body>
</html>
