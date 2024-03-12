2 formas de guardar un modelo en keras.

Forma #1:
model.save('modelo.h5')

Forma #2:
from google.colab import files

files.download('my_model.keras')