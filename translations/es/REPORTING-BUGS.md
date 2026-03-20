<!--TRANSLATION_LINKS_START-->
> 📖 **Otros idiomas**：[Inglés (en)](translations/en/REPORTING-BUGS.md) | [Español (es)](translations/es/REPORTING-BUGS.md) | [Japonés (ja)](translations/ja/REPORTING-BUGS.md) | [Coreano (ko)](translations/ko/REPORTING-BUGS.md)
<!--TRANSLATION_LINKS_END-->

# Cómo reportar errores

Si alguna parte del proyecto Nacos tiene errores o errores de documentación, háganoslo saber [abriendo un issue][Nacos-issue]. Tratamos los errores y los errores de documentación muy seriamente y creemos que ningún problema es demasiado pequeño; cualquiera puede contribuir. Antes de crear un informe de error, verifique que no exista ya un informe que reporte el mismo problema.

Para que el informe de error sea preciso y fácil de entender, por favor intente crear informes de error que sean:

- Específico. Incluya la mayor cantidad de detalles posible: qué versión, qué entorno, qué configuración, etc. Si el error está relacionado con la ejecución del servidor Nacos, adjunte el registro de Nacos (el registro de inicio con la configuración de Nacos es especialmente importante).

- Reproducible. Incluya los pasos para reproducir el problema. Entendemos que algunos problemas pueden ser difíciles de reproducir; incluya los pasos que podrían llevar al problema. Si es posible, adjunte el directorio de datos de Nacos afectado y el seguimiento de pila al informe de error.

- Único. No duplique el informe de error existente.


También puede ser útil leer el artículo de [Elika Etemad sobre cómo presentar buenos informes de errores][filing-good-bugs] antes de crear un informe de error.

Podríamos solicitar información adicional para localizar un error. Un informe de error duplicado será cerrado.

[etcd-issue]: https://github.com/etcd-io/etcd/issues/new
[filing-good-bugs]: http://fantasai.inkedblade.net/style/talks/filing-good-bugs/