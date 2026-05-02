# SV Liquidity (TradingView Indicator)

This is a TradingView Pine Script indicator for liquidity analysis based on Smart Money Concepts (SMC).

## Description

The SV Liquidity indicator identifies key liquidity zones, market structure shifts, fair value gaps, and provides entry/exit signals based on institutional trading concepts.

## Features

- Liquidity sweeps detection (Buy-Side Liquidity BSL, Sell-Side Liquidity SSL)
- Market Structure Shifts (MSS) and Break of Structure (BOS)
- Displacement Fair Value Gaps (FVG) with quality filters
- TJR Entry Model with confluence analysis
- Multiple market condition filters (Regime, Volatility, Momentum, HTF EMA bias, etc.)
- Killzone filtering (London, New York, Asian sessions)
- Dynamic risk-reward ratios based on signal confidence
- Trailing stop loss and break-even functionality
- Comprehensive dashboard showing filter status
- Visual legend for easy interpretation

## Inputs

The indicator includes numerous configurable inputs organized into groups:
- Core settings (pivot lookback, ATR length, displacement multiplier, etc.)
- Module A: Liquidity Sweeps visualization
- Module B: Market Structure visualization
- Module C: Displacement FVG visualization
- Module D: TJR Entry Model (signals, TP/SL, trailing)
- Module E: Market Condition Filters (8 different filters)
- Killzones: Session-based filtering
- UI: Legend and dashboard display

## Usage

1. Add the indicator to your TradingView chart
2. Adjust inputs according to your trading style and timeframe
3. Look for buy (▲) and sell (▼) signals with confidence percentages and RR ratios
4. The indicator automatically plots stop loss and take profit levels
5. Use the filter dashboard to see which conditions are allowing/blocking signals

## Requirements

- TradingView account
- Pine Script v6 compatibility

## Disclaimer

This indicator is for educational purposes only. Past performance does not guarantee future results. Always practice proper risk management and consider seeking advice from financial professionals.
