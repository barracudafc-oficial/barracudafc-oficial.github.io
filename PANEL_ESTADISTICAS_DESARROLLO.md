# Panel privado de estadísticas — prototipo de desarrollo

**Estado:** diseño local en rama de desarrollo. NO desplegado ni protegido con autenticación.

## Uso de prueba
Abrir `panel-estadisticas-prototipo.html` localmente y cargar un CSV con encabezados:
`path,visits,country,device,source,date`.
Cada fila representa una combinación de dimensiones; `visits` es entero no negativo. Los datos se procesan localmente en el navegador.

## Requisitos antes de producción
1. Elegir alojamiento compatible con protección real (Cloudflare Access o equivalente) y restringir a `secretaria@barracudafc.com`.
2. Integrar API de analítica desde servidor/worker, con token en secretos de servidor, **nunca** en HTML o JavaScript público.
3. Comprobar disponibilidad y alcance de métricas de Cloudflare; la atribución UTM puede requerir GA4.
4. Verificar seguimiento de cada artículo y consistencia entre visitas y vistas de página.
5. Validar el acceso en ventana privada antes de desplegar el panel.
6. No publicar informes CSV con datos privados en el repositorio.

No se han modificado DNS, correos ni la rama pública `main`.
