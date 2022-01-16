---
title: IBybitSocketClientInversePerpetualStreams
has_children: true
parent: IBybitClientInversePerpetualApi
grand_parent: IBybitClient
---
*[generated documentation]*  
`BybitClient > InversePerpetualApi > InversePerpetualStreams`
*Bybit inverse perpetual streams*
  

***

<details>
<summary>
<b>SubscribeToBalanceUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketwallet](https://bybit-exchange.github.io/docs/inverse/#t-websocketwallet)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToBalanceUpdatesAsync(Action<DataEvent<IEnumerable<BybitBalanceUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to user balance updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToInsurancesUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketinsurance](https://bybit-exchange.github.io/docs/inverse/#t-websocketinsurance)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToInsurancesUpdatesAsync(Action<DataEvent<IEnumerable<BybitInsuranceUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to insurance fund updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToInsuranceUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketinsurance](https://bybit-exchange.github.io/docs/inverse/#t-websocketinsurance)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToInsuranceUpdatesAsync(string symbol, Action<DataEvent<IEnumerable<BybitInsuranceUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbol`|The symbol to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to insurance fund updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToInsuranceUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketinsurance](https://bybit-exchange.github.io/docs/inverse/#t-websocketinsurance)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToInsuranceUpdatesAsync(IEnumerable<string> symbols, Action<DataEvent<IEnumerable<BybitInsuranceUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbols`|The symbols to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to insurance fund updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToKlinesUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketklinev2](https://bybit-exchange.github.io/docs/inverse/#t-websocketklinev2)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToKlinesUpdatesAsync(KlineInterval interval, Action<DataEvent<IEnumerable<BybitKlineUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`interval`|The interval of the klines|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to kline (candlestick) updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToKlineUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketklinev2](https://bybit-exchange.github.io/docs/inverse/#t-websocketklinev2)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToKlineUpdatesAsync(string symbol, KlineInterval interval, Action<DataEvent<IEnumerable<BybitKlineUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbol`|The symbol to receive updates for|
|`interval`|The interval of the klines|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to kline (candlestick) updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToKlineUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketklinev2](https://bybit-exchange.github.io/docs/inverse/#t-websocketklinev2)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToKlineUpdatesAsync(IEnumerable<string> symbols, KlineInterval interval, Action<DataEvent<IEnumerable<BybitKlineUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbols`|The symbols to receive updates for|
|`interval`|The interval of the klines|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to kline (candlestick) updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToLiquidationsUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketliquidation](https://bybit-exchange.github.io/docs/inverse/#t-websocketliquidation)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToLiquidationsUpdatesAsync(Action<DataEvent<BybitLiquidationUpdate>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to liquidation order updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToLiquidationUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketliquidation](https://bybit-exchange.github.io/docs/inverse/#t-websocketliquidation)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToLiquidationUpdatesAsync(string symbol, Action<DataEvent<BybitLiquidationUpdate>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbol`|The symbol to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to liquidation order updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToLiquidationUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketliquidation](https://bybit-exchange.github.io/docs/inverse/#t-websocketliquidation)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToLiquidationUpdatesAsync(IEnumerable<string> symbols, Action<DataEvent<BybitLiquidationUpdate>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbols`|The symbols to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to liquidation order updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToOrderBooksUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook25](https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook25)  
[https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook200](https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook200)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToOrderBooksUpdatesAsync(int limit, Action<DataEvent<IEnumerable<BybitOrderBookEntry>>> snapshotHandler, Action<DataEvent<BybitDeltaUpdate<BybitOrderBookEntry>>> updateHandler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`limit`|The amount of rows to receive updates for. Either 25 or 200.|
|`snapshotHandler`|The event handler for the initial snapshot data|
|`updateHandler`|The event handler for the update messages|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to orderbook updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToOrderBookUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook25](https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook25)  
[https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook200](https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook200)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToOrderBookUpdatesAsync(string symbol, int limit, Action<DataEvent<IEnumerable<BybitOrderBookEntry>>> snapshotHandler, Action<DataEvent<BybitDeltaUpdate<BybitOrderBookEntry>>> updateHandler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbol`|The symbol to receive updates for|
|`limit`|The amount of rows to receive updates for. Either 25 or 200.|
|`snapshotHandler`|The event handler for the initial snapshot data|
|`updateHandler`|The event handler for the update messages|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to orderbook updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToOrderBookUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook25](https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook25)  
[https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook200](https://bybit-exchange.github.io/docs/inverse/#t-websocketorderbook200)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToOrderBookUpdatesAsync(IEnumerable<string> symbols, int limit, Action<DataEvent<IEnumerable<BybitOrderBookEntry>>> snapshotHandler, Action<DataEvent<BybitDeltaUpdate<BybitOrderBookEntry>>> updateHandler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbols`|The symbols to receive updates for|
|`limit`|The amount of rows to receive updates for. Either 25 or 200.|
|`snapshotHandler`|The event handler for the initial snapshot data|
|`updateHandler`|The event handler for the update messages|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to orderbook updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToOrderUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketorder](https://bybit-exchange.github.io/docs/inverse/#t-websocketorder)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToOrderUpdatesAsync(Action<DataEvent<IEnumerable<BybitOrderUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to user order updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToPositionUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketposition](https://bybit-exchange.github.io/docs/inverse/#t-websocketposition)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToPositionUpdatesAsync(Action<DataEvent<IEnumerable<BybitPositionUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to user position updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToStopOrderUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketstoporder](https://bybit-exchange.github.io/docs/inverse/#t-websocketstoporder)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToStopOrderUpdatesAsync(Action<DataEvent<IEnumerable<BybitStopOrderUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to user stop order updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToTickersUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketinstrumentinfo](https://bybit-exchange.github.io/docs/inverse/#t-websocketinstrumentinfo)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToTickersUpdatesAsync(Action<DataEvent<BybitTickerUpdate>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to ticker updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToTickerUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketinstrumentinfo](https://bybit-exchange.github.io/docs/inverse/#t-websocketinstrumentinfo)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToTickerUpdatesAsync(string symbol, Action<DataEvent<BybitTickerUpdate>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbol`|The symbol to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to ticker updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToTickerUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketinstrumentinfo](https://bybit-exchange.github.io/docs/inverse/#t-websocketinstrumentinfo)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToTickerUpdatesAsync(IEnumerable<string> symbols, Action<DataEvent<BybitTickerUpdate>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbols`|The symbols to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to ticker updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToTradesUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websockettrade](https://bybit-exchange.github.io/docs/inverse/#t-websockettrade)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToTradesUpdatesAsync(Action<DataEvent<IEnumerable<BybitTradeUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to public trade updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToTradeUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websockettrade](https://bybit-exchange.github.io/docs/inverse/#t-websockettrade)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToTradeUpdatesAsync(string symbol, Action<DataEvent<IEnumerable<BybitTradeUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbol`|The symbol to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to public trade updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToTradeUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websockettrade](https://bybit-exchange.github.io/docs/inverse/#t-websockettrade)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToTradeUpdatesAsync(IEnumerable<string> symbols, Action<DataEvent<IEnumerable<BybitTradeUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`symbols`|The symbols to receive updates for|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to public trade updates*  

</p>
</details>

***

<details>
<summary>
<b>SubscribeToUserTradeUpdatesAsync</b>  

[https://bybit-exchange.github.io/docs/inverse/#t-websocketexecution](https://bybit-exchange.github.io/docs/inverse/#t-websocketexecution)  
</summary>
<p>

```C#  
Task<CallResult<UpdateSubscription>> SubscribeToUserTradeUpdatesAsync(Action<DataEvent<IEnumerable<BybitUserTradeUpdate>>> handler, [Optional] CancellationToken ct);  
```  

|Parameter|Description|
|---|---|
|`handler`|The event handler for the received data|
|`ct`|Cancellation token for closing this subscription|

*Subscribe to user trade updates*  

</p>
</details>