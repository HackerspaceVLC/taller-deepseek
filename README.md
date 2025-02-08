# Guía de Instalación: Taller de DeepSeek R1 con Ollama

## Introducción
En este taller aprenderemos a ejecutar modelos de IA localmente usando Ollama. Esta guía te ayudará a preparar tu entorno antes del taller.

## Requisitos del Sistema
- RAM: Mínimo 8GB (recomendado 16GB o más para modelos más grandes)
- Espacio en disco: 10GB mínimo recomendado
- Opcional pero recomendado: Tarjeta gráfica NVIDIA (mejorará significativamente el rendimiento)
- Sistema Operativo: Windows, macOS o Linux

## Pasos de Instalación

### 1. Instalar Ollama

#### Para Linux:
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

#### Para Windows:
1. Visitar https://ollama.com/
2. Descargar el instalador (.exe)
3. Ejecutar el instalador
4. Seguir las instrucciones en pantalla

#### Para macOS:
1. Visitar https://ollama.com/
2. Descargar el instalador para macOS
3. Instalar siguiendo las instrucciones

### 2. Descargar el Modelo

Una vez instalado Ollama, ejecuta el siguiente comando en la terminal:

```bash
ollama run deepseek-r1:1.5b
```

Este comando descargará e iniciará el modelo que usaremos en el taller.

## Notas Importantes sobre Recursos

### Requerimientos de RAM
- El consumo de RAM aproximado es 1.2GB por cada billón de parámetros
- Ejemplo: Un modelo de 8B parámetros necesitará aproximadamente 9.6GB de RAM
- Si tienes más RAM disponible, podrás usar modelos más grandes

### GPU vs CPU
- Si tienes una tarjeta gráfica NVIDIA, el modelo funcionará más rápido
- Si no tienes GPU, el modelo funcionará correctamente usando CPU, solo será algo más lento

## Verificación de la Instalación
Para verificar que todo está funcionando correctamente:
1. Abre una terminal
2. Ejecuta el comando de descarga del modelo
3. Espera a que termine la descarga
4. El modelo comenzará a ejecutarse y podrás interactuar con él

## Solución de Problemas
Si encuentras algún problema durante la instalación:
1. Verifica que cumples con los requisitos mínimos del sistema
2. Asegúrate de tener una conexión estable a internet
3. Revisa que tienes suficiente espacio en disco
4. Consulta la documentación oficial en https://ollama.com/ para problemas específicos

## Siguiente Paso
Una vez completada la instalación, estarás listo para comenzar el taller. Asegúrate de tener todo instalado y funcionando antes del inicio del taller para aprovechar al máximo el tiempo.
