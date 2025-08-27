# Multi-Repo Live

Este proyecto tiene como objetivo centralizar y organizar la infraestructura mediante múltiples repositorios,
utilizando Terraform para despliegues en AWS, con un enfoque modular y escalable.

## 🚀 Descripción

- **Infraestructura como código (IaC):** Definición de entornos con Terraform.  
- **Multi-repo:** Separación de módulos por servicios, para mayor escalabilidad y mantenibilidad.  
- **Automatización:** Scripts y configuraciones listas para CI/CD.  
- **Cloud:** Despliegue en AWS, siguiendo buenas prácticas de seguridad y gobernanza.


## 🔧 Requisitos

- Terraform >= 1.0  
- AWS CLI configurado  
- Credenciales IAM con permisos adecuados  

## ⚙️ Uso

1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/tuusuario/multi-repo-live.git
   cd multi-repo-live
   ```

2. Inicializar Terraform:  
   ```bash
   terraform init
   ```

3. Revisar el plan de ejecución:  
   ```bash
   terraform plan
   ```

4. Aplicar cambios:  
   ```bash
   terraform apply
   ```

## 📌 Buenas Prácticas

- Mantener **nombres descriptivos** en recursos.  
- Usar **variables y outputs** para evitar duplicidad.  
- Proteger ramas principales con **pull requests**.  
- Implementar **versionado** en módulos compartidos.  

## 👥 Contribución

1. Hacer un fork del repositorio  
2. Crear una nueva rama (`feature/nueva-funcionalidad`)  
3. Hacer commit de los cambios  
4. Subir la rama y abrir un Pull Request  

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Libre para usar y modificar.