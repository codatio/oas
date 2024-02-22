# Open API Specification (OAS)

These files are generated and bundled from our internal OpenAPI specs.

You can browse interactive versions of our OAS on [our docs](https://docs.codat.io/).

### API specs

| API | Description | JSON | YAML |
| :- | :- | :- | :- |
| [Platform API](https://docs.codat.io/platform-api#/) | Manage the building blocks of Codat, including companies, connections, and more.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Platform.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Platform.yaml)
| [Bank Feeds API](https://docs.codat.io/bank-feeds-api#/) | Set up bank feeds from accounts in your application to supported accounting platforms.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Bank-Feeds.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Bank-Feeds.yaml)
| [Sync for Commerce API](https://docs.codat.io/sync-for-commerce-api#/) | Push merchants' data from your ecommerce or point-of-sale (POS) platform into your merchants' accounting platform.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Sync-Commerce.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Sync-Commerce.yaml)
| [Sync for Expenses API](https://docs.codat.io/sync-for-expenses-api#/) | Push expenses to accounting platforms.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Sync-Expenses.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Sync-Expenses.yaml)
| [Lending API](https://docs.codat.io/lending-api#/) | Make credit decisions backed by enhanced financials, metrics, reports, and data integrity features.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Lending.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Lending.yaml)
| [Sync for Payables API](https://docs.codat.io/sync-for-payables-v2-api#/) | Streamline your customers' accounts payable workflow.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Sync-Payables.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Sync-Payables.yaml)
| [Sync for Payroll API](https://docs.codat.io/sync-for-payroll-api#/) | Push payroll to accounting platforms.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Sync-Payroll.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Sync-Payroll.yaml)

#### Alternative products and versions

| API | Description | JSON | YAM: |
| :-  | :-          | :-   | :-   |
| [Common API](https://docs.codat.io/codat-api#/) | Manage the building blocks of Codat, including companies, connections, and more.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Platform.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Platform.yaml)
| [Accounting API](https://docs.codat.io/accounting-api#/) | Access standardized accounting data from our accounting integrations.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Accounting.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Accounting.yaml)
| [Banking API](https://docs.codat.io/banking-api#/) | Access standardized banking data from our banking integrations.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Banking.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Banking.yaml)
| [Commerce API](https://docs.codat.io/commerce-api#/) | Access standardized commerce data from our commerce integrations.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Commerce.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Commerce.yaml)
| [Assess API](https://docs.codat.io/assess-api#/) | Make credit decisions backed by enhanced financials, metrics, reports, and data integrity features.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Assess.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Assess.yaml)
| [Sync for Expenses API (v1)](https://docs.codat.io/sync-for-expenses-v1-api#/) | Push expenses to accounting platforms.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Sync-Expenses-v1.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Sync-Expenses-v1.yaml)
| [Sync for Commerce API (v1)](https://docs.codat.io/sync-for-commerce-v1-api#/) | Push merchants' data from your ecommerce or point-of-sale (POS) platform into your merchants' accounting platform. | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Sync-Commerce-v1.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Sync-Commerce-v1.yaml)
| [Sync for Payables API (v1)](https://docs.codat.io/sync-for-payables-api#/) | Streamline your customers' accounts payable workflow.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Sync-Payables-v1.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Sync-Payables-v1.yaml)
| [Files API](https://docs.codat.io/files-api#/) | Capture your SMB's business documents with our file upload functionality.  | [JSON](https://raw.githubusercontent.com/codatio/oas/main/json/Codat-Files.json) | [YAML](https://raw.githubusercontent.com/codatio/oas/main/yaml/Codat-Files.yaml)

### Deprecated specifications

Still using our deprecated OpenAPI specification for code generation?

For clients still using our previous OpenAPI specification to generate libraries, you can continue to do so using our [Swagger-generated OAS](https://api.codat.io/swagger/v1/swagger.json). If you are new to Codat, do not use this specification. Instead, use one from the tables above. Alternatively, contact your account manager for further advice.

### Client library SDKs

- [TypeScript](https://github.com/codatio/client-sdk-typescript)
- [Python](https://github.com/codatio/client-sdk-python)
- [Go](https://github.com/codatio/client-sdk-go)
- [C#](https://github.com/codatio/client-sdk-csharp)

[Read more about our SDKs](https://docs.codat.io/introduction/libraries)
