## Alan Araujo

Trabalho com segurança da informação e redes e também desenvolvo aplicações web. Dessa base veio o hábito de pensar primeiro em como um sistema pode ser atacado e só depois em como ele vai funcionar.

### App Estoque

<a href="https://github.com/app-estoque">
  <img src="https://github.com/app-estoque/.github/raw/main/profile/assets/capa.png" alt="App Estoque" width="100%" />
</a>

Sistema para cozinhas profissionais controlarem o estoque de alimentos por lote e validade. Parti de um problema comum em restaurantes e refeitórios: ninguém sabe qual lote vence primeiro e o desperdício não é medido. O app lê a validade do rótulo pela câmera, avisa o que está para vencer, indica qual lote deve sair primeiro e mostra quanto se perdeu em reais. Hoje ele está em piloto.

Alguns pontos do projeto:

- Cada empresa só acessa os próprios dados, com a regra aplicada no banco (Row Level Security) e coberta por testes automatizados.
- Entrada só por convite, com MFA e CAPTCHA. O histórico de movimentações não pode ser editado nem apagado.
- Um assistente no WhatsApp consulta e registra o estoque por texto, áudio ou foto e sempre pede confirmação antes de gravar.
- O projeto foi feito em 10 fases, e cada uma terminou com teste de invasão e correção de tudo o que apareceu.
- Funciona como app instalado no celular e mostra a última leitura do estoque mesmo sem internet.

O código é privado. Em [github.com/app-estoque](https://github.com/app-estoque) estão as telas do produto, com dados fictícios.

### Outros projetos

- [pentest-toolkit](https://github.com/alan-araaujo/pentest-toolkit): script que automatiza o reconhecimento inicial de um pentest com nmap e sugere os próximos passos.

### Ferramentas

TypeScript, Next.js, React, PostgreSQL, Supabase, Tailwind CSS, Playwright, GitHub Actions e Linux.
Em segurança: nmap, semgrep, gitleaks e testes baseados no OWASP Top 10.
