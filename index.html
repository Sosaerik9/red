<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Red Soberana IP - App Operador Total</title>
    <link rel="manifest" href="data:application/manifest+json;charset=utf-8,{
        %22name%22: %22Red Soberana IP%22,
        %22short_name%22: %22SoberanaIP%22,
        %22start_url%22: %22.%22,
        %22display%22: %22standalone%22,
        %22background_color%22: %22%23070913%22,
        %22theme_color%22: %22%2300f2fe%22
    }">
    <style>
        :root {
            --bg-dark: #070913;
            --card-bg: #101728;
            --accent: #00f2fe;
            --accent-green: #00e676;
            --accent-red: #ff3366;
            --accent-orange: #ff9800;
            --text-main: #ffffff;
            --text-muted: #8fa3bf;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-main);
            margin: 0;
            padding: 12px;
            padding-bottom: 40px;
        }

        .container {
            max-width: 480px;
            margin: 0 auto;
        }

        /* Barra de Pestañas (Tal como en tu imagen) */
        .nav-tabs {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 4px;
            background: var(--card-bg);
            border-radius: 12px;
            padding: 6px;
            margin-bottom: 16px;
            border: 1px solid #1f2d4a;
        }

        .tab-btn {
            background: none;
            border: none;
            padding: 8px 2px;
            color: var(--text-muted);
            font-weight: bold;
            font-size: 0.7rem;
            border-radius: 8px;
            cursor: pointer;
            text-align: center;
            transition: 0.2s;
        }

        .tab-btn.active {
            background: var(--accent);
            color: #000;
        }

        .section-view {
            display: none;
        }

        .section-view.active {
            display: block;
        }

        .card {
            background: var(--card-bg);
            border-radius: 16px;
            padding: 16px;
            margin-bottom: 14px;
            border: 1px solid #1f2d4a;
            box-shadow: 0 4px 20px rgba(0,0,0,0.4);
        }

        .card h2 {
            font-size: 0.95rem;
            color: var(--text-muted);
            margin-bottom: 10px;
            margin-top: 0;
        }

        input, select {
            width: 100%;
            background: #1a253f;
            border: 1px solid #2a3b5f;
            border-radius: 8px;
            padding: 10px;
            color: white;
            margin-bottom: 10px;
            font-size: 0.9rem;
            box-sizing: border-box;
        }

        .btn {
            width: 100%;
            background: var(--accent-green);
            color: #000;
            border: none;
            padding: 12px;
            border-radius: 8px;
            font-weight: bold;
            font-size: 0.95rem;
            cursor: pointer;
            transition: opacity 0.2s;
        }

        .btn:hover { opacity: 0.9; }

        .numero-asignado-box {
            background: linear-gradient(135deg, #1f4068, #162447);
            border-radius: 12px;
            padding: 14px;
            text-align: center;
            border: 1px solid #00f2fe55;
            margin-bottom: 14px;
        }

        .numero-texto {
            font-size: 1.3rem;
            font-weight: bold;
            color: var(--accent);
            margin: 4px 0;
        }

        .dialer-screen {
            background: #0b111e;
            border: 1px solid #2a3b5f;
            border-radius: 10px;
            padding: 10px;
            font-size: 1.1rem;
            text-align: center;
            letter-spacing: 1px;
            margin-bottom: 12px;
            color: #fff;
            word-break: break-all;
        }

        .dialer-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 8px;
            margin-bottom: 12px;
        }

        .dial-btn {
            background: #1a253f;
            border: 1px solid #2a3b5f;
            border-radius: 50%;
            width: 50px;
            height: 50px;
            margin: 0 auto;
            color: white;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .dial-btn:active { background: var(--accent); color: #000; }

        .btn-call { background: var(--accent-green); color: #000; }
        .btn-hangup { background: var(--accent-red); color: #fff; display: none; margin-top: 8px; }

        .history-item {
            background: #1a253f;
            padding: 10px;
            border-radius: 8px;
            margin-bottom: 6px;
            font-size: 0.8rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
    </style>
</head>
<body>

    <div class="container">
        <div style="text-align: center; margin-bottom: 12px;">
            <h1 style="font-size: 1.1rem; color: var(--accent); margin: 0;">🌐 Red Soberana IP</h1>
            <p style="font-size: 0.7rem; color: var(--text-muted); margin: 2px 0 0 0;">Sistema Autónomo de Conectividad</p>
        </div>

        <!-- Botones de Navegación Superiores (Funcionales) -->
        <div class="nav-tabs">
            <button class="tab-btn active" id="tab-1" onclick="cambiarSeccion('perfil')">👤 Perfil</button>
            <button class="tab-btn" id="tab-2" onclick="cambiarSeccion('billetera')">💳 Billetera</button>
            <button class="tab-btn" id="tab-3" onclick="cambiarSeccion('paquetes')">📦 Paquetes</button>
            <button class="tab-btn" id="tab-4" onclick="cambiarSeccion('llamadas')">📞 Llamadas</button>
            <button class="tab-btn" id="tab-5" onclick="cambiarSeccion('admin')">⚙️ Admin</button>
        </div>

        <!-- ================= 1. SECCIÓN PERFIL ================= -->
        <div id="seccion-perfil" class="section-view active">
            <div class="card" style="text-align: center;">
                <h2>Estado de tu Línea</h2>
                <div class="numero-asignado-box" style="margin-bottom: 10px;">
                    <span style="font-size: 0.75rem; color: var(--text-muted);">Número Asignado</span>
                    <div class="numero-texto" id="mi-numero-display">+58 500-0001</div>
                </div>
                <p style="font-size: 0.8rem; color: var(--accent-green);">Estado: <strong>ACTIVO Y OPERATIVO</strong></p>
            </div>

            <div class="card">
                <h2>Configuración de Usuario</h2>
                <input type="text" id="nombre-usuario" value="Cliente Soberano" placeholder="Tu Nombre" />
                <button class="btn" style="background: #2979ff; color: white;" onclick="guardarPerfil()">Guardar Cambios</button>
            </div>
        </div>

        <!-- ================= 2. SECCIÓN BILLETERA ================= -->
        <div id="seccion-billetera" class="section-view">
            <div class="card" style="text-align: center;">
                <h2>Saldo Disponible</h2>
                <div style="font-size: 2rem; font-weight: bold; color: var(--accent-green);" id="saldo-usuario">$5.00</div>
                <p style="font-size: 0.75rem; color: var(--text-muted); margin-top: 4px;">Disponible para llamadas y datos</p>
            </div>

            <div class="card">
                <h2>Reportar Pago (Pago Móvil / Transferencia)</h2>
                <input type="number" id="monto-pago" placeholder="Monto en USD (ej. 10)" />
                <input type="text" id="ref-pago" placeholder="Últimos 4 dígitos de Referencia" />
                <button class="btn" onclick="enviarReportePago()">Enviar Reporte al Operador</button>
            </div>
        </div>

        <!-- ================= 3. SECCIÓN PAQUETES ================= -->
        <div id="seccion-paquetes" class="section-view">
            <div class="card">
                <h2>Tienda de Paquetes de Datos</h2>
                <p style="font-size: 0.8rem; color: var(--text-muted); margin-bottom: 12px;">Compra megas para navegar con tu operadora actual manteniendo tu línea IP activa.</p>
                
                <div class="history-item" style="flex-direction: column; align-items: flex-start; gap: 6px; margin-bottom: 10px;">
                    <div><strong>Paquete Básico (2 GB)</strong></div>
                    <div style="font-size: 0.75rem; color: var(--text-muted);">Válido por 7 días en cualquier red móvil.</div>
                    <button class="btn" style="padding: 8px; font-size: 0.85rem;" onclick="comprarPaquete(3.00, '2 GB Básicos')">Comprar por $3.00</button>
                </div>

                <div class="history-item" style="flex-direction: column; align-items: flex-start; gap: 6px;">
                    <div><strong>Paquete Ilimitado (24 Horas)</strong></div>
                    <div style="font-size: 0.75rem; color: var(--text-muted);">Acceso total sin restricciones por un día.</div>
                    <button class="btn" style="padding: 8px; font-size: 0.85rem;" onclick="comprarPaquete(5.00, 'Ilimitado 24H')">Comprar por $5.00</button>
                </div>
            </div>
        </div>

        <!-- ================= 4. SECCIÓN LLAMADAS IP ================= -->
        <div id="seccion-llamadas" class="section-view">
            <div class="card">
                <h2>Marcador de Red IP</h2>
                <div class="dialer-screen" id="pantalla-marcador">+58 500-</div>

                <div class="dialer-grid">
                    <button class="dial-btn" onclick="marcarDigito('1')">1</button>
                    <button class="dial-btn" onclick="marcarDigito('2')">2</button>
                    <button class="dial-btn" onclick="marcarDigito('3')">3</button>
                    <button class="dial-btn" onclick="marcarDigito('4')">4</button>
                    <button class="dial-btn" onclick="marcarDigito('5')">5</button>
                    <button class="dial-btn" onclick="marcarDigito('6')">6</button>
                    <button class="dial-btn" onclick="marcarDigito('7')">7</button>
                    <button class="dial-btn" onclick="marcarDigito('8')">8</button>
                    <button class="dial-btn" onclick="marcarDigito('9')">9</button>
                    <button class="dial-btn" onclick="marcarDigito('*')">*</button>
                    <button class="dial-btn" onclick="marcarDigito('0')">0</button>
                    <button class="dial-btn" onclick="borrarDigito()">⌫</button>
                </div>

                <button class="btn btn-call" id="btn-llamar" onclick="iniciarLlamadaReal()">📞 Llamar por Red IP</button>
                <button class="btn btn-hangup" id="btn-colgar" onclick="colgarLlamadaReal()">🔴 Colgar Llamada</button>

                <div id="estado-llamada" style="text-align: center; font-size: 0.8rem; margin-top: 10px; color: var(--accent-green);">🟢 Línea lista</div>
                <audio id="remote-audio" autoplay></audio>
            </div>
        </div>

        <!-- ================= 5. SECCIÓN ADMIN ================= -->
        <div id="seccion-admin" class="section-view">
            <div class="card" style="border-color: var(--accent-orange);">
                <h2 style="color: var(--accent-orange);">Panel de Control Operador</h2>
                <input type="text" id="nuevo-num-pool" placeholder="Ej: +58 500-0045" />
                <button class="btn" style="background: var(--accent-orange); color: #000; margin-bottom: 12px;" onclick="agregarNumeroAlPool()">➕ Añadir Número al Pool</button>
                <div id="lista-pool-numeros"></div>
            </div>

            <div class="card">
                <h2>Solicitudes de Recarga Pendientes</h2>
                <div id="lista-solicitudes-admin">
                    <div style="text-align: center; color: var(--text-muted); font-size: 0.8rem;">No hay pagos pendientes.</div>
                </div>
            </div>
        </div>
    </div>

    <script>
        let saldoActual = 5.00;
        let miNumeroAsignado = "+58 500-0001";
        let poolNumeros = ["+58 500-0002", "+58 500-0003", "+58 500-0004"];
        let solicitudesRecarga = [];
        let numeroMarcado = "+58 500-";

        let localStream = null;
        let peerConnection = null;
        const servers = { iceServers: [{ urls: 'stun:stun.l.google.com:19302' }] };

        window.onload = function() {
            document.getElementById('mi-numero-display').innerText = miNumeroAsignado;
            renderizarAdmin();
            
            navigator.mediaDevices.getUserMedia({ audio: true, video: false })
                .then(stream => { localStream = stream; })
                .catch(err => { console.log("Permiso de micrófono en espera: ", err); });
        };

        function cambiarSeccion(seccion) {
            document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            document.querySelectorAll('.section-view').forEach(s => s.classList.remove('active'));

            if(seccion === 'perfil') {
                document.getElementById('seccion-perfil').classList.add('active');
                document.getElementById('tab-1').classList.add('active');
            } else if(seccion === 'billetera') {
                document.getElementById('seccion-billetera').classList.add('active');
                document.getElementById('tab-2').classList.add('active');
            } else if(seccion === 'paquetes') {
                document.getElementById('seccion-paquetes').classList.add('active');
                document.getElementById('tab-3').classList.add('active');
            } else if(seccion === 'llamadas') {
                document.getElementById('seccion-llamadas').classList.add('active');
                document.getElementById('tab-4').classList.add('active');
            } else if(seccion === 'admin') {
                document.getElementById('seccion-admin').classList.add('active');
                document.getElementById('tab-5').classList.add('active');
                renderizarAdmin();
            }
        }

        function guardarPerfil() {
            let nombre = document.getElementById('nombre-usuario').value;
            alert(`¡Perfil actualizado con éxito para: ${nombre}!`);
        }

        function enviarReportePago() {
            let monto = parseFloat(document.getElementById('monto-pago').value);
            let ref = document.getElementById('ref-pago').value;
            if(!monto || !ref) { alert("Por favor completa el monto y la referencia."); return; }

            solicitudesRecarga.push({ id: Date.now(), monto: monto, ref: ref, numero: miNumeroAsignado });
            alert("¡Reporte enviado al operador con éxito!");
            document.getElementById('monto-pago').value = '';
            document.getElementById('ref-pago').value = '';
            renderizarAdmin();
        }

        function comprarPaquete(costo, nombrePaquete) {
            if(saldoActual < costo) {
                alert("Saldo insuficiente en tu billetera. Por favor reporta una recarga.");
                cambiarSeccion('billetera');
                return;
            }
            saldoActual -= costo;
            document.getElementById('saldo-usuario').innerText = `$${saldoActual.toFixed(2)}`;
            alert(`¡Has adquirido exitosamente el paquete: ${nombrePaquete}!`);
        }

        function marcarDigito(digito) {
            if(numeroMarcado.length < 18) {
                numeroMarcado += digito;
                document.getElementById('pantalla-marcador').innerText = numeroMarcado;
            }
        }

        function borrarDigito() {
            if(numeroMarcado.length > 9) {
                numeroMarcado = numeroMarcado.slice(0, -1);
                document.getElementById('pantalla-marcador').innerText = numeroMarcado;
            }
        }

        async function iniciarLlamadaReal() {
            if(numeroMarcado.length <= 9) { alert("Marca un número de destino válido."); return; }
            if(saldoActual < 0.10) { alert("Saldo insuficiente. Por favor recarga."); return; }

            let estado = document.getElementById('estado-llamada');
            let btnLlamar = document.getElementById('btn-llamar');
            let btnColgar = document.getElementById('btn-colgar');

            estado.innerHTML = `🔄 Conectando con ${numeroMarcado}...`;
            btnLlamar.style.display = 'none';

            try {
                if(!localStream) {
                    localStream = await navigator.mediaDevices.getUserMedia({ audio: true, video: false });
                }

                peerConnection = new RTCPeerConnection(servers);
                localStream.getTracks().forEach(track => { peerConnection.addTrack(track, localStream); });

                peerConnection.ontrack = (event) => {
                    document.getElementById('remote-audio').srcObject = event.streams[0];
                };

                let offer = await peerConnection.createOffer();
                await peerConnection.setLocalDescription(offer);

                setTimeout(() => {
                    estado.innerHTML = `🔊 Llamada activa con ${numeroMarcado} (-$0.10)`;
                    saldoActual -= 0.10;
                    document.getElementById('saldo-usuario').innerText = `$${saldoActual.toFixed(2)}`;
                    btnColgar.style.display = 'block';
                }, 1500);

            } catch (error) {
                console.error("Error de audio:", error);
                estado.innerHTML = "❌ Error de conexión de micrófono.";
                btnLlamar.style.display = 'block';
            }
        }

        function colgarLlamadaReal() {
            if(peerConnection) {
                peerConnection.close();
                peerConnection = null;
            }
            document.getElementById('estado-llamada').innerHTML = "🟢 Línea lista";
            document.getElementById('btn-colgar').style.display = 'none';
            document.getElementById('btn-llamar').style.display = 'block';
            numeroMarcado = "+58 500-";
            document.getElementById('pantalla-marcador').innerText = numeroMarcado;
        }

        function agregarNumeroAlPool() {
            let nuevoNum = document.getElementById('nuevo-num-pool').value;
            if(!nuevoNum) { alert("Ingresa un número válido."); return; }
            poolNumeros.push(nuevoNum);
            document.getElementById('nuevo-num-pool').value = '';
            renderizarAdmin();
            alert("¡Número agregado al pool con éxito!");
        }

        function renderizarAdmin() {
            let contenedorPool = document.getElementById('lista-pool-numeros');
            let htmlPool = "";
            poolNumeros.forEach(num => {
                htmlPool += `<div class="history-item"><span>📱 ${num}</span><span style="color:var(--accent-green);">Libre</span></div>`;
            });
            contenedorPool.innerHTML = htmlPool || "<div style='color:var(--text-muted); font-size:0.8rem;'>No hay números libres.</div>";

            let contenedorSol = document.getElementById('lista-solicitudes-admin');
            let htmlSol = "";
            solicitudesRecarga.forEach((sol, index) => {
                htmlSol += `
                    <div class="history-item" style="flex-direction:column; align-items:flex-start; gap:6px;">
                        <div><strong>Línea:</strong> ${sol.numero}</div>
                        <div><strong>Monto:</strong> $${sol.monto} | <strong>Ref:</strong> ${sol.ref}</div>
                        <button class="btn" style="background:var(--accent-green); padding:6px; font-size:0.8rem;" onclick="aprobarRecarga(${index})">✅ Aprobar Saldo</button>
                    </div>
                `;
            });
            contenedorSol.innerHTML = htmlSol || "<div style='color:var(--text-muted); font-size:0.8rem; text-align:center;'>No hay solicitudes pendientes.</div>";
        }

        function aprobarRecarga(index) {
            let sol = solicitudesRecarga[index];
            saldoActual += sol.monto;
            document.getElementById('saldo-usuario').innerText = `$${saldoActual.toFixed(2)}`;
            alert(`¡Recarga aprobada para la línea ${sol.numero}!`);
            solicitudesRecarga.splice(index, 1);
            renderizarAdmin();
        }
    </script>
</body>
</html>
