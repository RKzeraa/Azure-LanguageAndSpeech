# Azure-LanguageAndSpeech

### Análise de Texto com Language Studio

Neste exercício, você explorará os recursos da linguagem Azure AI analisando alguns exemplos de avaliações de hotéis. Use o Language Studio para entender se as avaliações são predominantemente positivas ou negativas.

- **Processamento de Linguagem Natural (PNL)**: Um ramo da IA que lida com linguagem escrita e falada.
- Utilize a PNL para extrair significado semântico de texto ou fala, ou para formular respostas significativas em linguagem natural.

#### Criar um Recurso de Idioma

1. Acesse o [Portal do Azure](https://portal.azure.com) e clique em **+ Criar um recurso**.
2. Pesquise por **Serviço de Idioma** e selecione **Criar um plano de serviço de idiomas**.
3. Configure o recurso com as seguintes configurações:
   - **Assinatura**: Sua assinatura do Azure.
   - **Grupo de Recursos**: Selecione ou crie um com um nome exclusivo.
   - **Região**: Leste dos EUA.
   - **Nome**: Insira um nome exclusivo.
   - **Nível de Preços**: F0 grátis ou S se F0 grátis não estiver disponível.
4. Marque a caixa de confirmação e clique em **Revisar + criar** e depois **Criar**.

#### Configurar no Azure AI Language Studio

1. Acesse o [Language Studio](https://language.cognitive.azure.com) e entre.
2. Em **Selecionar um recurso do Azure**, escolha o recurso criado anteriormente.
3. Selecione **Concluído**.

#### Analisar Avaliações

1. No Language Studio, selecione a guia **Classificar texto** e escolha **Analisar sentimento e extrair opiniões**.
2. Selecione **Inglês** como idioma do texto.
3. Carregue ou copie e cole a avaliação e execute.
4. Revise o resultado para determinar o sentimento e a confiança.

#### Resultados Obtidos no Language Studio

![Untitled (1)](https://github.com/RKzeraa/Azure-LanguageAndSpeech/assets/45771465/3cb8804b-0602-4d43-b91b-c187b5caf864)


Este exercício demonstrou como usar o Language Studio para análise de texto. Lembre-se de excluir recursos não utilizados para evitar custos desnecessários.

</br>

### Explorar o Estúdio de Fala

O serviço Azure AI Speech transcreve a fala em texto e o texto em fala audível. Use o AI Speech para criar aplicativos que possam transcrever notas de reuniões ou gerar texto a partir da gravação de entrevistas.

#### Criar um Recurso de Fala do Azure AI

1. Acesse o [Azure AI Speech Studio](https://aka.ms/mslearn-speech-studio) e entre com sua conta da Microsoft.
2. Selecione **Configurações** e depois **Crie um recurso**.
3. Configure-o com as seguintes configurações:
   - **Nome do novo recurso**: Insira um nome exclusivo.
   - **Assinatura**: Sua assinatura do Azure.
   - **Região**: Selecione uma região suportada.
   - **Nível de preços**: FO gratuito (se disponível, caso contrário, selecione Padrão S0).
   - **Grupo de recursos**: Selecione ou crie um com um nome exclusivo.
4. Selecione **Criar recurso**. Aguarde até que o recurso seja criado e selecione **Usar recurso**.

#### Explore a Fala em Texto no Speech Studio

1. Baixe o [speech.zip](https://aka.ms/mslearn-speech-files) e abra a pasta.
2. No Speech Studio, em **Fala para texto**, selecione **Experimente a fala em tempo real para texto**.
3. Em **Escolher arquivos de áudio**, selecione **Procurar arquivos** e navegue até a pasta onde você salvou o arquivo. Selecione **WhatAICanDo.m4a** e depois **Abrir**.
4. O serviço Speech transcreve e exibe o texto em tempo real. Se você tiver áudio em seu computador, poderá ouvir a gravação enquanto o texto é transcrito.
5. Revise a saída, que deve ter reconhecido e transcrito com êxito o áudio em texto.

#### Resultados Obtidos no Speech Studio

![Untitled (2)](https://github.com/RKzeraa/Azure-LanguageAndSpeech/assets/45771465/d1191c04-63b3-4963-83a2-8dd4954349ef)


Neste exercício, você criou um recurso AI Speech no Speech Studio e usou o serviço de fala em tempo real para texto para transcrever uma gravação de áudio.
