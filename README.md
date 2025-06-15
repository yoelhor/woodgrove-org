# Woodgrove org

This repository is used to host the [did.json](https://learn.microsoft.com/en-us/entra/verified-id/how-to-register-didwebsite) and [did-configuration.json](https://learn.microsoft.com/en-us/entra/verified-id/how-to-dnsbind) files required for decentralized ID (DID) registration for `did:web` and domain ownership verification as part of the Microsoft Entra Verified ID [advanced setup](https://learn.microsoft.com/en-us/entra/verified-id/verifiable-credentials-configure-tenant). The files are served under the /.well-known/ path at the root of the domain id.woodgroveorg.com.

By publishing this file, we enable decentralized identity trust between our domain and the associated decentralized identifier (DID), allowing verifiable credentials to be issued and validated securely.

## Deployment

This GitHub repository uses [GitHub Pages](https://docs.github.com/en/pages) with a workflow that automatically publishes files to a public website, enabling seamless deployment of static assets like JSON files to the root domain.
