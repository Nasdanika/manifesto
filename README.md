# Nasdanika Manifesto

This manifesto outlines the guiding principles behind Nasdanika products and provides a brief overview of the core products.   

## Principles

* Effective knowledge elicitation, retention, and dissemination:
    * Capturing of knowledge in documented models.
    * Web-based documentation system serving models documentation and visualizations. 
* Working at a high level of abstraction by leveraging model-driven development.
* Elimination of repetitive tasks through code generation and metadata-driven logic.
* Focus - full stack [T-shaped](https://en.wikipedia.org/wiki/T-shaped_skills) developer with deep knowledge of Java.

## Products 
* [Server](https://github.com/Nasdanika/server) - An OSGi-based framework for domain-driven development of web applications
    * [CDO](https://github.com/Nasdanika/server/tree/master/org.nasdanika.cdo)
        * [Security](https://github.com/Nasdanika/server/tree/master/org.nasdanika.cdo.security)
        * [Web](https://github.com/Nasdanika/server/tree/master/org.nasdanika.cdo.web)
            * [Doc](https://github.com/Nasdanika/server/tree/master/org.nasdanika.cdo.web.doc) - visualization
    * [Web](https://github.com/Nasdanika/server/tree/master/org.nasdanika.web)
* [HTML](https://github.com/Nasdanika/html) - Java bindings for HTML, Bootstrap, Font Awesome, KnockoutJS and AngularJS
* [Workspace Wizard](https://github.com/Nasdanika/workspace-wizard) - Wizards to generate modeling project workspace and NFS-based application workspace
* [Code generation](https://github.com/Nasdanika/codegen) - Code generation Ecore/CDO model and editor
    * [Ecore](https://github.com/Nasdanika/codegen-ecore) - Code generation from EMF Ecore models.
        * [Web UI Generation Target](https://github.com/Nasdanika/codegen-ecore-web-ui) - Generators and templates for generating CRUD NFS routes from selected EClasses
* [WebTest](https://github.com/Nasdanika/webtest) - Web/mobile UI testing framework
    * [Model](https://github.com/Nasdanika/webtest-model) - Ecore/CDO model for storing results of Web UI tests.
* [Story](https://github.com/Nasdanika/story) - User story model and editor
* [Server-side Java Development for Innovators](https://github.com/Nasdanika/server-side-java-development-for-innovators) - Sources of the [Server-side Java Development for Innovators](https://server-side-java-development-for-innovators.books.nasdanika.org/) book.
 