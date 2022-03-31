
<h2 align="center">
  <img src="https://img.icons8.com/fluency/2x/edit-text-file.png"/>
  <img src="https://img.icons8.com/fluency/2x/bot.png"/>
  <br/>
  <b>Live Editor<sup style="font-size:12px;">©</sup></b>
  <p>Aplicativo para automatizar criação de aplicativos em servidor AWS Linux</p>
</h2>

## O que é

- Aplicativo para gerenciar instâncias Streamlit por meio de um editor conectado com git e github. 
- Enquanto a porta `8001` está com o **App** aberto, o **Editor** na porta `8002` editar ao vivo e pode enviar modificações direto para o Github.

## O que utiliza

- **Ferramentas**
  - Python
  - Streamlit
  - Regular Expression

## Como Executar

- caso não tenha instalado as bibliotecas necessárias

`pip install -r requirements.txt`

```bash
git clone https://github.com/jvcss/LiveEditor.git

cd LiveEditor

streamlit run app.py
```

## Funcionalidades do Aplicativo

- Cria **chmod** automático a partir da interface de **contatos** e **conversas**

- Verificação automática das atualização de uma instância Streamlit para outra

- Permite atualizar a base de contatos retirando os que foram excluídos após execução

- Executável `Windows` e `Linux`

- Windows permite envio de imagem e textos com edição

- Linux não permite adicionar imagem na mensagem

- Chrome precisa de uma versão do driver compatível com o seu navegador [Baixar](https://chromedriver.chromium.org/downloads)

![Whatspper](images/plao_fundo_info_whatspper_automation.jpg)
