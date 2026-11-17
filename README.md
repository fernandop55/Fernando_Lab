
# Mi copia para practicar · laboratorio de IaC e IA

Este repositorio es **tu copia personal** del proyecto ficticio `portal-demo`. Puedes usarla para ensayar el recorrido del alumnado. La [plantilla original](https://github.com/b-regina/iac-ia-laboratorio-demo) es el enlace que debes compartir para que cada participante cree su propia copia.

## Cómo continuar en esta copia

1. Descarga la [Guía del ejercicio 1](GUIAS/Guia_Alumnado_Ejercicio_1.docx?raw=1). Como **ya tienes una copia**, puedes leer el paso de creación y comenzar en **Paso 2 · Comprueba la ejecución inicial**.
2. Abre **Actions → Validacion IaC** y comprueba la ejecución de este repositorio.
3. Para practicar la edición desde el navegador, abre [esta copia en github.dev](https://github.dev/b-regina/Profe-ejercicios), modifica `variables.tf`, haz **Commit & Push** y busca la ejecución correspondiente en Actions.

**Esta copia no es el enlace de entrada del alumnado.** La ruta común de clase utiliza el navegador, una copia personal por alumno, el editor web y la IA en otra pestaña. OpenTofu se instala temporalmente en el ejecutor de Actions; no hay que instalarlo en el ordenador.

## Guías de trabajo

| Orden | Word descargable | Qué añade al mismo proyecto |
| --- | --- | --- |
| 1 | [Primera configuración y primer plan](GUIAS/Guia_Alumnado_Ejercicio_1.docx?raw=1) | Copia, IA, cambio y comprobación. |
| 2 | [Dos escenarios](GUIAS/Guia_Alumnado_Ejercicio_2.docx?raw=1) | Variables y comparación de planes. |
| 3 | [Revisión y gobierno](GUIAS/Guia_Alumnado_Ejercicio_3.docx?raw=1) | Reglas, rama y pull request. |
| 4 | [Automatización y evidencias](GUIAS/Guia_Alumnado_Ejercicio_4.docx?raw=1) | Workflow, error y diagnóstico. |
| 5 | [Módulo reutilizable](GUIAS/Guia_Alumnado_Ejercicio_5.docx?raw=1) | Dos fichas desde un módulo local. |

Los archivos de código iniciales siguen en la raíz: `variables.tf`, `main.tf` y `outputs.tf`. El workflow está en `.github/workflows/validacion.yml`. El proyecto calcula planes con `terraform_data`; no aplica cambios ni despliega infraestructura comercial.

# Laboratorio de IaC e IA · empieza por aquí

Este repositorio contiene **un único proyecto ficticio**, `portal-demo`. Vas a trabajar en **una copia propia** del repositorio durante todos los ejercicios. Cada ejercicio amplía lo que hiciste en el anterior. Al principio solo existe el código necesario para el ejercicio 1; los demás archivos aparecerán cuando tú los crees.

## Tu primer paso

1. Descarga y abre la [Guía del ejercicio 1 (Word)](GUIAS/Guia_Alumnado_Ejercicio_1.docx?raw=1). Léela desde el principio: incluye los botones para crear tu copia y comprobarla.
2. En esta página pulsa **Use this template → Create a new repository**. En **Owner** elige tu usuario, deja **Include all branches** desmarcado y crea un repositorio público con otro nombre. **Hazlo una sola vez.**
3. Comprueba que la URL de tu copia empieza por `https://github.com/TU_USUARIO/`. A partir de aquí, todos tus cambios irán a esa copia.
4. Abre **Actions** en tu copia. Si aparece **Validacion IaC → Commit inicial → comprobar** en verde, el laboratorio ya ejecutó OpenTofu en GitHub. La guía explica qué hacer si no aparece.
5. Continúa la guía del ejercicio 1: abre **tu copia** en `github.dev`, cambia `variables.tf`, confirma y publica el cambio, y consulta la nueva ejecución de Actions.

**No necesitas instalar GitHub Actions, OpenTofu, Git ni VS Code en tu equipo para la ruta de navegador.** GitHub Actions es una pestaña de GitHub; el workflow instala OpenTofu en un ejecutor temporal. `github.dev` es el editor web. Abre ChatGPT o Copilot Chat en **otra pestaña** para preguntar, predecir y revisar. Usa solo datos ficticios.

## Las cinco guías

| Orden | Guía Word | Qué harás en la misma copia |
| --- | --- | --- |
| 1 | [Puesta en marcha, IA y primer plan](GUIAS/Guia_Alumnado_Ejercicio_1.docx?raw=1) | Crear la copia, comprender tres archivos, cambiar un entorno y leer el resultado. |
| 2 | [Dos escenarios](GUIAS/Guia_Alumnado_Ejercicio_2.docx?raw=1) | Parametrizar la configuración y comparar dos planes. |
| 3 | [Revisión y gobierno](GUIAS/Guia_Alumnado_Ejercicio_3.docx?raw=1) | Crear una rama, añadir validaciones y revisar un pull request. |
| 4 | [Automatización y evidencias](GUIAS/Guia_Alumnado_Ejercicio_4.docx?raw=1) | Mejorar el workflow y diagnosticar un fallo real de la práctica. |
| 5 | [Módulo reutilizable](GUIAS/Guia_Alumnado_Ejercicio_5.docx?raw=1) | Crear un módulo local y usarlo para dos fichas ficticias. |

**El ejercicio 2 empieza donde dejaste el 1**; no crees otra copia. Sigue el mismo principio para los siguientes. Las guías están en `GUIAS/` para poder descargarlas; el código que editarás está en la raíz y en `.github/workflows/`.

## Qué son los archivos iniciales

| Archivo | Función |
| --- | --- |
| `variables.tf` | Declara el entorno, inicialmente `desarrollo`. |
| `main.tf` | Describe una ficha ficticia con `terraform_data`. |
| `outputs.tf` | Define el resumen del plan. |
| `.github/workflows/validacion.yml` | Instala OpenTofu y ejecuta las comprobaciones en GitHub Actions. |

El workflow calcula un plan, **no ejecuta `tofu apply`** y no crea una web ni infraestructura comercial. Si tu equipo permite VS Code local, puedes usarlo con **esa misma copia**: el código y la comprobación en Actions son los mismos. La ruta principal, explicada paso a paso en los Word, funciona desde el navegador.

