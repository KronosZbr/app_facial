# 📸 App Facial - Detecção de Emoções

Este é um projeto Flutter que utiliza o **Google ML Kit** para detecção facial e reconhecimento de emoções básicas (como felicidade e seriedade) diretamente de imagens capturadas pela câmera ou selecionadas da galeria.

## 🚀 Funcionalidades

- 📷 **Captura de imagem** via câmera ou galeria
- 😊 **Detecção de rostos** nas imagens
- 😁 **Reconhecimento de emoções** simples (Feliz, Sério, Neutro)
- ⚡ **Processamento offline** usando Google ML Kit

## 🏗️ Como rodar o projeto

1. **Clone o repositório**
   ```bash
   git https://github.com/KronosZbr/app_facial
   cd app_facial
   ```
2. **Instale as dependências**
   ```bash
   flutter pub get
   ```
3. **Conecte um dispositivo físico** (a câmera geralmente não funciona bem no emulador)
4. **Execute o app**
   ```bash
   flutter run
   ```

## 📦 Dependências

O projeto utiliza as seguintes bibliotecas:

```yaml
dependencies:
  flutter:
    sdk: flutter
  camera: ^0.10.5+2
  google_mlkit_face_detection: ^0.10.0
  image_picker: ^1.0.4
  cupertino_icons: ^1.0.8
```

## 🧠 Estrutura de Código

- **main.dart**: Contém toda a lógica de inicialização do app
- **FaceDetectionScreen**: Tela principal com botões para capturar/selecionar imagens e exibir emoções
- **FaceDetector**: Configurações para o Google ML Kit, incluindo a detecção facial e classificação

## 🏷️ Exemplo de Uso

O app analisa as emoções faciais e exibe uma mensagem como:

```
Rosto detectado: Feliz (Confiança: 85%)
```

## 📚 Referências

- [Google ML Kit - Face Detection](https://developers.google.com/ml-kit/vision/face-detection)
- [google_mlkit_face_detection - pub.dev](https://pub.dev/packages/google_mlkit_face_detection)

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para contribuir!

---

💡 **Dica**: Se precisar de detecção de emoções mais avançadas (como raiva ou surpresa), considere integrar o TensorFlow Lite!

---

Desenvolvido por [João Vitor Dysarz](https://github.com/KronosZbr)

