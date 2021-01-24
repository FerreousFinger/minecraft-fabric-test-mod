====================
Fabric Starter Guide
====================

#. Create repository using the Fabric Example Mod as a template
#. Update files
    - gradle.properties
    - README.md
    - LICENSE
#. Download repository

Step 1: Create Repository
=========================

The Fabric Example Mod is an easy way to start your Minecraft Mod.

First, log in to your GitHub account and navigate to the
`Fabric Example Mod Repository`_. Click on the *Use this template* button
to create a new repository using the Fabric Example Mod as a template.

.. _Fabric Example Mod Repository: https://github.com/FabricMC/fabric-example-mod

Step 2: Update Files
====================

Next, you need to update some files:

gradle.properties
-----------------

Open the gradle.properties file which is located in the root directory of the project.
Make sure that the **Fabric Properties** and **Dependencies** are fully up to date.
You can check them on `Fabric Latest Versions`_. Just select the Minecraft version your
making your mod for and copy the properties and dependencies to your gradle.properties file.

Also make sure to set the maven_group and the archives_base_name to your preferred values.
The **maven group** uniquely identifies your project across all projects. It should follow
`Java's package name rules`_. This means it starts with a reversed domain name you control,
for example: :code:`com.myname.projectname`. However, you should avoid using a domain name
if you don't own it. Use something like :code:`mcmods.myname.projectname` instead.

The **archives_base_name** usually matches the name of your project, although it doesn't
have to. It is commonly written in lowercase using dashes instead of whitespaces, e.g.:
:code:`project-name`.

.. _Fabric Latest Versions: https://modmuss50.me/fabric.html?&version=1.16.4
.. _Java's package name rules: https://docs.oracle.com/javase/specs/jls/se6/html/packages.html#7.7

README.md
---------

Replace the description of the Fabric Example Mod with a description of the mod you're going to create.
Besides introducing your mod to other people, this can serve as a guideline to keep track of the goals
for your mod.

LICENSE
-------

Replace the license of the Fabric Example Mod with a license of your choice. If you're not sure which
license to use for your project, take a look at `choosealicense.com`_.

.. _choosealicense.com: https://choosealicense.com/

Step 3: Download Repository
===========================

First, open IntelliJ IDEA and click on the *Get from VCS* button. Next, copy the URL of your
repository and past it into the *URL* field. When your done click *Clone* to donwload a copy
of your project to your computer.

Step 4:
=======
