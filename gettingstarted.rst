===========
Getting started
===========

Requirements
========

The goal of Simple Injector is to provide .NET application developers with an easy, flexible, and fast `Inversion of Control library <http://martinfowler.com/articles/injection.html>`_ that promotes best practice to steer developers towards the pit of success.

Many of the existing IoC frameworks have a big complicated legacy API or are new, immature, and lack features often required by large scale development projects. Simple Injector fills this gap by supplying a simple implementation with a carefully selected and complete set of features. File and attribute based configuration methods have been abandoned (they invariably result in brittle and maintenance heavy applications), favoring simple code based configuration instead. This is enough for most applications, requiring only that the configuration be performed at the start of the program. The core library contains many features and allows almost any :doc:`advanced scenario <advanced>`.

The following platforms are supported:

* *.NET 4.0* and up.
* *Silverlight 4* and up.
* *Windows Phone 8*.
* *Windows Store Apps*.
* *Mono*.

.. container:: Note

    Simple Injector is carefully designed to run in **partial / medium trust**, and it is fast; blazingly fast.

Getting started
===============

The easiest way to get started is by installing  `the available NuGet packages <https://simpleinjector.org/nuget>`_ and if you're not a NuGet fan then follow these steps:

#. Download the latest **runtime library** from: https://simpleinjector.org/download;
#. Unpack the downloaded `.zip` file;
#. Add the **SimpleInjector.dll** to your start-up project by right-clicking on a project in the Visual Studio solution explorer and selecting 'Add Reference...'.
#. Add the **using SimpleInjector;** directive on the top of the code file where you wish to configure the application.
#. Look at the :doc:`Using <using>` section in the documentation for how to configure and use Simple Injector.
#. Look at the :ref:`QuickStart-More-Information` section to learn more or if you have any questions.
