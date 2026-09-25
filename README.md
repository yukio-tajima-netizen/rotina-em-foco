# Rotina em Foco

Meu sistema de produtividade pessoal, feito para o trabalho “Meu Sistema Operacional Pessoal” da disciplina **Produtividade e Gestão do Tempo** (UniFECAF). Este repositório guarda o painel web; a versão principal está no Notion.

- Painel web: https://yukio-tajima-netizen.github.io/rotina-em-foco/
- Notion: https://careful-flamingo-2c6.notion.site/Rotina-em-Foco-3e42d8a8a9b980df8418fd5f674518e8

## Descrição do sistema

O Rotina em Foco organiza tempo, tarefas, prioridades, compromissos e hábitos. Ele parte de um problema real da minha rotina: trabalho e faculdade se misturam, sem horários fixos separando os dois, as interrupções são constantes e as tarefas administrativas ocupam o tempo de outras prioridades.

O sistema tem duas partes:

- **Notion (sistema principal):** bases de Tarefas, Planejamento Semanal, Compromissos, Hábitos e Caixa de Entrada, dashboard com views filtradas, páginas sobre Matriz de Eisenhower, Pomodoro, uso da IA e Revisão Semanal.
- **Painel web (este repositório):** painel visual que qualquer pessoa pode abrir no navegador, sem login.

## Ferramentas utilizadas

- **Notion (plano gratuito):** bases de dados, views com filtros, quadros e calendário.
- **Inteligência Artificial:** Claude, usado para priorizar tarefas, planejar a semana e revisar mensagens profissionais. Os prompts e as respostas reais estão registrados no Notion.
- **Matriz de Eisenhower:** cada tarefa tem um quadrante (importante/urgente).
- **Pomodoro:** 25 minutos de foco, 5 de pausa e pausa maior após 4 ciclos. O painel tem um cronômetro.
- **GTD simplificado:** Caixa de Entrada para capturar demandas e revisão semanal.
- **GitHub Pages:** hospedagem gratuita deste painel.

## Fluxo de organização

1. **Capturar:** tudo o que chega vai para a Caixa de Entrada (Notion) ou para a captura rápida do painel.
2. **Classificar:** decidir se vira tarefa, se resolvo na hora ou se elimino.
3. **Priorizar:** definir área, prioridade, prazo e quadrante da Matriz de Eisenhower.
4. **Planejar:** encaixar as tarefas no Planejamento Semanal e conferir os compromissos.
5. **Executar:** seguir as tarefas de hoje e as prioritárias, com Pomodoro nas que pedem concentração.
6. **Revisar:** no domingo, responder as perguntas da Revisão Semanal e replanejar.

## Como utilizar o painel

1. Abra o site. Ele já vem com tarefas, semana e hábitos de exemplo, com prazos contados a partir do dia em que você abre.
2. Em **Captura rápida**, escreva uma demanda (por exemplo, "entregar relatório para o gestor sexta") e clique em **Classificar**. Revise a sugestão e salve.
3. Marque a caixa de uma tarefa para concluí-la. Na **Matriz de Eisenhower**, clique numa tarefa para mudar o quadrante.
4. Na **Semana**, clique num bloco para marcar como feito.
5. Em **Foco**, escolha uma tarefa e inicie o Pomodoro.
6. Em **Hábitos**, marque o que foi feito no dia.
7. **Restaurar dados de exemplo** (rodapé) volta tudo ao início.

As alterações ficam salvas só no navegador de quem abre. Nesta versão aberta, a classificação e o plano do dia usam regras fixas (prazo e palavras-chave), sem IA; o próprio site avisa isso. A versão do painel com IA (Claude) roda pelo claude.ai e aparece no vídeo de apresentação.

## Prints

Os prints do sistema estão no README do Notion (seção Evidências), que é o documento de referência do trabalho.

## Estrutura do repositório

- `index.html`: o painel completo (HTML, CSS e JavaScript em um arquivo só).
- `README.md`: este arquivo.
