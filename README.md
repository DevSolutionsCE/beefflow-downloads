# BeefFlow — Downloads

Instalador oficial do **BeefFlow** para o computador servidor da loja (Windows), publicado pela **DevSolutions**.

Este repositório guarda **só os arquivos de instalação** (em [Releases](https://github.com/DevSolutionsCE/beefflow-downloads/releases)). O código do sistema é privado.

## Baixar

- **Versão mais recente:** [BeefFlow-Setup-x64.exe](https://github.com/DevSolutionsCE/beefflow-downloads/releases/latest/download/BeefFlow-Setup-x64.exe)
- **Todas as versões e notas:** [Releases](https://github.com/DevSolutionsCE/beefflow-downloads/releases)

> **Versão piloto (0.2.0-piloto.1).** Estamos acompanhando as primeiras lojas de perto. Fale com a DevSolutions antes de instalar para combinarmos a implantação: WhatsApp (85) 99615-9544.

## Requisitos do servidor

- Windows 10 22H2 ou Windows 11, 64 bits (Home ou Pro)
- Conta de administrador do Windows
- 5 GB livres no disco
- Rede local (cabo recomendado) marcada como **Privada**

## Como instalar

1. Baixe e execute o instalador no computador que será o servidor. O instalador do piloto **ainda não tem assinatura digital**, então o Windows pode mostrar o aviso do SmartScreen: clique em **Mais informações** e depois em **Executar assim mesmo**.
2. No final, abra o primeiro acesso: cadastre a empresa (razão social e CNPJ) e crie o administrador.
3. O sistema fica liberado por **15 dias de teste**. Para continuar depois do teste, fale com a DevSolutions: a ativação da licença é feita junto com a nossa equipe.

Os caixas abrem o BeefFlow pelo navegador, na rede local. As vendas continuam mesmo sem internet.

## Conferir o arquivo baixado (opcional)

Cada release traz o `SHA256SUMS.txt`. No PowerShell, na pasta onde o arquivo foi salvo:

```powershell
Get-FileHash .\BeefFlow-Setup-x64.exe -Algorithm SHA256
```

O valor exibido deve ser **igual** ao do `SHA256SUMS.txt` da mesma release (e ao SHA-256 mostrado no site do BeefFlow). Se for diferente, não instale e fale com a DevSolutions.

## Suporte

DevSolutions — WhatsApp (85) 99615-9544.
