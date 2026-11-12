<a href="https://velirapay.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VeliraPay/.github/main/profile/banner-dark.png">
    <img alt="VeliraPay. Accept crypto payments. Follow each one to your wallet." src="https://raw.githubusercontent.com/VeliraPay/.github/main/profile/banner-light.png" width="100%">
  </picture>
</a>

VeliraPay lets businesses take crypto payments. You charge a customer with a payment link, an invoice or the API. They pay in the coin they hold, at a rate locked for them, to an address made for that payment alone. Once it confirms, your share is paid out to your own wallet.

[Website](https://velirapay.com) · [Documentation](https://velirapay.com/docs) · [Pricing](https://velirapay.com/pricing) · [Status](https://status.velirapay.com) · [X](https://x.com/VeliraPay) · [LinkedIn](https://www.linkedin.com/company/velirapay)

### Libraries

| Library | Install |
| --- | --- |
| [PHP](https://github.com/VeliraPay/velirapay-php): charges, payment links, invoices, events and webhook verification | `composer require velirapay/velirapay-php` |
| [Laravel](https://github.com/VeliraPay/velirapay-laravel): a facade for the API, and verified webhooks dispatched as Laravel events | `composer require velirapay/velirapay-laravel` |
| [Node.js](https://github.com/VeliraPay/velirapay-node): the whole API typed for TypeScript, with no dependencies | Coming to npm |
| [WooCommerce](https://github.com/VeliraPay/velirapay-woocommerce): crypto payments at checkout through hosted VeliraPay invoices | [Download the plugin](https://github.com/VeliraPay/velirapay-woocommerce/releases/latest) |

### For developers

- A REST API with idempotency keys, and a test mode to try every flow without real money
- Signed webhooks (HMAC-SHA256) with retries and a delivery log
- An [OpenAPI contract](https://velirapay.com/openapi.json)
- An [MCP server](https://velirapay.com/docs/mcp), so an AI assistant can create charges and invoices and check what has been paid

### Coins

[Bitcoin](https://velirapay.com/accept/bitcoin) · [Litecoin](https://velirapay.com/accept/litecoin) · [Dogecoin](https://velirapay.com/accept/dogecoin) · [Bitcoin Cash](https://velirapay.com/accept/bitcoin-cash) · [Ethereum](https://velirapay.com/accept/ethereum) · [Solana](https://velirapay.com/accept/solana) · [BNB](https://velirapay.com/accept/bnb) · [TRON](https://velirapay.com/accept/tron) · [Tether (USDT)](https://velirapay.com/accept/tether) · [USD Coin (USDC)](https://velirapay.com/accept/usd-coin) · [Polygon (POL)](https://velirapay.com/accept/polygon)

### Pricing

The free plan keeps 3% of each payment as it is forwarded to you. Pro costs $9.99 a month and takes no fee. [Compare plans](https://velirapay.com/pricing)

<sub>VeliraPay is in beta. [Create an account](https://velirapay.com/register) to try it.</sub>
