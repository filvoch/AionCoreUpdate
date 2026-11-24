<div align="center">

[English](README.md) · **Português (Brasil)** · [Español](README.es.md)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="media/aioncore-logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="media/aioncore-logo-light.svg">
  <img alt="AionCore" src="media/aioncore-logo-light.svg" width="340">
</picture>

### Veja o DPS do grupo, ache o Cubo Oculto e controle tudo por uma barra sobre o jogo.<br>Um app grátis para o Aion 2 no Windows.

[![Versão](https://img.shields.io/github/v/release/filvoch/AionCoreUpdate?label=vers%C3%A3o&color=1a9bbd)](https://github.com/filvoch/AionCoreUpdate/releases/latest)
![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)
![Grátis](https://img.shields.io/badge/pre%C3%A7o-gr%C3%A1tis-2ea44f)

<a href="https://github.com/filvoch/AionCoreUpdate/releases/latest/download/AionCore-Setup.exe"><img alt="Baixar o AionCore para Windows (AionCore-Setup.exe)" src="https://img.shields.io/badge/Baixar_para_Windows-AionCore--Setup.exe-1a9bbd?style=for-the-badge&logo=windows&logoColor=white"></a>

<sub>Instalador de uns 195 MB · se atualiza sozinho · Windows 10 ou 11, 64 bits · [Todas as versões](https://github.com/filvoch/AionCoreUpdate/releases) · [Site](https://aioncore.app) · [Discord](https://aioncore.app/discord)</sub>

<img alt="Captura de tela do Radar de Cubos com norte fixo: você no centro com uma seta para onde você olha, três Cubos Ocultos em volta, o mais perto destacado com uma linha, e o texto &quot;Cube 38 m northeast&quot; e &quot;+2 more · ahead, to the right&quot; (app em inglês, dados de exemplo)" src="media/shot-radar.jpg" width="820">

</div>

> [!NOTE]
> O medidor precisa do [Npcap](https://npcap.com) (o instalador confere e avisa se faltar), e o Aion 2 deve estar em **janela sem bordas** ou **modo janela**. Veja [Instale em 3 passos](#instale-em-3-passos).

## Por que baixar

- **Saiba quem carregou a luta.** Dano, DPS e parte de cada jogador do grupo, habilidade por habilidade.
- **Não perca nenhuma luta.** Cada luta fica no histórico do seu PC, para comparar com a próxima tentativa.
- **Ache o Cubo Oculto.** O radar abre sozinho quando o jogo mostra um cubo perto e diz para onde ir.
- **Tudo numa barra sobre o jogo.** Um botão para cada janela, um cadeado que deixa o clique passar e nada na frente quando você abre o mapa ou o inventário.

## Novidades desde a 1.20

- **PvP automático e grátis, com Abyss Rank:** um cartão sobre o jogo liga sozinho num combate PvP ou no Abismo/Fenda, com K/D/A, histórico de partidas e o seu Abyss Rank — sem precisar de apoio.
- **AionCore 2.0, o novo visual padrão:** painel do medidor redesenhado, com imagens de capa, cor e animação do nick, e modo Treino para quem apoia.
- **Avisos de mecânica do chefe com a fala do próprio jogo**, um cartão de Ameaça para quem apoia, e um resumo do jogador ao passar o mouse, com habilidades, buffs e o maior golpe.
- **Medidor mais fluido:** barras contínuas, o número de DPS desliza e as linhas que mudam de posição deslizam até o novo lugar.
- **Tela de plugins redesenhada:** liga, desliga ou oculta cada overlay numa só aba, com visão em Lista ou Grade.

[Tudo o que mudou](https://github.com/filvoch/AionCoreUpdate/releases/latest) · [As telas novas no site](https://aioncore.app/features)

## Medidor de DPS do grupo

- **O grupo inteiro numa olhada:** uma linha por jogador, com dano, DPS e parte de cada um. Abas **HPS**, **APS** (golpes por segundo) e **Recebido** para cura, golpes e dano recebido. Escopo **Eu**, **Grupo**, **Raid** ou **Automático**.
- **Cada habilidade aberta:** clique no nome e veja golpes, crítico, costas, multi-hit, média, mínimo e máximo, gráfico e log.
- **Tempos do chefe:** HP do chefe em números, **Derrota em** (estimativa pela velocidade com que o HP cai) e **Fúria em** para chefes com tempo de fúria conhecido.
- **Suas lutas guardadas no seu PC:** **Histórico**, resumo de cada luta, **Comparar lutas**, **Corridas de chefes**, recapitulação da morte e exportar em JSON, CSV ou PNG.
- **Grupo flutuante:** a vida do seu grupo numa janela pequena.
- **Cinco visuais grátis:** Faixas, Clássico, Denso, Painel e Vidro, e o **acabamento Vidro** sobre Denso, Painel e Faixas.
- **Barra de baixo, grátis em todos os visuais:** copiar o DPS do grupo para o chat (o AionCore só copia; quem cola é você) e print só do medidor.

<p align="center"><img alt="Captura de tela do AionCore Meter no visual Faixas numa luta de chefe: no alto o HP do chefe com Derrota em e Fúria em, e embaixo uma linha por jogador, seis jogadores, com dano, DPS e parte (app em inglês, dados de exemplo, nomes inventados)" src="media/shot-meter.jpg" width="400"></p>

## Radar de Cubos Ocultos

Uma janelinha que abre sozinha quando o jogo mostra um Cubo Oculto perto de você e some quando não há nenhum.

- **Automático:** abre quando aparece um cubo ainda fechado e se esconde uns 3 segundos depois que o último some. Prefere ver sempre? Ligue **Manter o radar sempre visível**.
- **Norte fixo**, como o minimapa do jogo, ou **Gira com você**.
- **Vários cubos:** o da vez ganha o ponto maior e a linha; o texto mostra "+N outros".
- **Altura, zoom e tamanho:** um cubo a 3 m ou mais acima ou abaixo de você ganha uma marca ▲ ou ▼ e o texto diz quantos metros. Destrave o radar para aproximar com a roda do mouse e arrastar as bordas.
- **Avisos que dizem para onde ir:** a menos de 80, 50, 25 e 10 m, se o cubo está à direita, à frente ou atrás, e quando outro jogador já abriu.

O radar mostra só os cubos que o jogo envia. O jogo só informa a sua posição quando você usa uma habilidade ou dash; sem uma posição recente, o radar mostra "Cubo detectado" e pede para você se mexer. Tudo fica em **Configurações › Avisos e eventos**.

<p align="center"><img alt="Demonstração animada do Radar de Cubos: um Cubo Oculto a nordeste, à sua frente, se aproxima conforme você anda até ele, de 85 m até 18 m (app em inglês, dados de exemplo)" src="media/demo.gif" width="720"></p>

## Barra do topo e janela principal

- **Barra do topo:** um botão para o medidor, o grupo flutuante, o checklist, os timers, o radar de pets, os avisos de mecânica, o guia de masmorras e o YouTube. O cadeado trava tudo e o clique passa direto para o jogo. Opacidade de 20% a 100% e modo recolhido.
- **Janela principal:** Início com a contagem para o reinício do dia e da semana, os seus personagens, os próximos eventos e a última luta; Ctrl+K busca telas e comandos. Abre pela barra, pela bandeja do Windows ou por Ctrl+Alt+A.
- **Fora do caminho:** a barra e os overlays somem quando outro programa está na frente e quando um menu do jogo abre (Esc, mapa, inventário). Com **Abrir o AionCore como administrador** ligado, o AionCore vê só se as teclas Alt e Esc estão apertadas, só com o jogo na frente; nenhuma outra tecla, e nada é gravado nem enviado. Sem o modo administrador, ele se guia pelo cursor do jogo. Desliga em **Configurações › Sobre o jogo**.
- **Atalhos Ctrl+Alt** que funcionam por cima do jogo (M medidor, G grupo, H recolher a barra, L travar, K clique atravessa, D esconder tudo). Se outro programa já usa um, o AionCore oferece trocar.
- O PvP automático é grátis; Ameaça é para quem apoia; Alvo PvP está em Acesso Antecipado de apoiador. O **Mapa** é uma aba grátis da janela principal.

<p align="center"><img alt="Captura de tela da barra do AionCore: o nome à esquerda, uma fileira de botões de ícone, o controle de opacidade em 100%, o cadeado e os botões de recolher, ajustes e fechar (app em inglês)" src="media/shot-bar.jpg" width="880"></p>

<p align="center"><img alt="Captura de tela da janela principal no Início: menu lateral com Início, Checklist, Medidor, Masmorras, Agenda e Pets, a contagem dos reinícios diário e semanal, o que não perder, dois personagens, os próximos eventos e a última luta (app em inglês, dados de exemplo, nomes inventados)" src="media/shot-home.jpg" width="820"></p>

## Mecânicas de chefe

- **Painel de mecânicas:** o que o chefe faz e o que você deve fazer, por DG. Grátis. A cobertura cresce a cada versão, e mecânica ainda não conferida no jogo vem marcada.
- **Avisos de mecânica na tela:** uma a três palavras no alto da tela antes do golpe. Quem apoia recebe primeiro; todo mundo a partir de **10 de novembro de 2026**.

## Em validação

Já vêm no instalador e passaram nos testes automáticos, mas ainda não foram conferidos ao vivo no jogo:

- **Checklist:** tarefas do dia e da semana por personagem. Missões de Dever, limite de Kinah do dia, Pontos do Abismo da semana e Energia Odyle são lidos do jogo; o resto você marca.
- **Agenda e Timers:** eventos da semana com contagem e chefes de campo lidos do jogo ao abrir o mapa-múndi.
- **Pets:** a coleção por família, as almas que faltam e onde farmar. O **radar de pets** lista os monstros perto que dão alma que falta; vem desligado.

<table>
  <tr>
    <td width="50%"><img alt="Captura de tela do Checklist de um personagem: Energia Odyle, limites de ganho, tarefas diárias e semanais, algumas lidas do jogo e outras marcadas à mão (app em inglês, dados de exemplo, nomes inventados)" src="media/shot-checklist.jpg"></td>
    <td width="50%"><img alt="Captura de tela da Agenda: eventos da semana com horários e contagem, e o bloco de chefes de campo esperando o mapa do jogo ser aberto (app em inglês, dados de exemplo)" src="media/shot-agenda.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Checklist</sub></td>
    <td align="center"><sub>Agenda</sub></td>
  </tr>
  <tr>
    <td width="50%"><img alt="Captura de tela da aba Pets: a coleção por família, o mapa de farm com os pontos de cada família e os pets mais perto do próximo nível (app em inglês, dados de exemplo)" src="media/shot-pets.jpg"></td>
    <td width="50%"><img alt="Captura de tela do radar de pets: monstros perto que dão alma que falta, com distância aproximada e um minirradar (app em inglês, dados de exemplo)" src="media/shot-petradar.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Pets</sub></td>
    <td align="center"><sub>Radar de pets</sub></td>
  </tr>
</table>

Viu algo errado? Conte no [Discord](https://aioncore.app/discord) ou abra uma [issue](https://github.com/filvoch/AionCoreUpdate/issues).

## Instale em 3 passos

Requisitos: Windows 10 (1809 ou mais novo) ou 11, 64 bits.

1. [Baixe o instalador](https://github.com/filvoch/AionCoreUpdate/releases/latest/download/AionCore-Setup.exe) e execute. Ele instala só para o seu usuário. Se o Windows mostrar "O Windows protegeu o computador", clique em **Mais informações** e depois em **Executar assim mesmo** ([por quê](#perguntas-frequentes)).
2. Instale o [Npcap](https://npcap.com) uma vez, marcando *Install Npcap in WinPcap API-compatible Mode* e *Support loopback traffic*. Se faltar, o instalador do AionCore avisa e abre o site do Npcap no fim.
3. Abra o AionCore pelo atalho. No Aion 2, use **janela sem bordas** ou **modo janela**: o Windows não deixa nada aparecer sobre a tela cheia exclusiva.

Na primeira abertura você escolhe idioma e região e lê o aviso de uso e dados. Conectar a conta do Discord é opcional. App e site em 6 idiomas: português, inglês, espanhol, alemão, francês e russo (alemão, francês e russo são tradução automática revisada, ainda sem revisão de falante nativo).

O AionCore se atualiza sozinho: confere a assinatura digital do instalador e não instala sozinho com o Aion 2 aberto (se você clicar em **Atualizar** com o jogo aberto, ele pergunta antes, e o medidor perde a luta em andamento). Suas configurações e o histórico de lutas ficam entre as versões.

## Para quem apoia

O AionCore é grátis. Quem quiser ajudar a mantê-lo pode apoiar no Ko-fi com qualquer valor. Um pagamento único de **US$ 15 ou mais, em dólar** (o item da loja do Ko-fi ou uma doação única) faz de você **Apoiador por 12 meses**, **sem renovação automática**. Valores menores são um agradecimento, sem benefícios. **Tudo o que já saiu grátis continua grátis para sempre.**

O que o apoiador tem hoje:

- **AionCore Theme:** o visual novo do medidor, com topo em duas linhas, seta de tendência por jogador, até 4 colunas por função (Tanque, DPS e Curandeiro) e **Só eu** com as suas melhores habilidades.
- **Avisos fora do jogo:** deu alt-tab ou minimizou? Convites de grupo e de Expedição, chamados para entrar e pedidos de entrada aparecem por cima de qualquer janela. Clique e o AionCore traz o jogo para a frente; ele nunca clica nem aceita nada por você. Grátis para todos a partir de 11/01/2027.
- **Painel da sala:** quem está na sala, GS, poder de combate e quem está pronto. Grátis para todos a partir de 11/02/2027.
- **Cartão do candidato:** quem pede para entrar na sua sala aparece numa janelinha com classe, nível, GS e o que você já jogou com a pessoa, e você pode consultar o resumo do perfil público dela no site.
- **Temas de cor** do medidor.
- **Análise de habilidades:** uma aba nos detalhes de cada jogador, ao vivo e no Histórico, com usos estimados, dano por uso, DPS ativo, picos e linha do tempo de cada habilidade.
- **Selo de apoiador:** um selo na sua linha do medidor com gema, estilo e movimento, e uma barra de éter na cor da sua barra. Só você vê no seu medidor.
- **Relatório da Arena:** no Resumo de uma luta de Arena, um cartão com resultado, pontuação, duração, abates e mortes (o que o jogo ainda não informou fica em branco; hoje só a vitória é reconhecida).
- **Antes de todo mundo:** avisos de mecânica de chefe (até 10/11/2026) e avisos da barra de guarda do chefe (até 11/11/2026).

<table>
  <tr>
    <td width="50%"><img alt="Captura de tela de três avisos fora do jogo empilhados: chamado para entrar, convite de Expedição e convite de grupo, cada um com classe, nível, GS, poder de combate e servidor do jogador (app em inglês, dados de exemplo, nomes inventados)" src="media/shot-alerts.jpg"></td>
    <td width="50%"><img alt="Captura de tela do Painel da sala: quatro membros com GS, poder de combate, nível e quem está pronto, uma vaga aberta e dois pedidos para entrar (app em inglês, dados de exemplo, nomes inventados)" src="media/shot-room.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Avisos fora do jogo</sub></td>
    <td align="center"><sub>Painel da sala</sub></td>
  </tr>
</table>

[Apoie o AionCore](https://aioncore.app/apoie)

<sub>Sem propaganda paga. No Início e em Configurações › Sobre há um cartão de parceiro (link de afiliado), avisado na tela: o AionCore pode receber uma comissão sem custo extra para você.</sub>

## Seus dados

Suas lutas ficam no seu PC. Sem conectar uma conta, nenhuma luta sai dele. Conectar a conta (pelo Discord) é opcional; ao conectar, um aviso mostra o que vai para o [aioncore.app](https://aioncore.app) e o envio das lutas de chefe e das inspeções liga. Desliga com 1 clique em **Configurações › Conta e envio**. Detalhes na [política de privacidade](https://aioncore.app/privacidade).

## Perguntas frequentes

<details>
<summary><b>Dá ban?</b></summary>

O AionCore lê o tráfego de rede do seu PC e o título da janela do jogo, sem alterar arquivos nem a memória do jogo. Ele não envia teclas nem cliques ao jogo: copiar o DPS para o chat só copia, quem cola é você. Mesmo assim, nenhuma ferramenta desse tipo pode garantir o que a política do jogo decide: o risco do uso é seu.
</details>

<details>
<summary><b>O AionCore lê o que eu digito?</b></summary>

Não. Com a opção **Nos menus do jogo** ligada e o AionCore aberto como administrador, ele vê só se as teclas Alt e Esc estão apertadas, e só com o Aion 2 na frente, para saber se um menu do jogo abriu. Nenhuma outra tecla é lida, e nada é gravado nem enviado. Desligue em **Configurações › Sobre o jogo**.
</details>

<details>
<summary><b>Quais servidores e regiões funcionam?</b></summary>

Feito e testado no Aion 2 Global (servidores da América do Sul). Em outras regiões (Taiwan, Coreia) pode funcionar, mas ainda não é garantido.
</details>

<details>
<summary><b>O medidor é preciso?</b></summary>

Ele conta o que o jogo envia. Em alguns casos o medidor não enxerga tudo, e ele avisa quando não está lendo o jogo. O site explica como ele mede: [precisão](https://aioncore.app/precisao).
</details>

<details>
<summary><b>Precisa rodar como administrador?</b></summary>

Não por padrão: o AionCore instala só para o seu usuário e abre sem pedir administrador. Três situações mudam isso:

- Se o seu Npcap foi instalado com *Restrict Npcap driver's access to Administrators only*, o medidor mostra **Reabrir como administrador** (vale só daquela vez). Para nunca precisar, reinstale o Npcap sem essa opção.
- **Nos menus do jogo** (esconder a barra e os overlays quando um menu do jogo abre): para ver se o Alt e o Esc estão apertados com o jogo na frente, o AionCore precisa rodar como administrador. Sem isso, ele se guia pelo cursor do jogo.
- Se o Aion 2 roda como administrador, o clique num aviso fora do jogo só traz o jogo para a frente se o AionCore também rodar como administrador.

Para esses casos existe **Configurações › Geral › Abrir o AionCore como administrador**, desligado por padrão. Ao ligar, o Windows pede a permissão (UAC).
</details>

<details>
<summary><b>A barra ou o medidor somem quando o jogo está na frente.</b></summary>

O jogo está em **Tela cheia** exclusiva, e o Windows não mostra janelas por cima dela. Nas opções de vídeo do Aion 2, troque para **Janela sem bordas**.
</details>

<details>
<summary><b>O Windows ou o antivírus avisou ao instalar.</b></summary>

O instalador não tem certificado pago de assinatura de código, então o Windows não conhece o editor e mostra "O Windows protegeu o computador". Clique em **Mais informações** e depois em **Executar assim mesmo**. Um antivírus pode pedir confirmação pelo mesmo motivo. Para conferir que o arquivo é o original, compare o valor `sha256` do `latest.json` (nos Assets da [versão mais recente](https://github.com/filvoch/AionCoreUpdate/releases/latest)) com o resultado de:

```powershell
Get-FileHash .\AionCore-Setup.exe
```
</details>

<details>
<summary><b>O que sai do meu PC?</b></summary>

Sem conta conectada, nenhuma luta sai. O AionCore baixa os ícones das habilidades da CDN do jogo e consulta este repositório para saber se há versão nova. Com a conta conectada, vão ao aioncore.app as lutas de chefe e as inspeções, como diz o aviso antes de ligar; desliga em **Configurações › Conta e envio**. A consulta do perfil no cartão do candidato manda só nome e servidor (desliga em **Configurações › Avisos e eventos › Convite de grupo**).
</details>

<details>
<summary><b>Como desinstalo? Perco meus dados?</b></summary>

*Configurações do Windows › Aplicativos instalados › AionCore*. O desinstalador pergunta se apaga também seus dados (histórico, configurações); por padrão, mantém. Instalar uma versão nova por cima também mantém tudo.
</details>

<details>
<summary><b>É oficial? O código é aberto?</b></summary>

Não e não. O AionCore é um projeto independente, feito por um jogador, sem vínculo com a NCSOFT. O código-fonte não é público: este repositório guarda os instaladores publicados, esta página e os arquivos de tradução, abertos a contribuições.
</details>

## Contribuir

- **Bugs e ideias:** abra uma [issue](https://github.com/filvoch/AionCoreUpdate/issues/new/choose) e escolha um modelo (relato de bug, pedido de recurso ou sugestão de tradução). Nunca cole nomes de personagem, logs ou pacotes sem tirar os nomes antes.
- **Traduções:** os textos do app estão na pasta [`i18n/`](i18n/README.md). Para corrigir uma palavra, abra uma issue com o modelo *Translation suggestion*; para um idioma inteiro, envie um pull request.
- **Segurança:** relate vulnerabilidades em privado, escrevendo para contato@aioncore.app, e não numa issue pública. Veja o [SECURITY.md](SECURITY.md).

## Comunidade e contato

- **Discord:** [aioncore.app/discord](https://aioncore.app/discord)
- **Bugs:** abra uma [issue](https://github.com/filvoch/AionCoreUpdate/issues) ou escreva para contato@aioncore.app.
- **No app:** **Configurações › Ajuda e diagnóstico**.

## O projeto em números

[![Estrelas no GitHub](https://img.shields.io/github/stars/filvoch/AionCoreUpdate?style=flat&color=1a9bbd)](https://github.com/filvoch/AionCoreUpdate/stargazers) [![Downloads do instalador](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ffilvoch%2FAionCoreUpdate%2Fstats%2Finstaller-downloads.json&style=flat)](https://github.com/filvoch/AionCoreUpdate/releases) [![Última versão](https://img.shields.io/github/v/release/filvoch/AionCoreUpdate?label=version&style=flat&color=1a9bbd)](https://github.com/filvoch/AionCoreUpdate/releases/latest)

<sub>Downloads do instalador conta as instalações e as atualizações automáticas de todas as versões e é atualizado uma vez por dia. Os números vêm dos contadores do próprio GitHub: o AionCore não rastreia quem visita esta página.</sub>

## Créditos

AionCore por **Guilherme Filvoch (Simavi)**.
Projeto de fã independente, sem vínculo com a NCSOFT. Aion 2 e seus ícones, nomes e artes pertencem à NCSOFT e a seus licenciantes.
