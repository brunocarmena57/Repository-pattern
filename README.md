# Bruno57.Repository
A Flexible Repository Framework for EF Core and Beyond

## Overview
**Bruno57.Repository** is a comprehensive repository framework crafted to simplify and unify the data access layer across modern applications. Based on solid design principles and abstraction patterns, it offers a customizable and scalable approach for implementing repositories that suit various project needs.

### This solution includes

#### Bruno57.Repository.Abstractions
A lightweight package containing interfaces and base abstractions for defining standardized data access contracts, adaptable to any backend or ORM.

#### Bruno57.Repository
A concrete implementation of the abstractions using Entity Framework Core, offering ready-to-use, production-quality repositories.
Thanks to its modular architecture, Bruno57.Repository enables developers to adopt parts of the framework independently or integrate them seamlessly as a whole.

## Features
* **Modular Abstractions:** Establish clean data access boundaries using Bruno57.Repository.Abstractions, promoting testability and decoupling.

* **Seamless EF Core Support:** Utilize ready-to-integrate repositories with Bruno57.Repository, optimized for Entity Framework Core workflows.

* **Highly Extensible:** Adapt or extend repository logic while maintaining a consistent and predictable interface.

* **Forward-Compatible:** Built with future support in mind, including upcoming integration with MongoDB and other non-relational databases.

## Getting Started

1. Install the Packages:

   Add the appropiate NuGet packages to your project:
    * For abstractions:
      ```
      dotnet add package Bruno57.Repository.Abstractions
      ```
    * For EF Core implementation:
      ```
      dotnet add package Bruno57.Repository
      ```

2. **Select Your Integration Path:**
    * Use **Bruno57.Repository** for projects leveraging Entity Framework Core.
    * Or implement your custom repository logic by referencing **Bruno57.Repository.Abstractions**.


3. **Define Your Domain:**
   Define repository interfaces and implementations for your domain entities using the provided abstractions to promote a clean and maintainable architecture.

## Active Development

Bruno57.Repository is actively developed and regularly improved.
My mission is to offer a flexible, future-proof framework that can adapt to evolving data access patterns.
We value community input and welcome your feedback to help shape the direction of the library.


