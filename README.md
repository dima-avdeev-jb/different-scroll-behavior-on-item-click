```Kotlin
Column(
        Modifier
            .fillMaxSize()
            .verticalScroll(rememberScrollState()),
        horizontalAlignment = Alignment.CenterHorizontally,
        verticalArrangement = Arrangement.spacedBy(10.dp)
    ) {
        repeat(10) {
            Button(
                modifier = Modifier.size(200.dp, 400.dp),
                onClick = {}
            ) {
                Text("Hello, World!")
            }
        }
    }
```

