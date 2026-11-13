# **Prompt final usado**

```txt

# Prompt
Olá copilot. Você pode me ajudar a revisar esse PRD - Product Requirements Document - que cirei? Pretendo usá-lo no lovable para exercitar minhas skills de Vibe Coding.
Me envie como resposta o PRD revisado, por favor. 

# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário em linguagem natural.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.
Quero que em caso de dívidas, a pessoa não se sinta punida, e sim tenha intruções práticas de como resolver a situação.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes, que possuem apenas o salário como forma de remuneração.

# Funcionalidades-Chave
1. Registrar o salário recebido.
2. Registrar gastos via chat em linguagem natural.
3. Registrar a forma de compra e a instituição financeira usada, via chat, em linguagem natural.
4. Ter visões dos gastos em cada instituição financeira.
5. Classificar automaticamente as transações.  
6. Definir e acompanhar metas financeiras.  
7. Receber dicas de economia do “Agente Financeiro”.  
8. Visualizar relatórios simples e personalizados.
9. Receber um plano de ação simples e recomendações em caso de dívida.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
Deve ter um Design Universal, para que possa ser usado com boa experiência com o maior número de usuários possíveis.

# Entrega > pedido final para o Copilot
Enviar o PRD como um snippet txt, para cópia. Usar apenas markdown simples, para formatação, sem emojis. 
```

## **Resultados gerados pelo Copilot**

