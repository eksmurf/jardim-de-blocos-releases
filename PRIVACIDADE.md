# Privacidade — Jardim de Blocos 0.1.2

Atualizado em 14 de outubro de 2026.

O jogo guarda pontuação, recorde, peças, sementes, flores e preferências localmente no aparelho. Não enviamos esses dados para um servidor. Não há anúncios, compras, contas de jogador ou telemetria nesta versão.

## Atualizações opcionais

O jogador pode habilitar **Verificar e baixar ao abrir** ou solicitar **Buscar e baixar agora**. Ao fazer isso, o aplicativo consulta a API pública do GitHub e, quando encontra uma versão nova válida, baixa o APK pelo GitHub Releases. Essa comunicação usa internet e pode consumir dados móveis.

O GitHub e seus provedores de distribuição recebem o endereço IP e informações técnicas da conexão, como o agente HTTP com nome e versão do jogo. O jogo não envia a pontuação, o jardim, identificadores do aparelho, contatos, arquivos pessoais ou localização. O GitHub pode registrar acessos e contagens de download conforme sua própria [declaração de privacidade](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

A preferência é desativada por padrão, pode ser ativada na primeira abertura e alterada pelo botão **Atualizações**. Desativá-la cancela consultas/downloads pendentes. Sem ela, o jogo continua funcionando offline. Uma busca manual continua disponível mediante ação do jogador.

O APK baixado fica no armazenamento privado do aplicativo. Tamanho e SHA-256 são verificados antes de abrir o instalador. A instalação exige confirmação e eventual autorização de fonte pelo próprio Android. O aplicativo não altera essa autorização automaticamente. O progresso é salvo antes de abrir o instalador.

## Permissões

- `INTERNET`: consultar e baixar atualizações opcionais.
- `REQUEST_INSTALL_PACKAGES`: encaminhar o APK baixado ao instalador do Android, que mantém o controle da confirmação.

Não solicitamos acesso a microfone, contatos ou armazenamento compartilhado. Não há token de acesso ao GitHub no APK. O repositório de código permanece privado; as versões para download são públicas.

## Dados locais e contato

Desinstalar o jogo apaga seus dados locais. Atualizações instaladas por cima, com o mesmo pacote e assinatura, devem preservar o progresso. Não há sincronização entre PC e celular.

Para dúvidas ou problemas, use as [issues do projeto de distribuição](https://github.com/eksmurf/jardim-de-blocos-releases/issues). As issues são públicas; não inclua informações pessoais sensíveis. Esta descrição corresponde ao protótipo atual e deverá ser revisada caso novos serviços sejam adicionados.
