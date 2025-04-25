# 📺 yt-latest-fetcher

Este script en Python permite obtener el video más reciente de cualquier canal de YouTube utilizando peticiones HTTP y expresiones regulares. 

## 🚀 Funcionalidad

El script permite ingresar:
- El **nombre del canal**, o
- Un **enlace directo al canal de YouTube**

Y devuelve:
- El **enlace al video más reciente** publicado por ese canal.

## 🧰 Tecnologías utilizadas

- `requests`: Para realizar peticiones GET a las URLs de los canales.
- `re`: Para aplicar expresiones regulares que extraen el ID del video más reciente.

## 📈 Enfoque progresivo

A lo largo del código, se documentan múltiples formas de mejorar el proceso de automatización, partiendo de una solución básica hasta versiones más robustas y reutilizables. Esto permite comprender mejor cada etapa y adaptarla fácilmente a distintos escenarios.

## 📝 Uso

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/yt-latest-fetcher.git
   cd yt-latest-fetcher
