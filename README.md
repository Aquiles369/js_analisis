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

- [ Checklist , análisis de archivos .js](#1)
- [Investigación propia](#2)
- [Palabras claves y Dorks](#3)
- [40 Informes diferentes](#4)
- [Recursos img entre otros](#5)



<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExc255bzh6OWZqdGI1eW54eGFiYjg1ZGt6cjJ5YzA5MDMwZzV2YjM0byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/3uKw2QfFkJ6zyvD5cU/giphy.gif" width = 80px>  </picture>  Checklist , análisis de archivos .js
<br><br>

#  1



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

#  2

• <br><br>
• <br><br>
• <br><br>
• <br><br>
• <br><br>
• <br><br>




<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMnI0aTAwanZhZHc2aTFsYzNid294Y3c4cGpzZ214bDh0Zm9sMTdzaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/djj4FGpee1d067eJID/giphy.gif" width = 80px>  </picture> “Palabras claves y Dorks”

#  3

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

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2k3eHk2YXB1bTdld20xZWRsaXduNjdlcmc0dHBseWxlZ2J5MnlpbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/bsvz1MTmt9PIMDi1rc/giphy.gif" width = 80px>  </picture> 40 Informes diferentes

#  4

**“En esta sección encontrarás 40 informes reales sobre análisis de .js que leí, estudié y anoté. Podés copiarlos directamente, importarlos en JSON con mis notas o cargarlos masivamente en tu gestor.”**

## Lista de informes link directo
```yam

```
Utilizar mi tool de gestor de informe para poder subir masivamente los informes y crear automaticamente las con las notas, link (aqui)
<br>

## json importar tools con mis notas

<br>

## Lo que aprendí leyendo de esos informes


• <br><br>
• <br><br>
• <br><br>
• <br><br>
• <br><br>




<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExODNlNmwwNG5uZmgweXBnZTRyNDBuOHN0aWMyb2xkc3doaXp5YnBvZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/4CWsgxwX4tGcIr6ztM/giphy.gif" width = 80px>  </picture> “Recursos img entre otros”


#  5


<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> “Cada .js es un mapa oculto: si sabés leerlo, encontrás el tesoro.”
<br>


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
