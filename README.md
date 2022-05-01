
<h2 align="center">
  <img src="https://img.icons8.com/fluency/2x/edit-text-file.png"/>
  <img src="https://img.icons8.com/fluency/2x/bot.png"/>
  <br/>
  <b>Live Editor<sup style="font-size:12px;">©</sup></b>
  <p>Aplicativo para automatizar criação de aplicativos em servidor AWS Linux</p>
</h2>

## O que é

- Aplicativo para gerenciar instâncias Streamlit por meio de um editor conectado com `git` e `github`.

- Enquanto a porta `8001` está com o **App** aberto, o **Editor** na porta `8002` edita ao vivo e pode enviar modificações direto para o Github.

<br/>

## O que utiliza

- **Ferramentas**
  - Python
  - Streamlit
  - Streamlit Ace

<br/>

## Como Executar

```bash
git clone https://github.com/jvcss/LiveEditor.git

cd LiveEditor

streamlit run app.py
```

- caso não tenha instalado as bibliotecas necessárias

`pip install -r requirements.txt`

<br/>

## Funcionalidades do Aplicativo

- Cria privilégio de execução `chmod` automático a partir da tela **Editor**

- Faz `commit` para o git com um click

- Faz `pull request` para o github com um click

- Permite personalizar o código-fonte com diversos temas

- Permite ver logs de inicialização e execução de todos executáveis

- Permite instânciar novos executáveis

- Reflexo imediato no código-fonte editado em execução

- Executável `Linux` kernel

## Funcionalidades Futuras

- Criar arquivos a partir da página `Editor`

- Reorganizar visualização de arquivos

![Whatspper](images/info_editor_live_automation.jpg)
