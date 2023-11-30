# HelloWorldNov_23
Aprender las bases de Github
#Encabezado
##Lucia Paulina Vargas Villalobos A0119124
### ITC 

#Tipos de letra

**Bold**
*Italic*
🐈‍⬛ 🦋 :t 

#Lista Ordenada 
1. Pizza Pepperoni
2. Pizza Queso
3. Maria, Hector, Luis, Diego (Encargados)

 #Lista desordenada actividades en vacaciones
 - Dormir
 - Ver Series
 - Ver Peliculas
 - Estudiar
 - Trabajar $$
 - Posadas 
 - Familia - convivir con ella 
 - Ir a linares - Glorias de Linares - visitar a Salvador
 - Cocina 

-----
 
  # Codigo
  ```
int main() {
    // Declaración del objeto de la clase Reloj
    Reloj evento;
    
    int opcion, hr, min;
    cout << evento.str()<< endl;

    
   evento.setHora(0);
  evento.setMinutos(0);
    
    cout << "Rolex" << endl;
    cout << evento.str()<< endl;
    
    
    // 1º Inicializar la vccc - la función menu( ) retorna la opcion elegida por el usuario
    opcion = menu();
    
    while (opcion != 4){ // 2º Incluir la condición la vccc
        
        if (opcion == 1){
            // leer hora
            //            cout << "Ingresa la nueva hora:";
            cin >> hr;
            evento.setHora(hr);
        }
        else if (opcion == 2){
            // leer minutos
            //            cout << "Ingresa los nuevos minutos:";
            cin >> min;
            evento.setMinutos(min);
        }
        else if (opcion == 3){
            evento.incrementaMinutos();
        }
        
        else
            
            cout << "Opcion incorrecta\n";
        
        cout << evento.str( ) << endl;
        opcion = menu(); // 3º Actualizar la vccc dentro del ciclo
    }
    
    //lamar metodos get
    evento.getHora();
    evento.getMinutos();
    
    return 0;
}

  ```

# 1. [Markdown](https://www.markdownguide.org/cheat-sheet/)


#Imagen 
![Imagen](https://media.istockphoto.com/id/1406932980/photo/santa-claus-in-eyeglasses-is-looking-at-camera-and-smiling-on-gray-background.jpg?b=1&s=170667a&w=0&k=20&c=0Xto80P2gjgSEkA8XhhZSGbT2G7a0sXBQlsuhF93Wds=)

![Pizza](https://www.pizzaiolo.mx/img/blog/una-pizza-con-queso-derretido--Pizza-blog.jpg)
#Planeacion de estudiar c++
| Fecha | Description |
| ----- | ------ |
| Diciembre | Apuntes 1 y 2 c++|
|  Enero | POO - Presentación - 2 - programar al menos 3 hrs a la semana |
| Febrero | POO - Presentacion 3 - progreamar al menos 3 hrs a la semana |
| Marzo | POO - Presentacion 4 - progreamar al menos 3 hrs a la semana |
