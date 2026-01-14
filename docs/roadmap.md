# Roadmap

## Fase 1: Base e ambiente
- Confirmar ambientes e dependencias por ferramenta.
- Definir estrutura de dados e convencoes de nomes.
- Criar configs base para areas de estudo e datasets.

## Fase 2: Pipelines InSAR (MVP)
- Implementar 1 pipeline funcional (ex: MintPy) com dataset pequeno.
- Padronizar outputs, logs e metadados.
- Criar testes smoke para cada pipeline.

## Fase 3: Integracao DL
- Extrair features derivadas de InSAR.
- Treinar modelos PyTorch com configuracao reproduzivel.
- Definir metricas e validacao.

## Fase 4: Escala e comparacao
- Adicionar pipelines adicionais (ISCE2, DePSI, SARvey, PyGMTSAR).
- Comparar produtos/metricas entre ferramentas.
- Consolidar resultados para escrita de artigos.
