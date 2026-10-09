الفنان الصغير 
تفضل، هذا هو الكود بالكامل جاهز للنسخ: ```kotlin
Surface( modifier = Modifier.fillMaxSize(), color = MaterialTheme.colorScheme.background
) { var text by remember { mutableStateOf("") } TextField( value = text, onValueChange = { text = it }, label = { Text("أدخل CompositionLocalProviderالنصCompositionLocalProvider هناCompositionLocalProvider") } )
}
`
