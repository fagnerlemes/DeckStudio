# Deck Studio

Seu espaço de comandos para Windows. **By Fagner Lemes.**

Aplicativos, pastas, informações do computador e controles do dia a dia em um painel personalizável.

**Versão atual: 1.2.2** — sincronização do painel por pasta, fundos animados, central de controles com mixer, Modo jogo, Organizar Painel e integração opcional com o Edge.

[Baixar instalador completo](https://github.com/fagnerlemes/DeckStudio/releases/download/v1.2.2/DeckStudio-1.2.2-x64-setup.exe) · [Histórico de atualizações](CHANGELOG.md)

## Deck Studio na sua segunda tela

[![Deck Studio em um monitor portátil à frente do computador](docs/images/deck-studio-mockup.png)](docs/images/deck-studio-mockup.png)

*Mockup ilustrativo com uma captura da versão 1.0.2. A disposição do equipamento é uma simulação; os downloads acima correspondem à versão atual.*

## Qual arquivo baixar?

| Pacote | Quando usar |
| --- | --- |
| **Instalador completo 1.2.2** | Primeira instalação ou atualização de qualquer versão anterior. Não precisa desinstalar. |

Conclua ou cancele edições abertas antes de atualizar. Perfis, botões, widgets, layouts, configurações e dados locais do navegador são preservados. A partir da 1.2.2 a distribuição pública é somente pelo instalador completo.

## Guia rápido

As sete telas abaixo são do guia disponível no programa. Clique em uma imagem para ampliar. Você pode rever o carrossel em **Configurações → Guia rápido** ou marcar **Não mostrar novamente ao abrir**.

### 1. Seu espaço de comandos

[![Bem-vindo ao Deck Studio: aplicativos, widgets e perfis em um painel personalizável](docs/images/01-boas-vindas.png)](docs/images/01-boas-vindas.png)

### 2. Arraste um atalho para o Deck

[![Arraste um atalho da área de trabalho para um espaço livre; o original permanece na área de trabalho](docs/images/02-arrastar-atalho.png)](docs/images/02-arrastar-atalho.png)

O Deck identifica o destino e cria o botão. Você também pode usar **Adicionar botão** para escolher um aplicativo, arquivo ou pasta.

### 3. Organize o painel

[![Mover, redimensionar e encaixar widgets; espaço reservado para manter uma área livre](docs/images/03-organizar.png)](docs/images/03-organizar.png)

Em **Organizar**, ajuste os tamanhos e posições. Um widget novo que ficar fora da área precisa ser encaixado ou ter a inclusão cancelada antes de concluir.

### 4. Crie perfis para suas rotinas

[![Perfis com ícones próprios, duplicação, edição e alteração da ordem; lateral recolhível](docs/images/04-perfis.png)](docs/images/04-perfis.png)

Recolher a lateral libera espaço para o painel. Ao reabrir, o menu aparece sobre os itens, sem reorganizá-los.

### 5. Personalize cada detalhe

[![Temas, fundos, cores, transparência, reflexos e brilho do perfil ou de cada elemento](docs/images/05-personalizacao.png)](docs/images/05-personalizacao.png)

Escolha temas e fundos em CSS, altere cores ou use sua imagem. A aparência também pode ser ajustada individualmente em botões e widgets.

### 6. Escolha seus widgets

[![Widgets de sistema, jogos, música e rede, com opções nos três pontos](docs/images/06-widgets.png)](docs/images/06-widgets.png)

CPU, GPU, RAM, armazenamento, rede, relógio, tarefas, música, controles rápidos, navegador, Arquivos, Jogos, Iluminação e Espaço reservado. **Arquivos** oferece até três abas, busca, navegação, lista com data de modificação quando há espaço, ícones grandes e menu do Windows com clique direito ou toque mantido por dois segundos.

Temperaturas dependem do suporte do hardware e das permissões locais. Iluminação requer SignalRGB compatível. O widget Jogos usa um coletor de desempenho; sua LAT é a medida de apresentação até conclusão na GPU e pode diferir da exibida pelo Alt+R da NVIDIA.

### 7. Recolha, restaure e faça backup

[![Recolher e restaurar o Deck com Ctrl+Alt+D ou pela lingueta; exportar backup nas Configurações](docs/images/07-acesso-backup.png)](docs/images/07-acesso-backup.png)

**Ctrl + Alt + D** é o atalho padrão, alterável nas Configurações. Desde a 1.1.5, o atalho também inicia o Deck encerrado por um auxiliar de teclado, ativado após a primeira abertura. Desativar o atalho nas Configurações encerra o auxiliar. A lingueta lateral também traz o Deck de volta. Exporte uma cópia do seu painel em **Configurações → Backup e dados**.

## Atualizar pelo programa

A partir da **1.1.4**, o Deck verifica atualizações em segundo plano na primeira abertura do dia. Quando existe uma versão mais nova, um pequeno botão verde com seta e brilho circulante aparece no topo. Clicar nele abre as Atualizações; você escolhe quando baixar e instalar.

Também é possível usar **Configurações → Atualizações → Verificar atualizações**. Na 1.1.3 e anteriores, a consulta é manual. O atualizador usa o instalador completo e verifica sua assinatura. Se o Deck ficar aberto durante a virada do dia, não há consulta periódica.

Clique no indicador **Monitor** do topo para escolher e salvar a tela de abertura. A nova aba **Configurações → Sobre o programa** apresenta a versão, a assinatura do criador e o contato de suporte.

## Downloads, integridade e suporte

A [Release atual](https://github.com/fagnerlemes/DeckStudio/releases/latest) reúne o instalador completo. Os demais anexos são a assinatura, o manifesto do atualizador, hashes, instruções e licenças. A assinatura `.sig` pertence ao atualizador; não é um certificado Authenticode do Windows. Os arquivos “Source code” gerados pelo GitHub contêm a documentação pública, não o código do aplicativo.

As mudanças anteriores estão reunidas em [um único histórico](CHANGELOG.md). Relate problemas nas [Issues](https://github.com/fagnerlemes/DeckStudio/issues), com a versão e os passos para reproduzir. Suporte: **fagner.lemes@gmail.com**.

Este repositório é destinado à distribuição e documentação. O código-fonte proprietário, as chaves de assinatura e os dados pessoais não são publicados aqui.
