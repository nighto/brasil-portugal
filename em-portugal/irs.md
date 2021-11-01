# IRS

Uma das obrigações anuais que temos, assim como no Brasil, é a Declaração do Imposto de Renda, aqui chamado de IRS - Imposto sobre o Rendimento de pessoas Singulares. Assim como no Brasil, tipicamente nos contratos com pessoa física - similar aos contratos de carteira assinada brasileiros - já é descontado o percentual do salário bruto referente ao IRS, de forma com a declaração anual feita é possível ter um valor de restituição do imposto de renda.

As alíquotas de imposto tem bem mais variações do que no Brasil (que são de 0, 15 e 27,5% dependendo da soma dos valores recebidos ao longo do ano). Variam igualmente com o valor do salário, mas tem graduações mais granulares, variando entre 0 a 41,8%, mas também há variações se a pessoa for casada (imposto menor), se somente um ou os dois casados trabalham (imposto maior), se tem filhos, se é jovem (dos 18 a 26 anos), se tem alguma deficiência, se mora no Continente ou nas regiões autônomas de Açores ou Madeira etc. Confira no site da Autoridade Tributária a [Tabela de Retenção de IRS](https://info.portaldasfinancas.gov.pt/pt/apoio\_contribuinte/tabela\_ret\_doclib/Pages/default.aspx), e sugiro este artigo explicativo: [Taxas de IRS 2020: consulte os escalões de IRS - Economias](https://www.economias.pt/taxas-de-irs/), assim como este [Simulador Salário Líquido 2020](https://www.doutorfinancas.pt/simulador-salario-liquido-2020/).

Ao contrário da Declaração do Imposto de Renda do Brasil, em que é preciso baixar um programa, instalar o Java etc., a declaração do IRS português é feita online, direto no [site das Finanças - IRS](https://irs.portaldasfinancas.gov.pt/home.action). É preciso ter um código de acesso para o portal, que é recebido por carta, conforme [detalhado na seção anterior sobre o NIF](https://github.com/nighto/brasil-portugal#nif). Os dados já vem pré-preenchidos, basta conferir, corrigir alguma eventual discrepância e entregar a declaração.

### Deduções

Nesta seção apresento algumas dicas para que você possa maximizar o seu valor de restituição de imposto de renda.

Diferente das deduções do imposto de renda do Brasil, que abrangiam basicamente despesas com saúde e educação, aqui há mais despesas que são dedutíveis, conforme a lista a seguir.

Aviso: não sou contador/contabilista, então se necessário confira as informações com um profissional da área.

> * 35% das despesas gerais familiares (por exemplo, despesas com água, luz, gás, telecomunicações, combustíveis, supermercado, vestuário), até ao máximo dedutível de 250 euros por sujeito passivo. Recorde-se que para as famílias monoparentais a percentagem sobe para 45%, com o limite de 335 euros;
> * 30% das despesas de educação (que inclui rendas de estudantes deslocados), até um máximo dedutível de 800 euros. É dedutível, a título de rendas, um valor máximo de 300 euros anuais, sendo o limite global das despesas de educação de 800 euros aumentado em 200 euros, quando a diferença seja relativa a rendas. Assim, os agregados familiares que atinjam o limite de 800 euros de dedução com despesas de educação podem ver este limite acrescido em 200 euros, quando a diferença corresponda a rendas, ficando assim o limite global de mil euros, no que diz respeito às despesas de educação e formação profissional.
> * 15% das despesas de saúde, até um máximo dedutível de mil euros;
> * 15% do IVA suportado em cada fatura relativa a despesas nos setores da restauração e hotelaria, cabeleireiros e reparações de automóveis e de motociclos, e despesas com veterinários, e 100% do IVA suportado com despesas em passes sociais, com um limite global de 250 euros por agregado familiar;
> * 15% das despesas com rendas, até um máximo dedutível de 502 euros; e 15% das despesas com juros de empréstimo à habitação, para contratos celebrados até 31/12/2011, até um máximo dedutível de 296 euros;
> * 25% das despesas com lares, até um máximo dedutível de 403,75 euros;
> * 20% das pensões de alimentos, sem limite.

via: [Deduções no IRS: novidades fiscais em 2020](https://www.cgd.pt/Site/Saldo-Positivo/leis-e-impostos/Pages/deducoes-no-irs.aspx)

Ou seja: sempre peça o contribuinte na nota para que essas despesas sejam lançadas atreladas ao seu NIF e você tenha o máximo de restituição possível.

A partir dessa tabela, é possível calcular o valor em gasto que seria necessário para atingir o **teto de restituição** em cada categoria. Dividindo em duas partes, as despesas que são por família:

* Rendas: 15%, até 502€ por família, portanto 502 / 0,15 = € 3.346,67 por ano, o que dá € 278,89 por mês (bem abaixo do valor típico de aluguel...);
* Educação: 30%, até 800€ por família, portanto 800 / 0,3 = € 2.666,67 por ano, o que dá € 222,22 por mês (pagando uma creche ou escola particular chega-se a esse valor);
* Saúde: 15%, até 1.000€ por família, portanto 1.000 / 0,15 = € 6.666,67 por ano, o que dá € 555,56 por mês (dificilmente se chegaria a esse valor uma vez que o teto é alto).

E as despesas que são por pessoa:

* Despesas gerais familiares: 35%, até 250€ por pessoa, portanto 250 / 0,35 = € 714,29 por ano;
* IVA: 15%, até 250€ por pessoa. Este é mais difícil de calcular pois o IVA (Imposto sobre o valor acrescentado) tipicamente varia entre 6 a 23% dependendo do produto comprado, supondo 23% para facilitar o cálculo (maior alíquota possível): 250 / 0,15 = € 1.666 **de IVA** / 0,23 = € 7.244 de compras em restaurantes e afins por ano, o que dá € 603,67 por mês.

É possível verificar no portal e-Fatura as [Deduções Provisórias em IRS](https://faturas.portaldasfinancas.gov.pt/painelAdquirente.action), o que recomendo que você faça **mesmo no primeiro ano com alguma frequência** (uma vez por mês no começo do mês, uma vez que só é possível registar faturas até o dia 12 do mês seguinte), afim de garantir que as suas despesas estejam entrando nas categorias corretas. É possível atribuir as faturas às categorias manualmente, se necessário. Caso você tenha se esquecido de incluir o NIF em uma fatura, ou se a loja não tiver comunicado a sua compra a Autoridade Financeira - _acontece!_ - é possível incluir manualmente a fatura.

Para incluir manualmente uma fatura, acesse o Portal no link acima, clique no botão **Registar Faturas** e inclua as informações de acordo com o exemplo:

![](https://user-images.githubusercontent.com/397851/95866620-0cefdd80-0d60-11eb-9211-3b9767f9cbfb.jpeg)

1. **NIF do Comerciante**;
2. **Tipo de Fatura**: escolha entre _Fatura_, _Fatura simplificada_ e _Fatura-recibo_, essa informação vem escrita na fatura; preencha também o **Número da Fatura**;
3. **Data de Emissão**;
4. **Código de Controlo**: são 4 caracteres que ficam junto da frase `Processado por programa certificado` e que ficam _em algum lugar_ na fatura (já encontrei no final, no meio, basta procurar por 4 letras ou números);
5. **Total de Itens por valor de IVA**: não é preciso adicionar todos os itens da fatura um por um, basta adicionar os totais por faixa de IVA cobrado. Se necessário, clique no botão _Adicionar Linha_ para criar mais linhas. No exemplo da fatura acima, será preciso duas linhas.

![](https://user-images.githubusercontent.com/397851/95867560-30ffee80-0d61-11eb-8ce2-27853aa55d75.png)

Após guardar a fatura, é preciso escolher a **Atividade de Realização da Aquisição**, uma vez que diferentes categorias de serviços tem cotas diferentes de reembolso. Neste exemplo, uma padaria, a atividade é _Alojamento, restauração e similares_ (restauração = restaurantes).

![](https://user-images.githubusercontent.com/397851/95867799-758b8a00-0d61-11eb-8fc5-fa92a91a477b.png)

**Dicas importantes:**

* caso você seja casado e/ou tenha filhos, divida as despesas informando o NIF de todos os membros da família, especialmente nas categorias de despesas gerais familiares (contas de serviços, supermercado) e restituição de IVA (restaurantes etc.), mesmo que somente você trabalhe / tenha rendimentos, uma vez que essas categorias tem limite de dedução **por pessoa**. Uma forma simples de fazer isto, para uma família de duas pessoas, seria informar o NIF de um na primeira metade e o NIF do outro na segunda metade do ano, e assim sucessivamente, e quanto as contas, colocar a conta de luz e gás no nome de uma pessoa e a de água e internet na outra, por exemplo. Você pode acessar a página de Deduções Provisórias em IRS mencionada anteriormente para verificar o quão perto do limite está e se precisa ou não se preocupar com isso.
* despesas de saúde podem ter restituição maior caso o remédio comprado tenha sido indicado por conta de uma receita médica. O portal dá a opção de associar uma receita a uma fatura de despesa de saúde.
* despesas com escolas de condução (para tirar carta de condução / carteira de motorista) **não** podem entrar na categoria "Educação", mas podem compor o valor de restituição na categoria "Despesas Gerais Familiares".
* atividades como ginásio (academia), natação etc. **não** podem entrar na categoria "Saúde", **a menos** que tenham sido indicadas por um médico.

Tendo passado o primeiro ano, e antes (ou mesmo depois) da declaração, é possível [Consultar Despesas para Deduções à Coleta](https://irs.portaldasfinancas.gov.pt/consultarDespesasDeducoes.action), ou seja, quanto valou acumulou de deduções em cada categoria.
