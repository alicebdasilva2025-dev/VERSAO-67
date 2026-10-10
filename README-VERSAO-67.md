# LiDire — versão 67

## Alterações
- Na criação e edição de compromissos, o campo Local agora possui um seletor de lugares frequentes.
- Ao escolher um lugar frequente, o nome preenche o campo Local e o endereço cadastrado preenche automaticamente o campo Endereço.
- Na tela Perfil, o botão “Editar Perfil” foi removido da área da foto e substituído por “Editar endereço”/“Cadastrar endereço”.
- O botão duplicado de edição de endereço na seção de informações pessoais foi removido.
- A edição do endereço residencial usa o endpoint existente `/api/profile` e mantém atualização local como fallback.

## Verificação
- `node --check app.js` executado sem erros de sintaxe.
- Não foram realizados testes integrados no Cloudflare ou em dispositivo real.
