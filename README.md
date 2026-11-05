# UTI Smart — Leitos Inteligentes

Protótipo escolar de inovação sobre previsão de demanda por leitos de UTI.

## Abrir o projeto
- Abra `index.html` no navegador, ou publique gratuitamente com GitHub Pages.
- Não é necessário instalar Node.js nem configurar servidor ou banco de dados.
- O painel, a simulação e a mini IA rodam no navegador. **A visualização 3D depende de internet para carregar o Three.js pelo CDN.**

## Funcionalidades
- Painel responsivo para celular e computador.
- Mapa 2D e visualização 3D de até 50 leitos com Three.js (InstancedMesh, sem sombras e sem texturas pesadas).
- Controle de leitos totais, ocupados, novas internações e altas.
- Cenários de lotação, avisos de risco e demanda estimada em 24, 48 e 72 horas.
- Mini IA demonstrativa: regressão linear treinada localmente em 49 dias **sintéticos** para estimar entradas e saídas dos dias 2 e 3.
- Proposta completa (8 tópicos) e roteiro para apresentação em dupla de 3–4 minutos.

## Publicar pelo GitHub Pages
1. Entre neste repositório e abra **Settings → Pages**.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha **main** e pasta **/(root)**; clique em **Save**.
4. Quando o GitHub concluir a publicação, o endereço esperado será:
   https://phbritodev.github.io/PROJETO-PLANEJAMENTO/

> O endereço só estará acessível depois de o GitHub Pages ser habilitado e de a publicação terminar.

## Atenção
Todo o conteúdo é demonstrativo. **Os dados são fictícios e o protótipo não é indicado para uso clínico** ou decisões reais sobre internações. O modelo não foi validado com informações hospitalares reais. A previsão para 24 horas usa os controles escolhidos; 48 e 72 horas usam estimativas da mini IA de demonstração. Porcentagens acima de 100% representam demanda superior à capacidade, não pacientes internados em leitos inexistentes.
