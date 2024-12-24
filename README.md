# Removing-Debug-banner
//Simple code for removing Debug banner in Flutter is belowe:
import 'package:flutter/material.dart';
void main()=> runApp(MyApp());
class MyApp extends StatelessWidget {
  

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false, 
      title: 'Explore Pakistan',
      theme: ThemeData(primarySwatch: Colors.green),
    home: MyHomeApp(), );

  }
}
class MyHomeApp extends StatelessWidget {
  
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text("Debug has been removed sucessfully"),
      ),
    
      );
  }
}
