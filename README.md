
//  Method takes a value and prints what's inside .

import 'dart:io';

int? num1 = int.parse(stdin.readLineSync()!);
int? num2 = int.parse(stdin.readLineSync()!);

main() {
  print("Enter tow numbers for sumation it  : ");
  print("First Number : ");
  num1;
  print("Second Number : ");
  num2;

  sum(num1, num2);
}

void sum(num1, num2) {
  print(num1 + num2);
}

