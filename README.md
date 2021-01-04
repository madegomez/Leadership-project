# Leadership_project
Data for leadership project

El archivo Corpus_Ont_Semilla_Original.zip contiene los 293 documentos originales. Para la tarea de enriquecimiento se tiene 35 texto, los restantes contienen información que ya está en la ontología semilla. La clasificación de textos (entre asociados o no a la ontología semilla) considero que si el texto tenía como mínimo un conceptos que no estuviera presente en la ontología, entonces era un documento no asociado a la ontología semilla (o empleado en la tarea de enriquecimiento). Por lo anterior, un documento con categoria 'no asociado a la ontología semilla' puede contener algunos constructos que si están dentro del modelo conceptual.

El archivo Corpus_Ont_Semilla_Original_v7.txt contiene los 293 documentos después de preprocesamiento. Los documentos están separados por sentencias. En este corpus existen 8333 unigramas unicos.

En Corpus_segmentation.txt se indica si el documento corresponde al corpus asociado a la ontología semilla ó fue usado para enriquecer el modelo.

En Sentences_relevence.txt están los nombres de cada documento y los números que corresponde a las sentencias relevantes dentro de cada texto.

El archivo Siglas_originales.txt tiene la estructura --> sigla:termino_definitivo.

El archivo Name_clases_originales.txt tiene las clases, subclases y instancias de la ontología del liderazgo. Estas etiquetas están preprocesadas.

El archivo Name_clases_alternativas_completas.txt tiene las alternativas de las etiquetas presentadas en el documetno anterior. Todas las ternativas están preoprocesadas.

En Kappa_alpha.txt está el indice Kappa para los 106 conceptos analizados por los etiquetadores. Los conceptos analizados son constructos que pueden o no estar en la ontología semilla. Algunos conceptos tienen un indice Kappa igual a cero, por ende, los etiquetadores tuvieron un acuerdo insignificante en cuanto a los términos a asociados a dichos constructos. Al contabilizar los 106 conceptos se obtiene un indice Kappa promedio de 0.765050980459272. Si se excluyen los conceptos con valor menor a 0.41, el indice Kappa promedio llega a ser casi perfecto con un valor de 0.8456228421052632


