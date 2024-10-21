# Python_Programacion_lineal_Industria_Alimentaria
Caso: Industria Alimentaria - Bebida Nutricional

### Desarrollo de una Bebida Nutricional

#### Contexto
Una agencia de cooperación internacional te ha contratado para desarrollar una bebida nutricional destinada a complementar los desayunos escolares en zonas rurales. La bebida debe ser a base de soya, maíz y avena y debe ser nutricionalmente rica y económica.

#### Objetivo
Desarrollar un modelo de programación lineal para minimizar el costo de producción de la bebida nutricional, cumpliendo con los requerimientos nutricionales específicos.

#### Variables de Decisión
- Cantidad de soya, maíz y avena (en gramos) a utilizar en la bebida.

#### Función Objetivo
- Minimizar el costo total de los ingredientes: `costo = 0.035*soya + 0.025*maiz + 0.040*avena`.

#### Restricciones
1. **Peso Total por Porción**:
   - La suma de los ingredientes debe ser igual a 50 gramos por porción.
2. **Calorías**:
   - La bebida debe tener al menos 150 kcal por porción. Se consideran 4.46 kcal/g para la soya, 0.95 kcal/g para el maíz y 3.74 kcal/g para la avena.
3. **Proteínas**:
   - La bebida debe tener al menos 10 g de proteínas por porción. Se consideran 0.360 g/g de proteína para la soya, 0.037 g/g para el maíz y 0.132 g/g para la avena.
4. **Carbohidratos**:
   - La bebida debe tener al menos 28 g de carbohidratos por porción. Se consideran 0.30 g/g de carbohidratos para la soya, 0.74 g/g para el maíz y 0.68 g/g para la avena.


Este ejercicio desafía a los estudiantes a aplicar conceptos de programación lineal en un contexto real, destacando la importancia de la nutrición y la economía en la planificación alimentaria.


