OBSERVATÓRIO Ω — JSON SCHEMA 3.0

Estrutura criada a partir do snapshot legado v2.1.

ARQUIVOS
- manifest.json: mapa da arquitetura.
- config.json: regras gerais e limites de fragmentação.
- metrics.json: definições e snapshot atual dos indicadores.
- predictions.json: camada prospectiva P-xxx + referência ao S-002.
- hypotheses.json: hipóteses em validação, incluindo H-AI².
- checkpoints/checkpoints-001.json: checkpoints históricos (limite: 50).
- evidence/evidence-json-001.json: S-001 em diante (limite: 50; capacidade atual até S-050).
- legacy/observatorio-v2.1.json: cópia integral do JSON anterior.
- migration-report.json: contagens e verificação da migração.

REGRA DE FRAGMENTAÇÃO
- evidence-json-001.json: S-001 a S-050
- evidence-json-002.json: S-051 a S-100
- evidence-json-003.json: S-101 a S-150
- checkpoints-001.json: até 50 checkpoints
- checkpoints-002.json: checkpoints 51 a 100

Fragmentos fechados não recebem novos registros, salvo correção técnica documentada.
