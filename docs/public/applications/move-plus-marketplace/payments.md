# Payments

**Status:** Public documentation draft

Move+ Marketplace supports separate payment paths for eligible Real Items.

Current payment options are based on:

- Energy eligibility inside the Move+ application.
- Supported stablecoins through the MiniPay-compatible hosted marketplace while that integration remains under testing.

Move+ Marketplace does not currently accept conventional Web2 payment methods.

Digital Gear transactions are separate from Real Item checkout and are not completed through the Move+ Marketplace payment system.

## Available payment methods

Current Marketplace payment eligibility can be summarized as follows:

| User eligibility | Energy use | Remaining payment |
|---|---|---|
| Active iOS Move+ subscriber | Full Energy payment may be available for eligible Real Items | No stablecoin remainder when full Energy checkout is approved |
| Verified compatible Digital Gear holder | Energy discount of up to 20% | At least 80% paid using a supported stablecoin |
| User without eligible subscription or verified Digital Gear | No Energy discount under these rules | Full supported stablecoin amount |

Payment availability also depends on:

- Product eligibility.
- Product availability.
- Sufficient Energy.
- Active subscription or verified Digital Gear status.
- Marketplace surface.
- Current checkout configuration.
- Supported delivery location.
- MiniPay availability.

The payment option shown by the marketplace should be treated as the applicable option for that checkout.

## Full Energy payment

Full Energy payment for eligible Real Items is currently limited to users with an active Move+ subscription purchased through the iOS application.

An eligible full Energy checkout generally requires:

- A valid Move+ account.
- An active qualifying iOS subscription.
- Sufficient Energy.
- An eligible Real Item.
- Current product availability.
- Complete delivery information.
- Successful marketplace validation.

A blockchain wallet is not required for full Energy payment.

Energy is an in-app reward and is not:

- Cash.
- A stablecoin.
- A bank balance.
- A transferable payment account.
- Guaranteed monetary value.

Full Energy checkout is not generally available to users who qualify only through Digital Gear ownership.

## Digital Gear holder discount

A user with verified compatible Digital Gear may apply Energy as a discount toward an eligible Real Item checkout.

The Energy discount is limited to a maximum of 20% of the eligible checkout value.

This means that at least 80% of the checkout value remains payable using a supported stablecoin when the maximum discount is applied.

Digital Gear holder discount eligibility may require:

- A valid Move+ account.
- A linked and verified compatible wallet.
- Verified ownership of supported Digital Gear.
- Sufficient Energy.
- An eligible Real Item.
- An active supported stablecoin checkout.
- Complete delivery information.

The exact amount of Energy required for a discount may depend on current marketplace settings.

The Marketplace documentation does not publish the internal Energy-to-stablecoin conversion formula.

Digital Gear ownership does not provide full Energy payment unless the user separately qualifies for an applicable full Energy checkout option.

## Supported stablecoins

The MiniPay-compatible marketplace is currently designed to support selected stablecoins on Celo.

Supported stablecoins under testing are:

- cUSD on Celo.
- USDT on Celo.
- USDC on Celo.

Token availability may depend on the active marketplace configuration and MiniPay environment.

The Marketplace does not accept every asset available on Celo.

Native CELO is not an accepted Real Item checkout currency.

## Unsupported payment methods

Move+ Marketplace does not currently accept conventional Web2 payment methods such as:

- Credit cards.
- Debit cards.
- Bank transfers.
- GCash.
- QR PH.
- PayPal.
- Cash on delivery.
- Direct cash payment.
- Other Web2 payment portals.

Move+ Marketplace also does not currently accept the following assets for Real Item checkout:

- Native CELO.
- RON.
- ENR.
- Bitcoin.
- Ether.
- Other volatile crypto assets.
- Unsupported tokens.
- Stablecoins on unsupported networks.

USDC is supported only where the active MiniPay-compatible checkout specifically supports USDC on Celo.

## MiniPay integration status

The hosted Move+ Marketplace includes a MiniPay-compatible stablecoin checkout that remains under developer testing.

The integration has been prepared for MiniPay use, but official marketplace listing, approval, or broad production availability has not been confirmed.

