Fancy Containers
Fancy container package lets you add a beautiful gradient container to your Flutter app.

Installation
Add the latest version of package to your pubspec.yaml (and rundart pub get):
dependencies:
  fancy_containers: ^0.0.1
Import the package and use it in your Flutter App.
import 'package:fancy_containers/fancy_containers.dart';
Example
There are a number of properties that you can modify:

height
width
title
subtitle
gradient (color1 and color2)
class FancyScreen extends StatelessWidget {  
  const FancyScreen({Key? key}) : super(key: key);  
  
  @override  
  Widget build(BuildContext context) {  
    return Scaffold(  
      body: Center(  
        child: const FancyContainer(  
          title: 'Hello World',  
          color1: Colors.lightGreenAccent,  
          color2: Colors.lightBlue,  
          subtitle: 'This is a new package',  
        ),  
      ),  
    );  
  }  
}

Next Goals
 Add onTap for functions. Now, you can specify the onTap and specify a function.

 Change font and color style for text. Change color by specifying textcolor and subtitlecolor properties.

 Add more containers to the package.