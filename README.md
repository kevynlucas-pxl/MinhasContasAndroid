# Minhas Contas — Android

Aplicativo Android offline para registrar contas, marcar pagamentos, acompanhar totais e exportar CSV. Os dados ficam no armazenamento local do WebView (`localStorage`).

## Gerar o APK no Android Studio

1. Instale o Android Studio e o Android SDK Platform 35.
2. Extraia este ZIP.
3. No Android Studio, escolha **Open** e selecione a pasta `MinhasContasAndroid`.
4. Aguarde a sincronização do Gradle e aceite a instalação dos componentes solicitados.
5. No menu **Build**, selecione **Build APK(s)**.
6. O APK de depuração será gerado em `app/build/outputs/apk/debug/app-debug.apk`.

## Alternativa: compilar na nuvem pelo GitHub

1. Crie um repositório no GitHub e envie o conteúdo desta pasta para ele.
2. Abra a aba **Actions** e selecione **Build Minhas Contas APK**.
3. Clique em **Run workflow** (ou envie um commit para `main`/`master`).
4. Quando a execução terminar, abra o artefato `MinhasContas-debug-apk` e baixe o ZIP que contém `app-debug.apk`.

## Observações

- O app não solicita permissões de internet nem acesso a contas bancárias.
- Os dados ficam neste aparelho e não são sincronizados com outros dispositivos. Limpar os dados do app pode apagar as contas salvas.
- O APK de depuração é para instalação e teste pessoal; não é assinado para publicação na Play Store.
