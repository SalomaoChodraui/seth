# Notas de cada versão

## 0.3.11 (14/11/2026)

### Novidades
- **Menu no botão direito:** clicar com o botão direito na imagem, sem arrastar, abre as ferramentas, as janelas, a projeção, o plano, girar e espelhar, o layout, a sincronização, a série anterior e a próxima, o MPR e o 3D. Arrastar com o botão direito continua dando zoom.
- **Atalhos editáveis:** em Ajustes > Atalhos, clique num atalho e aperte as teclas novas. Vale para 35 comandos do visualizador, na barra de menus, no menu do botão direito e no teclado. Um atalho já usado é recusado com o motivo, e Restaurar Padrões volta tudo.
- **Projeção e sincronização pelo teclado:** Fino, MIP, MinIP e Média em ⌃⌥1 a ⌃⌥4. Sincronizar rolagem, zoom e janela em ⌃⌥S, ⌃⌥Z e ⌃⌥W. Série anterior e próxima em ⌥↑ e ⌥↓.
- **Medidas novas:** Curva (U) mede uma linha de vários pontos. Relação (T) dá a razão entre duas linhas, como no índice cardiotorácico. Polígono (P) e Retângulo (Q) dão área, média, desvio padrão, mínimo e máximo, e a Área à mão livre passa a mostrar os mesmos valores. Curva e polígono terminam com clique duplo ou Return.
- **Calibrar Escala:** com uma régua selecionada, ⌥⌘L pede o tamanho real em mm, e as medidas da série passam a usá-lo. ⇧⌥⌘L remove a calibração.
- **Rótulos da coluna:** a ferramenta Rótulos da Coluna (J) nomeia a vértebra clicada e passa para a próxima, para os pés ou para a cabeça. O rótulo aparece em todas as séries do estudo e no MPR, nas imagens que passam por ele. ⌥⌘J desfaz e ⇧⌥⌘J limpa.

## 0.3.10 (13/11/2026)

### Novidades
- **Ferro e gordura no fígado:** a ferramenta Ferro e Gordura Hepáticos (F) mede uma RM gradiente-eco multieco, como o MRQuantif. Clique no fígado, no baço, no músculo paravertebral e no ar (ruído) para pôr círculos. O painel dá a fração de gordura (PDFF), o R2*, o T2* e a concentração de ferro por R2* e pela razão de sinal com o músculo (SIR), com o ajuste de cada círculo e a curva do sinal por eco.
- **Mapas de gordura e R2*:** pixel a pixel, sobre a imagem (⌃⌘P e ⌃⌘R).
- **Calibração do ferro:** Gandon 2025 por padrão, a fórmula dos laudos do MRQuantif, com Garbowski, Wood, Hankins, Henninger, Hernando e d'Assignies à escolha (⌃⌥⌘1 a ⌃⌥⌘6).
- **Grau de esteatose:** pela diretriz SAR (6, 17 e 22 %), pelos cortes do MRQuantif (4, 10 e 20 %) ou pelos dois, com a fonte no texto copiado (⇧⌃⌘1 a ⇧⌃⌘3).
- **Laudo:** ⌃⌘C copia a técnica, gordura, R2*, T2*, ferro e graus em texto.

## 0.3.9 (13/11/2026)

### Novidades
- **Servidores DICOM e DICOMweb:** em Ajustes > Rede, cadastre o PACS da clínica pelo AE Title, endereço e porta, ou um serviço DICOMweb pela URL. Cada servidor aparece na barra lateral, com busca por nome, ID, número de acesso, data e modalidade. ⌘D baixa o exame para a Biblioteca. O Seth também recebe os exames que os servidores da lista enviam para este Mac.
- **Remoção de osso no 3D:** a Tesoura (⌥⌘X) contorna o que sai, e o corte atravessa toda a profundidade. Remover Peça (⌥⌘P) tira com um clique o osso ligado ao ponto e mantém os vasos encostados nele. ⌘Z desfaz, Mostrar Removido tinge o que saiu, e o MIP do MPR deixa o osso removido de fora.
- **Ícone novo:** dois traços em curva no lugar do S de barras.

### Correções
- **Data do exame:** no Brasil, as datas apareciam um dia antes por causa do fuso.
- **Barra do 3D:** mostra só Janela e Girar 3D, as ferramentas que agem no volume.
- **Esc:** cada Esc fecha uma camada, na ordem: a medida em desenho, a ferramenta de remoção, o 3D, o quadro ampliado, o MPR e a tela cheia. O último volta para Janela.

## 0.3.8 (13/11/2026)

### Novidades
- **Ultrassom colorido em JPEG-LS:** os exames que mostravam "Can't Show These Images" abrem, com as imagens iguais às do original. Vale para o ultrassom obstétrico da GE Voluson e para qualquer arquivo que intercale as amostras de cor.
- **Cine gravado como vídeo:** ecocardiograma, endoscopia e cine de angiografia em MPEG-2, H.264 ou HEVC abrem no visualizador e rodam em loop, quadro a quadro, como qualquer outra série.
- **Cores de tabela e croma compartilhado:** imagens em PALETTE COLOR, comuns em Doppler antigo e medicina nuclear, e em YBR_FULL_422 aparecem com as cores certas.

## 0.3.7 (11/11/2026)

### Novidades
- **Escolher as colunas da lista:** clique com o botão direito nos títulos da lista de exames e marque o que quer ver. Há dez colunas novas: Instituição, Médico Solicitante, Número de Acesso, Idade, Sexo, Nascimento, Região, Equipamento, Hora do Exame e Séries. A escolha, a ordem e as larguras ficam guardadas.
- **Data de Adição:** a lista mostra quando cada exame entrou no Seth, com data e hora, e ordena por ela.
- **Angiografia na barra lateral:** os exames XA ganham página própria e saem de Raio-X. A página Outros sai da barra lateral.

