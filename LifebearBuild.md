# ビルド手順
1. `version.json` の `version` を書き換える。元のバージョン +100 にする
2. Dapper ディレクトリで `dotnet msbuild /p:Configuration=Release /p:PublicRelease=true /t:Pack`

# メモ
バージョン番号の管理には Nerdbank.GitVersioning が使われている。

https://github.com/AArnott/Nerdbank.GitVersioning
