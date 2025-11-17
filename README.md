Base de Datos (Calories)

Esta es una base de datos sintetica,  es decir, fue creada apartir de otra. Asimismo, la información contenida es acerca de la predicción de calorias quemadas teniendo en cuenta características biométicas como lo son la edad, peso y temperatura corporal. Por ende, no son datos reales.

Cuenta con 750000 filas y 9 columnas.

Columnas:

id:identifica a cada persona, ayudando así, a diferenciarlas y a la organización de la base.

Sex:Categoriza el género del usuario y permite obtener mejores resultados, pues las diferencias fisiológicas inciden en calorias quemadas. 

Age: Característica cuantitativa, La edad (en años) afecta el metabolismo, además el gasto energético del ser humano.

Height:Característica cuantitativa,La altura (en cm) influye en el índice de masa corporal (IMC) afectando indirectamente a la quema de energía del individuo.

Weight:Característica cuantitativa,El peso (en Kg) del usuario es un factor clave para la determinación del gasto caloríco.

Duration:Característica cuantitativa,La duración (en min) de la persona haciendo ejercicio es una claro determinante del gasto enérgetico.

Heart_Rate:Característica cuantitativa, La frecuencia cardiaca presentada durante la práctica (en lpm) refleja el esfuerzo físico.

Body_Temp:Característica cuantitativa, La temperatura corporal (° celsius) durante la actividad puede señalar la tasa metabólica o la respuesta fisiológica al esfuerzo físico.

Calories:Es la predicción de cuantas calorias va a quemar el usuario con relación las caracteristicas biométricas.


Base de Datos (Alzheimer's Disease)

Esta base de datos contiene información médica de pacientes reales para la investigación del Alzheimer, relaciona datos demográficos, estilo de vida, antecedentes familiares,historial clínico y resultado de exámenes cognitivos del usuario.

Contiene 2149 filas y 35 filas.

Columnas:

PatientID:Identificador único de cada paciente (4751 a 6900).

DoctorInCharge:Columna confidencial sin valor analítico.

Age:Edad del paciente (60 a 90 años).

Gender:Género del paciente (0: Masculino, 1: Femenino).
EthnicityEtnia del paciente {0: Caucásico, 1: Afroamericano, 2: Asiático, 3: Otro}.

EducationLevel:	Nivel educativo {0: Ninguno, 1: Secundaria, 2: Licenciatura, 3: Superior}.

BMI:Índice de Masa Corporal (15 a 40).

Smoking:El paciente fuma (0: No, 1: Sí).

AlcoholConsumption:Consumo semanal de alcohol (0 a 20 unidades).

PhysicalActivity:Actividad física semanal (0 a 10 horas).

DietQuality:Puntuación de la calidad de la dieta (0 a 10).

SleepQuality:Puntuación de la calidad del sueño (4 a 10).

FamilyHistoryAlzheimers:Antecedentes familiares de Alzheimer	{0: No, 1: Sí}.

CardiovascularDisease:Presencia de enfermedad cardiovascular {0: No, 1: Sí}.

Diabetes:Presencia de diabetes	{0: No, 1: Sí}.

Depression:Presencia de depresión	{0: No, 1: Sí}.

HeadInjury:Historial de lesión en la cabeza {0: No, 1: Sí}

Hypertension:Presencia de hipertensión (presión alta) 	{0: No, 1: Sí}.

SystolicBP:Presión arterial sistólica	(90 a 180 mmHg).

DiastolicBP:Presión arterial diastólica (60 a 120 mmHg).

CholesterolTotal:Niveles de colesterol total (150 a 300 mg/dL).

CholesterolLDL:Colesterol LDL ("malo")	(50 a 200 mg/dL).

CholesterolHDL:Colesterol HDL ("bueno")	(20 a 100 mg/dL).

CholesterolTriglycerides:	Niveles de triglicéridos (50 a 400 mg/dL).

MMSE:	Puntuación del Mini-Mental State Examination  [0 a 30 (Menor puntaje = Deterioro)]

FunctionalAssessment:	Puntuación de evaluación funcional.	[0 a 10 (Menor puntaje = Deterioro)]

MemoryComplaints:	Presencia de quejas de memoria{0: No, 1: Sí}.

BehavioralProblems:	Presencia de problemas de comportamiento	{0: No, 1: Sí}.

ADL:	Puntuación de Actividades de la Vida Diaria	[0 a 10 (Menor puntaje = Deterioro)].

Confusion:Presencia de confusión {0: No, 1: Sí}.

Disorientation:Presencia de desorientación {0: No, 1: Sí}

PersonalityChanges:	Presencia de cambios de personalidad 	{0: No, 1: Sí}

DifficultyCompletingTasks:	Presencia de dificultad para completar tareas	{0: No, 1: Sí}.

Forgetfulness:	Perdida de la memoria {0: No, 1: Sí}.

Diagnosis:	Diagnóstico de Alzheimer (Variable Objetivo) 	{0: No, 1: Sí}.

Heart Disease Dataset (Kaggle – UCI Heart Disease)
Conjunto de datos clínicos usados para evaluar factores relacionados con enfermedades cardíacas

Columnas y su significado:
	
	1.	age – Edad del paciente en años.
	
	2.	sex – Sexo del paciente (0 = mujer, 1 = hombre).
	
	3.	cp – Tipo de dolor en el pecho (chest pain type).
	
	•	0: angina típica
	
	•	1: angina atípica
	
	•	2: dolor no anginoso
	
	•	3: asintomático
	
	4.	trestbps – Presión arterial en reposo (mm Hg).
	
	5.	chol – Nivel de colesterol sérico (mg/dl).
	
	6.	fbs – Glucosa en ayunas > 120 mg/dl (1 = sí, 0 = no).
	
	7.	restecg – Resultados del electrocardiograma en reposo.
	
	8.	thalach – Frecuencia cardíaca máxima alcanzada.
	
	9.	exang – Angina inducida por ejercicio (1 = sí, 0 = no).
	
	10.	oldpeak – Depresión ST inducida por ejercicio comparada con reposo.
	
	11.	slope – Pendiente del segmento ST en el peak del ejercicio.
	
	12.	ca – Número de vasos mayores coloreados por fluoroscopía (0–3).
	
	13.	thal – Resultado de la prueba de tálamo (3 = normal, 6 = defecto fijo, 7 = defecto reversible).
	
	14.	target – Presencia de enfermedad cardíaca (0 = no, 1 = sí).

Indian Liver Patient Dataset (ILPD)

Datos clínicos usados para estudiar indicadores asociados a enfermedades del hígado

Columnas y su significado:
	1.	Age – Edad del paciente en años.
	
	2.	Gender – Sexo del paciente (Male/Female).
	
	3.	Total_Bilirubin – Bilirrubina total en sangre.
	
	4.	Direct_Bilirubin – Bilirrubina directa.
	
	5.	Alkaline_Phosphotase – Fosfatasa alcalina (enzima hepática).
	
	6.	Alamine_Aminotransferase (SGPT) – Enzima ALT, marcador de daño hepático.
	
	7.	Aspartate_Aminotransferase (SGOT) – Enzima AST, otro marcador de daño hepático.
	
	8.	Total_Proteins – Proteínas totales en sangre.
	
	9.	Albumin – Albúmina sérica (proteína producida por el hígado).
	
	10.	Albumin_and_Globulin_Ratio – Relación albúmina / globulina.
	
	11.	Dataset – Clasificación del paciente según diagnóstico:

	1 = presencia de enfermedad hepática
	
	2 = ausencia de enfermedad hepática
