# Dominando-o-Armazenamento-na-Azure

Vamos Criar uma Nova Conta de Armazenamento:
No menu à esquerda, selecione “Contas de armazenamento” pesquise na barra de pesquisa na área central.
Clique em “Criar” para iniciar o processo de criação.


Preencha os detalhes necessários:
Assinatura: Selecione sua assinatura do Azure.
Grupo de Recursos: Escolha um grupo de recursos existente ou crie um novo.
Nome da Conta de Armazenamento: Insira um nome exclusivo para sua conta.
Região: Selecione a região onde deseja criar a conta.
Desempenho: Escolha entre Standard ou Premium, dependendo de suas necessidades.
Replicação: Selecione a opção de replicação desejada (LRS, GRS, RA-GRS, etc.).
basic

Configurações Adicionais:
Configure as opções adicionais conforme necessário, como redes virtuais, tags, etc.
Clique em “Revisar e criar” e depois em “Criar” para finalizar a criação da conta.


Uso Básico:
Para copiar um arquivo local para um contêiner de blob:
azcopy copy 'C:\local\path\to\file.txt' 'https://<storage-account-name>.blob.core.windows.net/<container-name>/file.txt'
Para copiar um blob para um arquivo local:
azcopy copy 'https://<storage-account-name>.blob.core.windows.net/<container-name>/file.txt' 'C:\local\path\to\file.txt'
Azure Data Factory:
Azure Data Factory é um serviço de integração de dados baseado em nuvem que permite criar, agendar e orquestrar fluxos de trabalho de dados.
Ele suporta a movimentação de dados entre uma variedade de fontes de dados, incluindo armazenamento do Azure, bancos de dados SQL, e muito mais.
 Azure Storage Explorer:
Azure Storage Explorer é uma ferramenta gráfica que facilita a gestão de dados no armazenamento do Azure.
Permite visualizar, carregar, baixar e gerenciar blobs, arquivos, filas e tabelas.
