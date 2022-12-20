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

#Especialidade
![image](https://user-images.githubusercontent.com/110436354/208734820-c8953b80-9827-4b99-8941-8b62f9c759f7.png)

#Internação
![image](https://user-images.githubusercontent.com/110436354/208734977-25df73e0-abd0-4ddf-9018-925a42adf94f.png)

#Médico
![image](https://user-images.githubusercontent.com/110436354/208739446-16834f1b-0bd9-4feb-88b5-fcae457fa7b8.png)

#Paciente
![image](https://user-images.githubusercontent.com/110436354/208739605-cfbcd851-3e69-4447-acb2-f594b36b3d28.png)

#Quarto
![image](https://user-images.githubusercontent.com/110436354/208739945-d86744a5-5764-432e-ace7-75d3efce97aa.png)














