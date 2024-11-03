Para ejecutar el comando /mutant/ y agregar un nuevo ADN a la base de datos, dirígete a la URL de Render: https://parcialds-1.onrender.com/mutant/. En el cuerpo de la solicitud, incluye un JSON con el siguiente formato: {dna: "arreglo de strings NxN"}. Las letras dentro del String deben ser [ATCG]. Si el ADN enviado pertenece a un mutante, recibirás un HTTP OK; si no, recibirás un HTTP FORBIDDEN.

Si el arreglo no tiene el tamaño correcto, si alguna letra no es válida, o si el ADN ya ha sido registrado previamente, la API generará un error de inmediato y no se realizará ningún guardado ni análisis.

Para ejecutar el comando /stats, accede a la siguiente URL: https://parcialds-1.onrender.com/mutant/stats. Allí podrás ver las estadísticas desglosadas por la cantidad de humanos, la cantidad de mutantes y la proporción de mutantes por cada humano.
