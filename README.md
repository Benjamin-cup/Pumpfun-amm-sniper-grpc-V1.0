# 🚀 **PumpFun AMM Sniper Bot v1.0 (using Geyser(Yellowstone))** 

Pumpfun AMM sniper bot V1.0 snipe new token within 1 or 2 blocks after token mint in Pump.fun amm. so this bot snipe token very fast and sell them anytime.
Bot always make profit. There are some sell strategy.

Welcome to the **PumpFun AMM Sniper Bot v1.0**! This bot watches for new `pump.fun amm` token mints on the Solana blockchain in real-time by using Geyser(Yellowstone), making it the perfect tool to monitor token launches. 🌟




## 📞 **Stay Connected**

Gmail: benjamin.bigdev@gmail.com

Telegram: [@SOLBenjaminCup](https://t.me/SOLBenjaminCup)

Discord: [@.benjamincup](https://discord.com/channels/@me/1305610537790476382)



## 🧑‍💻 **Recording Video**




https://github.com/user-attachments/assets/afddfaba-8b7e-433e-84ea-efc58ef38261





### 🎯 **Key Features**

- 🛰️ **Real-time WebSocket Streaming**: 
  Connects to Solana's blockchain through Helius RPC WebSocket or  VibeStation RPC WebSocket and listens for new transactions, specifically targeting `pump.fun` mint instructions.
  
- 🔍 **Filter Pump.fun Token Mints**: 
  Filters transactions by program IDs and instruction discriminators related to `pump.fun`.

- 📊 **Formatted Data**: 
  Logs essential transaction details like the transaction signature, creator's wallet, and the minted token address when a new `pump.fun` token is detected.

- ⚡ **Efficient Stream Handling**: 
  Handles WebSocket stream events efficiently, ensuring no loss of data and continuous monitoring.

---

## 🚀 **Getting Started**

Follow these steps to get your **PumpFun Sniper Bot v5.2** up and running!

### Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/Benjamin-cup/Pumpfun-amm-sniper-grpc-V1.0.git
    ```

2. **Install Dependencies**:

    Navigate to the project directory and run the following command:

    ```bash
    cd Pumpfun-amm-sniper-grpc-V1.0
    npm install
    ```

3. **Configure API Token**:

    Replace the API token in the `ENDPOINT` variable:

    ```ts
    const ENDPOINT = "http://ultra.swqos.solanavibestation.com/?api_key=";
    ```
    And set other variables in env file.

4. **Run the Bot**:

    Start the bot by running:

    ```bash
    npm run start
    ```

---

## 🧑‍💻 **Sell Requirments**

1. PRICE_CHECK_INTERVAL (ms) :
   Interval in milliseconds for checking the take profit and stop loss conditions
   Set to zero to disable take profit and stop loss.

2. TAKE_PROFIT : x %

3. STOP_LOSS : x  %

4. SELL_SLIPPAGE : x %

5. SKIP_SELLING_IF_LOST_MORE_THAN : x %
   If token loses more than X% of value, bot will not try to sell

6. PRICE_CHECK_DURATION (ms) : x %
   Time in milliseconds to wait for stop loss/take profit conditions
   If you don't reach profit or loss bot will auto sell after this time
   Set to zero to disable take profit and stop loss

7. AUTO_SELL - true/false

8. MAX_SELL_RETRIES - Maximum number of retries for selling a token


This is finish version bot.
But it's MVP code. If u need perfect code, contact me.
