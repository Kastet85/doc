:orphan:

Gérer les tâches
================

Cet onglet permet de :

-  ajouter une nouvel tâche à cet élément ;
-  visualiser l'historique des tâches liées à cet élément (suivant les
   droits sur les tâches définis dans le profil) ;
-  modifier une tâche en cliquant sur la ligne correspondante dans le
   tableau.

.. figure:: /image/tache.png

   Onglet Tâches d'un ticket

Les icones de gauche vous permettent de visualiser rapidement le statut
d'une tâche. Dans l'image vous avez successivement une tâche faite, à
faire, en information et planifiée.

Une tâche peut :

-  avoir une *catégorie* (Voir `Configurer les
   intitulés <config_dropdown.html>`__) ;

-  avoir un *statut* (Information, A faire ou Fait), le statut par
   défaut étant ``A faire`` ;

-  être *privée* ou non Une tâche privée n'est visible que :
-  de son rédacteur ;
-  du technicien à qui elle a été affectée ;
-  des utilisateurs ayant le droit adéquat dans leur profil.

-  avoir une *durée* , ce qui permet au technicien de saisir la durée
   réelle de traitement de la tâche, notamment à fin de statistiques ou
   facturations ;

-  et être affecté à un technicien (*par*) ;

-  être associé au planning en cliquant sur **Planifier cette tâche**.
   Une fois la date de début, la durée ou la date de fin saisie, la
   tâche apparaîtra sur le planning du technicien à qui elle a été
   affectée.

***Remarques :***

*- Pour faciliter la planification d'une tâche, il est possible de
vérifier la disponibilité des techniciens. L'icône |image| à côté du mot
Durée ouvre une nouvelle fenêtre proposant un résumé rapide des périodes
libres du technicien séledtionné dans le champ Par.*

*- Il est possible de définir un rappel de la tâche avant son début en
définissant un intervalle de temps pour le rappel. Les notifications
doivent être activées pour cela (voir `Configurer les
notifications <config_notification.html>`__)*.

--------------

**Sujet parent :** `Gérer les
tickets <modules/assistance/tickets/ticketmanagement>`__

**Sujet parent :** `Gérer les
problèmes <modules/assistance/problems>`__

**Sujet parent :** `Gérer les
changements <modules/assistance/changes>`__

.. |image| image:: /image/reservation-3.png

