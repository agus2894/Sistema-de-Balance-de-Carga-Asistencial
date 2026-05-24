# 🏥 Sistema de Balance de Carga Asistencial

Sistema web para gestionar la distribución de enfermeros entre diferentes áreas de un hospital, optimizando los ratios paciente-enfermero en tiempo real.

## 📋 ¿Qué hace?

Permite administrar y visualizar la carga de trabajo en 4 sectores hospitalarios:
- **UTI** (Unidad de Terapia Intensiva)
- **Intermedia**
- **Cuidados Generales**
- **Guardia**

## ✨ Funcionalidades

- 🔄 **Gestión de Personal**: Modifica la cantidad de pacientes y enfermeros por sector
- 📊 **Indicadores Visuales**: Colores según nivel de saturación (Verde/Amarillo/Rojo)
- 🔀 **Transferencias**: Mueve enfermeros entre sectores con seguimiento
- 🕐 **Turnos**: Configuración independiente para Mañana, Tarde y Noche
- 💾 **Auto-guardado**: Los datos se guardan automáticamente en el navegador
- 📱 **Responsive**: Funciona en computadoras, tablets y celulares

## 🎯 Niveles de Saturación

- 🟢 **Normal**: Ratio ≤ 80% del máximo
- 🟡 **Alerta**: Ratio entre 80-100%
- 🔴 **Crítico**: Ratio > 100%

## 🚀 Cómo usar

1. Abre `dashboard.html` en cualquier navegador web
2. Selecciona el turno (Mañana/Tarde/Noche)
3. Configura el plantel base con el botón verde
4. Modifica pacientes y enfermeros según necesidad
5. Usa los botones de transferencia para mover personal entre sectores
6. Los cambios se guardan automáticamente

## 💡 Consejos

- **Modificar números directamente**: Solo afecta ese sector (útil para ausencias/licencias)
- **Botones de transferencia**: Mueven personal entre sectores con seguimiento
- **Botón ↻**: Restablece al plantel base configurado
- **Cada turno es independiente**: Los cambios no afectan otros turnos

## 🛠️ Tecnologías

- HTML5
- JavaScript (Vanilla)
- Tailwind CSS
- LocalStorage para persistencia

## 📄 Licencia

Proyecto de uso interno hospitalario.
