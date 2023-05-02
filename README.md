# pomodoro_mobx

# Projeto completo

"build.yaml" foi criado para tornar o processo de execução do comando "fvm flutter pub run build_runner watch" mais rápido. Quando executado sem o arquivo, o processo demora cerca de 18,0 segundos, mas com as configurações do arquivo, demora apenas 1,5 segundos. Isso ocorre porque o Flutter procura arquivos ".dart" em toda a aplicação, mas ao usar o arquivo "build.yaml", o processo de geração de código para o MobX é limitado à procura apenas dos arquivos em "lib/store" que possuem a extensão ".store.dart", tornando a busca mais eficiente e rápida.

A new Flutter project.

O aplicativo é baseado em um cronômetro que permite controlar o tempo de trabalho e descanso, e as modificações são realizadas utilizando MobX.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
