# Banco-de-Dados
Destinado a publicação da Avaliação de BD do professor Serra


BANCO DE DADOS RELACIONAL:

Um banco de dados relacional é um tipo de banco de dados que armazena e fornece acesso a pontos de dados que estão relacionados entre si.  Bancos de dados relacionais são baseados no modelo relacional, uma maneira intuitiva e direta de representar dados em tabelas. Em um banco de dados relacional, cada linha na tabela é um registro com uma ID exclusiva chamada chave. As colunas da tabela contêm atributos dos dados e cada registro geralmente tem um valor para cada atributo, facilitando o estabelecimento das relações entre os pontos de dados.

RELACIONAMENTO: 

Os relacionamentos de banco de dados são associações entre tabelas que são criadas usando instruções de junção para recuperar dados.

EXEMPLO:

UM PRA UM: 

Ambas tabelas podem ter somente um registro de cada lado do relacionamento.

Cada valor da chave primária se relaciona a nenhum ou a apenas um registro na tabela relacionada.

A maioria dos relacionamentos de um para um são forçados por regras de negócios e não fluem naturalmente dos dados. Sem tal regra, geralmente você pode combinar as duas tabelas sem quebrar nenhuma regra de normalização.

UM PARA MUITOS:

A tabela de chave primária contém somente um registro relacionado a nenhum, a um ou a muitos registros da tabela relacionada.

MUITOS PRA MUITOS:

Cada registro em ambas as tabelas pode se relacionar a nenhum ou a qualquer número de registros na outra tabela. Esses relacionamentos requerem uma terceira tabela, chamada de tabela associada ou de associação, pois os sistemas relacionais não podem acomodar diretamente o relacionamento.

CHAVE CANDIDATA:

Ocorrem quando em uma relação existe mais de uma combinação de atributos possuindo a propriedade de identificação única. A chave candidata é apenas conceitual, ou seja, ela não é implementada. O que acontece é que os atributos com essa características poderiam ser primária já que possuem por natureza a identificação única.

CHAVE PRIMARIA COMPOSTA:

A chave primária composta é aquela que é criada em dois campos e desta forma passa a utilizar a junção dos dados dos dois campos indicados para formar um valor único e assim aplicar o bloqueio de duplicidade.


3- 
 
A)SELECT * FROM Avaliação.Curso;

B)SELECT Disciplina, Carga_H(h) FROM Avaliação.Disciplina ORDER BY Disciplina ASC;

C)SELECT Curso, Disciplina, Carga_H(h) FROM Avaliaçao.Curso, Avaliação.Disciplina ORDER BY Curso, Disciplina ASC;

D)SELECT * FROM Avaliaçao.Disciplina WHERE Disciplina.Curso_idCurso = 1;

E)SELECT Curso, Disciplina, Carga_H(h) FROM Avaliação.Curso, Avaliação.Disciplina WHERE Carga_H > 40;

F)SELECT Curso, Disciplina FROM Avaliação.Curso, Avaliação.Disciplina WHERE Disciplina LIKE %Dados%;
