```text
app/
├── data
│   ├── local
│   │   ├── SleepDatabase.kt
│   │   ├── SleepDao.kt
│   │   └── SleepEntity.kt
│   │
│   └── repository
│       └── SleepRepositoryImpl.kt
│
├── domain
│   ├── model
│   │   └── SleepNight.kt
│   │
│   ├── repository
│   │   └── SleepRepository.kt
│   │
│   └── usecase
│       ├── StartSleepTracking.kt
│       ├── StopSleepTracking.kt
│       └── GetSleepHistory.kt
│
├── presentation
│   ├── tracker
│   │   ├── TrackerScreen.kt
│   │   ├── TrackerViewModel.kt
│   │   └── TrackerUiState.kt
│   │
│   ├── quality
│   │   ├── QualityScreen.kt
│   │   ├── QualityViewModel.kt
│   │   └── QualityUiState.kt
│   │
│   └── navigation
│       └── AppNavGraph.kt
│
└── di
    └── AppModule.kt
```