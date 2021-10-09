# dart
its the dart programming language, whats the difference between these 2 codes?

// the first one 
double NUMBER1(){
  print("Enter the 1st number");
  double mynum1 = double.parse(stdin.readLineSync());
  return mynum1; 
}

double NUMBER2(){
  print("Enter the 2nd number");
  double mynum2 = double.parse(stdin.readLineSync());
  return mynum2; 
}

String opr(String oprText){
  print("Enter an operation: ${oprText}");
  String oper = stdin.readLineSync();
  return oper;
}

void main() {
  
  double num1 = NUMBER1();
  double num2 = NUMBER2();
  String oper = opr("Enter an operation: +,-,/,* ");

}


// the second one

double NUMBER1(){
  print("Enter the 1st number");
  double mynum1 = double.parse(stdin.readLineSync());
  return mynum1; 
}

double NUMBER2(){
  print("Enter the 2nd number");
  double mynum2 = double.parse(stdin.readLineSync());
  return mynum2; 
}

String opr(){
  print("Enter an operation: +,-,/,* ");
  String oper = stdin.readLineSync();
  return oper;
}

void main() {
  
  double num1 = NUMBER1();
  double num2 = NUMBER2();
  String oper = opr();

}
