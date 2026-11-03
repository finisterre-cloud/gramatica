# Texto técnico

Reglas para textos técnicos y científicos de cualquier área: informes, artículos, manuales, normas y documentación. Se aplican junto con las demás referencias; donde difieren, mandan estas. Las reglas propias de software, código e interfaces están en [Informática](#informática).

## Anglicismos técnicos

**Excepción de estilo**: en textos técnicos, los anglicismos que son el término habitual del campo se escriben en redonda, sin cursiva. El lector especializado no los percibe como extranjeros y la cursiva repetida entorpece la lectura: software y byte (informática), stent y bypass (medicina), quark (física), flip-flop y offset (electrónica), bootstrap (estadística), western blot (biología), leasing y spread (finanzas).

- Si el campo tiene un término español asentado, úsalo: _realimentación_ (_feedback_, en control), _valor atípico_ (_outlier_, en estadística), _cribado_ o _tamizaje_ (_screening_, en medicina), _solución amortiguadora_ (_buffer_, en química), _base de datos_ (_database_), _rendimiento_ (_performance_).
- Las palabras inglesas que no son términos del campo siguen en cursiva: _una solución quick and dirty_.
- Elige una forma para cada concepto y mantenla en todo el texto: si escribes _realimentación_, no alternes con feedback; pero si el texto ya usa _feedback_, sigue con él.
- Género: masculino, salvo que el equivalente español imponga otro: el stent, el leasing, el software, la app (_aplicación_).
- Plural con _-s_: los stents, los quarks, los bytes, los flip-flops.
- Verbos: en textos formales, un verbo español en lugar del derivado del inglés: _probar_ o _ensayar_ en lugar de _testear_; _ajustar_ o _configurar_ en lugar de _setear_; _restablecer_ en lugar de _resetear_; _rastrear_ en lugar de _trackear_; _rendir_ en lugar de _performar_; _depurar_ en lugar de _debuggear_.
- Siglas: en todas las áreas valen las reglas generales de las [siglas](puntuacion.md#siglas). Usa la forma española cuando está asentada; otras se usan tal cual. Algunos ejemplos son
  - _CA_ (corriente alterna) en lugar de _AC_ (_alternating current_);
  - _CC_ (corriente continua) o _CD_ (corriente directa), según el país, en lugar de _DC_ (_direct current_);
  - _RMN_ (resonancia magnética nuclear) en lugar de _NMR_ (_nuclear magnetic resonance_);
  - _TAC_ (tomografía axial computarizada) o _TC_ (tomografía computarizada) en lugar de _CT_ (_computed tomography_);
  - _PCR_ (reacción en cadena de la polimerasa, del inglés _polymerase chain reaction_) se usa tal cual: _la PCR_.

## Unidades, símbolos y nomenclatura

La separación entre cifra y símbolo, y los símbolos sin punto ni plural, están en [Números](puntuacion.md#números). Además:

- La mayúscula o minúscula de un símbolo cambia su significado: _mW_ (miliwatt) y _MW_ (megawatt), _Mb_ (megabit) y _MB_ (megabyte), _s_ (segundo) y _S_ (siemens). El prefijo _kilo_ va en minúscula: _km_, _kg_, _kW_ (no _Km_, _Kg_).
- El litro admite dos símbolos, _l_ y _L_; se suele usar _L_ para no confundirlo con el número 1: _1,5 L_, _250 mL_.
- Símbolos y nombres no se mezclan: _km/h_ o _kilómetros por hora_ (no _kilómetros/h_).
- Magnitudes y variables en cursiva; unidades, constantes matemáticas (e, π) y funciones en redonda: la masa _m_ = 5 kg; sen _x_. En el texto, el seno se abrevia _sen_; en el código, con el nombre del lenguaje (`sin`).
- Producto y potencias de diez con _×_ o _·_ y exponente volado: _3 × 10⁸ m/s_ (no _3x10^8_).
- Valor con incertidumbre: valor e incertidumbre entre paréntesis y la unidad al final: _(25,0 ± 0,5) °C_.
- Fórmulas químicas con subíndices, y símbolos de elementos con su mayúscula exacta: _H₂O_, _CO₂_; _Co_ (cobalto) no es _CO_ (monóxido de carbono).
- Nombres científicos de especies en cursiva: _Escherichia coli_, _E. coli_. En genética humana, el gen en cursiva y la proteína en redonda: _BRCA1_ (gen), BRCA1 (proteína).

Los nombres de las unidades tienen en español dos formas: la internacional, que conserva la grafía del nombre propio y es la del SIMELA argentino (Ley 19.511), y la adaptada, que la ajusta a la ortografía española y es la de la RAE y la normativa de España (Real Decreto 2032/2009). Ninguna es más correcta: usa la que ya emplee el texto o, si no hay, la de su variedad según [regiones](regiones.md#nombres-de-las-unidades-del-si); sin variedad definida, la internacional, por ser la de uso internacional. Las diferencias y los puntos en común son estos:

- Grafía: _ampere_ o _amperio_, _volt_ o _voltio_, _watt_ o _vatio_ (lista completa en la tabla). _Newton_, _pascal_, _siemens_, _weber_, _tesla_ y _kelvin_ tienen una sola forma.
- Prefijos: se unen al nombre en ambas formas: _miliwatt_ o _milivatio_, _kilovolt_ o _kilovoltio_, _microfarad_ o _microfaradio_.
- Plural: las formas adaptadas lo forman de manera regular (_voltios_, _vatios_). Con las internacionales, el SIMELA recomienda no pluralizar las que vienen de nombres propios (_5 farad_, _220 volt_); otras normas, como la de Costa Rica, agregan _-s_ (_220 volts_) y dejan invariables _lux_, _hertz_ y _siemens_. Las demás unidades forman el plural regular en ambos casos: _8 metros_, _5 lúmenes_.
- En común: los nombres van en minúscula aunque el símbolo vaya en mayúscula (salvo _grados Celsius_), y los símbolos son los mismos (_A_, _V_, _W_).
- Una vez elegida una forma, mantenla en todo el texto.

| Símbolo | Forma internacional | Forma adaptada |
| ------- | ------------------- | -------------- |
| A       | ampere              | amperio        |
| V       | volt                | voltio         |
| W       | watt                | vatio          |
| Ω       | ohm                 | ohmio          |
| J       | joule               | julio          |
| Hz      | hertz               | hercio         |
| C       | coulomb             | culombio       |
| F       | farad               | faradio        |
| H       | henry               | henrio         |

## Código y valores literales

- Fragmentos de código, comandos, nombres de archivos y variables de programas, también en artículos de otras áreas que incluyen scripts (R, MATLAB, Python): en formato de código y sin traducir (`lm(y ~ x)`, `git commit`, `datos.csv`).
- Designaciones de normas, materiales y modelos, tal cual: _ISO 9001:2015_, _acero S275_.
- Los números dentro del código, de las versiones y de las designaciones conservan su formato aunque la prosa use coma decimal: _un tiempo de espera de 0,5 s_ en el texto, pero `timeout: 0.5` en el código; _la versión 2.10_ (no es un decimal).

## Documentación

Vale para manuales, informes, artículos y documentación de cualquier área:

- Presente para describir el funcionamiento: _La válvula se abre cuando la presión supera los 3 bar_; _La función devuelve una lista vacía si no hay resultados_ (no _se abrirá_ ni _devolverá_, calcos del _will_ inglés). Futuro solo para hechos realmente futuros: _La versión 3 eliminará esta opción_.
- Instrucciones en imperativo con el tratamiento elegido (_Calibra el sensor_) o en infinitivo en listas de pasos (_Calibrar el sensor_), sin mezclar ambas formas.
- En informes y artículos, primera persona del plural (_analizamos_) o impersonal con _se_ (_se analizó_), sin mezclar. La pasiva con _ser_, solo cuando aporta: ver [Voz pasiva](estilo.md#voz-pasiva).
- Referencias internas en minúscula: _la figura 3_, _la tabla 2_, _el capítulo 4_, _la ecuación (2)_.
- Una vez elegido un término (_ensayo_ o _prueba_ para _test_; _rama_ para _branch_), mantenlo en todo el texto.

## Informática

Reglas propias de software, código e interfaces.

### Siglas técnicas

Siguen las reglas generales de las [siglas](puntuacion.md#siglas): género del sustantivo principal de la expresión en español y plural sin _-s_ (_las API_, _los SDK_). Para público técnico, las muy conocidas no necesitan desarrollo.

| Sigla           | Desarrollo en español                            | Género                         |
| --------------- | ------------------------------------------------ | ------------------------------ |
| API             | interfaz de programación de aplicaciones         | _la API_                       |
| SDK             | kit de desarrollo de software                    | _el SDK_                       |
| URL             | dirección web (localizador uniforme de recursos) | _la URL_ (también _el URL_)    |
| CPU             | unidad central de procesamiento                  | _la CPU_                       |
| GPU             | unidad de procesamiento gráfico                  | _la GPU_                       |
| RAM             | memoria de acceso aleatorio                      | _la RAM_                       |
| SO (_OS_)       | sistema operativo                                | _el SO_                        |
| IDE             | entorno de desarrollo integrado                  | _el IDE_                       |
| CLI             | interfaz de línea de comandos                    | _la CLI_                       |
| DNS             | sistema de nombres de dominio                    | _el DNS_                       |
| VPN             | red privada virtual                              | _la VPN_                       |
| ID              | identificador                                    | _el ID_                        |
| LLM             | gran modelo de lenguaje                          | _el LLM_                       |
| HTML, JSON, PDF | lenguajes y formatos                             | _el HTML_, _el JSON_, _el PDF_ |

### Mensajes de commit

- Sigue primero la convención del repositorio (revisa `git log`): idioma, tiempo verbal y formato.
- Si no hay convención, la línea de asunto va en infinitivo, con mayúscula inicial y sin punto final: _Agregar validación del correo_, _Corregir el cálculo del IVA_.
- Asunto breve (unos 50 caracteres). El cuerpo, separado por una línea en blanco, explica el porqué con oraciones completas y puntuación normal.
- Con Conventional Commits, el prefijo queda en inglés como lo define la especificación, y la descripción sigue en minúscula tras los dos puntos: `feat: agregar exportación a PDF`, `fix: corregir el redondeo del total`.
- Verbos del control de versiones en español: hacer un commit o _confirmar los cambios_ en lugar de _commitear_; _fusionar_ en lugar de _mergear_; _subir los cambios_ en lugar de _pushear_; _desplegar_ en lugar de _deployar_.

### Interfaces y localización

- Tratamiento coherente con el resto del producto: _tú_ (_Haz clic_), _vos_ (_Hacé clic_) o _usted_ (_Haga clic_).
- Mensajes breves y directos; en botones, infinitivo o imperativo según la convención del producto (_Guardar_ / _Guarda_), siempre la misma.
- _Por favor_ solo cuando se pide algo que incomoda (esperar, repetir una acción); en instrucciones simples sobra: _Ingresa tu correo_.
- Frases completas con marcadores, nunca fragmentos concatenados: la concordancia y el orden de las palabras cambian según el contenido. `"Nuevo " + tipo` produce _Nuevo carpeta_; usa una cadena por caso (_Nuevo archivo_, _Nueva carpeta_).
- Plurales con las reglas de plural de la biblioteca de internacionalización (ICU MessageFormat, CLDR), no con condiciones escritas a mano: `{n, plural, one {# archivo eliminado} other {# archivos eliminados}}`. El cero va en plural: _0 archivos_.
- Fechas, números y monedas con la configuración regional (`Intl.DateTimeFormat`, `Intl.NumberFormat`, `toLocaleString` con `es-AR`, `es-ES`, `es-MX`...), sin separadores ni formatos escritos a mano.
- El texto en español suele ocupar entre un 20 y un 30 % más que en inglés, y bastante más en textos muy cortos: deja espacio en botones y etiquetas.
- Ver también: [mayúsculas en interfaces](estilo.md#mayúsculas-a-la-inglesa), [gerundios en mensajes de progreso](estilo.md#gerundios-y--ing) y [formas sin género](estilo.md#formas-sin-género).
