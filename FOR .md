void main (){
// 'var' declares a variable dartanalyzer infres the type.
  var a = "initial";
  print (a);
  
  // the type can also be declared:
  num b = 42;
  print (b);
  
  //final variables cannot be changed once declared
  final num c = 99;
  print (c);
  
  //const variables are compile-time constantas
  const double d = 44.00;
  print (d);
  
}