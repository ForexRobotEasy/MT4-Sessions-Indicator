# MT4 Sessions Indicator

This is an indicator developed by the Forex Robot Easy Team that enhances trading by displaying session open and close prices on the chart.

## Indicator Parameters

- `indicator_chart_window` - This parameter specifies whether the indicator should be displayed in a separate window or on the main chart.
- `indicator_buffers` - This parameter sets the number of indicator buffers used for storing data.
- `indicator_color1` - This parameter sets the color of the session open indicator.
- `indicator_color2` - This parameter sets the color of the session close indicator.

## Indicator Buffers

The indicator uses two buffers to store session open and close prices.

- `SessionOpenBuffer[]` - This buffer stores the session open prices.
- `SessionCloseBuffer[]` - This buffer stores the session close prices.

## Initialization Function

The `OnInit()` function is called when the indicator is initialized. In this function, the indicator buffers are mapped, and labels are set for the indicator.

## Indicator Calculation Function

The `OnCalculate()` function is called for each bar on the chart. In this function, the session open and close prices are calculated based on the time of the bar. If the time is 9:00 or 17:00, the session open and close prices are set to the current bar's open and close prices. Otherwise, the session open and close prices are set to the values of the previous bar.

## Product Description

The MT4 Sessions Indicator is a powerful tool developed by the Forex Robot Easy Team. It enhances trading by providing visual representations of session open and close prices on the chart.

With this indicator, traders can easily identify important session boundaries and make more informed trading decisions. The session open and close prices are displayed as arrows on the chart, making it easy to see the start and end of each session.

This indicator is highly customizable, allowing traders to choose the colors of the session open and close indicators to suit their preferences. It can be used on any time frame and with any currency pair.

Please note that Forex Robot Easy is not the official developer of this product. We are providing this sample code to demonstrate how the indicator works. To find the official developer and access detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mt4-sessions-indicator-review-enhance-trading-with-colored-candles/).

For further information and support, please consult the official developer and refer to the MQL5 platform.
