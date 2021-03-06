[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7773536&assignment_repo_type=AssignmentRepo)
# Primer Trabajo de Actuación en Clase
## Consigna

Encontrar los errores en el código de Terraform y corregirlos. El código despliega los siguientes objetos:

* Un VPC
* Dos subnets
* Una instancia EC2
* Una Route Table
* Un Internet Gateway
* Un LoadBalancer, target groups y rules.

## Definición de terminado

El resultado debe ser la web de "Caffé" visualizada desde la url del LoadBalancer obtenida del OUTPUT. 

![caffe img](./img/caffe.png)

---
Damian Alvarez, Eric Borba
---

    .....
Coreciones realizadas
    .....
 
- Cambiamos el perfil en Terraform.tfvars y en variables.tf
- Corregimos los puertos "88" por "80" en el low balancer
- Modificamos el CIDR en el route_table a la 0.0.0.0/0
- Se agrega la subnetid a la instancia
- Cambiamos el archivo y ruta de private_key a uno propio


Solucion: Se pudo acceder a la pagina web de la instancia a travez del LB.

