# Leadership_project
Data for leadership project

El archivo Corpus_Ont_Semilla_Original.zip contiene los 293 documentos originales.

El archivo Corpus_Ont_Semilla_v7.zip contiene los 293 documentos después de preprocesamiento. Los documentos están separados por sentencias. En este corpus existen 8333 unigramas unicos.

En Sentences_relevence.txt están los nombres de cada documento y los números que corresponde a las sentencias relevantes dentro de cada texto.

El archivo Siglas_originales.txt tiene la estructura --> sigla:termino_definitivo.

El archivo Name_clases_originales.txt tiene las clases, subclases y instancias de la ontología del liderazgo. Estas etiquetas están preprocesadas.

El archivo Name_clases_alternativas_completas.txt tiene las alternativas de las etiquetas presentadas en el documetno anterior. Todas las ternativas están preoprocesadas.

En Kappa_alpha.txt está el indice Kappa para los 106 conceptos analizados por los etiquetadores. Los conceptos analizados son constructos que pueden o no estar en la ontología semilla. Algunos conceptos tienen un indice Kappa igual a cero, por ende, los etiquetadores tuvieron un acuerdo insignificante en cuanto a los términos a asociados a dichos constructos. Al contabilizar los 106 conceptos se obtiene un indice Kappa promedio de 0.765050980459272. Si se excluyen los conceptos con valor menor a 0.41, el indice Kappa promedio llega a ser casi perfecto con un valor de 0.8456228421052632


