# VirtualSystems_PIS_2026

Repositorio correspondiente a la asignatura **Virtual Systems and Services**, orientada a la configuración del entorno de virtualización y al despliegue inicial de máquinas virtuales.

## 1. Descripción

Este repositorio tiene como propósito gestionar y versionar la configuración, documentación y evidencias relacionadas con la infraestructura virtual utilizada durante la práctica.

La infraestructura contempla el uso de:

* **VirtualBox** como hipervisor de tipo 2 para la virtualización local.
* **Microsoft Azure** como plataforma de nube pública para el despliegue de una máquina virtual.
* **AWS Academy** para la validación del entorno de servicios en la nube.
* **GitHub** como plataforma de control de versiones para la gestión del proyecto.

## 2. Arquitectura inicial

La arquitectura de la práctica está compuesta por dos entornos principales de virtualización:

```text
                    INFRAESTRUCTURA DE VIRTUALIZACIÓN
                              │
              ┌───────────────┴───────────────┐
              │                               │
       VIRTUALIZACIÓN LOCAL             NUBE PÚBLICA
              │                               │
          VirtualBox                       Azure
       Hipervisor Tipo 2                     │
              │                         Azure-VM-01
              │                         Ubuntu Server
       Local-VM-01
       Ubuntu Server
              │
       Equipo anfitrión
```

## 3. Recursos principales

| Recurso     | Plataforma           | Propósito                            |
| ----------- | -------------------- | ------------------------------------ |
| Local-VM-01 | VirtualBox           | Máquina virtual local                |
| Azure-VM-01 | Microsoft Azure      | Máquina virtual en la nube           |
| AWS Academy | AWS                  | Validación del entorno cloud         |
| GitHub      | Control de versiones | Gestión y documentación del proyecto |

## 4. Objetivos de la infraestructura

* Preparar un entorno base de virtualización para el Proyecto Integrador de Saberes (P.I.S.).
* Desplegar máquinas virtuales en un entorno local y uno de nube pública.
* Analizar la asignación y utilización de recursos virtuales.
* Comparar conceptualmente la virtualización local con la virtualización en la nube.
* Mantener la documentación y configuración del proyecto bajo control de versiones.

## 5. Estructura inicial del repositorio

```text
VirtualSystems_PIS_2026/
│
├── README.md
│
└── evidencias/
    ├── parte-a/
    └── parte-b/
```

La carpeta `evidencias/` permitirá organizar las capturas y documentación generadas durante el desarrollo de la práctica.

## 6. Tecnologías y herramientas

* Oracle VM VirtualBox
* Microsoft Azure
* AWS Academy
* Ubuntu Server
* Git
* GitHub
* SSH

## 7. Estado del proyecto

**Estado:** Configuración inicial del entorno.

Las siguientes etapas corresponden al despliegue y parametrización de las máquinas virtuales local en Azure o AWS.
