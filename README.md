# projeto_integrador_02
Projeto da Univesp
projeto_integrador-02 Aplicação web desenvolvida no âmbito da Disciplina Projeto Integrador II, da Universidade Estadual do Estado de São Paulo.
Tema do projeto:
Funcionalidades: Administrar a agenda de profissionais de Fisioterapia; Disponibilizar uma agenda para que pacientes logrem êxito em realizar marcações de seus atendimentos; Permitir ao usuário a consulta de eventuais datas e horários disponíveis na agenda do profissional que lhe atenderá, bem como o cancelamento de consulta/atendimento que já tiver sido marcado. Para rodar este projeto localmente, siga os seguintes passos: Configurando o ambiente para executar a aplicação web. Faça o download deste repositório: $ git clone https://github.com/aires-fael/projeto_integrador-02.git
Criando um ambiente virtual e instalando as dependências: (disponíveis no arquivo requirementes.txt): Entre na pasta criada e inicie um ambiente virtual: $ cd projeto_integrador_02 $ python3 -m venv venv (no Windows vá até pasta scripts e digite o comando: activate)
Ative o ambiente virtual com o seguinte comando: $ source ./venv/bin/activate
Após ativado, instale as bibliotecas necessárias para executar o projeto:
(venv)$ pip install -r requirements.txt Para poder realizar o primeiro acesso e configurar a aplicação, é necessário executar o comando migrate. Assim, será gerado o banco de dados padrão do Django (MySQL). E depois criar o superusuario:
Execute: (venv)$ ./manage.py migrate (Win) python manage.py migrate
(venv)$ ./manage.py createsuperuser (win) python manage.py createsuperuser Apelido/Usuário: admin E-mail: admin@mail.com Password: Password (again): Para iniciar o servidor, você deve executar:
(venv)$ ./manage.py runserver (Win) python manage.py runserver
Para visualizar se tudo está executando como esperado, basta acessar os seguinte endereços em seu navegador padrão: http://localhost:8000/ http://localhost:8000/admin http://localhost:8000/contas http://localhost:8000/clientes http://localhost:8000/fisioterapeutas http://localhost:8000/atendimento

