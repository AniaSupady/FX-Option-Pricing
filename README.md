# FX-Option-Pricing
Using QuantLib for FX Option Pricing. 

Link to Colab: https://github.com/AniaSupady/FX-Option-Pricing/blob/main/QuantLib_for_FX_Option_Pricing.ipynb



# QuantLib Overview

## Purpose of QuantLib
- **Comprehensive Framework**: QuantLib is a free/open-source library designed for quantitative finance, providing a robust software framework for modeling, trading, and risk management in real-life financial scenarios.
- **Multi-Language Support**: While primarily written in C++, QuantLib can be exported to other languages such as C#, Java, Python, and R, making it accessible to a wide range of developers and analysts.

## How QuantLib Can Help with FX
1. **FX Option Pricing**: 
   - QuantLib offers tools for pricing FX options, which are essential for effective FX trading and risk management.

2. **FX Swap Rate Calculations**: 
   - The library includes the `FxSwapRateHelper` class for bootstrapping over FX swap rates, useful for:
     - Calculating forward FX rates
     - Handling different currency pairs
     - Managing various tenors and fixing days
     - Applying business day conventions and end-of-month rules

3. **Yield Curve Construction**: 
   - QuantLib can construct yield curves from FX swap rates, which is crucial for valuing FX derivatives.

4. **Calendar Management**: 
   - The library provides calendar functionality to manage different trading and settlement dates across various currency pairs.

5. **Risk Management**: 
   - QuantLib supports scenario analysis and stress testing in FX markets, helping firms assess potential risks.

6. **Extensibility**: 
   - Users can extend the library to create custom FX models or incorporate specific FX trading strategies tailored to their needs.

7. **Integration**: 
   - QuantLib can be integrated into existing trading systems, facilitating real-time pricing and risk management for FX operations.

By providing these tools and functionalities, QuantLib enhances an organization's capability to manage FX trading, pricing, and risk assessment processes. Its open-source nature allows for community-driven improvements and adaptations to specific FX trading needs.
