# Stripe Alipay Gateway For WHMCS

由于2024年8月 Stripe 移除 Source 所以改用 Payment Intent.

开发 API 版本：	2024-06-20

侦听事件：`payment_intent.succeeded`

回调地址：`/modules/gateways/callback/haruka_stripe_alipay.php`