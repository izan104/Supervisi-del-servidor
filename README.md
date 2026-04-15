# Supervisi-del-servidor
# 🖥️ Supervisió del sistema en Windows

## 📌 Descripción
Esta práctica consiste en el análisis del rendimiento de un sistema operativo Windows mediante las herramientas **Resource Monitor** y **Performance Monitor**. Se estudia el uso de CPU, memoria, disco y red para evaluar el estado del sistema.

---

# 📊 EXERCICI 1 – Resource Monitor

## 🎯 Objetivo
Analizar el uso de recursos del sistema en tiempo real utilizando el monitor de recursos de Windows.

---

## 🔧 Acceso a la herramienta
- `Windows + R` → `resmon`
- `Ctrl + Shift + Esc` → pestaña Rendimiento → Monitor de recursos

---

## 🧠 CPU
- SearchApp → 0%
- System → 32%
- Chrome → 29%

👉 El consumo de CPU es moderado y está repartido entre procesos del sistema y aplicaciones de usuario.

---

## 💾 Memoria RAM
- Total: 2044 MB
- En uso: 1522 MB
- Proceso principal: MsMpEng.exe (~300 MB)

👉 Uso estable de memoria sin saturación.

---

## 💽 Disco
- Proceso con mayor actividad: msedge.exe
- Actividad: lectura/escritura de archivos del sistema y navegación

---

## 🌐 Red
- Actividad baja
- Procesos activos:
  - msedge.exe
  - svchost.exe

---

## 📌 Conclusión
El sistema funciona correctamente sin problemas de rendimiento. Los recursos se mantienen en niveles normales.

---

# 📈 EXERCICI 2 – Performance Monitor

## 🎯 Objetivo
Analizar el rendimiento del sistema de forma avanzada mediante contadores de rendimiento.

---

## 🔧 Acceso a la herramienta
- `Windows + R` → `perfmon`
- Buscador de Windows → Performance Monitor

---

## 📊 Contadores utilizados

### 🧠 CPU – % Processor Time
- Mide el uso del procesador
- Permite detectar sobrecarga del sistema

### 💾 Memory – Available MBytes
- Mide la memoria RAM disponible
- Permite detectar falta de memoria

### 💽 Disk – % Disk Time
- Mide el tiempo de actividad del disco
- Permite detectar cuellos de botella

---

## 📉 Resultados

- CPU: < 20% constante
- Memoria: estable y suficiente
- Disco: uso bajo y sin saturación

👉 El sistema presenta un funcionamiento normal.

---

## 📸 Captura
(Añadir aquí la captura del Performance Monitor con los contadores activos)

---

## 📌 Conclusión final
El sistema no presenta problemas de rendimiento. Todos los recursos se mantienen dentro de valores normales.

### 🔧 Posibles mejoras:
- Cerrar procesos innecesarios
- Ampliar RAM si aumenta la carga
- Sustituir disco HDD por SSD
- Reducir programas de inicio

---

## 👤 Autor
Ethan Rascón Domínguez  
CFGM Sistemas Microinformáticos y Redes  
Institut Escola del Treball – Barcelona
