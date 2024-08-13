---
title: 'Disparo'
excerpt: 'Una vez un grupo de naves finaliza su movimiento, todas sus naves pueden disparar sistemas de armas si las órdenes impartidas a las mismas lo permiten.'
position: 6
---

# {{ $frontmatter.title }}

Una vez un grupo de naves finaliza su movimiento, todas sus naves pueden disparar sistemas de armas si las órdenes impartidas a las mismas lo permiten.

## Procedimiento de Disparo

1. Comprobar Rango de detección y arco de fuego.
1. Generar y distribuir dados de ataque.
1. Tirar para impactar.
1. Determinar daño de Casco total infligido.
1. Realizar tiradas de salvación y reducir puntos de Casco.
1. Realizar tiradas de Daño incapacitante si los puntos de Casco se reducen al 50% o menos.
1. Realizar tiradas de Daño catastrófico si el valor de puntos de Casco se reduce a 0 o menos.

## 1. Comprobar Rango de detección y arco de fuego

En el combate espacial pocas armas tienen un 'alcance máximo' real. Sin verse afectados por los efectos de la atmósfera y la gravedad - da igual que el disparo proceda de un percutor cinético o de un rayo térmico - los proyectiles pueden lanzarse a distancias infinitas.

Sin embargo, las naves necesitan ser capaces de predecir con precisión donde se encontrará el enemigo cuando el arma sea disparada, a fin de ajustar el disparo para que impacte en el objetivo.

Para disparar un arma a un objetivo, éste debe estar tanto dentro del alcance del arma como del arco de fuego.

Para determinar el rango efectivo de las armas de una nave, escoge un objetivo y usa la siguiente fórmula para determinar el rango del arma:

**Escáner del atacante + Señal del objetivo = Rango del arma del atacante**.

Si el atacante tiene a rango su objetivo, podrá potencialmente disparar. El siguiente paso es comprobar si el objetivo está dentro de alguno de los arcos de fuego de las armas de la nave atacante.

Comprueba la característica Arco de los sistemas de armas disponibles para el ataque de la nave, y utiliza los arcos marcados en la base de la miniatura para comprobar si el objetivo está dentro del arco de fuego del sistema de armas correspondiente, pudiendo en caso afirmativo ser elegidos como objetivos potenciales de dicho arma.

Existen muchos objetivos potenciales en Dropfleet, pero nunca podrás disparar sobre naves amigas.

Como el espacio orbital es tridimensional, y debido a la habilidad de ver todas las otras miniaturas como se detalla previamente, las naves no bloquean la visión entre si a la hora de determinar objetivos de disparo - ésto se aplica incluso si viendo desde arriba la mesa de juego parece que una nave está oculta tras otra o 'ver' la nave objetivo desde la posición del atacante de forma normal.

