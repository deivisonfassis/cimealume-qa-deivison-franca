Cria 20 caso de teste baseados no requisitos enviado seguindo a estrutura abaixo:



ID,

RN,	

CA,

Técnica(Partição de equivalência, Tabela de Decisão, Valor limite, Exploratório, Caixa Branca, Revisão estática),

Tipo de teste(Funcional, Aceitação, Regressão, Confirmação, Smoke, Exploratório, Desempenho, Carga, Estresse, Volume, Segurança, Recuperação, acessibilidade, Usabilidade),

Nível(Unitario, Integração, Sistema, Aceitação),	

Título,

Pré-condições,

Passos,

Dados de entrada,

Resultado esperado,

Resultado obtido,

Status(Não preencher),

Bug(Não preencher),

relacionado(Não preencher),

Evidência(Não preencher).



Não preencher onde estiver "(Não preencher)".







Crie 10 relatório de bug usando os requisitos, index e os caso de teste usando essa estrutura:



ID,	

Título,	

RN violada,	

CA,	

Caso de teste,	

Tipo de teste(Funcional, Aceitação, Regressão, Confirmação, Smoke, Exploratório, Desempenho, Carga, Estresse, Volume, Segurança, Recuperação, acessibilidade, Usabilidade),	

Severidade(Critica, Alta, Media, Baixa),	

Prioridade(Alta, Media, Baixa),	

Passos para reproduzir,	

Dados usados,	

Resultado esperado,	

Resultado obtido(Não preencher),	

Evidência(Não preencher),	

Status do bug(Não preencher),	

Missão(Não preencher).



Não preencher onde estiver "(Não preencher)".





Crie 6 teste-não funcionais baseado usando a seguinte estrutura:



ID,	

Tipo de teste,	

RN,	

O que foi medido,	

Como testou (ferramenta e passos),	

Valor obtido,	

Critério de aceitação,	

Status,	

Bug, 

relacionado,	

Evidência.







Usando o arquivo regras.js crie 6 teste de caixa branca usando a seguite estrutura:



ID	

Função	

Condição ou trecho analisado	

Caminho coberto	Entrada usada	

Resultado esperado (pela RN)	

Resultado obtido	

Status	

RN	

Bug 

relacionado.







usando os arquivos testes.html e dados.js crie 7 teste automatizados usando a seguinte estrutura:



Função testada	

O que o teste verifica	

RN	

Chamada usada no testes.html	

Esperado	

Obtido	

Resultado no testes.html	

Bug relacionado.



siga essa instrução: 

Abra testes/testes.html pelo Live Server. A página mostra uma tabela com o resultado de cada teste.



Para criar um teste, acrescente uma linha testar(...) logo depois dos dois exemplos:



testar('AT01', 'Descrição do que está sendo testado', funcaoTestada(entradas), valorEsperado);

O primeiro argumento é o ID, que deve ser igual ao da aba 9\_Automacao.

sessao('far-2100') devolve uma sessão pelo código. Os códigos estão em js/dados.js.

Um teste que falha porque o sistema tem um bug é um bom teste: registre o bug.





