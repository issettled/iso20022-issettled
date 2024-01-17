[![IsSettled Instant Payment System](https://github.com/issettled/.github/blob/main/images/iso20022-issettled-repo.png)](https://issettled.com)

<p align="center">
  ·
  <a href="https://developer.issettled.com">IsSettled Documentation</a>
  ·
  <a href="https://developer.issettled.com/api-introduction">API Documentation</a>
  ·
  <br>
  <br>
</p>

# ISO 20022 Financial Messages

Financial messages for Members uses of the IsSettled unified financial infrastructure for banks and corporates.

IsSettled supports the generally accepted financial messages `head.001`, `pacs.002`, `pacs.004`, `pacs.008`, `pacs.009`, `camt.026`, `camt.029`, `camt.030`, `camt.056`, `camt.087`, as well as its messages `issd.001`, `issd.002`, developed based on the methodology of the ISO international standard 20022 and taking into account internal practices for use within the system.

# Repository Navigation

The repository contains financial XML message templates, XML schemas (XSD), sample ISO 20022 messages used by IsSettled Members, and UML diagrams for key business processes.

## XML Message Diagrams ISO 20022—XSD

Directory [`/xsd`](https://github.com/issettled/iso20022-issettled/tree/main/xsd) is the definition of an XML schema for messages in IsSettled.

> A configuration `issettled.xsd` XSD file  has been prepared for IsSettled Members for reading, checking, and creating XML messages. It is necessary to change the value of `/path/to` in the `schemaLocation` attribute according to the directory of the Member’s server system where the XSD files are located.

* [head.001.001.03](https://github.com/issettled/iso20022-issettled/blob/main/xsd/head.001.001.03.xsd)
* [issd.001.001.01](https://github.com/issettled/iso20022-issettled/blob/main/xsd/issd.001.001.01.xsd)
* [issd.002.001.01](https://github.com/issettled/iso20022-issettled/blob/main/xsd/issd.002.001.01.xsd)
* [pacs.002.001.11](https://github.com/issettled/iso20022-issettled/blob/main/xsd/pacs.002.001.11.xsd)
* [pacs.004.001.10](https://github.com/issettled/iso20022-issettled/blob/main/xsd/pacs.004.001.10.xsd)
* [pacs.008.001.09](https://github.com/issettled/iso20022-issettled/blob/main/xsd/pacs.008.001.09.xsd)
* [pacs.009.001.09](https://github.com/issettled/iso20022-issettled/blob/main/xsd/pacs.009.001.09.xsd)
* [camt.026.001.09](https://github.com/issettled/iso20022-issettled/blob/main/xsd/camt.026.001.09.xsd)
* [camt.029.001.11](https://github.com/issettled/iso20022-issettled/blob/main/xsd/camt.029.001.11.xsd)
* [camt.030.001.05](https://github.com/issettled/iso20022-issettled/blob/main/xsd/camt.030.001.05.xsd)
* [camt.056.001.10](https://github.com/issettled/iso20022-issettled/blob/main/xsd/camt.056.001.10.xsd)
* [camt.087.001.08](https://github.com/issettled/iso20022-issettled/blob/main/xsd/camt.087.001.08.xsd)
* [issettled](https://github.com/issettled/iso20022-issettled/blob/main/xsd/issettled.xsd)

## ISO 20022 XML Message Templates

Directory [`/templates/en/`](https://github.com/issettled/iso20022-issettled/tree/main/templates/en) are ISO 20022 XML message templates used in the IsSettled system.

* [issd.001.001.01](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/issd.001.001.01.xml)
* [issd.002.001.01](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/issd.002.001.01.xml)
* [pacs.002.001.11](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/pacs.002.001.11_02.xml)
* [pacs.004.001.10](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/pacs.004.001.10.xml)
* [pacs.008.001.09](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/pacs.008.001.09.xml)
* [pacs.009.001.09](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/pacs.009.001.09.xml)
* [camt.026.001.09](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/camt.026.001.09.xml)
* [camt.029.001.11](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/camt.029.001.11.xml)
* [camt.056.001.10](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/camt.056.001.10.xml)
* [camt.087.001.08](https://github.com/issettled/iso20022-issettled/blob/main/templates/en/camt.087.001.08.xml)

## Examples of ISO 20022 XML Messages and UML Diagrams

Examples of ISO 20022 XML messages and UML diagrams for key scenarios of Members’ interaction with IsSettled for clearing and settling international payments.

> Detailed information is presented in the directory [`/examples/`](https://github.com/issettled/iso20022-issettled/tree/main/examples/)

Directory [`/examples/en/settlement-method-TDSO/`](https://github.com/issettled/iso20022-issettled/tree/main/examples/en/settlement-method-TDSO) are examples of ISO 20022 XML messages and UML diagrams related to operations on settlement instruments of the [DSO](https://developer.issettled.com/docs-glossary/digital-settlement-obligation-dso) asset group.

Directory [`/examples/en/settlement-method-TDSA/`](https://github.com/issettled/iso20022-issettled/tree/main/examples/en/settlement-method-TDSA) are examples of ISO 20022 XML messages and UML diagrams related to operations on settlement instruments of the [DSA](https://developer.issettled.com/docs-glossary/digital-settlement-asset-dsa) asset group.

# ISO 20022 Financial Message structures

ISO 20022 financial message structures are available for programming languages:

* С — [iso20022-C](https://github.com/issettled/iso20022-C) repository.
* Go — [iso20022-Go](https://github.com/issettled/iso20022-Go) repository.
* Java — [iso20022-Java](https://github.com/issettled/iso20022-Java) repository.
* Rust — [iso20022-Rust](https://github.com/issettled/iso20022-Rust) repository.
* TypeScript — [iso20022-TypeScript](https://github.com/issettled/iso20022-TypeScript) repository.

# Directory Tree

```
├── LICENSE
├── README.md
├── examples
│   ├── README.md
│   └── en
│       ├── settlement-method-TDSA
│       │   ├── creditor-cancel-payment-dsa
│       │   │   ├── camt.026.001.09.xml
│       │   │   ├── camt.056.001.10.xml
│       │   │   ├── creditor-cancel-payment-dsa.svg
│       │   │   └── pacs.004.001.10.xml
│       │   ├── debtor-cancel-payment-dsa-agree
│       │   │   ├── camt.056.001.10.xml
│       │   │   ├── debtor-cancel-payment-dsa-agree.svg
│       │   │   └── pacs.004.001.10.xml
│       │   ├── debtor-cancel-payment-dsa-reject
│       │   │   ├── camt.029.001.11.xml
│       │   │   ├── camt.056.001.10.xml
│       │   │   └── debtor-cancel-payment-dsa-reject.svg
│       │   ├── payment-dsa
│       │   │   ├── pacs.002.001.11.xml
│       │   │   ├── pacs.008.001.09.xml
│       │   │   ├── payment-dsa.svg
│       │   │   └── issd.001.001.01.xml
│       │   ├── payment-dsa-modify
│       │   │   ├── camt.026.001.09.xml
│       │   │   ├── camt.087.001.08.xml
│       │   │   └── payment-dsa-modify.svg
│       │   └── redeem-dsa
│       │       ├── pacs.002.001.11.xml
│       │       ├── pacs.009.001.09.xml
│       │       └── redeem-dsa.svg
│       └── settlement-method-TDSO
│           ├── creditor-cancel-payment-dso
│           │   ├── camt.026.001.09.xml
│           │   ├── camt.056.001.10.xml
│           │   ├── creditor-cancel-payment-dso.svg
│           │   └── pacs.004.001.10.xml
│           ├── debtor-cancel-payment-dso-agree
│           │   ├── camt.056.001.10.xml
│           │   ├── debtor-cancel-payment-dso-agree.svg
│           │   └── pacs.004.001.10.xml
│           ├── debtor-cancel-payment-dso-reject
│           │   ├── camt.029.001.11.xml
│           │   ├── camt.056.001.10.xml
│           │   └── debtor-cancel-payment-dso-reject.svg
│           ├── payment-dso
│           │   ├── pacs.002.001.11.xml
│           │   ├── pacs.008.001.09.xml
│           │   ├── payment-dso.svg
│           │   └── issd.001.001.01.xml
│           ├── payment-dso-modify
│           │   ├── camt.026.001.09.xml
│           │   ├── camt.087.001.08.xml
│           │   └── payment-dso-modify.svg
│           └── return-dso-after-payment-dso
│               ├── pacs.004.001.10.xml
│               ├── return-dso-after-payment-dso.svg
│               └── issd.002.001.01.xml
├── templates
│   └── en
│       ├── README.md
│       ├── camt.026.001.09.xml
│       ├── camt.029.001.11.xml
│       ├── camt.056.001.10.xml
│       ├── camt.087.001.08.xml
│       ├── pacs.002.001.11_02.xml
│       ├── pacs.004.001.10.xml
│       ├── pacs.008.001.09.xml
│       ├── pacs.009.001.09.xml
│       ├── issd.001.001.01.xml
│       └── issd.002.001.01.xml
└── xsd
    ├── camt.026.001.09.xsd
    ├── camt.029.001.11.xsd
    ├── camt.030.001.05.xsd
    ├── camt.056.001.10.xsd
    ├── camt.087.001.08.xsd
    ├── head.001.001.03.xsd
    ├── issettled.xsd
    ├── pacs.002.001.11.xsd
    ├── pacs.004.001.10.xsd
    ├── pacs.008.001.09.xsd
    ├── pacs.009.001.09.xsd
    ├── issd.001.001.01.xsd
    └── issd.002.001.01.xsd
```

# IsSettled Documentation

More information about the IsSettled system is available on the [developer’s portal](https://developer.issettled.com).

# API IsSettled

More information about the API IsSettled: [API Member](https://developer.issettled.com/api-main-member/reference) and [API Tokenizer](https://developer.issettled.com/api-tokenizer/reference).

# License

Apache License 2.0 — See [LICENSE](https://github.com/issettled/iso20022-issettled/blob/main/LICENSE) for details.