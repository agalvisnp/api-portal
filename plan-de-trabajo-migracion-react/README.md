# Plan de trabajo migracion React

**Plan de Trabajo Migración REACT del Developer Portal**

Como sabemos hay un trabajo ya adelantado de una primera fase de pruebas de esta migración en el servidor de Pantheon en la rama william, así que se continuara el proceso de este de VueJs a React en esta rama, antes de continuar con esto se debe:

* Actualizar la BD y el código Respecto al portal actualmente\
  ![](../.gitbook/assets/0)
* Ya después de esto implementar la parte ya hecha en un tipo de contenido, se eligió How it works ya que la cantidad de componentes es baja y hace más breve su implementación

Para este último ítem hay que tener un plan específico de este

1. Aunque ya se estableció que el portal se puede tener tanto VueJs y React activados\
   ![](../.gitbook/assets/1)\
   Se debe empezar a establecer la conexión entre el servicio del tipo de contenido y React para poder usar este en la creación de los componentes en React
2.  Cuando ya se realiza esta conexión se debe empezar a armar la estructura de los componentes del how it works como es el menu:\
    ![](../.gitbook/assets/2)\
    El componente de multistep donde se ven el texto, botón y video\


    <figure><img src="../.gitbook/assets/3" alt=""><figcaption></figcaption></figure>
3. Luego de asegurarnos que los componentes se generan adecuadamente en estructura se verifican que los estilos y funcionamiento del multistep en cuanto a la funcionalidad de siguiente, atrás y final\
   ![](../.gitbook/assets/4)
4.  Luego de esto se debe ya armar el despliegue completo integrando los componentes anteriormente mencionados\


    <figure><img src="../.gitbook/assets/5" alt=""><figcaption></figcaption></figure>
5. Ya terminando este y haciendo las pruebas y salen satisfactoriamente, se procedería a continuar con los demás tipos de contenido, taxonomías y despliegues como el home, categorías y demás\
