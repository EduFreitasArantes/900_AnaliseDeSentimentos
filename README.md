# Processo de Análise de Texto com o Language Studio

Este projeto tem como objetivo explorar os recursos de análise de texto do Azure Language Studio. Com base nos conceitos aprendidos, realizamos a análise de sentimentos em textos para entender como essa funcionalidade pode ser aplicada em cenários práticos, como avaliar revisões de clientes para melhorar a experiência do usuário em plataformas de comércio eletrônico.

## Configuração do Projeto

### Criação do Recurso de Idioma no Azure:

Antes de começar, é necessário criar um recurso de serviços de IA do Azure. Siga as instruções abaixo para configurar o recurso:

1. Acesse o [Portal do Azure](https://portal.azure.com).
2. Clique em "+ Criar um recurso" e procure por "Serviços de IA do Azure".
3. Selecione "Criar um plano de serviços de IA do Azure" e configure as opções necessárias:
   - **Assinatura:** Sua assinatura do Azure.
   - **Grupo de Recursos:** Selecione ou crie um grupo de recursos com um nome exclusivo.
   - **Região:** Leste dos EUA.
   - **Nome:** Insira um nome exclusivo.
   - **Nível de Preços:** Standard S0.
   - **Termos do Avico de IA Responsavel:** Marcar (Aceitar).
4. Clique em "Revisar + criar" e, em seguida, em "Criar". Aguarde a conclusão da implantação.

A seguir, está os print screens da criação do recurso:

- [Print Screen 01](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeSentimentos/blob/main/config/001.jpg)

## Análise de Sentimento e Opinião:

1. Acesse o [Azure Language Studio](https://language.cognitive.azure.com).
2. Faça login com sua conta e verifique se está usando o mesmo diretório em que criou o recurso de serviços de IA do Azure.
3. Selecione a guia "Classificar texto".
4. Escolha a opção "Analisar sentimento e minerar opiniões".
5. Selecione o idioma do texto (por exemplo, Inglês).

### Conexão do Recurso ao Language Studio

Agora é necessário conectar o recurso de serviços de IA do Azure ao Language Studio.

1. Selecione o recurso criado na lista.

A seguir, está os print screens da conexão do recurso com o Language Studio:

- [Print Screen 02](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/config/002.jpg)

## Execução da Análise:
1. Copie o conteudo do arquivo **critica.txt** disponibilizado na pasta "inputs".
1. Cole o texto a ser analisado na caixa de texto.
2. Execute a análise e revise os resultados.

## Avaliação dos Resultados:
1. Analise o sentimento geral atribuído ao texto.
2. Verifique as pontuações de sentimentos atribuídas a cada frase.
3. Compare o texto com a análise de sentimento retornada pelo serviço.
  
A seguir, está os print screens da conexão do recurso com o Language Studio:

- [Print Screen 03](https://github.com/EduFreitasArantes/lab-ai-900_AnaliseDeImagens/blob/main/outputs/001.jpg)

## Insights e Possibilidades:
1. **Identificação de Sentimento:**
    <br>a. O serviço é capaz de identificar sentimentos positivos, negativos e neutros em um texto.
    <br>b. As pontuações de confiança ajudam a avaliar a precisão da análise de sentimento.

2. **Aplicações Potenciais:**
    <br>a. Empresas podem usar essa análise para entender a recepção de produtos, serviços ou experiências do cliente.
    <br>b. Agências de viagens podem avaliar revisões de hotéis para fornecer recomendações mais precisas aos clientes.

3. **Melhorias e Ajustes:**
    <br>a. É importante revisar e ajustar o modelo conforme necessário para melhorar a precisão da análise de sentimento.
    <br>b. Examinar manualmente os resultados pode revelar nuances que o modelo pode não capturar completamente.
