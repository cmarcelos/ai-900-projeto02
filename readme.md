# Detectar rostos no Vision Studio
As soluções de visão geralmente exigem IA para serem capazes de detectar rostos humanos. Suponha que a empresa de varejo fictícia Northwind Traders queira localizar onde os clientes estão em uma loja para melhor ajudá-los. Uma maneira de fazer isso é determinar se há faces nas imagens e, em caso afirmativo, retornar as coordenadas da caixa delimitadora que mostram sua localização.

Para testar os recursos de detecção facial do serviço Azure AI Face, você usará o [Azure Vision Studio] (https://portal.vision.cognitive.azure.com/gallery/featured). Esta é uma plataforma baseada em interface do usuário que permite explorar os recursos do Azure AI Vision sem precisar escrever nenhum código.

## Criar um recurso de serviços de IA do Azure
Você pode usar o serviço Azure AI Face com um recurso multisserviço dos ***serviços de IA do Azure***. Se você ainda não tiver feito isso, crie um recurso de serviços de IA do Azure em sua assinatura ***do Azure***.

1. Em outra guia do navegador, abra o portal do Azure em <https://portal.azure.com>, entrando com a conta da Microsoft associada à sua assinatura do Azure.

2. Clique no botão ***+Criar um recurso*** e procure serviços de IA do Azure. Selecione ***criar*** um plano de ***serviços de IA do Azure***. Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:

- ***Assinatura***: sua assinatura do Azure.
- ***Grupo de recursos***: selecione ou crie um grupo de recursos com um nome exclusivo.
- ***Região***: Leste dos EUA.
- ***Nome***: insira um nome exclusivo.
- ***Nível de preços***: Standard S0.
- ***Ao marcar esta caixa, reconheço que li e entendi todos os termos abaixo***: Selecionado.
3. Selecione ***Revisar + criar*** e, em seguida, ***Criar*** e aguarde a conclusão da implantação.

## Conectar seu recurso de serviço de IA do Azure ao Vision Studio
Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.

1. Em outra guia do navegador, navegue até o ***Vision Studio*** em <https://portal.vision.cognitive.azure.com>.

2. Entre com sua conta e verifique se você está usando o mesmo diretório em que criou seu recurso de serviços de IA do Azure.

3. Na home page do Vision Studio, selecione ***Exibir todos os recursos*** no cabeçalho ***Introdução ao Vision***.

4. Na página ***Selecione um recurso para trabalhar***, passe o cursor do mouse sobre o recurso criado acima na lista e marque a caixa à esquerda do nome do recurso e selecione ***Selecionar como recurso padrão.***

5. Feche a página de configurações selecionando o "x" no canto superior direito da tela.

## Detectar rostos no Vision Studio
1. Em um navegador da Web, navegue até ***o Vision Studio*** em <https://portal.vision.cognitive.azure.com>.

2. Na página inicial ***Introdução ao Vision***, selecione a guia ***Rosto*** e selecione o bloco ***Detectar faces em uma imagem***.

3. No subtítulo ***Experimentar***, reconheça a política de uso de recursos lendo e marcando a caixa.

4. Selecione cada uma das imagens de amostra e observe os dados de detecção de rosto retornados.

5. Agora vamos tentar com algumas de nossas próprias imagens. Selecione <https://aka.ms/mslearn-detect-faces> para baixar ***detect-faces.zip***. Em seguida, abra a pasta no computador.

6. Localize o arquivo chamado ***store-camera-1.jpg***; que contém uma imagem. (Mudei esta frase do original)

7. Carregue ***store-camera-1.jpg*** e revise os detalhes de detecção de rosto que são retornados.

8. Localize o arquivo chamado store-camera-2.jpg; que contém a seguinte imagem:

9. Carregue ***store-camera-2.jpg*** e revise os detalhes de detecção de rosto retornados.

10. Localize o arquivo chamado ***store-camera-3.jpg***; que contém a seguinte imagem:

11. Carregue ***store-camera-2.jpg*** e revise os detalhes de detecção de rosto retornados. Observe como o Azure AI Face pode detectar rostos parcialmente obscurecidos.

Neste exercício, você explorou como os serviços de IA do Azure podem detectar rostos em imagens. Se você tiver tempo, sinta-se à vontade para experimentar as imagens de amostra ou algumas de suas próprias imagens.


### Notas para as ativiades:
Para ter o passo a passo de como executar as demais atividades entre no link da microsoft abaixo.
- [Ler texto no Vision Studio] (https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)
- [Analisar imagens no Vision Studio] (https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)



### O autor do texto é a Microsoft segue a referência

<https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html>




