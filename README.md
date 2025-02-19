Sistema de Controle de Manifestações - Manifestação Fácil com Interface Gráfica
Este projeto é um sistema de controle de manifestações desenvolvido em Python, utilizando a biblioteca Tkinter para a interface gráfica. Ele permite registrar, alterar, excluir e visualizar manifestações de consumidores de forma fácil e prática. O sistema utiliza um arquivo de texto para armazenar os dados das manifestações.

Funcionalidades
Incluir nova manifestação: Permite adicionar uma nova manifestação ao sistema, validando o RA ID, nome, data e status.
Alterar manifestação: Permite alterar os dados de uma manifestação existente, baseada no RA ID.
Excluir manifestação: Permite excluir uma manifestação existente, baseada no RA ID.
Relatório Geral: Exibe um relatório geral de todas as manifestações registradas em uma tabela.
Pesquisa Parcial por RA ID: Permite realizar uma pesquisa parcial por RA ID para encontrar manifestações específicas.
Interface Gráfica: Interface amigável e intuitiva desenvolvida com Tkinter, incluindo campos de entrada, botões e uma tabela para exibição dos dados.

Estrutura do Código
Classe Manifestacao: Representa cada manifestação com atributos como RA ID, data, nome, assunto e status.
Funções de Manipulação de Dados: Funções para carregar, salvar, atualizar e remover manifestações do arquivo de texto.
Funções Principais: Funções para adicionar, atualizar, remover e listar manifestações, além de limpar os campos de entrada.
Interface Gráfica: Configuração da interface gráfica com Tkinter, incluindo a criação de janelas, rótulos, campos de entrada, botões e uma tabela.

Como Executar
Certifique-se de ter o Python instalado em sua máquina.
Clone este repositório.
Execute o arquivo principal do sistema.
python nome_do_arquivo.py

Exemplo de Uso
Ao iniciar o sistema, você verá a interface gráfica com campos de entrada para RA ID, nome, assunto, status e data. Utilize os botões para adicionar, atualizar, remover e listar manifestações.
