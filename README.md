# 🤖 Modo de uso:

## Primeros pasos:

- **Copiar repositorio a unidad local:** git clone <URL_del_repositorio>
- **Crear imagen**: build
- **Grabar imagen**: save
- **Subir imagen**: copiar la imagen al repositorio de Docker que usted utilice
- **Iniciar el contenedor**: Run

## Comandos utiles

- **Build:** docker buildx build --platform linux/amd64 -t sre-otel-collector_kong-dc .
- **Save image:** docker save -o /RUTA/sre-otel-collector_kong-dc.tar sre-otel-collector_kong-dc
- **Run:** docker run sre-otel-collector_kong-dc