⚡**Projeto segmentação rfm**

## O que é o projeto?

Este projeto marca o inicio do bootcamp da Laboratória, onde mergulhamos em análise de dados. Durante o curso, desenvolvemos sete projetos que aplicam os conhecimentos adquiridos.

## **Contexto**

A loja especializada em produtos alimentícios importados, El Mercado, está enfrentando desafios para se adaptar às preferências em constante mudança dos clientes. A loja carece de uma estratégia eficaz para segmentar sua base de clientes.

## **Objetivo**
O objetivo é preparar a base de dados disponibilizada pela empresa e aplicar a segmentação de clientes por meio do método RFM. A compreensão dos resultados da segmentação é essencial para identificar em quais grupos a empresa pode concentrar esforços e/ou traçar estratégias de fidelização. Além disso, busca-se tirar conclusões que permitam à empresa tomar decisões informadas, enquanto se procura por informações importantes ocultas nos dados, como: quem são esses clientes, estado civil, se têm filhos, idade e qual é o volume de vendas da empresa em termos de quantidade.

<details>
  <summary style="font-size: larger;"><strong>Obtenção dos dados</strong></summary>
  
  Para esse projeto foi disponibilizado pela Laboratória 3 tabelas.
  
  Tabela de clientes

  id_cliente: Identificador do cliente. Um número inteiro de 1 a 5 dígitos atribuídos exclusivamente a cada cliente.
  
  ano_nascimento: Ano de nascimento do cliente.
  
  nivel_educacao: Nível de escolaridade do cliente.
  
  estado_civil: Estado civil do cliente.
  
  salarioanualdolar: Renda anual da família do cliente em dólares.
  
  criancasatedez_anos: Número de crianças pequenas até 10 anos na casa do cliente.
  
  criancasmaisdez_anos: Número de crianças com mais de 10 anos na casa do cliente.
  
  data_entrada: Data de cadastro do cliente na empresa.
  
  resposta_campanha: Identifica se o cliente aceitou a campanha de marketing enviada. Onde 1 é sim e 0 é não.
  
  Tabela de transações

  id_transacao: Identificador da transação. Um número inteiro de 9 dígitos atribuído exclusivamente a cada transação.
  
  id_cliente: Identificador do cliente. Um número inteiro de 1 a 5 dígitos atribuídos exclusivamente a cada cliente.
  
  data_transacao: Data de compra no formato ano-mês-dia.
  
  lugar_transacao: O local onde a compra foi feita, pode ser online ou na loja.
  
  Tabela resumo_compras

  id_cliente: Identificador do cliente. Um número inteiro de 1 a 5 dígitos atribuídos exclusivamente a cada cliente.
  
  total_vinho: Valor monetário gasto em produtos do tipo vinho.
  
  total_frutas: Valor monetário gasto em produtos do tipo fruta.
  
  total_carnes: Valor monetário gasto em produtos do tipo carne animal.
  
  total_peixes: Valor monetário gasto em produtos do tipo pescado.
  
  total_doces: Valor monetário gasto em produtos do tipo doce.
  
  total_outros: Valor monetário gasto em outros produtos em geral.
</details>

## **Conclusções**

**Clientes Hibernando e quase dormindo:**

Ofertas Personalizadas: Enviar descontos exclusivos ou créditos na próxima compra para incentivar o retorno dos clientes que estão inativos há algum tempo.

Promoções Especiais: Criar promoções atraentes, como "Compre um, leve dois" ou "Descontos de 50% na primeira unidade", para despertar o interesse desses clientes em retornar ao mercado.

**Cliente Necessitando de Atenção, potencial perda e não perder:**

Serviços Adicionais: Ofereçer serviços extras, como entrega gratuita em suas próximas compras, para mostrar que o mercado valoriza a sua fidelidade.

Experiências Exclusivas: Criar experiências personalizadas, como acesso prioritário a novos produtos ou convites para eventos especiais, para demonstrar cuidado e atenção a esses clientes.

**Clientes Fiéis, Campeões e Potenciais Leais:**

Benefícios Exclusivos: Ofereçer benefícios exclusivos, como descontos progressivos com base no histórico de compras ou acesso antecipado a vendas especiais, como forma de reconhecimento pela fidelidade.

Surpresas e Mimos: Surpreender esses clientes com brindes especiais, amostras de produtos ou cupons de desconto exclusivos, para demonstrar valorização pela sua lealdade.

Feedback Valorizado: Solicitar feedback regularmente e demonstrar que suas opiniões são valorizadas, implementando melhorias com base nesses feedbacks.

Ao adotar uma abordagem personalizada e centrada no cliente, a empresa estará mais bem equipado para reter clientes em diferentes estágios de engajamento e fortalecer relacionamentos duradouros.

**Cliente promissor e novos clientes:**

Simplificarr o processo de compra, oferecendo opções de pagamento flexíveis, entrega rápida e conveniente, e um ambiente de compras acolhedor e amigável.
Podemos também oferecer amostras grátis de produtos populares do mercado para esses clientes experimentarem e se familiarizarem com a qualidade e variedade dos produtos oferecidos.

## 🛠 Tecnologias e ferramentas

- Google sheets
- Looker Studio: para visualização de dados.

  ## Dashboard no Looker Studio
  [Clique Aqui](https://lookerstudio.google.com/u/1/reporting/37621377-12cb-4b53-8a81-f0c9cb5d1a2b/page/zyxuD/edit)
  
  ![](https://github.com/Mayara-alvess/segmentacao_rfm/blob/main/01projeto/Dashboard.png)
  ![](https://github.com/Mayara-alvess/segmentacao_rfm/blob/main/01projeto/Dashboard1.png)

  ## Diretório

- Na pasta  01projeto, você encontrará o arquivo csv e a ficha tecnica mais detalhada.
