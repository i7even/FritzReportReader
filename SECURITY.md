# Security / Segurança

## English

### Verify the executable

Download the executable only from the official [Releases](https://github.com/i7even/FritzReportReader/releases/latest) page and compare its SHA-256 with `SHA256SUMS.txt`.

```powershell
Get-FileHash .\FritzReportReader-v0.6.1B-win-x64.exe -Algorithm SHA256
```

Version 0.6.1B does not yet have a publicly trusted Authenticode signature. Windows may show **Unknown publisher**. A matching hash confirms that the bytes match the published asset, but it does not replace an informed decision about the software source.

### Antivirus reference for this build

The exact Windows x64 executable identified by the SHA-256 above was submitted to [VirusTotal](https://www.virustotal.com/gui/file/f5a51376b96663b02321fbaef6bd6f7b61ba17f0600b58095b1ea416cd0115a1/detection) on 2026-08-30. At the end of that analysis, 1 of 66 engines reported a generic detection (`Zillya: Trojan.Agent.Win32.4629592`) and the other 65 engines reported `Undetected`.

An isolated detection can be a false positive, especially for a new unsigned self-contained executable, but it must not be presented as proof that a file is safe. Results can change as vendors update their engines. Always compare the hash and make an informed decision before running the file.

### Report a problem

Open a GitHub Issue with the application version, Windows version, action taken, expected result and displayed error.

**Never attach a real Support Data file.**

If a line is essential, first replace IPs, MACs, names, phone numbers, certificates, keys, identifiers and other private data with synthetic values.

## Português

### Verificar o executável

Transfira o executável apenas da página oficial de [Releases](https://github.com/i7even/FritzReportReader/releases/latest) e compare o SHA-256 com `SHA256SUMS.txt`.

```powershell
Get-FileHash .\FritzReportReader-v0.6.1B-win-x64.exe -Algorithm SHA256
```

A versão 0.6.1B não possui ainda assinatura Authenticode pública. O Windows pode apresentar **Editor desconhecido**. Um hash correto confirma que os bytes correspondem ao ficheiro publicado, mas não substitui uma decisão informada sobre a origem do programa.

### Referência antivírus desta compilação

O executável Windows x64 exato, identificado pelo SHA-256 acima, foi enviado ao [VirusTotal](https://www.virustotal.com/gui/file/f5a51376b96663b02321fbaef6bd6f7b61ba17f0600b58095b1ea416cd0115a1/detection) em 30/08/2026. No fim dessa análise, 1 de 66 motores apresentou uma deteção genérica (`Zillya: Trojan.Agent.Win32.4629592`) e os restantes 65 indicaram `Undetected`.

Uma deteção isolada pode ser um falso positivo, sobretudo num executável novo, autónomo e ainda não assinado, mas não deve ser apresentada como prova de que o ficheiro é seguro. Os resultados podem mudar quando os fabricantes atualizam os motores. Confirme sempre o hash e tome uma decisão informada antes de executar o ficheiro.

### Comunicar um problema

Abra um GitHub Issue com a versão da aplicação, versão do Windows, ação realizada, resultado esperado e mensagem apresentada.

**Nunca anexe um Support Data real.**

Se precisar de citar uma linha, substitua primeiro IPs, MACs, nomes, telefones, certificados, chaves, identificadores e outros dados privados por valores fictícios.
