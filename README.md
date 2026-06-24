# 🛡️ Sistema de Detección de Intrusos (NIDS) con Snort y EFK Stack

## 📝 Descripción
Este repositorio contiene la documentación y configuración de un Sistema de Detección de Intrusos en red (NIDS) desplegado como Proyecto Final del Ciclo de Sistemas Microinformáticos y Redes (SMR). El entorno está diseñado para monitorizar tráfico en tiempo real, detectar amenazas y visualizar alertas mediante un sistema SIEM.

## 🛠️ Tecnologías y Herramientas
*   **Sistema Operativo:** Ubuntu Server
*   **Redes:** Netplan
*   **IDS:** Snort (Modo NIDS)
*   **SIEM (Stack EFK):** Elasticsearch, Filebeat, Kibana
*   **Pruebas de Seguridad:** Nmap, ataques controlados (inundaciones ICMP)

## ⚙️ Implementación y Configuración

### 1. Infraestructura de Red
*   Despliegue de entorno sobre **Ubuntu Server**.
*   Configuración estricta de las interfaces de red utilizando **Netplan**.

### 2. Detección de Intrusos (Snort)
*   Instalación y configuración de **Snort** operando en modo NIDS.
*   Definición de reglas personalizadas para la detección de:
    *   Escaneos de puertos.
    *   Accesos no autorizados.
    *   Tráfico de red anómalo.

### 3. Monitorización y SIEM (Stack EFK)
*   Implementación del stack **EFK** para la centralización y análisis de eventos de seguridad.
*   Configuración de **Filebeat** para la ingesta y el envío eficiente de logs desde Snort hacia **Elasticsearch**.
*   Creación de dashboards en **Kibana** para la visualización de alertas en tiempo real.

## 🧪 Fase de Pruebas y Validación
Para asegurar la eficacia de las reglas de Snort y la correcta visualización en Kibana, se realizaron auditorías y ataques controlados, incluyendo:
*   Escaneos agresivos y de descubrimiento de servicios mediante **Nmap**.
*   Ataques de denegación de servicio (DoS) mediante inundaciones **ICMP**.

---
*Proyecto desarrollado de forma individual.* 
**Autor:** [Raúl Dumitrean](https://github.com/rauldumitrean)
