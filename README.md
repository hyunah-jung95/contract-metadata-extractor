# contract-metadata-extractor
A streamlit application for extracting metadata of contracts using Azure Document AI

# Live App
[Go to Live App](https://metadata-extractor-basic-787703115620.us-central1.run.app/)

If user uploads contracts, the app extract metadata.
<img width="585" alt="image" src="https://github.com/user-attachments/assets/7f233c17-bd9d-4ae0-9431-04183fb6f30c" />

# Metadata Schema
- Title, Parties(Name, address, reference name, clause)
- Execution date, effective date, expiration date, contract duration, renewal date
- Jurisdictions(clause, region)
- [Azure Document AI docs - contract AI schema](https://github.com/Azure-Samples/document-intelligence-code-samples/blob/main/schema/2024-11-30-ga/contract.md)

# License
The source code is not disclosed as this project was developed in association with Jigo.ai and is licensed under Jigo.ai Corporation.
