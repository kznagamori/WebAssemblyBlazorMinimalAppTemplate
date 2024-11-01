# WebAssemblyBlazorMinimalAppTemplate
最小限のBlazor WebAssembly アプリを作成するためのテンプレート

## 使用法

### テンプレートの取得
[WASMBlazorApp.nupkg](https://github.com/kznagamori/WebAssemblyBlazorMinimalAppTemplate/releases/download/v1.0.0/kznagamori.WASMBlazorMinApp.1.0.0.nupkg)
をダウンロードします。

### テンプレートのインストール
ダウンロードしたnugetパッケージをインストールします。
```
dotnet new install kznagamori.WASMBlazorMinApp.1.0.0.nupkg
```

### Blazor WebAssembly アプリ プロジェクトの作成
```
dotnet new wasm-blazor.min -n <プロジェクト名>
```
**例:** `dotnet new wasm-blazor.min -n MyWasnBlazorMinApp`

### テンプレートのアンインストール
```
dotnet new  uninstall kznagamori.WASMBlazorMinApp
```

### ターゲット

net8.0のみをターゲットとしています。

### ビルド

```
dotnet build
```

### 動作確認
```
dotnet watch run
```

### kznagamori.WASMBlazorMinApp.X.X.X.nupkgの作成

```
nuget pack .\WebAssemblyBlazorMinimalAppTemplate.nuspec
```

