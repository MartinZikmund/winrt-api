---
-api-type: winrt method
---
 To import an issued certificate, it is not necessary for the certificate request to have been generated on the importing computer.
 The certificates included in the response need not be chained to trusted root certificates on the importing computer.
 The certificate is installed in the app container MY store.
 [Certification authority](XREF:TODO:security.c_gly) and Root certificates are installed in the app container intermediate [certification authority](XREF:TODO:security.c_gly) store.
 The key container name and key specification for the imported certificate are determined as described in the Remarks section of [PFXImportCertStore](XREF:TODO:security.pfximportcertstore) with the exception that if AttributeId 1.3.6.1.4.1.311.17.1 is not present, MS_KEY_STORAGE_PROVIDER is always used as the provider name.