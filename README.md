import 'dart:io';

void main() {
  int x = 15;
  int? y;
  String? name;
  String? name2;
  double age = 11;
  print(x);
  print(y);
  name = 'jim';
  print(name);
  print('Welcome to ${name ?? 'Geust'}');

  age >= 18 ? print('able to vote ') : print('still kid');
  print(name2?.length);
  
}
