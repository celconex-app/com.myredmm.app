# com.myredmm.app
Esta aplicación móvil es una herramienta de bolsillo para el reconocimiento táctico y la auditoría pasiva de ciberseguridad en tiempo real. Permite a ingenieros de software, administradores de sistemas y analistas de seguridad escanear cualquier dirección web o API directamente desde su dispositivo móvil.


#Estructura.........................................
............................
.................
..........
....

MyRed-M-M/
│
├── settings.gradle.kts
├── build.gradle.kts
├── gradle.properties
│
└── app/
    │
    ├── build.gradle.kts
    │
    └── src/
        │
        └── main/
            │
            ├── AndroidManifest.xml
            │
            ├── java/
            │   └── com/
            │       └── myredmm/
            │           └── app/
            │               │
            │               ├── MainActivity.kt
            │               │
            │               ├── ui/
            │               │   ├── ScannerScreen.kt
            │               │   ├── components/
            │               │   │   ├── CounterCard.kt
            │               │   │   ├── VulnerabilityCard.kt
            │               │   │   └── DetailBottomSheet.kt
            │               │   │
            │               │   └── theme/
            │               │       ├── Color.kt
            │               │       ├── Theme.kt
            │               │       └── Type.kt
            │               │
            │               ├── data/
            │               │   ├── model/
            │               │   │   ├── Severity.kt
            │               │   │   └── Vulnerability.kt
            │               │   │
            │               │   └── repository/
            │               │       └── ScannerRepository.kt
            │               │
            │               ├── domain/
            │               │   └── usecase/
            │               │       └── AnalyzeHeadersUseCase.kt
            │               │
            │               ├── network/
            │               │   ├── HttpClientProvider.kt
            │               │   └── HeaderAnalyzer.kt
            │               │
            │               └── viewmodel/
            │                   └── ScannerViewModel.kt
            │
            └── res/
                ├── values/
                │   ├── colors.xml
                │   ├── strings.xml
                │   └── themes.xml
                └── xml/
                    └── network_security_config.xml
