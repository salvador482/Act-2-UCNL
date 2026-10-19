# Act-2-UCNL
Primera gestión escuela 
# Definición de la clase Estudiante
class Estudiante:
    def __init__(self, nombre, matricula, edad):
        self.nombre = nombre
        self.matricula = matricula
        self.edad = edad

    def mostrar_informacion(self):
        print("Nombre:", self.nombre)
        print("Matrícula:", self.matricula)
        print("Edad:", self.edad, "años")
        print("----------------------------")

    def obtener_nombre(self):
        return self.nombre


# Programa principal
def main():
    estudiante1 = Estudiante("Carlos Ramirez", "A001", 20)
    estudiante2 = Estudiante("Maria Lopez", "A002", 22)
    estudiante3 = Estudiante("Jose Hernandez", "A003", 19)

    print("SISTEMA DE GESTION DE ESTUDIANTES")
    print("===============================")

    estudiante1.mostrar_informacion()
    estudiante2.mostrar_informacion()
    estudiante3.mostrar_informacion()

    print("Consulta individual:")
    print("Nombre del primer estudiante:", estudiante1.obtener_nombre())


if __name__ == "__main__":
    main()

