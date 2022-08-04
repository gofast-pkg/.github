# GoFast PKG

## Motivation

In every compagny in which i have worked, i have developed each time the same core components (like http server, logger, tooling for observabilities, loading configuration, boilerplate(s) and more ...

This steps could not be avoid because the packages need to be wrapped to have a common configuration inside a compagny, to perform conform unit tests and to have a mocks stuff.

My motivation is to try to provide a consensus definition about the how write a package for all compagny like a framework to help to develop more fast with a robust adoption.

I know it can't help 100% company and 100% developers but i think it can help many of them.

And you ? What did you think ?

## Criteria(s)

* LICENCE LGPL v3 for each organization's repository
* Mocks for each interfaces inside a 'mock' folder
* Only expose public Interface for each struct which contains dependency driver (external dependency signature)
* Provide an example usage for each interface (it's permitted to use mock to avoid the connections
* Each packages need to be idempotent and use a Hexagonal architecture (auto loading from environment variables)
* Repositories need to respect the semver versionning

## Coverred subject

I will develop here only that i need for my personnal projects, but i will think the packages for a genaral usage to cover your common usages.

Nothing is never perfect, so, i invite you to contribute on all subjects.  

If you have specific needs and do not have the ressources to develop it/them, i am freelancer and i can accept contract(s) to upgrade this organization for you. 

## Licence

The repositories inside the gofast-pkg organization are coverred by the [GNU Lesser General Public Licence v3](#LICENCE.md)
