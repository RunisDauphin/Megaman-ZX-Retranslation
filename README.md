Parche de retraducción para Megaman ZX (NDS) / Patch de retraduction pour Megaman ZX (NDS)

Servidor de Discord / Serveur de Discord: https://discord.com/invite/3CrMpGxGHB

(Pour lire la version française de ce "Lisez-moi", descendez vers la moitié du fichier).

(Español)

Este parche es una retraducción de Megaman ZX que modifica las versiones española y francesa del juego para corregir fallos ortográficos y gramaticales que aparecen en todos los textos, así como arreglar algunas decisiones cuestionables de la versión originalmente lanzada en 2005 para dar una mejor experiencia de juego.

Preguntas frecuentes:

1->/¿Qué necesito?

Necesitarás los siguientes archivos:

-/El parche correctamente extraído (ir a la sección "Releases" disponible desde esta página).
-/Una copia europea de la versión de Nintendo DS de Megaman ZX (este archivo deberán obtenerlo por sus propios medios; no lo pidan por acá ni en Discord, ni publiquen enlaces de descarga del juego, puesto que les bloquearé inmediatamente así como borraré sus enlaces). Es importante que proporcionen una copia europea, ya que es la única que tiene español y francés.
-/DeltaPatcher, correctamente extraído, para poder aplicar el parche (disponible en https://github.com/marco-calautti/DeltaPatcher/releases)
-/El parche NDS Slot 2 Patch de Prof. 9 (disponible en https://github.com/Prof9/MMZX-Slot2-Patch/releases, es completamente opcional)
-/El parche de undub de este juego es incompatible con este parche, porque se diseñó para la versión japonesa y este parche se diseñó para la europea.

2->/Tengo todos los archivos que figuran en la pregunta 1. ¿Cómo parcheo?

Para ello deberás abrir el programa DeltaPatcher. Allá te pedirá aportar dos archivos.
El paquete contiene dos archivos.
El que simplemente dice Retranslation está pensado para ser aplicado sobre una copia limpia y original de Megaman ZX, versión europea, para Nintendo DS. Por ende, deberás indicar en el hueco de arriba dónde está tu archivo de Megaman ZX (tendrá extensión .nds) y abajo el archivo .xdelta que te he proporcionado. Le das a Apply Patch y ya estará listo.
El que dice NDS Slot 2 Patch - Retranslation está pensado para ser aplicado sobre una copia de Megaman ZX, versión europea, para Nintendo DS, previamente parcheada con el parche de Prof. 9 que está enlazado en la pregunta 1. El orden es importante (es decir, primero deberás aplicar el parche de Prof. 9 y luego éste). Por ende, deberás indicar en el hueco de arriba dónde está tu archivo de Megaman ZX ya parcheado (tendrá extensión .nds) y abajo el archivo .xdelta que te he proporcionado. Le das a Apply Patch y ya estará listo.

3->/He conseguido aplicar el parche sobre Megaman ZX. ¿Para qué sirve esto?

Esto sirve para corregir varios fallos de la versión original del juego en sus versiones española y francesa (el parche corrige ambas versiones simultáneamente). Estas correcciones consisten en:

-/Se han suprimido huecos innecesarios para ahorrar espacio (cada hueco eliminado reduce en un byte el tamaño del bloque).
-/Todas las instancias de la palabra "Disidente" han sido sustituidas por "Maverick", para mantener la terminología ya introducida en Megaman X.
-/La Base de los Guardianes ha pasado a denominarse "SC de los Guardianes" (SC significa "Sede Central").
-/Por traducción de la palabra francesa "livreur", todas las instancias de mensajero han sido sustituidas por repartidor.

4->/Supongamos que quiero probar otro idioma distinto a español y francés (por ejemplo, inglés). ¿Significa que ya no puedo jugar con ellas?

No. Lo que significa es que tu experiencia sería exactamente igual que si no hubieras aplicado este parche (es decir, este parche no modifica los textos de los otros cuatro idiomas).

5->/Los nombres de las cajas de texto no se ajustan a los nuevos nombres. ¿Por qué pasa esto?

Lo más seguro es que estés jugando a la versión francesa. Eso se produce porque desconozco dónde se hallan esos textos en el archivo del juego y por ende no están modificados y siguen los nombres antiguos.

6->/Yo ya tenía una partida de antes y quiero probar este parche pero no perder progreso. ¿Puedo hacerlo?

Todos los archivos de salvado son compatibles entre sí sin hacer modificaciones extra. Es decir, independientemente de cuál de las cuatro combinaciones posibles tenga (ningún parche, solo NDS Slot 2, solo retraducción o ambos parches), la partida puede ser continuada en cualquiera de las cuatro combinaciones (asegúrense de que el archivo de salvado esté bien nombrado, normalmente emuladores y cartuchos flash exigen que juego y archivo de salvado tengan el mismo nombre).

7->/He empezado una partida, he salvado y cuando vuelvo a cargar me dice que no hay partida. ¿Qué ha pasado?

Esto supongo que es un sistema antipiratería que trae el juego base y que se activa con algunos cartuchos flash. Desconozco qué lo produce (no encuentro información en Internet al respecto) pero sí sé como evitarlo. Si se produce, simplemente abre el juego en un emulador de DS como melonDS o DeSmuME, llega hasta el primer punto de salvado que el juego ofrezca (después de la misión inicial) y salva. Una vez hayas hecho esto, el juego nunca más activará el sistema antipiratería (por si acaso, recomiendo que, si vais a jugar simultáneamente con Vent y con Aile, una partida con cada uno, hagáis este procedimiento con cada uno antes de transferir la partida).

8->/He conseguido extraer el juego de la colección Megaman Zero/ZX Legacy Collection. ¿Es compatible con este parche?

Lo desconozco, y este parche no está diseñado para esa versión. No se responderán cuestiones relacionadas con ella.

9->/He encontrado un bug. ¿Cómo lo notifico?

Te recomiendo que para ello vayas al servidor de Discord enlazado y lo comuniques allá.

10->/Soy el actual poseedor de los derechos de Megaman ZX (a fecha de la escritura de este documento, Capcom es la propietaria). ¿Puedo utilizar este parche en mi versión?

Sí. Perfectamente. No hay ningún problema al respecto.

11->/¿Cómo se ha hecho este parche?

Este parche se ha hecho con la ayuda de Translhextion, donde, con la ayuda de una tabla de caracteres tbl, se ha visionado mejor los textos, y HxD, donde se han modificado los textos manualmente. También se modificaron los punteros en HxD para que apunten a los lugares correctos.

(Français)

Ce patch est une retraduction de Megaman ZX qui modifie les versions espagnole et française du jeu pour corriger des erreurs ortographiques et grammaticals qui apparaissent dans tous les textes, et arranger quelques décisions questionables de la version originalement lancée en 2005 pour donner une meilleure expérience de jeu.

Questions fréquentes:

1->/Qu'est-ce que j'ai besoin?

Vous aurez besoin de ces fichiers:

-/Le patch correctement extraît (aller à la section "Releases" disponible depuis cette page).
-/Une copie européenne de la version de Nintendo DS de Megaman ZX (ce fichier doit être obtenu par vos propres moyens; ne le demandez pas ici ni sur Discord, et ne publiquez pas de liens de télécharge du jeu, car vous serez immédiatement bloqué(e)s et j'effacerai vos liens). C'est important que vous fournissez une copie européenne, car c'est l'unique en avoir espagnol et français.
-/DeltaPatcher, correctement extraît, pour appliquer le patch (disponible sur https://github.com/marco-calautti/DeltaPatcher/releases)
-/Le patch NDS Slot 2 Patch de Prof. 9 (disponible sur https://github.com/Prof9/MMZX-Slot2-Patch/releases, il est complètement optionnel)
-/Le patch d'undub de ce jeu est incompatible avec ce patch, parce qu'il était conçu pour la version japonaise et ce patch était conçu pour l'européenne.

2->/J'ai tous les fichiers réflechis dans la Question 1. Comment je patche?

Pour ça vous devrez ouvrir le programme DeltaPatcher. Le programme vous demandera apporter deux fichiers.
Le paquet contient deux fichiers.
Celui-ci qui simplement dit Retranslation est pensé pour être appliqué sur une copie propre et originale de Megaman ZX, version européenne, pour Nintendo DS. Donc vous devrez indiquer dans l'espace au dessus où est votre fichier de Megaman ZX (il aura extension .nds) et au dessous le fichier .xdelta que je vous ai fourni. Cliquez Apply Patch et vous êtes pret.
Celui-ci qui dit NDS Slot 2 Patch - Retranslation est pensé pour être appliqué sur une copie propre et originale de Megaman ZX, version européenne, pour Nintendo DS. Donc vous devrez indiquer dans l'espace au dessus où est votre fichier de Megaman ZX (il aura extension .nds) et au dessous le fichier .xdelta que je vous ai fourni. Cliquez Apply Patch et vous êtes pret.
El que dice NDS Slot 2 Patch - Retranslation est pensé pour être appliqué sur une copie de Megaman ZX, version européenne, pour Nintendo DS, antérieurement patchée avec le patch de Prof. 9 qui est lié dans la question 1. C'est important, l'ordre (c'est à dire, premier vous devrez appliquer le patch de Prof. 9 et après celui-ci). Donc vous devrez indiquer dans l'espace au dessus où est votre fichier de Megaman ZX déjà patché (il aura extension .nds) et au dessous le fichier .xdelta que je vous ai fourni. Cliquez Apply Patch et vous êtes pret.

3->/J'ai réussi à appliquer le patch sur Megaman ZX. Quelle est son utilité?

Ceci sert à corriger quelques erreurs dans la version originale du jeu en ses versions espagnole et française (le patch corrige les deux versions simultanément). Ces corrections consistent en:

-/Tous les espaces innecessaires ont été supprimés pour économiser espace (chaque espace eliminé reduit en un byte la taille du bloc).
-/Tous les noms des Gardiens ont été retournés à ses noms originaux, qui étaient en français (pour quelque raison, en 2005, tous ces noms ont été changés de français à anglais seulement dans la version française du jeu). Rappelons-nous que, dans les jeux de Megaman Zero, beaucoup de membres de la Résistance avaient des noms en français. Les noms des pseudodroïdes ont aussi été retourné aux noms des autres versions, parce que les noms des pseudodroïdes commençaient par la même lètre que le modèle qu'ils protègeaient et, originalement, ce jeu de mots était perdu.
-/Le QG des Gardiens est maintenant dénommé "SC des Gardiens" (SC signifie "Siège Central").

4->/Supposons que je veux jouer en une langue différente à espagnol et français (par exemple, anglais). Ça signifie que je ne pouurai plus jouer avec elles?

Non. Ça signifie que ton expérience serait exactement égale que sans avoir appliqué ce patch (c'est à dire, ce patch ne modifie pas les textes des autres quatre langues).

5->/Les noms des boîtes texte ne s'ajustent pas aux nouveaux noms. Pourquoi ça se passe?

Ça se produit parce que j'ignore où ces textes sont dans le fichier du jeu, ils n'ont pas été modifiés et ils continuent en avoir les vieux noms.

6->/J'ai déjà eu une partie et je veux essayer ce patch, mais je ne veux pas perdre aucun progrès. Peux-je le faire?

Tous les fichiers de suavegarde sont compatibles parmi eux sans modifications extra. C'est à dire, indépendentement de quelle des quatre combinaisons possibles j'aie (aucun patch, seulement NDS Slot 2, seulement retraduction ou les deux patches), la partie peut être continuée n'importe sur quelle des quatre combinaisons (assûrez-vous que le fichier de sauvegarde est correctement nommé, normalement émulateurs et cartouches flash requièrent que le jeu et le fichier de sauvegarde aient le même nom).

7->/J'ai commencé une partie, j'ai sauvé et, quand je recharge le jeu me dit qu'il n'y a pas de partie. Que s'est-il passé?

Je crois que c'est un système antipiraterie qui vient avec le jeu base et s'active avec quelques cartouches flash. J'ignore pourquoi ça se passe (je ne rencontre aucune d'information sur Internet au sujet) mais je sais comment l'éviter. Si ça se produit, simplement ouvre le jeu dans un émulateur de DS comme melonDS ou DeSmuME, arrivez jusqu'au premier point de sauvegarde que le jeu offre (après la première mission) et sauvez. Une fois vous avez fait ceci, le jeu n'activera plus le système antipiraterie (par précaution, je vous recommande que, si vous allez jouer simultanément avec Vent et avec Aile, une partie avec chacun, suivez ce processus avec chacun avant de transférer la partie).

8->/J'ai achevé à extraîre le jeu de la colection Megaman Zero/ZX Legacy Collection. Est-elle compatible avec ce patch?

Je l'ignore, et ce patch n'a pas été conçu pour cette version. On ne répondra aucune question associée avec elle.

9->/J'ai rencontré un bug. Comment je le notifie?

Je vous recommande que vous allez sur le serveur Discord lié et vous communiquez là.

10->/Je suis l'actuel propriétaire des droits de Megaman ZX (à date de l'écriture de ce document, Capcom est la proprietaire). Peux-je utiliser ce patch dans ma version?

Oui. Parfaitement. Il n'y a aucun problème au sujet.

11->/Ce patch, comment c'est fait?

Ce patch est fait avec l'aide de Translhextion, où, avec l'aide d'une table de caractèrs tbl, on a mieux visionné les textes, et HxD, où on a modifié manuellement les textes. On a modifié aussi avec HxD les pointeurs pour qu'ils pointent aux lieux corrects.

Gracias por utilizar este parche.

Merci pour utiliser ce patch.
