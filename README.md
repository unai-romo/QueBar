# QuéBar

La aplicación se ha construido con el objetivo de paliar dos grandes problemas que ha generado la pandemia del COVID-19. En primer lugar, se busca generar una sensación de seguridad en los ciudadanos y ciudadanas que, por motivos evidentes, sufren de intranquilidad a la hora de dirigirse a establecimientos (e.g. bares) por no conocer si se encontrará un lugar con poco espacio o si, por el contrario, un negocio en el que apenas hay gente y, por lo tanto, ofrece la tranquilidad añadida de no tener que pensar en distancias de seguridad, etc. que se han alojado en el centro de nuestras preocupaciones en el último año. En segundo lugar, permite a los dueños de estos comercios, mediante una interfaz muy sencilla, proporcionar esta tranquilidad a la vez que cuentan con herramientas para promover el crecimiento de su productividad.

## Descripción y futura implementación de la app

La app tiene dos interfaces muy diferenciadas: la destinada al usuario y la que utilizará el local. La parte destinada al usuario le permitirá visualizar los establecimientos que tiene a 1km a la redonda (distancia que se recorre en, aproximadamente, 10 minutos) de esta forma la app no requerirá de demasiada memoria del teléfono. Como se aprecia en la primera captura del prototipo el usuario podrá ver aquellos locales que se ajusten a su filtro en su proximidad geográfica; en una primera fase de desarrollo estos establecimientos serán bares (de ahí el nombre original de la aplicación) pero a medida que se avance con dicho desarrollo el filtro incorporará otro tipo de locales como gimnasios, supermercados o centros comerciales (sin olvidar que el objetivo principal, en primera instancia, es la de ayudar al pequeño comercio). El mencionado filtro por tipo de local está implementado en el prototipo.

La pantalla de local de la app (segunda captura del prototipo) mostrará la ocupación en tiempo real del local que será actualizado mediante la interfaz de propietario (tercera captura del prototipo) para cuya implementación habrá que construir una base de datos con la información de aforo de los distintos establecimientos. Además de ello, la base de datos deberá también alojar las distintas ofertas que realicen los propietarios. La forma en la que se ha planteado este tipo de promoción es la conocida como "Happy hour". La "Happy hour" permitirá por un lado atraer más clientela y, por el otro, dotar a los establicimientos de estrategias para dar salida a productos que de otra forma podrían generar pérdidas (e.g. productos que hay que tirar al cerrar). Esta funcionalidad se puede ver en la parte inferior de la segunda y tercera captura del prototipo.

El usuario podrá diferenciar de los locales con ofertas y sin ofertas con un sencillo marcador en el icono de ubicación del establecimiento (primera captura del prototipo) además, se podría implementar un sistema de notificaciones que permita al usuario conocer cuando un local en su proximidad geográfica tiene activada la "Happy hour".

Como se puede apreciar, el prototipo tiene un diseño minimalista y con líneas muy simples; de esta forma, se consigue mostrar la información esencial sin que esta tenga demasiada carga cognitiva en el usuario (la gran cantidad de white space ayuda con esto). Además, se ha realizado un diseño que incorpora un color principal (utilizando distintas opacidades) a la paleta greyscale evitando la gran mayoría de problemas de accesibilidad relacionadas con el daltonismo. Si una persona sufriese de tritanopia (ausencia de receptores para el color azul) el haber utilizado el mismo azul (#006699) con distinta opacidad debería solventar el problema. Al no tener conocidos con dicha condición no se ha podido probar si podría suponer un problema pero una única iteración de evaluaciones heurísticas de la app serviría para solucionarlo.

Por último, y aprovechando la mención de la evaluación heurística, consideramos que siendo una interfaz tan sencilla una evaluación bastará para corregir cualquier consideración de diseño que pueda resultar equivocada. Por ello, solo haría falta generar la base de datos, codificar la interfaz (se ha utilizado la herramienta Figma para construir el prototipo) y construir un "backend" con el que hacer "queries" en tiempo real a la mencionada base de datos para tener una app funcional y comercializable.

## Plan de marketing y estrategias de crecimiento

### Análisis de la competencia

La rivalidad entre competidores existentes es indirecta. Esto se debe a que las aplicaciones como TripAdvisor o ElTenedor ofrece información de restaurantes y distintas ofertas, sin embargo, ni las aplicaciones mencionadas ni aplicaciones de navegación como GoogleMaps indican al usuario cuál es la ocupación de un local en tiempo real de una forma precisa.

Las barreras de entrada serían medio-altas debido a que es una aplicación nueva en el mercado y su reconocimiento será bajo en las primeras semanas de lanzamiento por lo que los canales de comunicación jugarán un papel importante en la promoción y alcance de la app.

### Target market

La investigación de mercado realizada (mediante cuestionarios) indica que el usuario final es una persona concienciada y preocupada con el COVID-19 que quiere seguir viviendo su vida con la máxima seguridad posible mientras ayuda al comercio minorista. Además, en una primera fase de desarrollo la app se centrará en el pequeño comercio y, en desarrollos futuros se extenderá a grandes superficies como supermercados o centros comerciales.

Teniendo en cuenta la gran diversidad de usuarios que utilizarán la app se ha diseñado una interfaz muy sencilla e intuitiva.

### Comunicación

Se realizará una demostración gratuita para los establecimientos con el fin de que empiecena utilizar la app. Se tratará de atraer a los usuarios mediante la promoción realizada por los propios establecimientos y anuncios, por ejemplo, en redes sociales.

### Estrategia de crecimiento

La estrategia de crecimiento, centrada en el ámbito geográfico, se basará en la internacionalización; además, se buscará también un crecimiento en la cuota de mercado añadiendo nuevos tipos de cliente como las grandes superficies y, por último, grandes marcas que quieran notificar a usuarios de distintas promociones en sus tiendas.

En cuanto al plan de internacionalización, puede dividirse en 4 fases bien diferenciadas. Se inicaría una prueba piloto en una zona concreta de Madrid (e.g. alrededores de IBM). Las siguientes 3 fases corresponden a una expansión gradual del alcance de la app: en primer lugar se habilitaría el uso de la app para todo Madrid, seguido de una expansión al territorio nacional para, en último lugar, y conocociendo en qué tipo de lugares se consigue mayor uso de la app (por ejemplo utilizando la densidad de población como baremo) se pasaría a internacionalizarla.


### Financiación

Será una aplicación gratuita para los usuarios que se financiará con una cuota mensual que cubrirán los establecimientos (siempre buscando una cuota que sea mucho menor a lo que un establecimiento pueda gastarse en empresas de publicidad). Teniendo en cuenta que en Madrid hay más de 30.000 bares y restaurantes, si la cuota fuese de 10€/mes los ingresos superarían los 300.000€/mes si la app tiene un uso extensivo.
