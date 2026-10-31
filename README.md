# Ghosting Scouting — brainMachine 17728

1. `config.js` já está com o firebaseConfig do projeto ghosting-scouting.
2. Firebase Console → Authentication → ative **Google** e, em *Domínios autorizados*, adicione `SEUUSUARIO.github.io`.
3. Firestore Database → crie o banco → aba **Regras** → cole o conteúdo de `firestore.rules` (ou abra o site, clique em "Regras do Firebase" e use o botão Copiar) → Publicar.
4. Suba esta pasta para um repositório GitHub → Settings → Pages → Deploy from branch (main / root).
5. Abra o site, entre com Google e crie a equipe. Outros usuários pedem entrada pelo ID da equipe e você aprova na aba **Equipe**.

IA: aba **IA** → configure provedor/chave (ficam só no seu navegador). Se a API da NVIDIA bloquear por CORS, use um proxy ou OpenRouter (aceita navegador).
PDFs/manuais: aba **Biblioteca**. Não usa Firebase Storage (sem plano pago): o texto vai para o Firestore.
