# Como escolher uma licença para seus jogos livres

## O que são licenças?

Licenças de software são contratos entre seus produtores e os usuários finais.
Softwares proprietários em geral utilizam licenças que restringem certas
liberdades, como a modificação do software em questão, bem como sua
redistribuição. Mesmo programas *freeware*, isto é, de uso gratuito, podem não
permitir sua redistribuição. Essas licenças podem afetar duas dimensões do
software: o direito de uso e cópia (direito autoral) e a patente.

O direito autoral é um dispositivo legal que permite que o autor de uma obra a
aproveite, tanto do ponto de vista de moral (o autor de uma obra deve ser
sempre reconhecido como tal), quanto do ponto de vista patrimonial. Esse último
confere à obra – seja ela uma obra musical, uma livro ou uma ilustração –
status de propriedade. Os direitos atrelados a uma propriedade, que são
direitos de uso, exploração econômica, modificação, venda, empréstimo etc.
Esses últimos são transferíveis em diversos níveis. Por exemplo, no caso de uma
licença de software proprietário, seu autor confere ao usuário o direito de
uso, mas não o direito da exploração econômica ou compartilhamento. No Brasil,
o direito autoral de uma obra é válido por 70 anos após a morte do autor.

As patentes são um caso bastante diferente. Criações artísticas não podem ser
patenteadas, apenas invenções. As patentes são conferidas em troca da
especificação pública daquele invenção, isto é, desenhos técnicos, explicações
de seu funcionamento e outros documentos necessários para garantir que a
invenção seja reproduzível. Em contrapartida, o governo concede ao seu inventor
a exclusividade da exploração. No Brasil, as patentes expiram após 20 anos a
partir da data do depósito. Além disso, não é possível patentear software no
país.

O autor de um software pode desejar conferir ao seu usuário mais direitos do
que o direito autoral tradicional. Pode querer, por exemplo, que seus usuários
possam modificar ou distribuir o programa e seu código fonte. É assim que
nasceu o *copyleft* (uma brincadeira com *copyright*, "direito autoral").  O
software livre usa esse hack inteligente do direito autoral para conferir aos
seus usuários basicamente quatro liberdades:

> 0. A liberdade de executar o programa como você desejar, para qualquer
>    propósito (liberdade 0).
> 1. A liberdade de estudar como o programa funciona, e adaptá-lo às suas
>    necessidades (liberdade 1). Para tanto, acesso ao código-fonte é um
>    pré-requisito.
> 2. A liberdade de redistribuir cópias de modo que você possa ajudar ao
>    próximo (liberdade 2).
> 3. A liberdade de distribuir cópias de suas versões modificadas a outros
>    (liberdade 3). Desta forma, você pode dar a toda comunidade a chance de
>    beneficiar de suas mudanças. Para tanto, acesso ao código-fonte é um
>    pré-requisito.

Existem vários graus de direitos e deveres que podem ser conferidos ao usuário.
Por isso, existem diversas licenças de software, algumas das quais são livres
(isto é, dão as liberdades acima). O Projeto GNU mantém [uma lista atualizada
de licenças e suas diferenças][licenças-livres].

Para conhecer mais sobre a história do software livre, recomendamos a leitura
[desse artigo no gnu.org: O que é Software Livre?][software-livre].

[licenças-livres]: https://www.gnu.org/licenses/license-list.html
[sotware-livre]: https://www.gnu.org/philosophy/free-sw.pt-br.html

## Como escolher uma licença?

A escolha de uma licença é uma decisão bastante pessoal. A **MIT** e a **BSD**
são algumas das licenças mais simples, porém também mais permissivas. Grosso
modo, isso significa que software licenciado por meio delas não precisa,
necessariamente, ser redistribuído como software livre. Ele pode se tornar
software proprietário.

A licença **GPL**, atualmente na versão 3, não permite que o software se torne
proprietário. Todas as mudanças feitas em software licenciado pela GPL devem se
distribuídas usando a mesma licença. Por isso, dizemos que a GPL é restritiva.

O site [choosealicense.com][choose-a-licence] é uma parada rápida para ajudar
nessa decisão. Eles também têm uma [tabela de licenças e suas
diferenças][tabela-licenças] bem enxuta e fácil de ler.

Finalmente, as licenças Creative Commons não são recomendadas para software,
porque não dispõe de assuntos como o uso, modificação e redistribuição, que são
específicas para o software livre. Para mais informações, veja [o FAQ da
própria CC][faq-cc].

[choose-a-license]:https://choosealicense.com/
[tabela-licenças]: https://choosealicense.com/licenses/
[faq-cc]: https://creativecommons.org/faq/#can-i-apply-a-creative-commons-license-to-software

Após escolher uma licença para seu programa, basta colocá-la num arquivo
chamado `LICENSE` na raiz do repositório. Também é necessário incluir esse
arquivo nas distribuições do software.

## E o conteúdo artístico?

Jogos são um misto de software e conteúdo artístico, como música, sprites,
vídeos, dublagens, ilustrações e modelos 3D. Esse tipo de conteúdo,
naturalmente, não é coberto pelos mesmos tipos de licença que server para
software. Para esse fim, recomendamos o uso das licenças da [Creative
Commons][cc], que vem em uma série de sabores com diferentes graus de
permissões e restrições.

[cc]: https://creativecommons.org/licenses/?lang=pt_BR
