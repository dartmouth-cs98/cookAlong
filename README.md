# CookAlong

TODO: super short project description, some sample screenshots or mockups that you keep up-to-date.

CookAlong makes learning to cook an accessible experience with AR technology that streamlines the cooking experience, provide tutorials, explaination of cooking techniques, and a variety of recipes.

## Architecture

TODO:  overall descriptions of code organization and tools and libraries used
We will be using th MagicLeap headset with enviroment in conjuction with Unity for our front end.
In the backend we have a Java Springboot rest API with a AWS database storage

## Setup

TODO: how to get the project dev environment up and running, npm install etc, all necessary commands needed, environment variables etc

## Deployment

TODO: how to deploy the project

## Authors

TODO: list of authors

## Acknowledgments


# Magic Leap Unity Project Template

## Project

Hello, Cube!

## Versions

### Unity

2019.2.x

### MLSDK

v0.22.0

### LuminOS

0.97.x

## Downloading

1) Download the latest Source Code .`zip` release file from <https://github.magicleap.com/DevRelSamples/Unity-Project-Template/releases/>.
2) Extract the zip file in a directory of your choice.

## Instructions After Downloading

1) Using Unity Hub, download Unity 2019.2.x and make sure Lumin support is checked during installation
2) `ADD` the project using Unity Hub
3) Open the project using Unity Hub
4) Under File > Build Settings, make sure the build target is Lumin
5) Under Unity preferences, set the MLSDK path
6) Under project settings > publishing settings, set your cert path (and make sure the privkey file is in the same directory. If this is confusing, refer to and read our docs. There’s also a `README` in the privkey folder after unzipping)
7) Make sure USB debugging is enabled between your device and computer (which requires MLDB access) and you’re allowing untrusted sources
8) Open the `HelloCube` Scene from `Assets`>`Scenes`>`HelloCube`
9) Build and Run
10) Accept the cert if prompted after build is complete
11) There will be a cube 1 meter in front of where your current headpose session started
