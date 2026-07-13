# Ficha de Implantação — WGK7 Solutions

Formulário online para clientes preencherem os dados de implantação do condomínio.
As respostas chegam automaticamente por e-mail.

## 🔗 Qual é o link da ficha?

**https://welliton0304.github.io/wgk7-ficha/**

Esse link é público, permanente e gratuito (hospedado no GitHub Pages).

## 📤 Como envio o link para um cliente?

É só copiar o endereço acima e mandar por WhatsApp, e-mail ou onde preferir.
O cliente abre no celular ou computador, preenche e clica em **"Enviar ficha de implantação"**.
Não precisa instalar nada.

## 📬 Onde chegam as respostas?

Cada ficha enviada chega como um e-mail no endereço que foi cadastrado na chave
do Web3Forms (o serviço gratuito que faz a entrega). O assunto do e-mail é
**"Nova ficha de implantação — WGK7"**.

> Na primeira vez, confira também a caixa de **spam** e marque como "não é spam"
> para os próximos chegarem na caixa de entrada.

⚠️ **Atenção:** os documentos anexados pelo cliente (RG, CPF, comprovantes) **não**
seguem junto com o e-mail — o plano gratuito do Web3Forms não envia arquivos.
A própria ficha avisa o cliente para mandar os documentos por WhatsApp.

## ✉️ Como troco o e-mail que recebe as fichas?

1. Entre em **https://web3forms.com** e crie uma chave nova ("Create Access Key")
   usando o **novo e-mail**. A chave chega por e-mail em 1 minuto.
2. Abra o arquivo `index.html` (veja "Como edito a ficha" abaixo) e procure a linha
   que tem `name="access_key"`.
3. Troque o código que está em `value="..."` pela chave nova e salve/publique.

## ✏️ Como edito a ficha e republico?

O jeito mais fácil, direto pelo site do GitHub (sem programas):

1. Entre em **https://github.com/welliton0304/wgk7-ficha** (logado na conta `welliton0304`).
2. Clique no arquivo **`index.html`**.
3. Clique no ícone de **lápis** (✏️ "Edit") no canto superior direito.
4. Faça a alteração desejada (ex: mudar um texto, acrescentar um campo).
5. Clique no botão verde **"Commit changes"** e confirme.
6. Aguarde 1 a 2 minutos — o site atualiza sozinho no mesmo link.

Também dá para editar o arquivo `index.html` desta pasta no computador e pedir
ao Claude Code para republicar.

## 🗂️ Onde ficam guardadas as coisas?

| O quê | Onde |
|---|---|
| Página no ar | https://welliton0304.github.io/wgk7-ficha/ |
| Código-fonte | https://github.com/welliton0304/wgk7-ficha |
| Cópia no computador | `Desktop\Wgk7\ficha-wgk7` |
| Respostas das fichas | No e-mail cadastrado na chave do Web3Forms |

> 💡 O e-mail é hoje o único registro das respostas — não apague os e-mails de ficha.
> Se quiser um histórico automático em planilha (Google Sheets), isso é a "Fase 2"
> do projeto: é só pedir ao Claude Code.
