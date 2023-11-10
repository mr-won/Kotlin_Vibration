# Kotlin_Vibration
Kotlin_Vibration Vibrator를 이용한 코틀린 진동 

## 권한등록
![image](https://github.com/mr-won/Kotlin_Vibration/assets/58906858/416f4c36-802c-4419-b79d-625d4fcc4d75)
```
진동 효과를 내기 위해서 AndroidManifest.xml에 권한을 등록한다.
```
## Vibrator 실행코드 (SDK 버전 마다 상이함, 안드로이드 8)
![image](https://github.com/mr-won/Kotlin_Vibration/assets/58906858/50c34b69-fbb9-4478-a0d9-4952000a504f)
```
안드로이드 8 오레오 이상은 vibrate(vibrateEffect.createOneShot(시간, 진동세기)
이하는 vibrate(시간), 진동세기는 설정하지 못하는 것 같다.
```
