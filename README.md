KunstmaanUtilitiesBundle by Kunstmaan
=================================

About
-----
The KunstmaanUtilitiesBundle for Symfony 2 is part of the bundles we use to build custom and flexible applications at Kunstmaan.
This bundle will contain a set of helpful helper classes.

Installation requirements
-------------------------
You should be able to get Symfony 2 up and running before you can install the KunstmaanUtilitiesBundle.

Installation instructions
-------------------------
Installation is straightforward, add the following lines to your deps file:

```
[KunstmaanUtilitiesBundle]
    git=https://github.com/Kunstmaan/KunstmaanUtilitiesBundle.git
    target=/bundles/Kunstmaan/UtilitiesBundle
```

Register the Kunstmaan namespace in your autoload.php file:

```
'Kunstmaan'        => __DIR__.'/../vendor/bundles'
```

Add the KunstmaanUtilitiesBundle to your AppKernel.php file:

```
new Kunstmaan\UtilitiesBundle\KunstmaanUtilitiesBundle(),
```

Contact
-------
Kunstmaan (support@kunstmaan.be)

Download
--------
You can also clone the project with Git by running:

```
$ git clone git@github.com:Kunstmaan/KunstmaanUtilitiesBundle.git
```
