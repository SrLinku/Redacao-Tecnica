# Proteção de Dados Sensíveis - Front-End

Este trabalho foi desenvolvido com base no filme _Snowden_, para a disciplina de Front-End do curso de ADS (Análise e Desenvolvimento de Sistemas).

## 🎯 Reflexão (10 a 15 linhas)

O filme Snowden evidencia os riscos associados à vigilância em massa e à manipulação indevida de informações pessoais, trazendo à tona discussões fundamentais sobre segurança da informação e privacidade. No contexto do desenvolvimento de sistemas, especialmente no front-end, esse alerta se traduz na necessidade de práticas rigorosas para proteger os dados dos usuários.

O desenvolvedor front-end desempenha papel crucial nesse cenário, pois atua diretamente na interface onde dados sensíveis como CPF, e-mail, localização e senhas são coletados. É imprescindível que esses dados sejam requisitados apenas quando estritamente necessários, com base em princípios de minimização de dados e consentimento explícito, conforme previsto na Lei Geral de Proteção de Dados (LGPD).

Além disso, recomenda-se a utilização obrigatória de conexões seguras (HTTPS), a não persistência de dados sensíveis em ambientes inseguros como localStorage ou sessionStorage, e a exclusão de informações críticas de arquivos client-side acessíveis ao usuário. A validação das entradas no lado do cliente deve ser implementada para mitigar riscos de ataques como Cross-Site Scripting (XSS), sempre em conjunto com validações no servidor.

Em última instância, como revela o filme, negligências na camada de interface podem expor sistemas inteiros a espionagem e vazamentos, reforçando que a segurança deve ser uma prioridade desde a construção da interface.

## ✅ Checklist de Boas Práticas

- [x] Informar o usuário sobre como os dados serão usados
- [x] Utilizar HTTPS sempre que houver envio de dados
- [x] Evitar armazenar senhas em campos visíveis
- [x] Nunca salvar dados sensíveis no LocalStorage
- [x] Sanitizar e validar entradas do usuário
- [x] Utilizar autenticação de múltiplos fatores quando possível
- [x] Evitar exibir dados sensíveis no frontend

## 📄 Como visualizar

Abra o arquivo `index.html` no navegador para ver o exemplo com campos comentados, checklist e modal de aviso.
