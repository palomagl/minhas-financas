# Minhas Finanças

App de despesas do mês com login Google (Firebase Auth) e dados no Firestore.

## Configurar o Firebase
1. Authentication → Método de login → ative **Google**.
2. Authentication → Configurações → Domínios autorizados → adicione `palomagl.github.io`.
3. Firestore Database → crie o banco → aba **Regras** → cole o conteúdo de `firestore.rules` → Publicar.
4. ⚙ Configurações do projeto → Seus apps → Web (`</>`) → copie o `firebaseConfig` para `firebase-config.js`.

## Publicar
GitHub → Settings → Pages → Branch `main`, pasta `/ (root)` → Save.
Site: https://palomagl.github.io/minhas-financas/
