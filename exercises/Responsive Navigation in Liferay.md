---
uuid: 51c3ac8c-084d-4593-a8aa-042a9312894c
---

![Responsive Navigation in Liferay](./images/responsive-navigation-in-liferay/01.jpg)

# Responsive Navigation in Liferay

## A Masterclass on Using the Responsive Menu Fragments

* [Prerequisite: Verifying and Launching Liferay Workspace](#prerequisite-verifying-and-launching-liferay-workspace)
* [Optional Exercise: Uploading Language Properties](#optional-exercise-uploading-language-properties)
* [Exercise 1: Build a Responsive Menu](#exercise-1-build-a-responsive-menu)
* [Exercise 2: Customise styles & behaviour](#exercise-2-customise-styles-and-behaviour)
* [Exercise 3: Accessibility & mobile usability](#exercise-3-accessibility-and-mobile-usability)
* [Exercise 4: Adapt menus for layouts](#exercise-4-adapt-menus-for-layouts)

## Prerequisite: Verifying and Launching Liferay Workspace

*If you already have a fully conifgured Liferay Workspace, then you can skip to the next lesson.*

Throughout this training, you’ll use a local Liferay environment. Here you’ll verify that you’ve completed the prequisits and finish setting up your workspace:

1. Open your terminal and verify you have Java JDK 21.

   ```bash
   java -version
   ```

   If you don't have Java 21 installed, see [Microsoft OpenJDK installation](https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-21) for instructions according to your OS.

2. Verify Git is installed:

   ```bash
   git version
   ```

   If Git is not installed, see [Git's official documentation](https://git-scm.com/downloads) for how to install it on your OS ([macOS](https://git-scm.com/download/mac)|[Windows](https://git-scm.com/download/win)|[Linux/Unix](https://git-scm.com/download/linux)).

3. Verify Liferay Blade CLI is installed:

   ```bash
   blade version
   ```

   If you don't have Blade installed, see [Blade CLI](https://learn.liferay.com/w/dxp/liferay-development/tooling/blade-cli) documentation for how to install it on your OS ([Linux/macOS](https://learn.liferay.com/w/dxp/liferay-development/tooling/blade-cli#installing-from-the-cli)|[Windows](https://learn.liferay.com/w/dxp/liferay-development/tooling/blade-cli#installing-from-the-graphical-installer)).

4. In your terminal, go to your desired folder and clone the training workspace to your computer:

   ```bash
   git clone https://github.com/liferay/liferay-course-building-enterprise-websites.git
   ```

   This saves a copy of the project in your current terminal directory.

   **Note**: If you've cloned the repo previously, ensure your workspace is up to date by running `git pull origin main`.

5. Go to the workspace's root folder in your terminal:

   ```bash
   cd liferay-course-building-enterprise-websites/
   ```

6. Initialize your Liferay bundle:

   ```bash
   blade server init
   ```

   If you don't have Blade installed, run this command:

   * **Unix-based systems**:

      ```bash
      ./gradlew initBundle
      ```

   * **Windows**:

      ```bash
      .\gradlew.bat initBundle
      ```

   This downloads and builds dependencies for running Liferay, including the Liferay server.

7. Start your Liferay server:

   **Blade**:

   ```bash
   blade server run
   ```

   * **Unix-based systems**:

      ```bash
      ./bundles/tomcat/bin/catalina.sh run
      ```

   * **Windows**:

      ```bash
      .\bundles/tomcat/bin/catalina.bat run
      ```

   **Tip**: Wait until you see `org.apache.catalina.startup.Catalina.start Server startup in X milliseconds` to indicate startup completion.

8. When finished, access your Liferay DXP instance by going to [http://localhost:8080/](http://localhost:8080/) in your browser.

9. Sign in using these credentials:

   * Username: `test@lifeary.com`
   * Password: `test`

Great! Now you're ready to start using the Responsive Menu fragments

## Optional Exercise: Uploading Language Properties

This is an optional step, but it will replace some of the label placeholders in Liferay so the text reads correctly.

1. Navigate to the Control Panel -> System -> Language Override
2. Click the (+) button to add a new language override.
3. From the dropdown menu, select "Upload"
4. Select the `Language_en_US.properties` file from the `resources` folder of this project.
5. Click "Publish"

## Exercise 1: Build a Responsive Menu

## Exercise 2: Customise styles and behaviour

## Exercise 3: Accessibility and mobile usability

## Exercise 4: Adapt menus for layouts
