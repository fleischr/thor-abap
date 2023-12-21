# thor-abap
thor-abap : an open source SDK to unite the VeChain ecosystem to SAP ABAP

## Architecture

- Emphasis on SAP ABAP on BTP (Steampunk)
- Consumes APIs exposed by [Vechain Thor](https://github.com/vechain/thor)
- May leverage some capabilities of [provide-abap](https://github.com/provideplatform/provide-abap) for authentication, transaction signing, and other enterprise blockchain capabilities for SAP. But is otherwise provider-agnostic in how wallets, authentication, and other services are implemented
- To be offered as a multitenant SaaS application to simplify customer and partner adoption