Public documentation should not describe Move+ Marketplace as an officially approved or fully production-live MiniPay application until that status is confirmed.

When available, stablecoin checkout generally must be opened inside the supported MiniPay environment.

A normal mobile or desktop browser may allow users to:

- Browse products.
- Review product details.
- Use the hosted cart.
- Review available checkout information.
- Link a Move+ account where supported.

A normal browser may not be able to complete MiniPay wallet signing.

## Stablecoin checkout process

A typical MiniPay-compatible checkout may include:

1. Open the hosted Move+ Marketplace inside MiniPay.
2. Browse eligible Real Items.
3. Add supported products to the cart.
4. Review the product quantity and price.
5. Link the Move+ account where an Energy discount is being used.
6. Apply an eligible Digital Gear holder Energy discount of up to 20%.
7. Select a supported Celo stablecoin.
8. Enter the required delivery information.
9. Review the final stablecoin amount.
10. Approve the payment through the MiniPay wallet.
11. Wait for blockchain confirmation and payment verification.
12. Check the resulting payment status.
13. Continue to fulfillment after successful verification.

Checkout availability may change while MiniPay integration remains under testing.

## Payment verification

A submitted wallet transaction is not automatically treated as a completed marketplace order.

The marketplace may wait for:

- Wallet submission.
- Blockchain confirmation.
- Payment verification.
- Product and order validation.
- Fulfillment registration.

Users may see payment messages such as:

- Awaiting payment.
- Payment pending.
- Payment submitted.
- Payment verified.
- Payment failed.
- Payment rejected.
- Payment expired.
- Pending fulfillment.

Blockchain or verification delays may occur.

Users should avoid submitting another payment while the original transaction remains pending.

Where available, users should use the payment-status function before starting another checkout.

## Energy discount finalization

An Energy discount may be temporarily associated with a hosted checkout while payment is pending.

The discount should not be treated as fully completed until the corresponding stablecoin payment is successfully verified.

When a checkout expires or fails before completion, the marketplace may release the pending discount according to the active checkout rules.

This does not create a general guarantee of automatic Energy restoration for every cancelled or disputed order.

Exact reservation, release, and finalization procedures are not part of the public documentation.

## Failed and expired payments

A stablecoin checkout may fail or remain incomplete when:

- The user rejects the wallet request.
- The wallet has insufficient stablecoin balance.
- The wrong blockchain network is selected.
- An unsupported token is selected.
- The checkout session expires.
- The product becomes unavailable.
- The transaction fails.
- Payment verification is delayed.
- Delivery information is incomplete.
- The marketplace is opened outside the supported MiniPay environment.
- Marketplace functionality is unavailable.

When a transaction has already been submitted but verification is delayed, users should not immediately send another payment.

Users should check the current payment status or contact official Move+ support.

## Refunds and reversals

Move+ Marketplace does not currently present automatic stablecoin refunds as a guaranteed standard feature.

The Marketplace also does not guarantee automatic Energy restoration for every:

- Cancelled order.
- Failed fulfillment.
- Disputed purchase.
- Incorrect payment.
- Wrong-token transfer.
- Duplicate payment.
- Overpayment.

An expired unpaid checkout may release an associated pending Energy discount according to the current checkout rules.

This is different from refunding a confirmed blockchain payment.

Blockchain payments are generally irreversible after confirmation.

Order or payment issues should be reported through an official Move+ support channel.

The availability of any refund, reversal, replacement, or Energy adjustment depends on review of the specific order.

## Accounts and wallets

### Full Energy payment

Full Energy payment generally requires:

- A Move+ account.
- An active qualifying iOS Move+ subscription.
- Sufficient Energy.

A blockchain wallet is not required.

### Digital Gear holder discount

A Digital Gear holder discount generally requires:

- A Move+ account.
- A linked wallet for the supported Digital Gear network.
- Verified compatible Digital Gear ownership.
- Sufficient Energy.
- A supported stablecoin checkout for the remaining amount.

The wallet used to verify Ronin or Base Digital Gear ownership may be separate from the MiniPay wallet used for Celo stablecoin payment.

