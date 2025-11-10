# Liferay DEVCON 2025

## Responsive Navigation in Liferay

### A Masterclass on Using the Responsive Menu Fragments

This repository contains the resources for the Response Menu fragments masterclass from Liferay DEVCON 2025.

It contains a set of exercises which compliemnt the demonstratoin given within the session and gives participanets the opporunity to get hands-on experience on how to use them.

It also contains a number of additional resources to make it eaiser to complete these exercises.

## Folder Structure

The repository is structured as follows:

```sh
/
├───exercises/
│   ├───Responsive Navigation in Liferay.md
│   └───images/
├───resources/
│   ├───dxp-blue-fragments.zip
│   └───responsive-menus-collection.zip
└───workspace/
    ├───.blade.properties
    ├───build.gradle
    ├───Dockerfile.ext
    ├───GETTING_STARTED.md
    ├───gradle.properties
    ├───gradlew
    ├───gradlew.bat
    ├───platform.bndrun
    ├───settings.gradle
    ├───configs/
    ├───gradle/
    ├───modules/
    └───themes/
```

The main folders of interest are:

* `exercises`: Contains the [exercises for the masterclass](./../exercises/Responsive%20Navigation%20in%20Liferay.md).
* `resources`: Contains the resources needed for the exercises. The `responsive-menus-collection.zip` is the fragment set needed for the exercises and the `dxp-blue-fragments.zip` is a optional collection of fragments which help give more content to the pages within the workspace.
* `workspace`: Contains a Liferay 2025 Q1.8 LTS workspace for development. It has a local configuration aimed at making local development easier.

## Resources

Marketplace - <https://marketplace.liferay.com/p/responsive-menu-fragments>

<img src="./images/marketplace.png" width="100" alt="Marketplace QR Code">

Source Code - <https://github.com/peterrichards-lr/liferay-fragments/tree/main/responsive-menus>

<img src="./images/source.png" width="100" alt="Source Code QR Code">
