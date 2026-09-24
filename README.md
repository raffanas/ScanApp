# Scan App 📄✨

Aplicativo nativo Android para escaneamento profissional de documentos, organização de páginas e geração de arquivos PDF de alta qualidade.

Desenvolvido em **Kotlin Puro + Jetpack Compose (Material 3)**, construído para o **Android Studio** (sem Expo, sem dependências externas complexas, 100% offline, gratuito e sem necessidade de login/senha).

---

## 🚀 Principais Funcionalidades

1. **Escaneamento Inteligente com Google ML Kit Document Scanner:**
   - **Enquadramento Automático:** A câmera detecta as 4 bordas do documento/papel em tempo real.
   - **Correção de Perspectiva:** Alinha folhas tortas ou fotografadas em ângulo.
   - **Modo FULL:** Permite recortar manualmente os cantos, rotacionar páginas (se a foto ficar de lado), reordenar páginas (página 1, 2, 3...) e aplicar filtros (Original, Preto e Branco para contraste de texto e Colorido).
   - **Importação de Fotos:** Permite tanto tirar fotos na hora quanto importar imagens existentes da galeria.
   - **Geração Direta em PDF:** Compila todas as fotos em um único arquivo PDF.

2. **Galeria Interna e Gerenciador de Documentos:**
   - Exibe **apenas os documentos criados pelo aplicativo**.
   - Cada cartão exibe:
     - Miniatura de alta qualidade da primeira página.
     - Título do documento.
     - Data e hora da criação formatadas.
     - Quantidade de páginas e tamanho do arquivo.
   - **Barra de Busca:** Filtro dinâmico para encontrar documentos pelo nome em tempo real.

3. **Visualizador de PDF Embutido:**
   - Ao tocar em um documento, abre um leitor interno rápido que renderiza as páginas em alta resolução (`PdfRenderer`).
   - Opção de abrir também em qualquer leitor de PDF do sistema (Google Drive, Adobe, etc.).

4. **Ações e Compartilhamento:**
   - **Compartilhar:** Envia o PDF diretamente para WhatsApp, E-mail, Google Drive, Telegram, etc., via `FileProvider`.
   - **Renomear:** Altere o nome de qualquer documento com facilidade.
   - **Excluir:** Confirmação de exclusão para remoção segura.

5. **100% Gratuito, Seguro e Offline:**
   - Sem cadastro, sem login, sem dados enviados para servidores externos.
   - Não requer permissões invasivas de câmera no manifesto (o fluxo é gerenciado com segurança pelo Google Play Services).

---

## 🛠️ Como Abrir e Rodar no Android Studio

1. Abra o **Android Studio**.
2. Clique em **File > Open** (ou **Open Project** na tela inicial).
3. Selecione a pasta deste projeto: `d:\Z_Ideias\Scan-App`.
4. O Android Studio reconhecerá o Gradle e fará o sync automaticamente.
5. Conecte seu smartphone via cabo USB (com Depuração USB ativada) ou inicie um emulador.
6. Clique no botão verde de **Run (Play)** no topo do Android Studio.

---

## 📦 APK de Teste Já Compilado

O APK já foi compilado com sucesso e está pronto em:
`app/build/outputs/apk/debug/app-debug.apk`
