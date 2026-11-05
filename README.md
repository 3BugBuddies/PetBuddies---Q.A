# Pet Buddies - Sprint 4 (Compliance, QA & Tests)

## Links de entrega
| Acesso | Link |
|---|---|
| Azure DevOps | [PetBuddies - Sprint 4 – Azure DevOps](https://dev.azure.com/RM565834/PetBuddies%20-%20Sprint%204%20%E2%80%93%20Azure%20DevOps) |
| Vídeo da automação | [PetBuddies - Sprint 4 – Video Youtube](https://youtu.be/dk14hYvgTJQ) |

## Testes manuais
Planejados e executados no Azure Boards / Test Plans: um plano por Sprint e uma suíte por PBI, com dados de entrada e saída (Parameter values), passos e resultados esperados e relatórios de Outcome e Run by. Os prints estão em /evidencias.

## Automação
- Ferramenta: Postman
- 4 casos automatizados: login válido, login com senha incorreta, cadastro de tutor e consulta do tutor
- Arquivos em /postman

## Como executar
1. Subir a API (https://github.com/3BugBuddies/PetBuddies-AI)
2. Importar a collection e o environment no Postman
3. Preencher a senha da conta de teste no environment
4. Rodar a collection no Collection Runner (Functional, 1 iteração)
