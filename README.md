# NETAUTH Lab 3 report

`main.tex` is the report source. Compile it with pdfLaTeX (`latexmk -pdf main.tex`) or the default pdfLaTeX compiler in Overleaf.

- `figures/`: selected screenshots from the laboratory, numbered as captured.
- `artifacts/`: the five requested submission files: `rootCA.crt`, `server.csr`, `server.crt`, `server.cnf`, and `server.ext`.
- `main.pdf`: compiled report.

The final certificate is documented in screenshots 11 and 12. Screenshot 10 was an earlier issuance and is deliberately excluded. No private key is included. The CSR configuration requests `netauth.server`; the CA issuance extension also includes `sec-lab.local`, reflecting the handout's different final-checklist name.
