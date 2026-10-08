# Wazuh Home Lab

Laboratorio de ciberseguridad realizado en un entorno virtual para practicar monitoreo, detección y análisis de eventos de seguridad.

## Arquitectura

- **Kali Linux:** máquina atacante
- **Ubuntu:** máquina víctima
- **Wazuh:** plataforma de monitoreo y detección

## Objetivo

Simular diferentes actividades de seguridad desde Kali Linux contra Ubuntu y analizar cómo Wazuh registra y detecta los eventos.

## Tecnologías utilizadas

- Kali Linux
- Ubuntu
- Wazuh
- Virtualización
- Linux

## Desafíos técnicos

Las máquinas virtuales priorizaban IPv6 por defecto, lo que generaba 
problemas de conectividad entre ellas. Se identificó la causa y se 
solucionó deshabilitando IPv6 y configurando IPs estáticas en modo 
puente, logrando comunicación estable entre Kali, Ubuntu y Wazuh.
