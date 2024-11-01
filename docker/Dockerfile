# Usa una imagen base de Alpine para un contenedor ligero
FROM hashicorp/terraform:latest

# Define el directorio de trabajo
WORKDIR /app

# Copia los archivos de Terraform al contenedor
COPY . .

# Comando por defecto para el contenedor
CMD ["terraform", "--version"]
