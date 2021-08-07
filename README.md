# Evolución de vacunados contra COVID-19 en Perú

## Antecedentes

Con la llegada del primer lote de vacunas contra la COVID-19 al país, se inició la [Campaña Nacional de Vacunación, Pongo el hombro por el Perú](https://www.gob.pe/institucion/minsa/campa%C3%B1as/3451-campana-nacional-de-vacunacion-contra-la-covid-19 "Gobierno del Perú"), con el fin de proteger a la población y disminuir el riesgo de enfermar o fallecer.

## Proceso

Este proyecto se desarrolló en Python 3.8.5 usando los paquetes **numpy**, **pandas**, **matplotlib**, **seaborn** y **datetime**.

### Adquisición de Datos

Obtuve las cifras de vacunados contra COVID-19 actualizadas a la fecha **2021-08-07** de la Plataforma Nacional de Datos Abiertos del Gobierno de Perú. Los conjuntos de datos utilizados están disponibles en el repositorio "Vacunación contra COVID-19" del Ministerio de Salud [[1]].

El indicador del umbral mínimo sobre la Inmunidad de Rebaño se definió tomando en consideración lo expuesto en la publicación "Coronavirus disease (COVID-19): Herd immunity, lockdowns and COVID-19" de la Organización Mundial de la Salud [[2]].

La población total por regiones del 2020 se recuperó manualmente del gráfico expuesto en la página de inicio del Repositorio Único Nacional de Información en Salud del Ministerio de Salud [[3]].

## Resultados

![alt text](dist/20210807_PERÚ.png "PERÚ")

![alt text](dist/20210807_AMAZONAS.png "AMAZONAS")

![alt text](dist/20210807_ANCASH.png "ANCASH")

![alt text](dist/20210807_APURIMAC.png "APURIMAC")

![alt text](dist/20210807_AREQUIPA.png "AREQUIPA")

![alt text](dist/20210807_AYACUCHO.png "AYACUCHO")

![alt text](dist/20210807_CAJAMARCA.png "CAJAMARCA")

![alt text](dist/20210807_CALLAO.png "CALLAO")

![alt text](dist/20210807_CUSCO.png "CUSCO")

![alt text](dist/20210807_HUANCAVELICA.png "HUANCAVELICA")

![alt text](dist/20210807_HUANUCO.png "HUANUCO")

![alt text](dist/20210807_ICA.png "ICA")

![alt text](dist/20210807_JUNIN.png "JUNIN")

![alt text](dist/20210807_LA_LIBERTAD.png "LA LIBERTAD")

![alt text](dist/20210807_LAMBAYEQUE.png "LAMBAYEQUE")

![alt text](dist/20210807_LIMA.png "LIMA")

![alt text](dist/20210807_LORETO.png "LORETO")

![alt text](dist/20210807_MADRE_DE_DIOS.png "MADRE DE DIOS")

![alt text](dist/20210807_MOQUEGUA.png "MOQUEGUA")

![alt text](dist/20210807_PASCO.png "PASCO")

![alt text](dist/20210807_PIURA.png "PIURA")

![alt text](dist/20210807_PUNO.png "PUNO")

![alt text](dist/20210807_SAN_MARTIN.png "SAN MARTIN")

![alt text](dist/20210807_TACNA.png "TACNA")

![alt text](dist/20210807_TUMBES.png "TUMBES")

![alt text](dist/20210807_UCAYALI.png "UCAYALI")

## Referencias

1. Ministerio de Salud - MINSA. (s.f.). _[Vacunación contra COVID - 19 - [Ministerio de Salud - MINSA] | Plataforma Nacional de Datos Abiertos_. Gobierno del Perú. Recuperado el 3 de abril de 2021 de https://www.datosabiertos.gob.pe/dataset/vacunaci%C3%B3n-contra-covid-19-ministerio-de-salud-minsa

[1]: https://www.datosabiertos.gob.pe/dataset/vacunaci%C3%B3n-contra-covid-19-ministerio-de-salud-minsa

2. World Health Organization. (31 de diciembre de 2020). _Coronavirus disease (COVID-19): Herd immunity, lockdowns and COVID-19_. Organización de las Naciones Unidas. Recuperado el 10 de abril de 2021 de https://www.who.int/news-room/q-a-detail/herd-immunity-lockdowns-and-covid-19

[2]: https://www.who.int/news-room/q-a-detail/herd-immunity-lockdowns-and-covid-19

3. Ministerio de Salud - MINSA. (s.f.). _.: REUNIS :. Repositorio Único Nacional de Información en Salud - Ministerio de Salud_. Gobierno del Perú. Recuperado el 10 de abril de 2021 de https://www.minsa.gob.pe/reunis/data/poblacion_estimada.asp

[3]: https://www.minsa.gob.pe/reunis/data/poblacion_estimada.asp

