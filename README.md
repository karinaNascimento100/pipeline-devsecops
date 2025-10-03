# Pipeline DevSecOps — Relatório + Fluxo

Este repositório contém o relatório e o diagrama do Pipeline DevSecOps proposto na atividade.

Conteúdo principal:
- `RelatorioFluxoDevSecOps.odt` — relatório editável (fonte)
- `RelatorioFluxoDevSecOps.pdf` — versão PDF para entrega
- `FluxoSeguroPipeline.drawio` / `FluxoSeguroPipeline.drawio.png` — diagrama do fluxo
- `.github/workflows/ci.yml` — workflow de CI para gerar PDF/PNG e rodar scans

Como usar localmente (exemplos):

- Exportar PDF do ODT via LibreOffice:

	```bash
	libreoffice --headless --convert-to pdf docs/RelatorioFluxoDevSecOps.odt --outdir docs
	```

- Exportar o diagrama Draw.io para PNG (usa drawio CLI via npx):

	```bash
	npx -y @drawio/cli -x -f png -o docs/FluxoSeguroPipeline.drawio.png FluxoSeguroPipeline.drawio
	```

- Rodar tarefas do VS Code: `Terminal > Run Task...` → escolha "Exportar PDF" ou "Exportar Diagrama".

CI (GitHub Actions) já gera o PDF do relatório e o PNG do diagrama em cada push para `main`.

Licença: MIT (arquivo `LICENSE`).
