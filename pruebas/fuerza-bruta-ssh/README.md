# Prueba: Ataque de fuerza bruta SSH

## Objetivo
Simular un ataque de fuerza bruta por SSH desde Kali Linux contra Ubuntu, y verificar que Wazuh lo detecte y genere alertas.

## Procedimiento
Desde Kali se intentó autenticar varias veces por SSH contra Ubuntu (192.168.0.13) con credenciales incorrectas.

```bash
ssh -l victima 192.168.0.13
