<h1>OpenBook Market Identification and Cost Reduction</h1>
Obtaining an OpenBook market ID is a mandatory step if you plan to list your project on exchange platforms such as Raydium.io on the Solana network.
While transactions on the Solana network are generally cost-effective, the process of acquiring an OpenBook market ID can initially seem complicated and expensive. In this article, we will show you how to create a market ID compatible with Raydium and other exchange platforms using web3 technology with only 0.2 SOL.
<h2>Step-by-Step Market ID Creation</h2>
<strong>Note:</strong> We recommend doing all of this from a device such as a desktop or laptop. I also recommend using the Chrome browser and Phantom wallet for best results.

1. Visit <a href="https://www.openbooklab.xyz/"><strong>https://www.openbooklab.xyz/</strong></a>

<strong>Basic Mint:</strong> Your token mint address.

<strong>Quote Mint:</strong> The token you want to match your token with.

SOL: So11111111111111111111111111111111111111112
USDC: EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v
USDT: Es9vMFrzaCERmJfrF4H2FYD4KCoNkY11McCe8BenwNYB
<h2>2. Make the settings:</h2>
<strong>Min. Order Size:</strong> Minimum order quantity for the order book.
Example: Set to 4 -&gt; can place order for 0.0001 unit.
Example: Set to 0 if set to 0 -&gt; can place order for 1 unit.
Example: 1 -&gt; can place an order for 0.0001 units: Set to 1 -&gt; can place an order for 0.1 units.

<strong>Price Step:</strong> Number of decimal places for price display.
Example: Set to 5: Set to 5 -&gt; Token price is displayed with 5 decimal places, such as 11.12345.
Example: Set to 4: Set to 4 -&gt; Token price is displayed with 4 decimal places, like 11.1234.

<strong>Note</strong>
The minimum order size must not exceed the base token decimals.
The price step size must not exceed the decimals of the quote token.
The sum of 'Minimum order size' + 'Price Step' must not exceed the decimals of the quote token.

<strong>Example:</strong>
If the token decimal of base token A is set to 9, it is paired with USDC with a token decimal of 6.
The minimum order size must not exceed 9.
Price step size must not exceed 6.
'Minimum order size' + 'Price Step' must not exceed 6 (bid token decimals).

Therefore, you can set the minimum order size and price step to 3 and 2 (total 5, less than 6), but not 4 and 4 as the total exceeds 6.
