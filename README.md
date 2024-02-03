# Proyecto de Redes y Comunicaciones de Datos: FashionNet

## Descripción del Proyecto
Este proyecto tiene como objetivo proporcionar una solución integral para la red empresarial de FashionNet, una empresa de TI líder en su campo con múltiples sedes. La infraestructura de red existente ha crecido de manera no planificada, lo que ha generado problemas de duplicidad de direcciones IP y dificultades en la expansión de nuevas sedes. La solución propuesta aborda estos desafíos mediante el diseño e implementación de una red interconectada, considerando aspectos como la escalabilidad, la seguridad y la eficiencia.

## Resumen del Proceso
El desarrollo del proyecto se dividió en varias etapas:

1. **Conocimiento de las Sedes:** Se identificaron las ubicaciones de las sedes donde opera FashionNet.
2. **Diseño Lógico en Packet Tracer:** Se realizó un diseño lógico de la red utilizando Packet Tracer, considerando las funciones y propósitos de todos los dispositivos y equipos de telecomunicaciones.
3. **Segmentación en VLAN:** Cada sede se dividió en segmentos de usuarios, los cuales fueron segmentados en VLAN.
4. **Asignación de Direcciones IP:** Se seleccionaron rangos de direcciones IP según la demanda de hosts en cada sede. Se asignaron direcciones IP a dispositivos finales y puertos en switches.
5. **Comunicación Inter-VLAN:** Se implementó un switch de capa 3 para la comunicación entre dispositivos finales en cada sede.
6. **Configuración de Servicios y Seguridad:** Se configuraron servicios como Web, Email y FTP. Además, se implementó seguridad de autenticación PAP y CHAP en routers, así como ACL para restringir el acceso entre sedes.
7. **Investigación de Soluciones Cloud:** Se realizó una investigación sobre las soluciones cloud de Microsoft Azure, Oracle y AWS.
8. **Cotización y Dimensionamiento:** Se calcularon los precios y la dimensión del hardware utilizado en cada sede.

## Descripción del Caso de Estudio: FashionNet
FashionNet es una empresa de TI que ha crecido de manera no planificada durante diez años, enfrentando problemas de duplicidad de direcciones IP y falta de documentación de la infraestructura de red.

## Problema o Necesidad
Al realizar pruebas de integración en nuevas sedes, los usuarios experimentaban problemas de duplicidad de direcciones IP, causando dificultades en el acceso a servicios de red.

## Objetivos de la Solución
1. Implementar una red sólida para la comunicación fluida entre sedes.
2. Garantizar el acceso seguro a recursos y datos.
3. Diseñar una infraestructura escalable para futuros crecimientos.
4. Dimensionar económicamente la solución técnica propuesta.

## Análisis de Requisitos de la Red
Se detallaron los requisitos específicos para cada sede, distribuyendo hosts en diferentes redes internas y segmentando por departamentos.
[![ISP](https://github.com/FashionNet/PacketTracer/blob/main/img/ISP.jpg) 
1. Sede Principal (Lima): 185 hosts
[![LIMA](https://github.com/FashionNet/PacketTracer/blob/main/img/LIMA.jpg) 
2. Sede Sucursal 1 (Piura): 180 hosts
[![PIURA](https://github.com/FashionNet/PacketTracer/blob/main/img/PIURA.jpg) 
3. Sede Sucursal 2 (Arequipa): 125 hosts
[![AREQUIPA](https://github.com/FashionNet/PacketTracer/blob/main/img/AREQUIPA.jpg) 
4. Sede Sucursal 3 (Cajamarca): 131 hosts
[![CAJAMARCA](https://github.com/FashionNet/PacketTracer/blob/main/img/CAJAMARCA.jpg) 
5. Sede Sucursal 4 (Cusco): 103 hosts
[![CUSCO](https://github.com/FashionNet/PacketTracer/blob/main/img/CUSCO.jpg)

## Conclusiones y Recomendaciones
El proyecto logró cumplir con los objetivos establecidos, proporcionando a FashionNet una solución de red integral y escalable. Se recomienda mantener la documentación actualizada y considerar la adopción de soluciones cloud para una mayor flexibilidad.

## Glosario
- **VLAN:** Red de Área Local Virtual.
- **ACL:** Listas de Control de Acceso.
- **PAP/CHAP:** Protocolos de Autenticación de Contraseña Débil/Fuerte.
- **RIP V2:** Protocolo de Información de Enrutamiento Versión 2.
- **MSL Switch:** Switch Multicapa.

Este README proporciona una visión general del proyecto, sus objetivos, el proceso de implementación y los resultados alcanzados. Se recomienda revisar la documentación detallada para obtener información más específica sobre la configuración y la implementación de la red.
