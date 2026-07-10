# 🔌 Constante de Tiempo en Circuitos RC y RL

Esta herramienta permite calcular la **constante de tiempo** en circuitos **RC (Resistencia-Capacitor)** y **RL (Resistencia-Inductor)**, y analizar los procesos de carga y descarga exponencial.

---

## 🎯 ¿Qué es la constante de tiempo?

La constante de tiempo (τ) es el tiempo necesario para que un capacitor o inductor alcance el **63.2%** de su valor final durante la carga, o caiga al **36.8%** durante la descarga.

### Fórmulas principales

| Circuito | Constante de tiempo (τ) | Carga | Descarga |
|----------|-------------------------|-------|----------|
| **RC** | τ = R × C | Vc(t) = Vf × (1 - e^(-t/τ)) | Vc(t) = Vi × e^(-t/τ) |
| **RL** | τ = L / R | I(t) = If × (1 - e^(-t/τ)) | I(t) = Ii × e^(-t/τ) |

---

## 📋 Parámetros y unidades

| Parámetro | Símbolo | Unidad |
|-----------|---------|--------|
| Resistencia | R | Ohmios (Ω) |
| Capacitancia | C | Faradios (F) |
| Inductancia | L | Henrios (H) |
| Constante de tiempo | τ | Segundos (s) |

---

## 📝 Ejemplo de uso

### Circuito RC

**Datos de entrada:**

| Parámetro | Valor |
|-----------|-------|
| Resistencia (R) | 10 kΩ (10,000 Ω) |
| Capacitancia (C) | 100 µF (0.0001 F) |
| Voltaje de la fuente | 12 V |

**Cálculo:**
τ = R × C = 10,000 × 0.0001 = 1 segundo

text

**Resultado:** La constante de tiempo es de **1 segundo**. El capacitor tardará aproximadamente 5 segundos (5τ) en cargarse completamente.

### Circuito RL

**Datos de entrada:**

| Parámetro | Valor |
|-----------|-------|
| Inductancia (L) | 10 mH (0.01 H) |
| Resistencia (R) | 100 Ω |
| Corriente de la fuente | 2 A |

**Cálculo:**
τ = L / R = 0.01 / 100 = 0.0001 segundos = 0.1 ms

text

**Resultado:** La constante de tiempo es de **0.1 ms**. La corriente alcanzará su valor final en aproximadamente 0.5 ms (5τ).

---

## 🛠️ Solución de problemas

| Problema | Solución |
|----------|----------|
| **El resultado no coincide** | Verificar que las unidades sean correctas (Ω, F, H) |
| **Error en los valores** | Asegurarse de que la resistencia y capacitancia/inductancia estén en las unidades adecuadas |

---

## 📚 Referencias

- [Constante de tiempo RC](https://es.wikipedia.org/wiki/Circuito_RC)
- [Constante de tiempo RL](https://es.wikipedia.org/wiki/Circuito_RL)
