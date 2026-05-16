# Docs

Some useful templates, links and archived Web content.

## Templates

These templates can be used for:
- Docker Hub: [`jotools/codesign`](https://hub.docker.com/r/jotools/codesign) and [`jotools/innosetup`](https://hub.docker.com/r/jotools/innosetup)
- Xojo Example Project: `AAS CodeSign InnoSetup.xojo_project`

Template configuration files for Codesigning using:
- [Azure Artifact Signing](./aas-codesign/)
- [Codesigning certificate `.pfx`](./pfx-codesign/)

## Links

### Microsoft

- [Azure Artifact Signing](https://azure.microsoft.com/en-us/products/artifact-signing/)  
  Secure your applications with a fully managed end-to-end signing service for code, documents, applications, and more
- [Microsoft: Quickstart](https://learn.microsoft.com/en-us/azure/artifact-signing/quickstart)  
  Set up Artifact Signing


### HowTo's
- [Melatonin](https://melatonin.dev/blog/code-signing-on-windows-with-azure-trusted-signing/)  
  Code signing with AAS
- [KoalaDocs](https://github.com/koaladsp/KoalaDocs/blob/master/azure-code-signing-for-plugin-developers.md#232-preparing-signtoolexe)  
  AAS | signtool.exe


### Components
- [Docker Hub: jotools/codesign](https://hub.docker.com/r/jotools/codesign)  
  Azure Artifact Signing | PFX | Docker | jsign
- [Docker Hub: jotools/innosetup](https://hub.docker.com/r/jotools/innosetup)  
  InnoSetup | Docker | jsign
- [jsign](https://github.com/ebourg/jsign)  
  Authenticode signing tool in Java
- [InnoSetup](https://jrsoftware.org/isinfo.php)  
  Inno Setup is a free installer for Windows programs


## Archived Web Content

These articles have been very helpful and are worth being preserved as `.pdf`.

- [Melatonin: Code signing with AAS](./archive/01_Melatonin-Dev_AzureTrustedSigning.pdf)
- [KoalaDocs: AAS | signtool.exe](./archive/02_KoalaDocs_Signtool.pdf)
