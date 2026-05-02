# Aula-06-ES

Exercício Prático — Miro + Python

Tema: Cadastro e Aprovação de Usuário num App

Cenário: Um usuário tenta se cadastrar num aplicativo. O sistema valida o e-mail, verifica se já existe conta, envia confirmação e libera o acesso.

# Parte 1 — Miro

Monte o Diagrama de Atividades com Swimlanes para:

Raia	Responsabilidade
Usuário	Preenche formulário, confirma e-mail
Sistema	Valida dados, verifica duplicidade, envia e-mail

Pontos obrigatórios no diagrama:
- [ ] Nó inicial e nó final
- [ ] Pelo menos 2 decisões ([e-mail válido?], [já cadastrado?])
- [ ] Swimlanes definidas
- [ ] Transições rotuladas

# Parte 2 — Python no Colab/VS Code

Implemente o fluxo do diagrama em Python:

     """
    def cadastro_usuario(email: str, senha: str, email_ja_existe: bool, confirmou_email: bool) -> str:
    """
    TODO: Implemente baseado no seu diagrama do Miro.
    
    Fluxo esperado:
    1. Validar se email tem formato correto
    2. Verificar se email já está cadastrado
    3. Criar conta
    4. Enviar e-mail de confirmação
    5. Aguardar confirmação
    6. Liberar acesso (ou expirar cadastro)
    """

    # Seu código aqui!
    pass

    Testes (não apague!)
    print(cadastro_usuario("joao@email.com", "senha123", False, True))
    print(cadastro_usuario("email-invalido", "senha123", False, True))
    print(cadastro_usuario("joao@email.com", "senha123", True, True))
