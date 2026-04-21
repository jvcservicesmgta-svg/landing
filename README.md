<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <style>
        @page {
            size: A4;
            margin: 0;
            background-color: #0b0e14;
        }
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #e6edf3;
        }
        .container {
            width: 210mm;
            height: 297mm;
            position: relative;
            overflow: hidden;
        }
        .header {
            background-color: #161b22;
            padding: 40px 50px;
            border-bottom: 4px solid #ff6600;
        }
        .brand {
            font-size: 26pt;
            font-weight: 800;
            color: #ffffff;
            margin: 0;
            letter-spacing: 1px;
        }
        .brand span {
            color: #ff6600;
        }
        .tagline {
            font-size: 11pt;
            color: #8b949e;
            margin-top: 5px;
            text-transform: uppercase;
        }
        .content {
            padding: 40px 50px;
        }
        .hero-title {
            font-size: 24pt;
            color: #ffffff;
            margin-bottom: 15px;
            line-height: 1.2;
        }
        .hero-subtitle {
            font-size: 12pt;
            color: #c9d1d9;
            margin-bottom: 35px;
            max-width: 600px;
        }
        .section-title {
            font-size: 14pt;
            color: #58a6ff;
            text-transform: uppercase;
            margin-bottom: 20px;
            border-left: 4px solid #58a6ff;
            padding-left: 12px;
        }
        .service-card {
            background: #1c2128;
            border: 1px solid #30363d;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 15px;
        }
        .service-card h3 {
            margin: 0 0 10px 0;
            font-size: 13pt;
            color: #ff6600;
        }
        .service-card p {
            margin: 0;
            font-size: 10pt;
            color: #c9d1d9;
            line-height: 1.4;
        }
        .highlight-box {
            background-color: rgba(88, 166, 255, 0.1);
            border-left: 3px solid #58a6ff;
            padding: 8px 12px;
            margin-top: 10px;
            font-size: 9pt;
            font-style: italic;
        }
        .footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            background: #161b22;
            padding: 30px 50px;
            box-sizing: border-box;
            border-top: 1px solid #30363d;
        }
        .contact-table {
            width: 100%;
        }
        .contact-cell {
            vertical-align: top;
            font-size: 10pt;
            color: #8b949e;
        }
        .highlight {
            color: #ffffff;
            font-weight: bold;
        }
        .cta-box {
            background: linear-gradient(90deg, #ff6600 0%, #ff8c00 100%);
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <p class="brand">JVCservices<span>_mgta</span></p>
            <p class="tagline">Tecnología de Datos & Automatización Inteligente</p>
        </div>

        <div class="content">
            <h1 class="hero-title">Elevamos la eficiencia de su empresa al siguiente nivel</h1>
            <p class="hero-subtitle">Especialistas en transformar sistemas tradicionales en ecosistemas inteligentes y automatizados.</p>

            <h2 class="section-title">Nuestras Soluciones</h2>
            
            <div class="service-card">
                <h3>1. BI, Reportes Web & Soporte ERP</h3>
                <p>Conectamos su sistema administrativo (Profit Plus, saint, d3xd, Valery) a Dashboards dinámicos para control de ventas, cobranzas y nómina en tiempo real.</p>
                <div class="highlight-box">
                    <strong>Optimización Especializada:</strong> Incluye la <strong>automatización de la tasa BCV</strong> directamente en su sistema, eliminando procesos manuales y errores en facturación.
                </div>
            </div>

            <div class="service-card">
                <h3>2. Agentes IA & Mensajería 24/7</h3>
                <p>Implementamos agentes inteligentes capaces de gestionar el flujo de mensajes en WhatsApp e Instagram y responder correos de forma autónoma. Atención inmediata y cierre de ventas sin intervención humana constante.</p>
            </div>

            <div class="service-card">
                <h3>3. Suministro de Hardware de Alta Gama</h3>
                <p>Equipamiento tecnológico diseñado para el alto rendimiento retail: Servidores SQL, estaciones de auto-pago, pantallas touch screen, impresoras térmicas y estaciones de trabajo configuradas.</p>
            </div>

            <h2 class="section-title">¿Por qué JVCservices_mgta?</h2>
            <p style="font-size: 10pt; color: #c9d1d9; line-height: 1.6;">
                • <strong>Expertos en Profit Plus:</strong> Conocimiento profundo de la estructura de datos para integraciones sin errores.<br>
                • <strong>Transformación Digital Real:</strong> De tareas manuales lentas a procesos automáticos precisos.<br>
                • <strong>Soporte Local Integral:</strong> Hardware y Software atendidos por el mismo equipo técnico en la Isla de Margarita.
            </p>

            <div class="cta-box">
                IMPULSE SU OPERATIVIDAD HOY MISMO
            </div>
        </div>

        <div class="footer">
            <table class="contact-table">
                <tr>
                    <td class="contact-cell">
                        <span class="highlight">WhatsApp:</span> +58 412-1118743<br>
                        <span class="highlight">Instagram:</span> @jvcservices_mgta
                    </td>
                    <td class="contact-cell" style="text-align: right;">
                        <span class="highlight">Email:</span> jvcservices.mgta@gmail.com<br>
                        <span class="highlight">Ubicación:</span> Isla de Margarita, Venezuela
                    </td>
                </tr>
            </table>
        </div>
    </div>
</body>
</html>
