# Curriculum Vitae - David Ibarra Luna

Repositorio con diferentes versiones de mi CV en LaTeX, cada una enfocada en un area profesional distinta. Los PDFs se compilan automaticamente con GitHub Actions al actualizar los archivos `.tex`.

## CVs disponibles

- [General](general_cv/cv.pdf) - Resumen completo de mi formacion y experiencia.
- [Data Science](data_science_cv/cv.pdf) - Enfocado en analisis de datos, machine learning y desarrollo en Python.
- [Laboratorio](lab_tech_cv/cv.pdf) - Orientado a quimica industrial, ciencia de materiales y trabajo de laboratorio.

## Compilacion local

Cada carpeta tiene un Makefile. Para compilar localmente:

```bash
cd general_cv  # o data_science_cv, lab_tech_cv
make
```

Esto genera `cv.pdf` en la carpeta correspondiente. Para limpiar archivos temporales:

```bash
make clean
```

## Estructura

```
CVs_repo/
├── general_cv/        # CV general
├── data_science_cv/   # CV de data science
├── lab_tech_cv/       # CV de laboratorio
└── .github/workflows/ # GitHub Actions para compilacion automatica
```

Base de plantilla: https://github.com/jitinnair1/autoCV - autoCV