Las armas de corto alcance tienen un rango corto, y solo utilizan el valor de Escáner del atacante para determinar el rango del arma - ver [Reglas especiales de los Sistemas de Armas](/es/dfc/special-rules#close-action) para más detalles.

### Picos de energía{#energy-spikes}

Ciertos eventos causan la aparición de Picos de energía que se colocan en las naves para marcar su estado actual. Los Picos de energía representan todo tipo de acciones o eventos que ayudan al enemigo en detectar y fijar blanco en una nave (uso de motores, disparar armas, o incluso fugas causadas por el daño en una nave o acciones de escaneado de naves enemigas). Los Picos de energía se clasifican en dos tipos: Menores y Mayores.

* **Un Pico de energía Menor incrementa la Señal de una nave en 6"**.
* **Un Pico de energía Mayor incrementa las Señal de una nave en 12"**.

Una nave solo puede tener un Pico a la vez. Si una nave tiene un Pico menor y obtiene otro mas, se convierte en un Pico mayor. Si una nave ya tiene un Pico mayor, ya brilla como un arbol de Navidad gigante y no recibe más picos hasta que el Pico mayor ha sido eliminado o reducido a Pico menor.

Los incrementos de la Señal ganados por Picos sólo duran mientras el Pico esté activo en dicha nave.

::: info _Por ejemplo; una nave con una Señal de 6" gana un Pico menor. Su Señal contará como 12" hasta que el Pico sea eliminado. Si la nave gana otro Pico menor, el que tenía se transforma en su lugar en un Pico mayor, y la Señal de la nave cuenta como 18" hasta que el Pico mayor es eliminado_.
:::

Usa el dial de estado de la base de la nave para marcar apropiadamente sus Picos de energía, girándolo apropiadamente cuando se ganan o pierden Picos. Los jugadores pueden utilizar marcadores alternativos para ello si desean.

## 2. Generar y distribuir dados de ataque

El número de ataques de un perfil de arma es el número de dados que se lanzan cuando dicho arma es disparada.

Cada nave atacante selecciona un Sistema de Armas y un objetivo que esté dentro del alcance del Sistema de Armas y su arco de fuego. A continuación se asignan **todos** los Dados de Ataque de dicho Sistema de Armas al objetivo. Los Dados de Ataque de un único Sistema de Armas no se pueden dividir entre varias naves. Puedes repetir este paso para todos los Sistemas de Armas de la nave atacante.

Cuando realices una tirada para varios Sistemas de ARmas con diferentes características a la vez puede resultar útil utilizar dados con diferentes colores para marcar los diferentes tipos de sistemas de armas utilizados, en lugar de lanzar por cada uno separadamente.

Varios sistemas de armas lanza un número aleatorio de dados de ataque (por ejemplo, D6 o D3) los cuales se determinan cada vez que dicho arma dispara. Realiza una tirada para determinar cuantos ataques son generados por el Sistema de Armas antes de distribuir los dados entre los objetivos disponibles.

Generalmente un grupo activo generalmente contiene varias naves con sistemas de armas para disparar. **Todos los Dados de Ataque del Grupo deben ser ubicados entre los diferentes objetivos válidos disponibles antes de realizar cualquier tirada para impactar**. Esto ayuda a agilizar el juego y previene que un jugador optimice excesivamente sus disparos de una forma poco realista.

### Armas de corto alcance

Los Sistemas de Armas de Corto Alcance tienen un rango efectivo pequeño pero tienen una mayor cadencia de fuego y requieren menores cantidades de energía para ser utilizados.

Los sistemas de armas de corto alcance pueden ser disparados siempre, como complemento a cualquier otro sistema de armas permitido por la orden dada a la nave. Si una nave no puede disparar sistemas de armas, tampoco podrá disparar los sistemas de armas de corto alcance en dicha acción.

## 3. Tirada para impactar

Lanza los Dados de Ataque asignados y compara los resultados con la característica de Puntería del arma (después de aplicar modificadores). Cualquier dado que haya obtenido un resultado igual a dicho número ha conseguido un impacto. Cualquier dado que no haya obtenido un resultado igual a dicho número ha fallado al impactar.

Recuerda, los resultados de un 1 después de modificadores siempre fallan y los resultados de 6 después de modificadores siempre impactan.

Puedes agrupar armas idénticas disparadas al mismo objetivo y lanzarlos juntos para ayudar a acelerar el juego.

### Impacto crítico

**Cualquier Dado de Ataque que obtenga un resultado que supere en dos o más el valor de Puntería del sistema de armas se considera que ha infligido un impacto crítico. El daño causado por este dado de ataque ignora la Salvación por armadura del objetivo**.

Las Contramedidas Pasivas pueden seguir utilizándose para salvar daño producido por impactos críticos utilizando su valor de Armadura adicional (ver [Contramedidas Pasivas](/es/dfc/core-rules/damage#contramedidas-pasivas) para detalles adicionales).

::: info _Por ejemplo, si un sistema de armas tiene un valor de Puntería de 4+, cada Dado de Ataque que resulte en un 6 ignorará la Salvación por armadura del objetivo a la hora de determinar el daño causado en el Casco. Un sistema de armas con una Puntería de 3+ ignorará salvaciones por armadura en tiradas con resultados de 5 o 6, y así sucesivamente_.
:::

### Disparar entre Capas orbitales

Una nave que dispare de una Capa Orbital a otra sufre un penalizador de +1 al valor de Puntería del arma disparada (por ejemplo, una Puntería de 4+ se transforma en 5+).

### Disparar dentro o fuera de la Atmósfera

::: tip _La dificultad de disparar entre Capas orbitales aumenta al intentar disparar a través de la Atmósfera, donde disparar cualquier tipo de arma se vuelve altamente impreciso debido a pérdidas de energía, dispersiones de plasma, etc. Apuntar y causar daño de forma efectiva a naves o ciudades en la Atmósfera es más o menos similar a golpear un objeto en el fondo de un estanque lleno de limo_.
:::

**A menos que un sistema de armas esté específicamente diseñado para atacar en este tipo de situaciones, cualquier sistema de armas que dispare en la Atmósfera o a ua nave ubicada en la Atmósfera tendrá un valor de Puntería para dicho ataque de 6+, independientemente de cualquier otro modificador. Además, el rango de detección para disparar se limita al valor de Escáner del atacante**. La Señal y Picos de energía son ignorados.

Los Sistemas de Armas de Corto Alcance no pueden ser disparados hacia dentro o hacia fuera de la Atmósfera.

Los Sistemas de Armas de Corto Alcance no pueden ser disparados mientras la nave esté en la Atmósfera, a no ser que así lo especifique una regla especial de la nave o el sistema de armas.

Ciertas reglas como Bombardeo o Aire/aire ignoran los penalizadores por disparar a través de capas orbitales. Dichas excepciones están cubiertas en la sección de reglas especiales o en los perfiles individuales de cada nave.

### Bombardeo

A veces, el mejor curso de acción es destruir el mismo planeta por el que se está luchando. Las naves pueden apuntar a Sectores (ver [Sectores](/es/dfc/core-rules/ground-combat#sectores)) como cualquier otro objetivo, pero se aplican las siguientes reglas. Consulte la sección [Combate terrestre](/es/dfc/core-rules/ground-combat) para obtener más detalles sobre sectores y clústers.

**Los Sectores solo pueden ser elegidos como objetivo por naves en Órbita baja** y siguen las mismas normas que cualquier otro elemento situado en la Atmósfera.

Si un Sector recibe daño, se realizan salvaciones igual que si fuera cualquier otra nave. Los Impactos Críticos ignoran las salvaciones por armadura al igual que contra naves, pero dado que la mayoría de armas tendrán un valor de Puntería de 6+ por hacer objetivo a algo en la Atmósfera, únicamente las armas especializadas podrán causar Impactos Críticos. (por ejemplo, armas con la regla especial Bombardeo). **Únicamente pueden elegirse Sectores como objetivo de un sistema de armas si no contiene ningún activo terrestre amigo**.

### Daño Colateral por Bombardeo

Si un Sector sufre un punto de daño y el Sector está ocupado por Activos terrestres debes realizar una tirada para evaluar daños colaterales. Cada punto de daño causará un punto de daño en un Activo terrestre en dicho sector (las tiradas de salvación por armadura se tiran normalmente - ver la sección [Activos terrestres](/es/dfc/core-rules/ground-combat#activos-terrestres) para más detalles). El jugador que infligió el daño elige como distribuir este daño. Debe causarse un punto de daño a cada Activo terrestre antes de poder causar un segundo punto de daño a cualquiera de ellos.

Un sector que pierde todos sus puntos de Casco se convierte en ruinas. Si hay cualquier  Activo terrestre en el sector, realiza una tirada de un D6. Con un resultado de 2 o más todos los Activos Terrestres en el sector son destruídos, para representar la devastación apocalíptica realizada en un area amplia de la superficie. Esto también elimina el valor estratégico del Sector. Las ruinas también pueden ser bombardeadas para tratar de eliminar activos terrestres, pero dado que las ruinas no tienen valor de Casco, no conservarán dicho daño causado en turnos posteriores.
