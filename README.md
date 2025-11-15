# Zeno ID Docs

Identity document processing service for the **ZenoN-Cloud** platform.

This service is responsible for:
- Secure handling of identity documents (passports, ID cards, driver licenses)
- Storing raw documents in encrypted GCS buckets
- Using Google Cloud Document AI (Identity) to extract structured fields
- Exposing verification and lookup APIs to other ZenoN-Cloud services

## Dependencies

- **Auth / Identity:** [Zeno Auth](https://github.com/ZenoN-Cloud/zeno-auth)
- **Infrastructure:** [Zeno Infra](https://github.com/ZenoN-Cloud/zeno-infra)

## Related services

- **Financial documents:** [Zeno Docs](https://github.com/ZenoN-Cloud/zeno-docs)
