# O hospital fundamental
Um pequeno hospital local busca desenvolver um novo sistema que atenda melhor às suas necessidades. Atualmente, parte da operação ainda se apoia em planilhas e arquivos antigos, mas espera-se que esses dados sejam transferidos para o novo sistema assim que ele estiver funcional. Neste momento, é necessário analisar com cuidado as necessidades desse cliente e sugerir uma estrutura de banco de dados adequada por meio de um Diagrama Entidade-Relacionamento.

## :question:Questões:question:
O hospital necessita de um sistema para sua área clínica que ajude a controlar consultas realizadas. Os médicos podem ser generalistas, especialistas ou residentes e têm seus dados pessoais cadastrados em planilhas digitais. Cada médico pode ter uma ou mais especialidades, que podem ser pediatria, clínica geral, gastroenterologia e dermatologia. Alguns registros antigos ainda estão em formulário de papel, mas será necessário incluir esses dados no novo sistema.

Os pacientes também precisam de cadastro, contendo dados pessoais (nome, data de nascimento, endereço, telefone e e-mail), documentos (CPF e RG) e convênio. Para cada convênio, são registrados nome, CNPJ e tempo de carência.

As consultas também têm sido registradas em planilhas, com data e hora de realização, médico responsável, paciente, valor da consulta ou nome do convênio, com o número da carteira. Também é necessário indicar na consulta qual a especialidade buscada pelo paciente.

Deseja-se ainda informatizar a receita do médico, de maneira que, no encerramento da consulta, ele possa registrar os medicamentos receitados, a quantidade e as instruções de uso. A partir disso, espera-se que o sistema imprima um relatório da receita ao paciente ou permita sua visualização via internet.

## Resposta :heavy_check_mark:


![Hospital drawio(1)](https://user-images.githubusercontent.com/110436354/197145834-90ef03ae-bcb9-4f42-9e59-ab58df68208e.png)

# Parte 2

No hospital, as internações têm sido registradas por meio de formulários eletrônicos que gravam os dados em arquivos. 

Para cada internação, são anotadas a data de entrada, a data prevista de alta e a data efetiva de alta, além da descrição textual dos procedimentos a serem realizados. 

As internações precisam ser vinculadas a quartos, com a numeração e o tipo. 

Cada tipo de quarto tem sua descrição e o seu valor diário (a princípio, o hospital trabalha com apartamentos, quartos duplos e enfermaria).

Também é necessário controlar quais profissionais de enfermaria estarão responsáveis por acompanhar o paciente durante sua internação. Para cada enfermeiro(a), é necessário nome, CPF e registro no conselho de enfermagem (CRE).
A internação, obviamente, é vinculada a um paciente – que pode se internar mais de uma vez no hospital – e a um único médico responsável.

## Resposta :heavy_check_mark:

![image](https://user-images.githubusercontent.com/110436354/206246354-95bfa58b-ae63-4ead-aa23-63911f7e5181.png)

# Parte 3

Abastecer o banco com informações fictícias.

# Cargo

![image](https://user-images.githubusercontent.com/110436354/208550486-9c2c3e6f-022a-4bec-920c-2fd09113a127.png)

# Consultas

![image](https://user-images.githubusercontent.com/110436354/208550672-f1906fb6-0dc8-45ab-91a1-64d9d0af2613.png)

# Convenio

![image](https://user-images.githubusercontent.com/110436354/208550805-856e6226-a27d-47b4-ab1f-70eae5482bf5.png)

# Endereço
![image](https://user-images.githubusercontent.com/110436354/208734456-3f4bb1ba-f399-4279-9c61-77f0572a6bed.png)

# Enfermeiro
![image](https://user-images.githubusercontent.com/110436354/208734620-7261b11b-8ae0-45b0-9327-3d19477738fc.png)

# Especialidade
![image](https://user-images.githubusercontent.com/110436354/208734820-c8953b80-9827-4b99-8941-8b62f9c759f7.png)

# Internação
![image](https://user-images.githubusercontent.com/110436354/208734977-25df73e0-abd0-4ddf-9018-925a42adf94f.png)

# Médico
![image](https://user-images.githubusercontent.com/110436354/208739446-16834f1b-0bd9-4feb-88b5-fcae457fa7b8.png)

# Paciente
![image](https://user-images.githubusercontent.com/110436354/208739605-cfbcd851-3e69-4447-acb2-f594b36b3d28.png)

# Quarto
![image](https://user-images.githubusercontent.com/110436354/208739945-d86744a5-5764-432e-ace7-75d3efce97aa.png)

# Receita
![image](https://user-images.githubusercontent.com/110436354/208741335-44499e77-831c-4a57-85b3-74244a077ffe.png)

# Tipo de Quarto
![image](https://user-images.githubusercontent.com/110436354/208744760-2269a877-7bd8-4037-98dd-3e22b6874ee4.png)

# Parte 4

Pensando no banco que já foi criado para o Projeto do Hospital, realize algumas alterações nas tabelas e nos dados usando comandos de atualização e exclusão:
Crie um script que adicione uma coluna “em_atividade” para os médicos, indicando se ele ainda está atuando no hospital ou não. 
Crie um script para atualizar ao menos dois médicos como inativos e os demais em atividade.

## Resposta :heavy_check_mark:
![image](https://user-images.githubusercontent.com/110436354/208757189-e967b157-798b-4c99-9f98-65cb71481687.png)

# Parte 5 

Pergunta 1: Todos os dados e o valor médio das consultas do ano de 2020 e das que foram feitas sob convênio.

![image](https://user-images.githubusercontent.com/110436354/209412733-7c5e211b-3b18-4aed-852b-244e8afa7b8d.png)

Pergunta 2: Todos os dados das internações que tiveram data de alta maior que a data prevista para a alta.

![image](https://user-images.githubusercontent.com/110436354/209856844-2d1be903-c353-4f81-93e4-fb4859e05073.png)

Pergunta 3: Receituário completo da primeira consulta registrada com receituário associado.

![image](https://user-images.githubusercontent.com/110436354/209864560-5e4bd08a-4f08-4fb4-879e-3ccfd45af2fa.png)

Pergunta 4: Todos os dados da consulta de maior valor e também da de menor valor (ambas as consultas não foram realizadas sob convênio).

![image](https://user-images.githubusercontent.com/110436354/209866277-fd9c62f4-a18b-43d1-8abe-3446a6b459e6.png)

Pergunta 5: Todos os dados das internações em seus respectivos quartos, calculando o total da internação a partir do valor de diária do quarto e o número de dias entre a entrada e a alta.

![image](https://user-images.githubusercontent.com/110436354/210011402-e34dee20-1b01-408a-b8d1-1fd7395b4422.png)

Pergunta 6: Data, procedimento e número de quarto de internações em quartos do tipo “apartamento”.

![image](https://user-images.githubusercontent.com/110436354/210012798-d141a17a-890d-483f-818a-74c886aed1ff.png)


























