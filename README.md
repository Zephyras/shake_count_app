# shake_count_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


[패스트캠프 플러터 공부]
* velocity_x 라이브러리 정리
  * 위젯을 가독성을 높혀주는 라이브러리
  * 파라미터 선언을 
  * TextWidget 경우 Text(size: 20, 
                        color:Colors.red),
  * velocity_x 적용 예시 '흔들어서 카운트를 올려보세요.'
                        .text
                        .size(20)
                        .color(Colors.red)
                        .bold
                        .white
                        .black
                        .isIntrinsic
                        .makeCentered()
                        .box
                        .withRounded(value: 50)
                        .color(Colors.green)
                        .height(150)
                        // .size(70, 70)
                        .make()
                        .pSymmetric(h: 20, v: 50),
  