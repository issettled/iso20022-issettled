# ISO 20022 Financial Message Templates

ISO 20022 financial message templates used in the IsSettled automated instant payment system.

## issd.001.001.01

The `issd.001` message, within the implementation of transfers via IsSettled, is intended to notify the result of identification of the Payer and the ultimate Beneficiary per compliance requirements, as well as to verify the details of the ultimate Beneficiary.

[Learn more about rules using and filling a issd.001 message](https://developer.issettled.com/docs-iso-20022/issettled-001-customer-identification-status-notification).

## issd.002.001.01

The `issd.002` message, within the implementation of transfers via IsSettled, is intended to notify a settlement outside IsSettled for a completed interbank customer Credit transfer of funds—`pacs.008`.

[Learn more about rules using and filling a issd.002 message](https://developer.issettled.com/docs-iso-20022/issettled-002-transaction-settlement-notification).

## pacs.002.001.11

The `pacs.002` message, within the implementation of transfers via IsSettled, is intended to notify the results of checking messages: `issd.001`, `issd.002`, `pacs.004`, `pacs.008`, `pacs.009`, and `pacs.002 of subtype 02` for compliance with the requirements established in IsSettled and the results of processing: execution or non-execution Credit transfer of funds.

[Learn more about rules using and filling a pacs.002 message](https://developer.issettled.com/docs-iso-20022/pacs-002-fi-to-fi-payment-status-report).

## pacs.004.001.10

The `pacs.004` message, within the implementation of transfers via IsSettled, is intended to notify positive reception of the Member’s request for the `issd.002`, `camt.056` messages.

## pacs.008.001.09

The `pacs.008` message, within the implementation of transfers via IsSettled, is intended to send for requesting Payment—transmitting the customer’s payment instructions on a Credit transfer of funds through the IsSettled Settlement Center when the Payer and Beneficiary are not banks or non-bank credit and financial organizations.

[Learn more about rules using and filling a pacs.008 message](https://developer.issettled.com/docs-iso-20022/pacs-008-fi-to-fi-customer-credit-transfer).

## pacs.009.001.09

The `pacs.009` message, within the implementation of transfers via IsSettled, is intended to send a [DSA Redeem Request](https://developer.issettled.com/docs-scenarios/redeem-dsa/) (transfer of payment instructions on the Credit transfer of funds).

[Learn more about rules using and filling a pacs.009 message](https://developer.issettled.com/docs-iso-20022/pacs-009-financial-institution-credit-transfer).

## camt.026.001.09

The `camt.026` message, within the implementation of transfers via IsSettled, is intended to notify refusal in the execution of interbank customer Credit transfer—`pacs.008` with an indication of the reason for unable to apply.

[Learn more about rules using and filling a camt.026 message](https://developer.issettled.com/docs-iso-20022/camt-026-unable-to-apply).

## camt.029.001.11

The `camt.029` message, within the implementation of transfers via IsSettled, is intended to send a negative response to a recall of the Member’s Payment Cancelation Request of the interbank customer Credit transfer of funds.

[Learn more about rules using and filling a camt.029 message](https://developer.issettled.com/docs-iso-20022/camt-029-resolution-of-investigation).

## camt.056.001.10

The `camt.056` message, within the implementation of transfers via IsSettled, is intended to send Payment Cancelation Request (recall of an interbank customer credit transfer of funds).

[Learn more about rules using and filling a camt.056 message](https://developer.issettled.com/docs-iso-20022/camt-056-fi-to-fi-payment-cancellation-request).

## camt.087.001.08

The `camt.087` message, within the implementation of transfers via IsSettled, is intended to send a request to modify Payment (making changes to the details of a previously sent and unfulfilled Payment Request).

[Learn more about rules using and filling a camt.087 message](https://developer.issettled.com/docs-iso-20022/camt-087-request-to-modify-payment).

# IsSettled Documentation

Detailed information about using ISO 20022 financial messages in the IsSettled system is available on the [developer’s portal](https://developer.issettled.com/docs-iso-20022-introduction).