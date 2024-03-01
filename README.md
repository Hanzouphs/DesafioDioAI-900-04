# Processo para trabalhar com índice do Azure AI Search (UI)

Para utilizar o Azure Machine Learning, foi necessário aprovisionar um espaço de trabalho do Azure Machine Learning na subscrição do Azure. Depois, você foi possível usar o estúdio Azure Machine Learning para trabalhar com os recursos do workspace

Recursos do Azure necessários:

* A solução que você criará para o Fourth Coffee requer os seguintes recursos na sua assinatura do Azure:
* Um recurso de serviços de IA do Azure , que fornece serviços de IA para habilidades que sua solução de pesquisa pode usar para enriquecer os dados na fonte de dados com insights gerados por IA.
* Uma conta de armazenamento com contêineres de blobs, que armazenará documentos brutos e outras coleções de tabelas, objetos ou arquivos.

# Crie um recurso do Azure AI Search

* Entre no portal do Azure.
* Clique no botão + Criar um recurso , pesquise Azure AI Search e crie um recurso Azure AI Search com as seguintes configurações:
* Selecione Review + create e depois de ver a resposta Validation Success , selecione Create.
* Após a conclusão da implantação, selecione Ir para o recurso . Na página de visão geral do Azure AI Search, você pode adicionar índices, importar dados e pesquisar índices criados.

# Crie um recurso de serviços de IA do Azure

Você precisará provisionar um recurso de serviços de IA do Azure que esteja no mesmo local que seu recurso do Azure AI Search. Sua solução de pesquisa usará esse recurso para enriquecer os dados no armazenamento de dados com insights gerados por IA.

* Retorne à página inicial do portal do Azure. Clique no botão ＋Criar um recurso e pesquise os serviços de IA do Azure . Selecione criar um plano de serviços de IA do Azure . Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
* Selecione Revisar + criar . Depois de ver a resposta Validation Passed , selecione Create.
* Aguarde a conclusão da implantação e visualize os detalhes da implantação.
