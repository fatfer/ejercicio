Git
Para otros usos de este t�rmino, v�ase GIT.
Git
Git-logo.svg
Desarrollador
Junio Hamano, Linus Torvalds
http://git-scm.com/
Informaci�n general
Dise�ador	Linus Torvalds
�ltima versi�n estable	1.9.0 (info)
14 de febrero de 2014; hace 34 d�as
G�nero	Control de versiones
Programado en	C, Bourne Shell, Perl1
Licencia	GNU GPL v2
Git es un software de control de versiones dise�ado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran n�mero de archivos de c�digo fuente. Al principio, Git se pens� como un motor de bajo nivel sobre el cual otros pudieran escribir la interfaz de usuario o front end como Cogito o StGIT. 2 Sin embargo, Git se ha convertido desde entonces en un sistema de control de versiones con funcionalidad plena. 3 Hay algunos proyectos de mucha relevancia que ya usan Git, en particular, el grupo de programaci�n del n�cleo Linux.
El mantenimiento del software Git est� actualmente (2009) supervisado por Junio Hamano, quien recibe contribuciones al c�digo de alrededor de 280 programadores.
�ndice  [ocultar] 
1 Caracter�sticas
2 V�ase tambi�n
3 Referencias
4 Enlaces externos
Caracter�sticas[editar]

El dise�o de Git se bas� en BitKeeper y en Monotone. 4 5
El dise�o de Git resulta de la experiencia del dise�ador de Linux, Linus Torvalds, manteniendo una enorme cantidad de c�digo distribuida y gestionada por mucha gente, que incide en numerosos detalles de rendimiento, y de la necesidad de rapidez en una primera implementaci�n.
Entre las caracter�sticas m�s relevantes se encuentran:
Fuerte apoyo al desarrollo no lineal, por ende rapidez en la gesti�n de ramas y mezclado de diferentes versiones. Git incluye herramientas espec�ficas para navegar y visualizar un historial de desarrollo no lineal. Una presunci�n fundamental en Git es que un cambio ser� fusionado mucho m�s frecuentemente de lo que se escribe originalmente, conforme se pasa entre varios programadores que lo revisan.
Gesti�n distribuida. Al igual que Darcs, BitKeeper, Mercurial, SVK, Bazaar y Monotone, Git le da a cada programador una copia local del historial del desarrollo entero, y los cambios se propagan entre los repositorios locales. Los cambios se importan como ramas adicionales y pueden ser fusionados en la misma manera que se hace con la rama local.
Los almacenes de informaci�n pueden publicarse por HTTP, FTP, rsync o mediante un protocolo nativo, ya sea a trav�s de una conexi�n TCP/IP simple o a trav�s de cifrado SSH. Git tambi�n puede emular servidores CVS, lo que habilita el uso de clientes CVS pre-existentes y m�dulos IDE para CVS pre-existentes en el acceso de repositorios Git.
Los repositorios Subversion y svk se pueden usar directamente con git-svn.
Gesti�n eficiente de proyectos grandes, dada la rapidez de gesti�n de diferencias entre archivos, entre otras mejoras de optimizaci�n de velocidad de ejecuci�n.
Todas las versiones previas a un cambio determinado, implican la notificaci�n de un camb