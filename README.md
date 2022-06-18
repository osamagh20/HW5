
//  1- Method takes a value and prints what's inside .

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

// 2- Method only prints .

List names = ["osama", "Faisal", "Fahad", "Turki"];

main() {
  printinfo();
}

void printinfo() {
  for (var name in names) {
    print(name);
  }
}

// 3- Method takes a value and returns a value: 

import 'dart:io';

int? length = int.parse(stdin.readLineSync()!);
int? width = int.parse(stdin.readLineSync()!);

main() {
  print("Enter Length and Width for calculate the area ...");

  var area = calcArea();
  print("Area is ${area}");
}

calcArea() {
  print("Enter length :");
  length;
  print("Enter width :");
  width;
  return (length! * width!);
}

