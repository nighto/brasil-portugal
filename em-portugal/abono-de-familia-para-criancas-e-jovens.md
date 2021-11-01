# Abono de Família para Crianças e Jovens

O [Abono de Família para Crianças e Jovens](http://www.seg-social.pt/abono-de-familia-para-criancas-e-jovens) é um valor pago pela Segurança Social para pais de crianças e jovens até 24 anos. O valor pago depende do escalão de rendimentos, calculados a partir do valor declarado no imposto de renda no ano anterior e no número de filhos.

Tipicamente os salários de TI não se encaixam no valor para pagamento para pais com um único filho, mas ao menos no primeiro ano é possível pedir o auxílio, uma vez que comprova-se renda apresentando a declaração do Imposto de Renda do ano anterior (seja o IRPF no Brasil com o valor convertido a euro para o primeiro ano, seja o IRS nos próximos anos).

O valor que se tem direito é um pouco confuso de entender, mas destrinchei a burocracia para você. Copiando os trechos mais relevantes (o destaque é meu):

> **Condições de atribuição**\
> Têm direito ao abono de família as crianças e jovens:\
> Residentes em Portugal ou equiparados a residentes\
> (...) Tenha um rendimento de referência igual ou inferior ao valor estabelecido para o **3.º escalão de rendimentos ou igual ou inferior ao 4.º escalão de rendimentos no caso de crianças com idade igual ou inferior a 72 meses ou sejam considerados pessoas isoladas**.
>
> O rendimento de referência é calculado pela **soma do total de rendimentos** de cada elemento do agregado familiar **a dividir pelo número de crianças** e jovens com direito ao abono de família, nesse agregado, **acrescido de um**.\
> (...)\
> Na determinação do total dos rendimentos do agregado familiar são considerados os seguintes rendimentos:\
> Rendimentos de trabalho dependente\
> Rendimentos anuais **ilíquidos** provenientes de trabalho dependente

A tabela de escalões é:

![](https://user-images.githubusercontent.com/397851/100439536-943caa80-309b-11eb-9594-53624879f792.png)

Supondo uma família aonde um adulto ganhe 2.000€ bruto por mês, em 14 salários por ano, o outro adulto não trabalhe, e tenha um filho. Neste caso, a conta é: `(2.000 + 0) * 14 / (1 + 1) = 14.000`. Neste caso, o rendimento corresponde ao 4º escalão, que só dá direito ao auxílio caso o filho tenha 4 anos ou menos.

Fazendo a conta invertida - do limite do escalão para o salário bruto mensal, para um filho, o limite do 4º escalão é `15.358,35 * (1 + 1) / 14 = 2.194,05€` (para filho com 4 anos ou menos) e o do 3º escalão é `9.215,01 * (1 + 1) / 14 = 1.316,43€` (um filho com mais de 4 anos); ou ainda, considerando dois filhos: `15.358,35 * (2 + 1) / 14 = 3.291,07€` (dois filhos sendo pelo menos um com 4 anos ou menos), ou `9.215,01 * (2 + 1) / 14 = 1.974,64€` (dois filhos com mais de 4 anos).

Os valores pagos estão descritos na tabela a seguir:

![](https://user-images.githubusercontent.com/397851/100441435-c0115d80-30a6-11eb-8dcf-724331a2a36b.png)

Os valores são majorados caso sejam pelo menos 2 filhos com 36 meses ou menos, e em casos de monoparentalidade (caso um dos responsáveis tenha ficado no Brasil, por exemplo).

Para solicitar, é preciso primeiro [ter o NISS e ter acesso à Segurança Social Direta](https://github.com/nighto/brasil-portugal#niss), ou solicitar diretamente nos postos de atendimento da Segurança Social, através do [formulário RP5045-DGSS](http://www.seg-social.pt/formularios?kw=RP5045-DGSS). Para tal, é preciso agendar atendimento através do telefone 300 502 502.

Também há um [abono de família pré-natal](http://www.seg-social.pt/abono-de-familia-pre-natal2), destinado a pessoas grávidas, ou cuja criança tenha até 6 meses de idade.