### Stablecoin payment

Stablecoin payment requires:

- A compatible MiniPay wallet environment.
- A supported Celo stablecoin.
- Sufficient stablecoin balance.
- Wallet approval.
- Successful blockchain and marketplace verification.

Ronin and Base wallets are not used as the Real Item stablecoin payment rail.

## Digital Gear payment limitations

The Marketplace Digital Gear section remains a preview and discovery experience.

The following are not currently supported through Marketplace Digital Gear:

- Full Energy purchase.
- Energy discount checkout.
- MiniPay NFT purchase.
- Stablecoin NFT purchase.
- ENR payment.
- RON payment.
- Direct NFT minting.
- Direct NFT transfer.
- NFT wallet signing inside the marketplace preview.

Where available, Digital Gear transactions take place through external marketplaces.

Digital Gear ownership may later be verified inside Move+ for compatible application utility.

## Pricing

Each eligible Real Item may have:

- A listed Energy requirement.
- A listed stablecoin amount.
- Both values where multiple eligibility paths exist.
- A limited offer period.
- Product-specific availability.

Prices and eligibility may change before checkout is completed.

Users should review the final amount shown immediately before confirming payment.

The Marketplace documentation does not publish:

- Internal Energy conversion formulas.
- Treasury calculations.
- Marketplace commissions.
- Merchant settlement rates.
- Internal exchange-rate handling.
- Payment-provider configuration.
- Private receiver addresses.

## Fees

Celo network fees may apply to stablecoin transactions.

The amount shown by the wallet should be reviewed before approval.

Move+ does not currently publish a universal marketplace fee schedule for every checkout.

Delivery fees are not presented as a universal standard payment component and may depend on the applicable product or fulfillment arrangement.

## Payment safety

Before approving a stablecoin payment, users should verify:

- The product and quantity.
- The final stablecoin amount.
- The Celo network.
- The selected stablecoin.
- The wallet transaction details.
- The receiving application or transaction request.
- Applicable network fees.
- The delivery information.

Users should:

- Use only official Move+ marketplace links.
- Avoid duplicate payments.
- Wait for payment verification.
- Be cautious of fake support accounts.
- Ignore unsolicited requests to transfer funds.
- Contact official Move+ support when assistance is needed.

Move+ will never request:

- A seed phrase.
- A wallet recovery phrase.
- A private key.
- Remote access to a wallet or device.
- A separate transfer to “verify” a payment.

## Future payment methods

Move+ Marketplace does not currently support or announce the following as active payment methods:

- QR PH.
- GCash.
- Cards.
- Bank transfer.
- Cash.
- PayPal.
- RON.
- ENR.
- Native CELO.
- Other volatile tokens.
- Other blockchain networks.

Amaya L1 is not currently used as a Marketplace payment or settlement network.

Any future payment method will require implementation, testing, security review, and separate public documentation before it is treated as available.

## Current limitations

- Full Energy payment is limited to eligible active iOS subscribers.
- Verified compatible Digital Gear holders may use Energy only for a discount of up to 20%.
- At least 80% of a Digital Gear holder checkout remains payable in supported stablecoin when the maximum discount is applied.
- Exact Energy conversion calculations are not published.
- Hosted stablecoin checkout remains under testing.
- Official MiniPay listing or approval has not been confirmed.
- Stablecoin checkout may require the MiniPay browser.
- Supported stablecoins are limited to cUSD, USDT, and USDC on Celo.
- Native CELO and non-stablecoin tokens are not accepted.
- Web2 payment portals are not supported.
- Normal browsers may not complete MiniPay wallet signing.
- Automatic stablecoin refunds are not guaranteed.
- Automatic Energy restoration is not guaranteed for every order issue.
- Digital Gear cannot be purchased through the Marketplace preview.
- Amaya L1 is not a current Marketplace payment rail.

## Related documentation

- Move+ Marketplace Overview
- Real Items
- Marketplace Digital Gear
- Delivery and Fulfillment
- Move+ Digital Gear
- Rewards and Progression
- Privacy Policy
