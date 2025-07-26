#Hello, guys! ✌️

class Pabllo {
  final String name = "Pabllo Oliveira Martins";
  final String position = "Desenvolvedor Júnior";
  final List<String> languages = ["Flutter", "Dart", "Python", "SQL"];

  String introduce() {
    return "Meu nome é $name,\n"
           "sou $position,\n"
           "e atualmente estou focado em: ${languages.join(', ')}.";
  }
}

void main() {
  final pabllo = Pabllo();
  print(pabllo.introduce());
}
