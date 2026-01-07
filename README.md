# Modelos 3D – Configurador

Este repositorio contiene modelos 3D en formato `.glb` para usarse en el configurador.

---

## 📁 Estructura de carpetas

models/
├─ muebles/
│ ├─ silla_basica.glb
│ ├─ escritorio_120.glb
│ └─ escritorio_160.glb
├─ accesorios/
│ └─ cajonera.glb


---

## 📦 Reglas para subir modelos

- Formato: **.glb**
- Escala real (1 unidad = 1 metro)
- Sin luces
- Sin cámaras
- Sin animaciones
- Texturas embebidas en el GLB
- Peso recomendado: **menos de 20 MB**

---

## 🎯 Convenciones

- El modelo debe estar centrado correctamente
- El piso del modelo debe tocar Z = 0
- El nombre del archivo debe describir el modelo

Ejemplo:


escritorio_120.glb
silla_operativa.glb


---

## ⬆️ Cómo subir un modelo

1. Copia el archivo `.glb` dentro de la carpeta `models/`
2. En terminal:

```bash
git add models/
git commit -m "subo modelo glb"
git push
