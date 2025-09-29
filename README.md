import 'package:flutter/cupertino.dart';
import 'package:flutter/material.dart';

void main (){
  runApp(
    MaterialApp(
      home: Scaffold(
        backgroundColor: Colors.black,
        //appBar: AppBar(backgroundColor: Colors.amberAccent,
        body:Center(
       child:  Container(
         height: 150,
         width: 250,
         color: Colors.green,
         child: Container(
          margin: EdgeInsets.all(10),
           decoration: BoxDecoration(
             color: Colors.red,
             shape: BoxShape.circle

           ),
         

         ),

          )
          ),
        ),


      ),


  );
}
