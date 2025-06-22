# Trading Experts Collection

A comprehensive collection of Expert Advisors (EAs) for automated trading on MetaTrader 5 platform.

## 📊 Available Experts

### 1. ExpertMAPSARSizeOptimized
- **Description**: Optimized Parabolic SAR expert with dynamic position sizing
- **Strategy**: Trend-following with SAR signals and risk management
- **Files**: 
  - Source: `ExpertMAPSARSizeOptimized.mq5`
  - Executable: `ExpertMAPSARSizeOptimized.ex5`

### 2. ExpertMAMA
- **Description**: MESA Adaptive Moving Average expert advisor
- **Strategy**: Adaptive trend following using MESA algorithm
- **Files**:
  - Source: `ExpertMAMA.mq5`
  - Executable: `ExpertMAMA.ex5`

### 3. ExpertMAPSAR
- **Description**: Standard Parabolic SAR expert advisor
- **Strategy**: Classic SAR trend following strategy
- **Files**:
  - Source: `ExpertMAPSAR.mq5`
  - Executable: `ExpertMAPSAR.ex5`

### 4. ExpertMACD
- **Description**: MACD-based expert advisor
- **Strategy**: Momentum and trend analysis using MACD signals
- **Files**:
  - Source: `ExpertMACD.mq5`
  - Executable: `ExpertMACD.ex5`

## 📁 Repository Structure

```
trading-experts/
├── experts/           # Expert Advisor files
│   ├── *.mq5         # MQL5 source files
│   └── *.ex5         # Compiled executables
├── images/           # Screenshots and charts
├── docs/            # Documentation and guides
└── README.md        # This file
```

## 🚀 Installation

1. **For Compiled EAs (.ex5 files)**:
   - Copy the `.ex5` files to your MetaTrader 5 `Experts` folder
   - Restart MetaTrader 5
   - Drag and drop the EA onto your chart

2. **For Source Code (.mq5 files)**:
   - Copy the `.mq5` files to your MetaTrader 5 `Experts` folder
   - Compile in MetaEditor (F7)
   - Use the compiled version

## ⚙️ Configuration

Each expert advisor has customizable parameters:
- **Risk Management**: Stop Loss, Take Profit, Position Size
- **Strategy Parameters**: Timeframes, Signal thresholds
- **Trading Hours**: Session filters and time restrictions

## 📈 Performance

*Performance metrics and backtest results will be added for each expert*

## 🔧 Development

- **Platform**: MetaTrader 5
- **Language**: MQL5
- **IDE**: MetaEditor

## 📝 License

This project is for educational and trading purposes. Use at your own risk.

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests.

## 📞 Support

For questions or support, please open an issue in this repository.

---

**Disclaimer**: Trading involves risk. These expert advisors are for educational purposes. Always test thoroughly on a demo account before live trading. 