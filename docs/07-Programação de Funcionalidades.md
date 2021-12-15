# Programação de Funcionalidades

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="5-Arquitetura da Solução.md"> Arquitetura da Solução</a>

## Banco de dados (RF-06 e RF-02)
Banco de dados SQL Server integrado a aplicação. 


- Requisitos atendidos
RF-06 - 
RF-02 - 

### Artefatos da funcionalidade
* ClinicDb.mdf
* DoctorTbl
* PatientTbl
* ReceptionistTbl
* PrescriptionTbl
* TestTbl


## GUI (RF-02)
A interface gráfica do projeto é limpa e coesa para o melhor funcionamento e entendimento do usuário.


### Artefatos da funcionalidade
* Login.cs
* Homes.cs
* Receptionists.cs
* Doctors.cs
* LabTests.cs
* Prescriptions.cs
* Patients.cs


## Tela de Login (RF-01)
A tela de login permite selecionar o tipo de usuário para acessar.


### Artefatos da funcionalidade
* Login.cs
* Método RoleCb_SelectedIndexChanged()
* ComboBox de seleção.


## Cadastros (RF-05)
O sistema permite cadastrar Pacientes, Recepcionistas, Médicos e Exames Laboratoriais. Cada tipo tem sua respectiva tabela no banco de dados seguindo os padrões mostrados a seguir.


### Artefatos da funcionalidade
* Gerenciador de servidores
* ClinicDb.mdf
* DoctorTbl
* PatientTbl
* ReceptionistTbl
* PrescriptionTbl
* TestTbl


## Navegação (RF-04)
O sistema permite navegação através do painel lateral, clicando nas labels em questão.


### Artefatos da funcionalidade
* Métodos internos no .cs de cada tela.
* PatientLbl_Click
* DoctorLbl_Click
* LabTestsLbl_Click
* ReceptioniststLbl_Click
* LogoutLbl_Click


## Data Grid View (RF-06 e RF-08)
O sistema permite visualizar e alterar as tabelas em tempo real e direto no banco de dados com eventos on_click.


### Artefatos da funcionalidade
* Data Grid View
* Métodos DGV no .cs de cada tela
* ClinicDb


## Receituário (RF-09 e RF-10)
O sistema permite gerar uma prescrição automaticamente através de um evento on_click no Data Grid View. É possível também imprimir a prescrição.


### Artefatos da funcionalidade
* Data Grid View
* Método PrintBtn_Click no Prescription.cs
* Método CellContentClick no DGV do Prescription.cs


## Tela de Login em caso de usuário inválido (RF-07)
O sistema alerta em caso de usuário inválido.


### Artefatos da funcionalidade
* Login.cs
* Métodos de autenticação
* ClinicDb
* Respectivas tabelas do banco para cada tipo de usuário