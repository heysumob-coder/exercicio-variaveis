Exercício: Camaleão do CSS - Variáveis

Conteúdo:
- index.html  -> Estrutura do card
- style.css   -> Arquivo onde os alunos deverão alterar as variáveis
- scripts/grade.js -> Autograder simples para CI (verifica uso de variáveis)
- .github/workflows/grade.yml -> Workflow para rodar o autograder no GitHub Actions

Instruções rápidas para professor:
1) Crie um repositório template no GitHub com este conteúdo.
2) Use GitHub Classroom (ou crie manually) para distribuir aos alunos.
3) O workflow roda automaticamente quando o aluno fizer push e mostra resultados em Actions/Checks.

Objetivos para os alunos:
- Alterar apenas as variáveis em :root (ex.: --cor-principal, --borda-raio) para ver mudança no card.
- Garantir que var(--cor-principal) é usado em .foto, h1 e .botao.
