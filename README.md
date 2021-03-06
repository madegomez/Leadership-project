# Leadership_project
Data and results for leadership project

El archivo Corpus_Ont_Semilla_Original.zip contiene los 288 documentos originales. Para la tarea de enriquecimiento se tiene 33 texto, los restantes contienen información que ya está en la ontología semilla. La clasificación de textos (entre completamente asociado o no a la ontología semilla) considero que si el texto tenía como mínimo un concepto que no estuviera presente en la ontología, entonces era un documento no completamente asociado a la ontología semilla (o empleado en la tarea de enriquecimiento). Por lo anterior, un documento con categoria 'no completamente asociado a la ontología semilla' puede contener algunos constructos que si están dentro del modelo conceptual y otros que no están presentes.

El archivo Rev_org_txt.zip tiene las etiquetas que hicieron los revisores. Cada txt tiene la estructura concept:::term1----term2----term3 donde 'concept' hace referencia al concepto que el etiquteador identificó y 'termX' sugiere los términos que el revisor relacionó.

En Kappa_alpha.txt está el indice Kappa para los 106 conceptos analizados por los etiquetadores. Los conceptos analizados son constructos que pueden o no estar en la ontología semilla. Algunos conceptos tienen un indice Kappa igual a cero, por ende, los etiquetadores tuvieron un acuerdo insignificante en cuanto a los términos a asociados a dichos constructos. El indice Kappa promedio es casi perfecto con un valor de 0.8458675330278812 para los 106 conceptos cuando se excluyen los constructos con valor menor a 0.41.

El indice Kappa para los datos con categoria 'completamete asociado a la ontología semilla' están en Kappa_alpha_semilla.txt, el indice Kappa promedio es 0.8161540711017236 considerando valores superiores a 0.41. El indice Kappa para los datos con categoria 'no completamente asociado a la ontología semilla' es 0.923068339415609 haciendo el filtrado mencionado previamente, estos valores están en el archivo Kappa_alpha_enriquecimiento.txt

El archivo Siglas_originales.txt tiene la estructura --> sigla:termino_definitivo.

El archivo Name_clases_originales.txt tiene las clases, subclases y instancias de la ontología del liderazgo. Estas etiquetas están preprocesadas.

El archivo Name_clases_alternativas_completas.txt tiene las alternativas de las etiquetas presentadas en el documento anterior. Todas las ternativas están preprocesadas.

En Stopwords_compilation.txt están las stopwords que se usaron en este proyecto.

En Corpus_semilla_v9.txt contiene los 255 documentos con categoria 'completamente asociado a la ontología semilla' después de preprocesamiento, además en Corpus_enriquecimiento_v9.txt están los 33 textos que se emplean en enriquecimiento. Todos los documentos están separados por sentencias, en particular, hay 46749 oraciones en la primera categoria y 8365 en la segunda.

En Sentences_relevence_semilla.txt están los nombres de cada documento con categoria 'completamente asociado a la ontología semilla' y los números de las respectivas sentencias relevantes. En Sentences_relevence_enriquecimiento.txt se asocian los textos en categoria 'no completamente asociado a la ontología semilla'. Es así como en la primera categoria hay 9304 sentencias relevantes y 2747 en la segunda.
