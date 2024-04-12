# Reconhecimento-Facial-e-transformacao-de-imagens-azure
Esse repositório mostra a utilização do recurso do Azure AI Services e o portal vision studio.

# Criando recurso
1. Entre no portal do Azure e clique em "Criar um recurso"
2. Clique na categoria de "AI + Machine Learning" e escolha o Azure AI Services
3. Para criar um recurso do "Azure AI Services", você deve: selecionar o grupo de recursos para o seu recurso (ou criar um novo) e colocar o nome do recurso
4. Dentro da região que você escolheu para hospedar o recurso, você deve colocar o Pricing tier (preço do tier). Por último, você deve checar a caixa de seleção confirmando os temos das notas da utilização desse Recurso de IA e confirmar a criação no Review + Create
5. Após concluir, você deve ir para o portal (https://portal.vision.cognitive.azure.com/). Acessando-o, vá para o View All Resources (ou clique no recurso que estiver nessa região)
6. Selecione o recurso com o qual você vai trabalhar que será o que foi criado anteriormente. Passe o mouse no recurso e verá uma caixa de seleção redonda. Vendo ela, clique na mesma e confirme isso no "Select as default resource" (Selecione como recurso padrão)
7. No início do portal, você pode escolher uma das funcionalidades e entrar pelo Try it out
8. Para cada funcionalidade que você utilizar, você deve confirmar que essa funcionalidade demo irá utilizar um pouco do recurso selecionado anteriormente na sua conta do Azure. Dessa forma, irá poder utilizar as ferramentas por amostras e resultados.

# Ferramenta Detectar Rosto
1. No portal do Vision Studio desca na tela inicial e selecione a opção de "rosto ou face" e depois clicar no "Try it out" do Detect faces in an image (detectar rosto em uma imagem). Essa função irá detectar se os rostos estão bem visíveis e, caso estejam cobertos de alguma forma, descreve o "mask: true" com o que possivelmente estaria os cobrindo.
2. Vamos fazer um teste com a imagem abaixo:



3. Ao passar pela funcionalidade "Face ou rosto" termos o resultado do mask conforme imagem abaixo:




# Ferramenta Extrair Texto de Imagem





