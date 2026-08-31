Entregas de proyecto del curso "Data Science III: NLP & Deep Learning aplicado a Ciencia de Datos" de CoderHouse 2026

#learning_rate=0.001

#Forward/backward pass:

  history = model.fit(epochs=300, batch_size=32, x=x_train, y=y_train, validation_data=(x_test, y_test), callbacks=[early])

#Cálculo de error, gradientes:
Se utiliza el optimizador ADAM para actualizar gradientes 
  model.compile(optimizer='adam', loss='sparse_categorical_crossentropy', metrics=['accuracy'], learning_rate=0.001)
 

 
