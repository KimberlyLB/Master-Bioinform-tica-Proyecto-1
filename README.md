# Master-Bioinformatica-Proyecto-1
Análisis bioinformático de secuencias mediante herramientas para procesar datos biológicos.
## Descripción
Proyecto de análisis bioinformático de secuencias mediante herramientas de procesamiento de datos biológicos.
## Objetivos
- Analizar secuencias biológicas  
- Procesar archivos FASTA  
- Generar resultados reproducibles  
## Estructura del proyecto
- data/: datos de entrada  
- scripts/: código fuente  
- results/: resultados  
- notebooks/: análisis interactivo  
- docs/: documentación
## Datos de entrada
El programa requiere un archivo en formato FASTA (.fasta o .fa) que contenga las secuencias biológicas a analizar.
### Ubicación esperada
El archivo debe colocarse en la carpeta:
data/sample.fasta
### Formato del archivo FASTA
Ejemplo de estructura:
```fasta
>Secuencia_1
ATGCGTAGCTAG
>Secuencia_2
ATCGATCGATCG
## Requisitos
- Python 3  
- Biopython  
## Instalación
```bash
pip install -r requirements.txt
