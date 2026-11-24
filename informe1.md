<<<<<<< HEAD
#3. Análisis de las THD en Microsoft

#3.1. Cloud Computing e Infraestructura Híbrida
Definición: Suministro bajo demanda de servidores, almacenamiento y software por Internet mediante pago por uso [1].
Informe THD: Microsoft · 1º DAW - DIGIPage 1 of 3
Características: Escalabilidad global (+60 regiones), modelos IaaS/PaaS/SaaS y gestión híbrida unificada.
Aplicación en Microsoft: Aloja Microsoft 365 (Teams, Outlook) y GitHub sobre Microsoft Azure [2] para dar servicio a millones de usuarios simultáneos.
Mejora IT-OT: Mediante Azure Arc, controla servidores situados en plantas industriales (OT) desde la nube corporativa (IT).

#3.2. Inteligencia Artificial Generativa y Machine Learning
Definición: Sistemas capaces de aprender patrones de datos para generar código, texto o diagnósticos técnicos.
Características: Modelos multimodales, chips propios de baja latencia (Azure Maia 100) [3] y protección de datos internos (RAG).
Aplicación en Microsoft: Integra modelos GPT en Azure OpenAI y GitHub Copilot [4], usado a diario por más de 100.000 desarrolladores internos para programar y revisar código.
Mejora IT-OT: Azure Machine Learning detecta fallos en sensores de fábrica (OT) y envía avisos al software de gestión empresarial (IT).

#3.3. Internet de las Cosas Industrial (IIoT) y Edge Computing
Definición: Conexión en red de sensores y máquinas industriales (IIoT) procesando datos junto al equipo (Edge) para evitar retardos [5].
Características: Soporte de protocolos industriales (OPC UA, MQTT), funcionamiento local sin Internet y gemelos digitales.
Aplicación en Microsoft: Desarrolla Azure IoT Operations y lo aplica en sus propios centros de datos para controlar energía y refrigeración [6].
Mejora IT-OT: Azure IoT Edge traduce las señales de maquinaria (OT) hacia bases de datos analíticas de oficina (IT) como Microsoft Fabric.

#3.4. Ciberseguridad Zero Trust
Definición: Modelo de defensa que verifica continuamente cada usuario y dispositivo sin confiar por defecto en ninguno [7].

Características: Autenticación multifactor continua (MFA), acceso con privilegios mínimos y bloqueo automático de amenazas.

Aplicación en Microsoft: Protege sus repositorios de código y redes internas con Microsoft Entra ID, Defender y Sentinel [8].

Mejora IT-OT: Microsoft Defender for IoT supervisa redes industriales (OT) sin detener las máquinas y centraliza sus alertas en el panel de seguridad de oficina (IT).
Informe THD: Microsoft · 1º DAW - DIGIPage 2 of 3

# THD
    Solución en Microsoft
    Impacto en la convergencia IT-OT
    
    Cloud Computing
    Microsoft Azure y Azure Arc
    Control remoto de servidores de fábrica desde la nube corporativa.
    
    IA Generativa y ML
    Azure OpenAI y GitHub Copilot
    Transforma datos de sensores en avisos claros para el ERP.
    
    IIoT y Edge
    Azure IoT Operations
    Traduce señales de máquinas industriales hacia bases de datos IT.
    
    Ciberseguridad
    Defender for IoT y Sentinel
    Unifica la vigilancia de amenazas de fábrica y oficina en un panel.
=======
## Conclusiones
THD más determinante: El Cloud Computing e Infraestructura Híbrida (Microsoft Azure) es la tecnología clave del modelo de negocio de Microsoft, ya que actúa como plataforma base sobre la que funcionan su IA, el IoT y la ciberseguridad, genera sus mayores ingresos recurrentes y permite unir de forma segura los entornos industriales (OT) con los sistemas corporativos (IT).

## 5. Fuentes
NIST. (2011). The NIST Definition of Cloud Computing (SP 800-145). (Cloud Computing).
Microsoft Learn. (2024). Guía de arquitectura híbrida de Azure con Azure Arc. (Cloud Computing).
Microsoft News. (2023). Chips propios de Microsoft para IA: Azure Maia 100 y Cobalt 100. (IA Generativa).
Microsoft Learn. (2024). Arquitectura y privacidad en Azure OpenAI Service y Copilot. (IA Generativa).
Microsoft Learn. (2024). Arquitectura de referencia de Azure IoT Operations. (IIoT y Edge).
Microsoft Datacenters. (2024). Telemetría IoT y eficiencia energética en centros de datos. (IIoT y Edge).
Microsoft Security. (2024). Centro de orientación de arquitectura Zero Trust. (Ciberseguridad).
Microsoft Learn. (2024). Supervisión de redes OT con Microsoft Defender for IoT y Sentinel. Cibersegurida
>>>>>>> b846673dda9f4134cb04c6f7001821d6fc7c4fef

