---
layout: default
title: Política de privacidad — Meyparking
description: Política de privacidad específica de la aplicación móvil Meyparking (Android + Android Auto) de MEYPAR.
permalink: /privacy-policy-es.html
---

# Política de Privacidad — Meyparking

[← Volver al índice](./)

> **Aplicable a:** aplicación móvil **Meyparking** para Android y Android Auto.
> Complementa, a los solos efectos del tratamiento de datos realizado por la app, la [Política de Privacidad general de meypar.com](https://meypar.com/politica-de-privacidad/).

**Responsable del tratamiento:** Maquinaria Estacionamientos y Parkímetros, S.L. (en adelante, “MEYPAR”), con NIF **B63650071** y domicilio social en **Avda. Ragull, 50 — Sant Cugat del Vallès, Barcelona (Spain)**.

**Contacto para temas de privacidad y legal:** meypar@meypar.com

**Teléfono de contacto general:** (+34) 93 544 29 33.

**Fecha de entrada en vigor:** 20 de abril de 2026.

**Versión:** 1.0

---

## 1. ¿Qué es Meyparking?

Meyparking es una aplicación móvil para Android y Android Auto diseñada para uso profesional de clientes y personal autorizado de MEYPAR. Permite:

- Gestionar una lista de parkings y sus números de teléfono de contacto.
- Llamar al parking seleccionado con un toque (también desde Android Auto, en manos libres).
- Mostrar el parking en un mapa y avisar al usuario cuando se aproxima a él (funcionalidad de proximidad opcional).

Esta política explica, de forma específica para la app, **qué datos personales trata Meyparking**, **por qué**, **con quién se comparten** y **qué derechos tienes sobre ellos**, conforme al Reglamento (UE) 2016/679 (RGPD) y la Ley Orgánica 3/2018 (LOPDGDD).

---

## 2. Qué datos tratamos

### 2.1 Datos que introduces tú mismo en la app

- **Nombre del parking** (texto libre).
- **Dirección del parking** (texto libre o seleccionada en el mapa).
- **Número de teléfono del parking** (formato internacional).
- **Coordenadas geográficas del parking** (latitud y longitud, obtenidas al seleccionar un punto en el mapa o buscar una dirección).

Estos datos se guardan **exclusivamente en el almacenamiento local privado del dispositivo** (base de datos Room aislada por Android). MEYPAR no tiene acceso a ellos.

### 2.2 Datos que el dispositivo facilita cuando usas la app

| Dato | Cuándo | Finalidad | ¿Sale del dispositivo? |
|---|---|---|---|
| **Ubicación precisa (GPS)** | Cuando abres la app y tienes concedido el permiso | Mostrar tu posición en el mapa, calcular distancia al parking, activar el radar de proximidad | No |
| **Ubicación aproximada** | Fallback si rechazas la ubicación precisa | Mostrar ubicación general en el mapa | No |
| **Ubicación en segundo plano** (`ACCESS_BACKGROUND_LOCATION`) | Solo si activas “proximidad” y concedes el permiso específico | Enviarte una notificación cuando llegas al parking, sin que tengas la app abierta | No |
| **Historial local de llamadas** (fecha, parking llamado, duración) | Cada vez que pulsas “Llamar” | Mostrarte tu propio historial en la pantalla Historial | No |

### 2.3 Datos que la app **NO** recopila

- No recopilamos **nombre, apellidos, email, identificador publicitario (AAID), IMEI ni IMSI**.
- No accedemos a tus **contactos, mensajes SMS, fotos, micrófono, calendario, historial del sistema de llamadas ni archivos**.
- No usamos **analítica** (ni Firebase Analytics, ni Google Analytics, ni otros SDK de tracking).
- No mostramos **publicidad**.
- No usamos **cookies** (la app no es web; la política de cookies de meypar.com aplica únicamente a la web y se describe en <https://meypar.com/politica-de-cookies/>).

---

## 3. Dónde se guardan tus datos

**Todos tus datos permanecen en tu dispositivo.** Meyparking **no tiene servidor propio de usuarios** y no envía información personal a MEYPAR ni a terceros.

Las únicas peticiones de red que realiza la app son:

| Destino | Información enviada | Finalidad |
|---|---|---|
| **OpenFreeMap** (`tiles.openfreemap.org`) | Coordenadas aproximadas del área visible en pantalla | Descargar el mapa vectorial que se muestra al usuario |
| **Nominatim** (`nominatim.openstreetmap.org`) | El texto que escribes en el buscador de direcciones | Convertir el texto en coordenadas (geocoding) |
| **Red telefónica del operador** | El número al que llamas | Establecer la llamada al parking |

Ni OpenFreeMap ni Nominatim reciben datos personales identificativos: solo las consultas técnicas necesarias para el mapa y el buscador. Sus políticas:
- OpenFreeMap: <https://openfreemap.org/>
- OpenStreetMap / Nominatim: <https://osmfoundation.org/wiki/Privacy_Policy>

---

## 4. Base legal del tratamiento (RGPD art. 6)

- **Ejecución del servicio (art. 6.1.b)** — para que la app funcione como esperas: guardar parkings, mostrar mapa, llamar al parking configurado.
- **Consentimiento explícito (art. 6.1.a)** — para acceder a la ubicación (pedido en *runtime* por Android) y para activar la proximidad en segundo plano.

Puedes **retirar el consentimiento en cualquier momento** desactivando los permisos en Ajustes de Android → Apps → Meyparking → Permisos. La app seguirá funcionando sin las funciones que dependan de ese permiso.

---

## 5. Destinatarios y transferencias internacionales

- **No compartimos tus datos con terceros** con fines comerciales.
- **No hacemos transferencias internacionales** de tus datos personales.
- Las comunicaciones técnicas con OpenFreeMap y Nominatim pueden implicar servidores fuera del EEE, pero no contienen datos identificativos personales.

---

## 6. Plazo de conservación

- Los datos permanecen en tu dispositivo mientras tengas la app instalada.
- Al **desinstalar** la app se elimina toda la base de datos local (parkings, historial, preferencias).
- Puedes **borrar parkings e historial manualmente** desde la pantalla de Ajustes en cualquier momento.
- La app **no admite copias de seguridad automáticas de Android** (`allowBackup="false"`), por lo que tus datos no se transfieren a Google Drive ni a otro dispositivo durante un cambio de móvil.

---

## 7. Derechos que tienes (RGPD arts. 15–22 y LOPDGDD arts. 12–18)

Como los datos están en tu dispositivo, ejerces la mayoría directamente:

- **Acceso y portabilidad:** los datos son accesibles desde las pantallas Parkings, Historial y Ajustes de la propia app.
- **Rectificación:** edita cualquier parking desde la pantalla de Parkings.
- **Supresión:** borra parkings e historial desde Ajustes, o desinstala la app.
- **Limitación del tratamiento:** revoca permisos en Ajustes de Android.
- **Oposición:** desactiva la proximidad o la ubicación.

Si aun así quieres contactar con MEYPAR por un tema de privacidad, escribe a **meypar@meypar.com** o por correo postal a **Avda. Ragull, 50 — Sant Cugat del Vallès, Barcelona (Spain)**, indicando la referencia “Datos Personales — App Meyparking” y especificando el derecho a ejercer.

Tienes derecho a presentar una reclamación ante la **Agencia Española de Protección de Datos** (<https://www.aepd.es>).

---

## 8. Menores de edad

Meyparking es una aplicación de uso profesional y no está dirigida a menores de 14 años. MEYPAR no recopila conscientemente datos de menores.

---

## 9. Seguridad

- Los datos se almacenan en la base de datos local privada de la app, aislada por el sistema Android.
- Las comunicaciones con mapas y geocoding se realizan siempre sobre **HTTPS** cifrado.
- La app no admite **backups automáticos de Android**, evitando que tus parkings y teléfonos salgan del dispositivo durante un cambio de móvil o restauración desde la nube.
- Se aplican medidas técnicas y organizativas descritas en la política general de MEYPAR: <https://meypar.com/politica-de-privacidad/> § 6.

---

## 10. Cambios a esta política

Si actualizamos esta política publicaremos la nueva versión en esta misma URL con nueva fecha de entrada en vigor. Los cambios relevantes se anunciarán dentro de la app antes de su entrada en vigor.

---

## 11. Contacto

- **Responsable:** Maquinaria Estacionamientos y Parkímetros, S.L.
- **NIF:** B63650071
- **Dirección postal:** Avda. Ragull, 50 — Sant Cugat del Vallès, Barcelona (Spain)
- **Teléfono general:** (+34) 93 544 29 33
- **Email para temas de privacidad de la app:** meypar@meypar.com
- **Web corporativa:** <https://meypar.com>
- **Aviso legal general:** <https://meypar.com/aviso-legal/>
- **Política de privacidad general (web corporativa):** <https://meypar.com/politica-de-privacidad/>
