# 🖥️ DARNEYLAB — Infraestructura de Homelab

Proyecto de infraestructura propio: diseño, despliegue y administración de un entorno completo con Active Directory, PKI interna, clúster Kubernetes en alta disponibilidad, segmentación de red, firewall, VPN y seguridad.

Documentado fase por fase como registro técnico del trabajo realizado.

---

## 🏗️ Infraestructura

| Componente | Detalle |
|---|---|
| Nodo 1 (k3s) | Lenovo M90q — Ubuntu Server |
| Nodo 2 (k3s) | Lenovo M700 — Ubuntu Server |
| Nodo 3 (k3s) | Lenovo M700 — Ubuntu Server |
| Servidor Windows | Lenovo M710 — Windows Server 2022 (Active Directory + CA interna) |
| Firewall | Lenovo M700 — OPNsense |
| Switch principal | TP-Link SG608E |
| Switches de laboratorio | Cisco 2950 / Cisco 2960 |

## 📍 Topología de Red

![Topología DARNEYLAB](TOPOLOGIA%20RED%20HOMELAB%20DARNEYLAB.jpg)

## 🧪 Fase 2 — Simulación de VLANs y Routing (Cisco Packet Tracer)

Antes de aplicar la segmentación en los switches Cisco reales del laboratorio (2950/2960), se diseñó y validó el escenario completo en Cisco Packet Tracer: routing inter-VLAN, conectividad entre segmentos y comportamiento esperado antes de tocar el hardware físico.

![Simulación Packet Tracer](PACKET_TRACER_VLANS_SIMULACION.png.PNG)

---

## 🗺️ Progreso del Proyecto

| Fase | Estado |
|---|---|
| Fase 1 — Topología y segmentación VLANs | ✅ Completado |
| Fase 2 — Simulación VLANs (Packet Tracer) | ✅ Completado |
| Fase 3 — Active Directory (AD DS + CA/PKI interna) | ✅ Completado |
| Fase 4 — OPNsense (NAT, routing, firewall) | ✅ Completado |
| Fase 5 — Kubernetes (k3s, 3 nodos en alta disponibilidad) | ✅ Completado |
| Fase 6 — VPN WireGuard (acceso remoto) | ✅ Completado |
| Fase 7 — Almacenamiento distribuido (Longhorn) | 🔨 En construcción |
| Fase 8 — Hardening y seguridad | 🔨 En construcción |

---

## 📬 Contacto

- 💼 [LinkedIn](https://www.linkedin.com/in/didhier-palacios)
- 📧 didhierpalacios@gmail.com
