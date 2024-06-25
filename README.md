# [FontImage not support woff2 format #23217](https://github.com/dotnet/maui/issues/23217)

# Steps to Reproduce

1. Download [Google Material Symbols/github](https://github.com/google/material-design-icons/blob/master/variablefont/MaterialSymbolsRounded%5BFILL%2CGRAD%2Copsz%2Cwght%5D.woff2)
2. Copy MaterialSymbolsRounded.woff2(renamed) to /Resources/Fonts
3. ConfigureFonts `fonts.AddFont("MaterialSymbolsRounded.woff2", "MaterialSymbols");`
4. Use it anywhere

![Issue23217](/MauiIssue_23217/Resources/Images/Screenshot_1719314678.png "#23217")
