# Bot de Trading con Backtrader- Version Mejorada

Este repositorio contiene una versión mejorada de un bot de trading desarrollado con Backtrader. Se han implementado mejoras significativas, como el uso de Stop-Loss y Take-Profit, así como un filtrado adicional con Medias Móviles para mejorar la calidad de las señales de trading.

## 📈 Descripción del Bot
El bot utiliza el índice RSI (Relative Strength Index) para identificar zonas de sobrecompra y sobreventa en los datos históricos de precios de una criptomoneda. Adicionalmente, se han añadido:
- **Stop-Loss y Take-Profit** para reducir riesgos y asegurar ganancias.
- **Filtrado con Medias Móviles** para evitar falsas señales y mejorar la precisión de las entradas y salidas del mercado.

## 🌐 Tecnologías Utilizadas
- Python 3.x
- Backtrader
- Pandas
- Matplotlib (para visualización de datos)

## 🔧 Instalación
Antes de ejecutar el bot, asegúrese de tener instaladas las dependencias necesarias. Puede hacerlo ejecutando:

```bash
pip install backtrader pandas matplotlib
```

## 💰 Estrategia de Trading
1. **Compra**: Se ejecuta cuando el RSI cae por debajo de 30 y el precio está por encima de una media móvil (evitando mercados bajistas prolongados).
2. **Venta**: Se ejecuta cuando el RSI supera 70 y el precio está por debajo de una media móvil (evitando falsas rupturas alcistas).
3. **Stop-Loss**: Se establece un límite de pérdida para reducir el impacto de movimientos adversos.
4. **Take-Profit**: Se establece un objetivo de ganancia para cerrar posiciones de forma automática.

## 📊 Uso
1. Descargue o clone el repositorio:
   ```bash
   git clone https://github.com/tuusuario/bot-backtrader-mejorado.git
   ```
2. Asegúrese de contar con datos históricos en formato CSV.
3. Modifique el script según sus necesidades, específicamente los parámetros de RSI y medias móviles.
4. Ejecute el bot:
   ```bash
   python bot_backtrader.py
   ```

## 🔄 Posibles Mejoras
- **Optimizar parámetros** usando Backtrader para realizar backtesting con diferentes configuraciones.
- **Implementar estrategias más avanzadas** como MACD, Bandas de Bollinger o combinaciones de indicadores.
- **Agregar integración con APIs** para operar en tiempo real con exchanges como Binance o Kraken.

## 📚 Licencia
Este proyecto se distribuye bajo la licencia MIT. Puede ser utilizado y modificado libremente.

---



