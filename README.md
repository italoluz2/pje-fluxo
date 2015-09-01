# pje-fluxo
Fluxos do PJe do TJRN

Informações gerais
------------------

Fluxos no formato XML não trazem os eventos de tarefa, nem os nomes das variáveis. Logo, ao inserir o fluxo pela primeira vez na aplicação, se faz necessária a criação de seus eventos de tarefas, quando houver a presença da EL <kbd>#{lancadorMovimentosService.setCondicaoLancamentoMovimentosTemporarioNoFluxo('#{true}')}</kbd> nos nós de tarefa, bem como as variáveis declaradas deverão ser alteradas para nomes amigáveis.
