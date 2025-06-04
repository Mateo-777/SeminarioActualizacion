# 🪙 Análisis de la Primera Versión de Bitcoin

![Bitcoin Logo](https://upload.wikimedia.org/wikipedia/commons/4/46/Bitcoin.svg)

##  Introducción

La primera versión de **Bitcoin (v0.1)** fue lanzada por Satoshi Nakamoto el **9 de enero de 2009**, marcando el nacimiento del sistema de efectivo digital descentralizado más influyente hasta hoy.

Este documento resume las ideas clave y limitaciones técnicas de esa versión inicial.

---

## Características Clave de Bitcoin v0.1

| Característica           | Descripción                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Lenguaje                 | C++                                                                         |
| Plataforma               | Windows XP (binario precompilado)                                           |
| Algoritmo de Consenso    | Prueba de trabajo (Proof-of-Work, SHA-256)                                  |
| Bloque Génesis           | Bloque 0 minado el 3 de enero de 2009                                       |
| Recompensa               | 50 BTC por bloque                                                           |
| Intervalo de Bloques     | Aproximadamente cada 10 minutos                                             |
| Límite de Suministro     | No incluido aún en el código (pero descrito en el paper: 21 millones)       |

---
##  ¿Por qué se creó?
Bitcoin fue diseñado como una respuesta directa a la desconfianza en las instituciones financieras tradicionales, buscando ofrecer:

- Un sistema de pagos descentralizado, sin bancos ni intermediarios.

- Una alternativa al dinero fiduciario, con una oferta limitada y controlada (21 millones de bitcoins).

- Un libro de cuentas público (blockchain) que asegurara transparencia, verificabilidad y resistencia a la censura.
---
## Primeros hitos históricos
### 3 de enero de 2009: Bloque Génesis
- Se mina el primer bloque de Bitcoin (Bloque 0).

### 9 de enero de 2009: Publicación de la versión 0.1 del software
- Satoshi lanza el código fuente en C++.
- Solo unos pocos entusiastas en foros de criptografía lo descargan.

### Mayo de 2010: Primera transacción comercial con Bitcoin
- El programador Laszlo Hanyecz compra 2 pizzas por 10,000 BTC.
- Hoy eso equivaldría a cientos de millones de dólares
- Este evento es celebrado cada año como el Bitcoin Pizza Day.

---
##  Elementos Técnicos

###  Estructura básica

- El software incluía una **interfaz gráfica (GUI)** rudimentaria.
- Tenía su propio monedero, nodo y minero integrados.
- No existía aún el concepto de nodos ligeros (SPV wallets).
- Estableció las bases para miles de criptomonedas posteriores y contratos inteligentes.

###  Seguridad

- Todas las transacciones se validaban mediante firmas digitales y se almacenaban en una cadena de bloques.
- La dificultad de minería era estática en el primer bloque; no había ajuste dinámico inmediato.

---

##  Limitaciones Identificadas

1. **No había protección contra ataques de Sybil** (limitado solo por el bajo uso).
2. **No existía separación entre nodo y monedero**.
3. **No existía scripting avanzado** para contratos inteligentes.
4. **Difusión limitada**: solo unos pocos usuarios técnicos podían usarlo al inicio.

---

## Evolución Posterior

- Las versiones posteriores introdujeron:
  - **Ajuste de dificultad**
  - **Direcciones base58**
  - **Segregated Witness (años después)**
  - **Mejoras en seguridad y portabilidad multiplataforma**

---

## Referencias

- Whitepaper original: [bitcoin.org/bitcoin.pdf](https://bitcoin.org/bitcoin.pdf)
- Código fuente inicial en C++ (vía archive): [github.com/bitcoin/bitcoin](https://github.com/bitcoin/bitcoin)
- Historia técnica: [History of Bitcoin codebase](https://github.com/bitcoin/bitcoin/commits/master)

---


