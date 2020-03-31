# Proyecto_Personal_004FQ
**Deploy de un sistema de recomendación con IBM - Watson**

# **Fuentes y Datos:**

1. http://www.cs.cornell.edu/people/pabo/movie-review-data/

# **Worflow**

1. **Carga de API Watson**: *WatsonMachineLearningAPICliente*
2. **Creación de Credenciales**
3. **Cliente:** se crea una variable para guardar el objeto cliente con las credenciales necesarias y otra que guarda las propiedades del modelo, así como mi autoría.
4. **Entrenamiento:** se crea un **pipeline** para el entrenamiento del modelo utilizando como vectorizador **TfidfVectorizer**
5. **Subir el modelo:** utilizo client.repository.store_model
6. **Carga**
7. **Resultados:** **classification_report

# **Modelos**

1. **WatsonMachineLearningAPIClient**
