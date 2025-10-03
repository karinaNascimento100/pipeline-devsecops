# Pipeline DevSecOps — Relatório + Fluxo

Este repositório contém o relatório e o diagrama do Pipeline DevSecOps proposto na atividade.

## 📂 Conteúdo Principal

- **[RelatorioFluxoDevSecOps.pdf](https://github.com/karinaNascimento100/pipeline-devsecops/blob/main/RelatorioFluxoDevSecOps.pdf)** — versão final em PDF para entrega
- **[FluxoSeguroPipeline.drawio](https://github.com/karinaNascimento100/pipeline-devsecops/blob/main/FluxoSeguroPipeline.drawio)** — diagrama do fluxo (formato editável)
- **[FluxoSeguroPipeline.drawio.png](https://github.com/karinaNascimento100/pipeline-devsecops/blob/main/FluxoSeguroPipeline.drawio.png)** — imagem PNG do diagrama
- **[.github/workflows/ci.yml](.github/workflows/ci.yml)** — workflow GitHub Actions para geração automática de artefatos e execução de scans


## 📽️ Apresentação

- **Apresentação (download):** https://github.com/karinaNascimento100/pipeline-devsecops/blob/main/ApresentacaoDevSecOps.pptx
- **Link direto (raw):** https://raw.githubusercontent.com/karinaNascimento100/pipeline-devsecops/main/ApresentacaoDevSecOps.pptx

> Observação: o GitHub não pré-visualiza arquivos PPTX grandes (ex.: "Sorry about that, but we can’t show files that are this big right now"). Use o link raw para download.

- **Versão em PDF (download):** https://github.com/karinaNascimento100/pipeline-devsecops/blob/main/ApresentacaoDevSecOps.pdf
- **Link direto PDF (raw):** https://raw.githubusercontent.com/karinaNascimento100/pipeline-devsecops/main/ApresentacaoDevSecOps.pdf


Como usar localmente (exemplos):

- Exportar o diagrama Draw.io para PNG (usa drawio CLI via npx):

	```bash
	npx -y @drawio/cli -x -f png -o FluxoSeguroPipeline.drawio.png FluxoSeguroPipeline.drawio
	```

- Rodar tarefas do VS Code: `Terminal > Run Task...` → escolha "Exportar PDF" ou "Exportar Diagrama".

CI (GitHub Actions) já gera o PDF do relatório e o PNG do diagrama em cada push para `main`.


