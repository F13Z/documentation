TA
=======

Ceci est un exemple de doc sur les TA !!!

.. figure:: images/moi.jpeg
    :align: center
    

### Comportement constaté

```gherkin
     Étant donné un OT de type "Fibre" dans le module "Affectation"
     Et l'activité/produit est "Act. Prod."
     Lorsque la vue est réglé en "Fibre"
     Alors le NRO de l'ot ne s'affiche pas
     Et le PM de l'ot ne s'affiche pas
     Et la sécurité de l'ot ne s'affiche pas
```

### Comportement attendu

```gherkin
     Étant donné un OT de type "Type" dans le module "Affectation"
     Et le produit est "FTH"
     Lorsque la vue est réglé en "Fibre"
     Alors le NRO de l'ot s'affiche
     Et le PM de l'ot s'affiche
     Et la sécurité de l'ot s'affiche
```