```
# PRD – Organizador Financeiro Conversacional

## Visão do Produto

Criar um aplicativo de organização financeira pessoal baseado em conversas em linguagem natural, permitindo que usuários registrem receitas, despesas e objetivos financeiros de forma simples, sem depender de planilhas ou formulários complexos.

O sistema atuará como um "Agente Financeiro Virtual", ajudando o usuário a compreender seus hábitos financeiros, economizar dinheiro e criar planos de ação realistas para atingir seus objetivos ou resolver situações de endividamento.

---

# Problema

Grande parte das pessoas abandona aplicativos de controle financeiro porque:

- Exigem cadastro manual excessivo.
- Possuem interfaces complexas.
- Demandam categorização manual das despesas.
- Não fornecem orientações financeiras personalizadas.
- Tratam situações de dívida apenas com alertas negativos, sem orientação prática.

Como consequência, muitos usuários deixam de acompanhar sua vida financeira e tomam decisões sem visibilidade sobre sua situação econômica.

---

# Objetivo do Produto

Permitir que qualquer pessoa consiga organizar sua vida financeira apenas conversando com o aplicativo.

O produto deve:

- Reduzir o esforço de registro financeiro.
- Transformar linguagem natural em dados estruturados.
- Gerar insights acionáveis.
- Incentivar hábitos financeiros saudáveis.
- Auxiliar usuários endividados sem julgamentos.
- Tornar educação financeira simples e acessível.

---

# Público-Alvo

## Público Primário

Pessoas que:

- Possuem renda proveniente principalmente de salário.
- Estão começando a organizar suas finanças.
- Não utilizam planilhas financeiras regularmente.
- Sentem dificuldade em manter disciplina financeira.
- Desejam controlar gastos sem dedicar muito tempo ao processo.

## Perfil do Usuário

### Maria, 29 anos

- Recebe salário mensal.
- Possui cartão de crédito.
- Utiliza PIX frequentemente.
- Não sabe exatamente quanto gasta por categoria.

### Carlos, 35 anos

- Está endividado.
- Tem dificuldade para acompanhar parcelas e vencimentos.
- Procura orientação simples para sair das dívidas.

---

# Proposta de Valor

"Converse com seu assistente financeiro como se estivesse falando com uma pessoa e receba organização, análises e orientações automaticamente."

---

# Funcionalidades do MVP

## 1. Cadastro Inicial

Coletar:

- Nome
- Salário líquido mensal
- Dia de pagamento
- Meta financeira principal

Exemplo:

Recebo R$ 4.000 por mês e quero juntar R$ 5.000 para uma viagem.

---

## 2. Registro de Receitas

O usuário poderá informar receitas em linguagem natural.

Exemplos:

- Recebi meu salário de R$ 4.000.
- Ganhei R$ 300 fazendo um trabalho freelancer.

O sistema deverá identificar:

- Valor
- Tipo de receita
- Data

---

## 3. Registro de Despesas via Chat

Exemplos:

- Gastei R$ 45 no almoço.
- Paguei R$ 120 de internet.
- Comprei roupas por R$ 250.

O sistema deverá extrair:

- Valor
- Categoria
- Data
- Descrição

---

## 4. Registro da Forma de Pagamento

Exemplos:

- Gastei R$ 80 no mercado usando Nubank crédito.
- Paguei R$ 35 no PIX pelo Itaú.
- Comprei um lanche de R$ 20 no débito do Inter.

O sistema deverá identificar:

- Instituição financeira
- Meio de pagamento
- Valor
- Categoria

---

## 5. Classificação Inteligente

Classificar automaticamente despesas em categorias como:

- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Assinaturas
- Outros

O usuário poderá corrigir classificações incorretas.

O sistema deverá aprender com as correções futuras.

---

## 6. Visão Consolidada por Instituição Financeira

Exibir:

- Total gasto por banco.
- Total gasto por cartão.
- Total gasto via PIX.
- Distribuição percentual dos gastos.

Exemplo:

Instituição | Valor
Nubank | R$ 1.200
Itaú | R$ 850
Inter | R$ 420

---

## 7. Metas Financeiras

Permitir criar metas como:

- Reserva de emergência.
- Viagem.
- Compra de veículo.
- Entrada de imóvel.
- Quitação de dívidas.

Exibir:

- Valor atual.
- Valor-alvo.
- Percentual de progresso.
- Previsão de conclusão.

---

## 8. Agente Financeiro

Assistente virtual que acompanha a evolução financeira.

Exemplos de mensagens:

- Você gastou 18% menos com alimentação neste mês.
- Seu gasto com delivery aumentou 25% nas últimas duas semanas.
- Mantendo esse ritmo, você atingirá sua meta em 7 meses.

O tom deve ser:

- Educativo.
- Positivo.
- Motivador.
- Sem julgamentos.

---

## 9. Modo Recuperação Financeira

Quando o usuário informar dívidas, o aplicativo deverá ativar um fluxo de apoio financeiro.

Exemplo:

Tenho R$ 5.000 de dívida no cartão.

O sistema deve:

- Calcular impacto da dívida na renda.
- Identificar urgência financeira.
- Propor plano de pagamento.
- Sugerir redução de gastos não essenciais.
- Acompanhar evolução semanal.

Importante:

O aplicativo não deve culpar ou constranger o usuário.

Deve comunicar-se de forma acolhedora e prática.

---

## 10. Relatórios Simples

Visualizações com:

- Gastos por categoria.
- Gastos por instituição financeira.
- Evolução mensal.
- Comparação entre meses.
- Progresso das metas.

---

# Principais Telas do MVP

## Tela 1: Onboarding

Objetivo:

- Entender perfil financeiro inicial.

Campos:

- Nome
- Salário
- Objetivo financeiro principal

---

## Tela 2: Chat Financeiro

Principal ponto de interação.

Funções:

- Registrar receitas.
- Registrar despesas.
- Fazer perguntas.

Exemplos:

- Quanto gastei com alimentação este mês?
- Quanto falta para minha meta?

---

## Tela 3: Dashboard

Exibir:

- Saldo atual.
- Gastos do mês.
- Economia acumulada.
- Progresso das metas.

---

## Tela 4: Instituições Financeiras

Exibir:

- Bancos utilizados.
- Cartões utilizados.
- Gastos por instituição.

---

## Tela 5: Metas

Exibir:

- Lista de metas.
- Evolução.
- Previsão de conclusão.

---

## Tela 6: Plano de Recuperação Financeira

Exibir:

- Total de dívidas.
- Parcelas futuras.
- Prioridades de pagamento.
- Recomendações semanais.

---

# Requisitos Não Funcionais

## Usabilidade

- Interface simples.
- Linguagem acessível.
- Pouca necessidade de treinamento.

## Acessibilidade

Seguir princípios de Design Universal:

- Contraste adequado.
- Compatibilidade com leitores de tela.
- Navegação via teclado.
- Ícones acompanhados por texto.
- Não depender exclusivamente de cores para transmitir informações.

## Performance

- Registrar transações em menos de 2 segundos.
- Responder perguntas em até 3 segundos.

## Segurança

- Dados criptografados em trânsito e em repouso.
- Autenticação segura.
- Conformidade com LGPD.

---

# Fluxos Conversacionais Esperados

## Registro de Gasto

Usuário:

Gastei R$ 120 no mercado com o cartão Nubank.

Sistema:

Registrei uma despesa de R$ 120 na categoria Alimentação usando Nubank Crédito. Deseja adicionar alguma observação?

---

## Consulta Financeira

Usuário:

Quanto gastei esse mês?

Sistema:

Você registrou R$ 2.450 em despesas neste mês. Alimentação representa 32% do total.

---

## Situação de Dívida

Usuário:

Estou devendo R$ 3.000 no cartão.

Sistema:

Entendi. Vamos montar um plano para reduzir essa dívida sem comprometer despesas essenciais. Posso começar analisando sua renda mensal?

---

# Critérios de Sucesso do MVP

Após os primeiros testes, medir:

- Percentual de usuários que registram pelo menos uma transação.
- Percentual de usuários que retornam após 7 dias.
- Quantidade média de registros por usuário.
- Taxa de criação de metas financeiras.
- Taxa de conclusão de metas.
- Satisfação do usuário com as recomendações geradas.

Metas iniciais:

- 70% dos novos usuários registrarem uma transação no primeiro dia.
- 40% retornarem após 7 dias.
- Pelo menos 1 meta financeira criada por usuário ativo.

---

# Entregável Esperado da IA

Gerar:

1. Arquitetura do MVP.
2. Modelagem básica de dados.
3. Principais telas e componentes.
4. Fluxos conversacionais.
5. Estratégia de classificação automática das transações.
6. Regras do Agente Financeiro.
7. Plano de validação com usuários.
8. Sugestões de stack tecnológica.
9. Roadmap de evolução pós-MVP.

Utilizar linguagem clara, educativa e acessível, sempre alinhada aos princípios de Design Universal.

---

# Diferencial Estratégico

## Finanças Compassivas

O produto deve adotar o conceito de "Finanças Compassivas".

Em vez de apontar erros ou apenas alertar sobre problemas financeiros, o Agente Financeiro deve ajudar o usuário a entender seu contexto, identificar oportunidades de melhoria e criar planos realistas de evolução financeira.

Princípios:

- Não julgar o usuário.
- Não utilizar linguagem punitiva.
- Valorizar pequenas conquistas.
- Priorizar orientação prática.
- Incentivar consistência em vez de perfeição.

Essa abordagem deve estar presente em todas as interações, tornando o aplicativo mais humano, acolhedor e motivador.
```




