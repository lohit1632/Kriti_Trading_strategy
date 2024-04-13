**Bank Nifty Options Trading Strategy**

**Overview:**
Developed a trading strategy based on historical options data for BANK NIFTY, spanning July to December 2023. Utilized open interest analysis for sentiment detection.

**Dataset Description:**
- Historical options data for BANK NIFTY.
- Includes Date, Open, High, Low, Close, Strike price, No. of contracts, Open interest, and Change in open interest.

**Option Chain Analysis:**
- Option chain provides comprehensive listing of call and put options.
- Open interest reflects market activity and sentiment, aiding decision-making.

**Trading Strategy Rationale:**
- Focuses on analyzing trends in call and put open interest.
- Bullish sentiment indicated by increased ITM call open interest; bearish sentiment by increased ITM put open interest.

**Strategy Logic and Signal Generation:**
- Utilizes ITM and OTM options.
- Calculates net difference in open interest over recent expiry dates, weighted for relevance.
- Generates buy or square-off signals based on resulting net value.

**Risk Management Measures:**
- Weighs recent data more heavily, smoothing out fluctuations.
- Sets specific thresholds to filter significant market sentiment shifts.
- Implements automatic stop loss to limit potential losses during major drawdowns.

**Strategy Execution:**
- Trades initiated based on buy signals, holding positions until sell signals are generated.
- Long positions maintained through successive buy signals.

**Backtesting and Performance Metrics:**
- Backtested strategy from July 3rd to December 27th, 2023.
- Achieved returns of 14.6%, outperforming benchmark return of 7.05%.
- Average profitable trade return: 1.54%.
- Maximum trade return: 6.7%; maximum loss: 1.31%.
- Number of trades taken: 14 during the backtesting period.

**Conclusion:**
This trading strategy, based on BANK NIFTY options data, demonstrates effectiveness in generating superior returns and managing risk during the specified period.

**Contributors:**
- Lohit Hostel Team - Lohit Pattnaik, Daksh Arora, Arush Mathur, Divyanshu Tiwari

