# 🥗 30 Receitas Fit Deliciosas - Landing Page

Landing page profissional para venda do e-book "30 Receitas Fit Deliciosas"

## 🚀 Como Hospedar no GitHub Pages

### Passo 1: Criar Repositório

1. Acesse [GitHub.com](https://github.com) e faça login
2. Clique em **"New Repository"** (botão verde)
3. Nome do repositório: `receitas-fit` (ou qualquer nome)
4. Marque: **Public**
5. Clique em **"Create repository"**

### Passo 2: Upload dos Arquivos

#### Opção A - Via Interface Web (Mais Fácil):

1. No repositório criado, clique em **"Add file"** → **"Upload files"**
2. Arraste o arquivo `index.html`
3. Clique em **"Commit changes"**

#### Opção B - Via Git (Linha de Comando):

```bash
# Clone o repositório
git clone https://github.com/SEU_USUARIO/receitas-fit.git
cd receitas-fit

# Adicione o arquivo index.html
# (copie o HTML da landing page e salve como index.html)

# Commit e push
git add index.html
git commit -m "Add landing page"
git push origin main
```

### Passo 3: Ativar GitHub Pages

1. No repositório, vá em **"Settings"** (Configurações)
2. No menu lateral, clique em **"Pages"**
3. Em **"Source"**, selecione: **"Deploy from a branch"**
4. Em **"Branch"**, selecione: **"main"** e pasta **"/ (root)"**
5. Clique em **"Save"**
6. Aguarde 1-2 minutos

### 🎉 Sua página estará disponível em:

```
https://SEU_USUARIO.github.io/receitas-fit/
```

Exemplo: `https://joaosilva.github.io/receitas-fit/`

## 📱 Configurações Atuais

- ✅ WhatsApp: **+55 11 94484-3932**
- ⏰ Link Hotmart: *Será adicionado quando disponível*
- 📊 Analytics: *Configurar depois*

## 🔧 Próximas Configurações

### 1. Quando Tiver o Link da Hotmart:

Edite o arquivo `index.html` na linha 660:

```javascript
hotmartLink: 'https://pay.hotmart.com/SEU_LINK_REAL',
```

E em todas as tags `<a href="https://pay.hotmart.com/...">` (há 3 no código)

### 2. Domínio Personalizado (Opcional):

Se você comprar um domínio (ex: `receitasfit.com.br`):

1. Em **Settings → Pages**
2. Em **"Custom domain"**, adicione seu domínio
3. Configure o DNS no seu provedor:
   ```
   Type: CNAME
   Name: www
   Value: SEU_USUARIO.github.io
   ```

### 3. Google Analytics (Gratuito):

1. Crie conta em [analytics.google.com](https://analytics.google.com)
2. Adicione sua URL do GitHub Pages
3. Copie o ID (ex: `G-XXXXXXXXXX`)
4. Cole na linha 31 do HTML:
   ```javascript
   gtag('config', 'G-XXXXXXXXXX');
   ```

### 4. Facebook Pixel:

1. Acesse [Facebook Business](https://business.facebook.com)
2. Crie um Pixel no Gerenciador de Eventos
3. Copie o ID do Pixel
4. Cole na linha 25 do HTML:
   ```javascript
   fbq('init', 'SEU_PIXEL_ID');
   ```

### 5. Captura de E-mails:

**Opção Gratuita - Google Forms:**

1. Crie um Google Form
2. Configure webhook com [Zapier](https://zapier.com) (grátis até 100/mês)
3. Conecte com Google Sheets
4. Use Apps Script para enviar e-mail automático

**Opção Profissional:**
- [Mailchimp](https://mailchimp.com) - Grátis até 500 contatos
- [SendPulse](https://sendpulse.com) - Grátis até 500 contatos

## 📊 Métricas para Acompanhar

- [ ] Número de visitantes únicos
- [ ] Taxa de conversão (compras/visitantes)
- [ ] Taxa de captura de e-mail
- [ ] Tempo médio na página
- [ ] Taxa de rejeição
- [ ] Cliques no WhatsApp

## 🛠 Atualizações Futuras

Para atualizar a página:

1. Edite o arquivo `index.html` localmente
2. Volte ao repositório no GitHub
3. Clique no arquivo `index.html`
4. Clique no ícone de lápis (Edit)
5. Cole o novo código
6. **"Commit changes"**
7. Aguarde 1-2 minutos para atualizar

## 💡 Dicas Importantes

✅ **Teste em diferentes dispositivos** (celular, tablet, desktop)
✅ **Compartilhe o link** nas redes sociais
✅ **Crie anúncios** no Facebook/Instagram direcionando para a página
✅ **Use o WhatsApp Business** para gerenciar mensagens
✅ **Atualize regularmente** com novos depoimentos

## 📞 Suporte

- WhatsApp: +55 11 94484-3932
- Quando tiver dúvidas, me chame! 😊

## 🔒 Segurança

O GitHub Pages já inclui:
- ✅ HTTPS automático (SSL)
- ✅ CDN global (carregamento rápido)
- ✅ Hospedagem gratuita
- ✅ 99.9% de uptime

## 📈 Próximos Passos

1. ✅ Hospedar no GitHub Pages
2. ⏰ Adicionar link da Hotmart quando disponível
3. 📊 Configurar Google Analytics
4. 📱 Configurar Facebook Pixel
5. 📧 Configurar captura de e-mails
6. 🎯 Criar campanha de anúncios
7. 💬 Criar grupo VIP no WhatsApp

---

**Criado com ❤️ para ajudar você a vender mais!**
