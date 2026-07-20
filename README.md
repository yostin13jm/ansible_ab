# ansible_ab
# Laboratorio de Ansible con Docker

## Objetivo

Aprender a administrar varios servidores Docker utilizando Ansible mediante un inventario y un playbook.

## Archivos del laboratorio

- docker-compose.yml
- inventory.ini
- playbook.yml
- README.md

## Levantar los contenedores

```bash
docker compose up -d
```

## Verificar los contenedores

```bash
docker ps
```

## Ejecutar el playbook

```bash
ansible-playbook -i inventory.ini playbook.yml
```

## Captura de pantalla
![Ejecución del playbook](imagen/Captura de pantalla 2026-07-20 165050), (imagen/Captura de pantalla 2026-07-20 165129)

