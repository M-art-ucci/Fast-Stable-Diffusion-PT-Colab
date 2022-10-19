<h1 align="center">Stable Diffusion em Português</h1>
</p>

Esta é uma bifurcação do repositório de [TheLastBen](https://github.com/TheLastBen/fast-stable-diffusion/).

Abrir o Google Colab Notebook [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/M-art-ucci/fast-stable-diffusion-pt/blob/main/fast_stable_diffusion_AUTOMATIC1111.ipynb)

<h1 align="center">Pré-Requisitos</h1>

1. [Conta Google](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp), para acessar o Google Drive (as imagens geradas vão para lá).
2. Criar uma conta no [HuggingFace](https://huggingface.co/)(precisa confirmar por e-mail).
3. Em settings > Access Tokens, criar um novo token (pode ser o nome que você quiser e escolha a opção "write").

<h1 align="center">Instalação</h1>

Dentro do Notebook, você só precisa rodar as células na ordem em que estão, apertando o botão de play ao lado.

### Conectar ao Google Drive
Vai abrir uma janela de popup para você escolher a conta do Google e autorizar o acesso. Algumas pastas vão ser criadas ao longo do processo, para poder rodar o Stable Diffusion em português, utilizando o modelo que você preferir, e salvar as imagens que você gerar.

### Instalação do repositório do AUTOMATIC1111
Aqui vão começar as criações de pastas dentro do seu Google Drive, dentro da pasta `sd`.

### Download de Modelo/Carregar Modelo
Em `token`, copia e cola o toekn de acesso que você criou no HuggingFace.
Se você tem um modelo diferente do padrão no seu Google Drive, é só especificar o caminho.
Para modelos de fora do seu Google Drive, é só colar o link.

### Instalar Requisitos
Nesta célula não é necessário fazer nada. Neste fork é criado o meu arquivo de localização em português.

### Instalar xformers(para reduzir processamento)
Basta rodar a célula. Ela fará com que o processamento exija menos dos notebooks de colaboração e tona os processos mais eficientes.

### Iniciar Stable Diffusion - Copiar a url gerada para usar em qualquer navegador
Aqui vai gerar um link para você acessar em qualquer navegador, incluindo smartphones.
A interface ainda estará em inglês.

### Selecionar idioma
Para rodar o Stable Diffusion em português, você precisa ir em:
1. `settings`, e rolar até a opção `localizations`.
2. Selecione a opção `localizationpt`.
3. Vá até o final e clique em `Reload Gradio and update components`.
4. No topo da aba, clique em `Apply Settings`.
5. Feche o link e rode a célula `Iniciar Stable Diffusion` novamente.

Pronto! Agora o Stable Diffusion estará em português.

Obs 1: apesar do link ficar disponível por 72h, se a página do notebook de colaboração ficar sem atividade por muito tempo, o acesso é cortado e o Stable Diffusion vai parar de rodar.

Obs 2: você pode rodar este fork várias vezes sem que arquvios duplicados sejam gerados.
