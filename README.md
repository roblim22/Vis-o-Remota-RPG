# 🚀 APK OFFLINE - SEM INSTALAR NADA!

## ✅ O QUE VOCÊ PRECISA:
- Conta no GitHub (grátis)
- Seu arquivo do jogo: `rpg-maker-visao-remota.html`
- 10 minutos

## ❌ O QUE NÃO PRECISA:
- Java JDK
- Android Studio
- Nada instalado no PC!

---

## 📋 PASSO A PASSO:

### 1️⃣ CRIAR CONTA NO GITHUB
1. Acesse: https://github.com/
2. Clique em "Sign up"
3. Crie sua conta (grátis)

---

### 2️⃣ CRIAR REPOSITÓRIO
1. Clique no **"+"** (canto superior direito)
2. Clique em **"New repository"**
3. Nome: `visao-remota-rpg`
4. Marque: **"Public"**
5. Marque: **"Add a README file"**
6. Clique em **"Create repository"**

---

### 3️⃣ FAZER UPLOAD DOS ARQUIVOS
1. Dentro do repositório, clique em **"Add file"** → **"Upload files"**
2. Arraste TODOS os arquivos desta pasta:
   - `.github/` (pasta inteira com workflows)
   - `app/` (pasta inteira)
   - `build.gradle`
   - `settings.gradle`
   - `gradle/` (pasta inteira)
3. ⚠️ **IMPORTANTE:** Também arraste o arquivo do jogo:
   - `rpg-maker-visao-remota.html`
   - Salve como: `app/src/main/assets/index.html`
4. Clique em **"Commit changes"**

---

### 4️⃣ ADICIONAR O JOGO
1. Ainda no repositório, navegue até: `app/src/main/assets/`
2. Se a pasta não existir, clique em **"Add file"** → **"Create new file"**
3. No nome, digite: `app/src/main/assets/index.html`
4. Cole o conteúdo do seu `rpg-maker-visao-remota.html`
5. Clique em **"Commit new file"**

---

### 5️⃣ RODAR O BUILD
1. Clique em **"Actions"** (menu superior)
2. Você verá: **"Build APK"**
3. Clique nele
4. Clique em **"Run workflow"**
5. Clique em **"Run workflow"** (botão verde)
6. **Aguarde 3-5 minutos** ☕

---

### 6️⃣ BAIXAR O APK
1. Quando aparecer ✅ verde, clique no build
2. Role até **"Artifacts"**
3. Clique em **"visao-remota-rpg"**
4. **BAIXE O ZIP**
5. Extraia
6. Dentro terá: **`app-debug.apk`**

---

### 7️⃣ INSTALAR NO ANDROID
1. Copie o APK para o celular
2. Configurações → Segurança → **"Fontes desconhecidas"** (ativar)
3. Toque no APK → **Instalar**
4. **JOGUE!** 🎮

---

## ✅ RESULTADO:
- APK **100% offline**
- Funciona **para sempre**
- **Não depende** de Netlify
- **Não depende** de nenhum site
- **Não precisa** de internet para jogar

---

## 🔧 SE DER ERRO NO BUILD:

### "Gradle build failed"
- Verifique se o `index.html` está em: `app/src/main/assets/index.html`
- Verifique se todos os arquivos foram enviados

### "Workflow not found"
- Verifique se a pasta `.github/workflows/build.yml` foi criada corretamente
- Deletar e criar novamente o arquivo

---

## 🔄 ATUALIZAR O JOGO:
1. Edite o `app/src/main/assets/index.html` no GitHub
2. Commit
3. Actions roda automaticamente
4. Baixe o novo APK!

---

## 💡 DICA:
Guarde o link do seu repositório GitHub.
Sempre que quiser atualizar o jogo:
1. Edite o arquivo
2. APK novo gerado automaticamente!
