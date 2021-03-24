void main() {
  // 'var'deslares a variable. dartanalyzer infers the type.
  var a = "initial";
  print(a);
  
  //the type can also be declared:
  num b = 42;
  print (b);
  
  //final variables cannot be changed once deslared
  final num c = 99;
  print(c);
  
  //const variables are compile-time constants
  const double d = 44.00;
  print(d);
}