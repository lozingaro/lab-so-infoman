# Progetto per il Laboratorio di Sistemi Operativi 
## Anno Accademico 2019/2020

In questo spazio sono conservati contenuti utili per la documentazione del progetto del corso di Sistemi Operativi per la Laurea Triennale in Informatica per il management dell'Università di Bologna, anno accademico 2019-2020.
I contenuti possono servire per scrivere documentazioni simili usando [il template LaTeX](docs/main.tex) e per accedere al [codice delle interfacce pubbliche](docs/assets/listings/) necessarie ad implementare il sistema descritto nella documentazione.

### Getting Started

Clonare il codice con il comando `git`:

```bash
git clone https://github.com/szingaro/lab-so-project-2020
```

Ottenere il PDF della documentazione compilando il codice contenuto in _docs/_ con `pdflatex` e `bibtex`:

```bash
cd docs
pdflatex main
bibtex main
pdflatex main
pdflatex main
```

### Build with

- pdfTeX 3.14159265-2.6-1.40.20 (TeX Live 2019)
- OpenJDK Runtime Environment (build 13+33)
- Jolie 1.9.0 (C) 2006-2020 the Jolie team

### Autori

- [@szingaro](https://github.com/szingaro)

### Licenza

Il progetto è rilasciato con licenza GNU v3; per maggiori dettagli consultare il file [LICENSE](LICENSE).
