## 概要
Roadrunner ScenairoはMathWorksの提供する商品である。Roadrunnerというソフトウェアにシナリオ（シミュレーション）作成機能が追加されたもので、学生なら無料で使える:https://jp.mathworks.com/products/roadrunner-scenario.html  
本リポジトリをクローンすることでRoadrunner Scenarioが扱えるわけではないので注意。クローンして得られるものは環境とシーンシナリオのソースコードのみ。  
RoadRunner Scenario では、シミュレーションのために他のシミュレーターに接続するためのエディター内再生がサポートされている。シナリオは ASAM OpenSCENARIO形式でエクスポートでき、
エクスポートしたシナリオは、esmini などの OpenSCENARIO 対応の任意のシミュレーターやプレーヤーで使用できる。なお、Roadrunner Scenairo単体ではシミュレーションのパラメータを取得することは難しく、別途アドオン（Automated Driving Toolbox及びMATLAB）が必要になる。

## purpose
塩尻市における右折を対象としたシナリオ及びシーンを成果物として格納する。  

## Development Environment
以下のリンクを参照。  
Roadrunner Scenairo:https://jp.mathworks.com/products/roadrunner-scenario.html  

## repo structure
```
├── Assets  マップを作成するにあたって必要なアセット
├── Exports  シナリオ、シーンがxml,xodr形式で出力される
├── Project  恐らく既存のプロジェクトデータ
├── Scenarios  シナリオが格納されている
└── Scenes  シーンが格納されている
```
