# Cities-Board Eclipse Plugin

This repository contains the Cities-Board Eclipse plugin, which enables the installation and use of Cities-Board, a tool that automates the development of graphic dashboards for smart cities. If you are interested on extend the Cities-Board project, you should visit our [cities-board-dev](https://github.com/cabrerac/cities-board-dev) repository.

## Requirements

Cities-Board was developed on top of the Eclipse Modelling Framework (EMF). Please install Eclipse following the next steps:

1. Download the latest version of the [Eclipse Installer](https://www.eclipse.org/downloads/packages/installer).
2. Open the installer and select the Eclipse Modelling Tools package.
3. Click on Install.

## Installation

Please follow the next steps to install Cities-Board in Eclipse:

1. Download the file [cities-board-update.zip](https://github.com/cabrerac/cities-board/blob/master/cities-board-update.zip) from this repository.
2. Open Eclipse and Click on Help -> Install New Software.
3. Click on Add -> Archive -> Select the file cities-board-update.zip from your file system.
4. Click on Next and follow the installation wizard.

## Use

1. Open Eclipse and Click on File -> New -> Modeling Project.
2. Right click on the Project -> Viewpoints Selection -> Check cdb.
3. Right click on the project -> New -> Other -> Cdb Model.
4. Follow the wizard and select the element Dashboard as Model Object.
5. Expand the model in the project, right click on Dashboard -> new Representation -> new Cities-Board Diagram.

Now, you should see the Cities-Board environment where you can create your dashboards models. 

## Code Generation

You can generate the code for the modeled dashboard once it is ready, following the next steps:

1. Click on the icon Generate Dashboard Code.
2. Select the path where you want to save the generated code.
3. Select the model to transform

A success message confirms the code generation, you can find the ASP.Net project that implements your dashboard in the path specified in the step 2.
  
