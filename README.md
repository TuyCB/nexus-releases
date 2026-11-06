# nexus-releases

Pacotes dos apps Nexus, baixados e atualizados pelo **NexusHub** (botões Baixar / Atualizar).

- `versoes.json`: manifesto com app, versão, URL do zip, tamanho e SHA-256 (o Hub confere o hash antes de instalar).
- Cada app tem uma release com o nome dele; os zips ficam como arquivos da release.
- Os apps usam o .NET 8 Desktop Runtime. Sem ele, o Windows avisa e abre a página de download.

Gerado pelo `publicar.ps1` do NexusHub. O código dos apps não fica aqui.
