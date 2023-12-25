# Criador de currículo
## Introdução
O criador de currículo é um site que permite o usário criar um **elegante** e **profissional** currículo com **facilidade** e **velocidade**.
## Especificação
Um currículo é organizado hierárquicamente entre:

***áreas > elementos > itens > tipos***

- **tipo:** Um texto que recebe diferentes tamanhos e cores dependendo de sua **categoria**.
- **item:** Um conteiner que guarda diversos tipos.
- **elemento:** Um conteiner que recebe um título de destaque e guarda diversos itens.
- **área:** Um conteiner que guarda vários elementos.

Um currículo é divido em **três áreas** sendo essas: 
- **Área principal:** Ocupa cerca de 70% da largura da tela e permite a criação de diversos elementos dentro.
- **Barra vertical:** Ocupa cerca de 30% da largura da tela e também permite a criação de diversos elementos dentro.
- **Cabeçalho:** É uma área especial que não segue os padrões das outras, ocupa 100% da largura de tela e é encontrada no topo do currículo, além de permitir apenas um elemento, todos os seus tipos são 1.5x maiores.

Em resumo, dentro de uma **área** (com exeção do **cabeçalho**) existem diversos **elementos** dentro desses elementos existem diversos **itens**, dentro desses itens existem diversos **tipos**.

Cada **tipo** tem determinadas caracteríscas que os difere de outros tipos, sendo esses:
- **Obrigatório:** esse tipo precisa obrigatóriamente existir dentro de um item.
- **Opcional:** este tipo pode ou não existir dentro de um item.
- **Único:** esse tipo só pode ser usado uma vez em um item
- **Simples:** é permitido haver mais de um do mesmo tipo em cada item.
- **Lista:** permite agrupar vários tipos iguais em formato de lista.

Tipos também são separados em duas **clasificações**:
- **Normais:** Existem apenas dentro de um item.
- **Especiais:** São únicos e podem existir fora de um item.

Como dito no começo, todo **tipo** se difere com base na sua **categoria**, sendo essas as categorias:
- **Título**
Classificação: Especial
Características: Único, Obrigatório em elementos, Opcional em itens
O título é o único tipo especial, além de ser possível colocar um título em um item, também é possível colocar um título em um elemento, com seu estilo mudando dependendo do conteiner colocado.
Seu objetivo é titular um conteiner e seu tamanho sempre deve ser maior que todos os tipos/itens dentro do conteiner.

- **Subtítulo**
Classificação: Normal
Características: Opcional, Simples
O subtítulo é um tipo normal que é geralmente utilizado para adicionar um contexto maior em um parágrafo ou frase.
A sua fonte é acizentada e fina com a intenção de chamar o mínimo de atenção possível, assim permitindo adicionar mais contexto sem poluir o currículo.
É recomendado que seja utilizado em datas ou locais.

- **Parágrafo**
Classificação: Normal
Características: Opcional, Simples, Lista
O parágrafo é utilizado quando apenas uma frase não é o suficiente para descrever um determinado assunto.
Parágrafos muito longos não são recomendados pois podem poluir seu currículo, tente ser objetivo ao usá-los.
Por conterem muito texto, sua fonte é fina quando comparada aos outros tipos, assim um parágrafo também pode ser utilizado como uma frase que chama menos atenção.


- **Frase**
Classificação: Normal
Características: Opcional, Simples, Lista
O tipo de texto mais básico, sua fonte é maior e mais grossa que a maoria dos tipos (com execeção do título), logo chama muito mais atenção, é bem versátil e ótima para criar listas ou até mesmo "pseudotítulos" dentro de um item.
É recomendado que uma frase não passe de cinco palavras para não poluir o currículo com informação.

