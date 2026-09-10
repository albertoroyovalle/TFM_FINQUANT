# Black-Scholes y Heston: una comparación teórica y práctica de modelos de valoración de opciones

Trabajo Fin de Máster (Máster en Finanzas Cuantitativas, UNED) sobre modelos de valoración de opciones: desarrollo teórico e implementación numérica de Black-Scholes y del modelo de volatilidad estocástica de Heston.

Este repositorio contiene los notebooks de Python con las implementaciones numéricas asociadas al trabajo.

## Contenido

- `1_fundamentos_estocasticos.ipynb` — Simulación numérica de SDEs: movimiento browniano, integral de Itô vs. Stratonovich, Ornstein-Uhlenbeck (Euler-Maruyama y Milstein).
- `2_black_scholes.ipynb` — Black-Scholes: simulación de la SDE (Euler-Maruyama, Milstein), pricing por Monte Carlo, diferencias finitas (Crank-Nicolson) y comparación con la fórmula cerrada.
- `3_heston_implementacion.ipynb` — Modelo de Heston: función característica, pricing semi-analítico (inversión de Gil-Pelaez), pricing por Monte Carlo, sonrisa de volatilidad frente a datos reales (SPY) y calibración aproximada de los parámetros.

## Requisitos

- Python 3.10+
- numpy, scipy, matplotlib, yfinance

Instalación rápida:

```bash
pip install numpy scipy matplotlib yfinance
```

## Uso

Cada notebook es independiente y puede ejecutarse de arriba a abajo con Jupyter:

```bash
jupyter notebook
```

## Autor

Alberto Royo Valle — Máster en Finanzas Cuantitativas, UNED (2025/2026)
