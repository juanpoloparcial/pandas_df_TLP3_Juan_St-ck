creacion de nuestro entorno virtual:
  python -m venv env
activamos nuestro entorno
  ./env/Scripts/activated

Instalamos las pandas:
  pip install pandas

Chequeamos que se haya instalado correctamente: 
  pip list

creamos la conexión a la base de datos brindada.
  conn = sqlite3.connect("Nombre_de_la_Base_de_datos".sqlite")
    conn = sqlite3.connect("Salaries.sqlite")

Creamos el dataframe con los datos del datasets
  df = pd.read_sql_query("SELECT * FROM Salaries", conn)
  conn.close()

Realizamos los ejercicios siguiendo las instrucciones solicitadas en cada enunuciado.