## 0.3.6 (11/11/2026)

### Novidades
- **Giroscópio no MPR:** num plano do MPR, segure o botão parado por um instante, até o cursor virar o giroscópio, e arraste para inclinar os três planos juntos em torno do ponto pressionado. Vale também segurando sobre o cruzamento. A imagem não roda no próprio plano, e ⌘R endireita tudo.
- **Cubo de orientação:** cada plano do MPR mostra no canto um cubo com as faces do paciente (R, L, A, P, H, F). Arrastar o cubo gira os planos e clicar nele endireita.
- **MIP fino durante o giro:** com MIP, MinIP ou média ligados, os planos que estão girando mostram corte fino enquanto o botão está apertado e voltam ao slab ao soltar.
- **Espessura no vaso retificado:** na linha central do vaso, o controle de slab da barra (MIP, MinIP, média e mm) vale também para o vaso retificado.
- **Ferramenta Densidade (D):** um clique lê o HU do pixel. Arrastar desenha uma elipse com média, desvio padrão, mínimo, máximo e área.
- **Séries no MPR:** a faixa de séries fica escondida durante o MPR. Escolher outra série sai do MPR e mostra a série.

## 0.3.5 (10/11/2026)

### Novidades
- **Escore de cálcio coronariano:** na TC sem contraste, a ferramenta de escore de cálcio pinta de rosa tudo a partir de 130 HU. Escolha a artéria (TCE, DA, CX ou CD, ou ⌥⌘1 a ⌥⌘4) e clique na calcificação: ela ganha a cor da artéria em todos os cortes que alcança. O painel mostra Agatston e volume por artéria e o total, e ⌥⌘C copia o resultado para o laudo.
- **Contorno para separar ramos:** arrastar em volta de um trecho marca só o cálcio de dentro, naquele corte. Os cliques seguintes param no contorno, então contorne o TCE primeiro e depois clique na DA e na CX.
- **Guia passo a passo:** abre no primeiro uso e depois pelo "?" do painel ou por ⌥⌘/.

## 0.3.4 (09/11/2026)

### Novidades
- **Linha central do vaso na angio-TC:** com a ferramenta Linha Central do Vaso (tecla E), dois cliques dentro do vaso no MPR traçam a linha pelo centro do contraste. A tela mostra o vaso retificado, que gira com o scroll, e o corte perpendicular, que anda pelo vaso com o scroll e mede diâmetro mínimo e máximo, área e distância desde o início. A régua no vaso retificado mede comprimento ao longo do vaso.
- **Pontos de passagem:** cliques entre o início e o fim guiam a linha em trechos difíceis. ⌥⌘⌫ remove o último ponto e ⌥⌘E limpa a linha.

## 0.3.3 (07/11/2026)

### Novidades
- **JPEG-LS:** exames comprimidos em JPEG-LS abrem, como angiografias (XA) e relatórios de dose de aparelhos Philips.

### Correções
- **Série que não abre:** quando uma imagem não pode ser lida, a miniatura mostra um aviso e o visualizador diz o motivo, em vez de ficar carregando.
- **Quadros em vários fragmentos:** imagens comprimidas divididas em vários pedaços, sem tabela de posições, são remontadas corretamente.

## 0.3.2 (07/11/2026)

### Novidades
- **Mac com Intel:** o Seth agora roda também em Macs com Intel no macOS 26 Tahoe.
- **Abrir uma imagem solta:** ao abrir um .dcm pelo Finder, o Seth procura o resto do exame na pasta e oferece importar o exame inteiro.

### Correções
- **Delete na lista** apaga o exame selecionado, depois de confirmar.

## 0.3.1 (07/11/2026)

### Novidades
- **Barra de espaço no Finder:** num arquivo .dcm, o Quick Look mostra o exame grande, como uma foto, com paciente, data e descrição.
- **Abrir com o Seth:** em Ajustes > Geral > Finder, o Seth pode virar o app que abre os arquivos DICOM, no duplo clique e no botão do Quick Look.

### Desempenho
- O app ficou menor: 6,8 MB, antes 11 MB.

## 0.3.0 (07/11/2026)

O Kidicom agora se chama **Seth**, com ícone novo. Seus exames e ajustes passam sozinhos para o Seth na primeira abertura.

### Novidades
- **Atualizações automáticas:** o Seth avisa quando sai versão nova e se atualiza com um clique. Também em Seth > Procurar Atualizações…
- **Subtração digital em angiografias:** X liga e desliga, ⇧X usa o quadro na tela como máscara.
- **Tela cheia:** duplo clique numa imagem sozinha; a faixa de séries, a barra de ferramentas e os menus aparecem ao encostar o ponteiro na borda.
- **Giro com dois dedos** no trackpad, no 2D, no MPR e no 3D.
- **Atalhos:** A, C e S mostram axial, coronal e sagital; 0 a 4 aplicam as janelas; o ângulo passa para G; Tab esconde o nome do paciente.
- **Faixa de séries recolhível** (⇧⌘S) e comandos de leitura no menu Visualizar.

### Correções e desempenho
- Scroll no MPR rápido e sem pular cortes.
- Janela/nível, cine, 3D e importação muito mais leves.
- Cada medida aparece só na imagem em que foi feita.
- Na comparação, cada exame mostra a própria descrição.

### Segurança dos dados
- Antes de cada atualização, uma cópia da biblioteca é guardada. Se algo der errado, o Seth oferece restaurar.

