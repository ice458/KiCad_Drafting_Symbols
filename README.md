# KiCad_Drafting_Symbols
KiCad9 用回路図シンボルです。  
サイズや見た目に統一感のある回路図を作ることができます。  
発表資料等、人に見せる用の回路図を清書する時に使うことを想定しています。  
CMOS回路を描くのに便利なシンボルが多く含まれます。MOSFETのシンボルにはW、L、Mのプロパティを設定できます。  

## 使い方  
[Drafting_Symbols.kicad_sym](Drafting_Symbols.kicad_sym) をシンボルライブラリに登録するだけです。  
[Drafting_Symbols.kicad_sym](Drafting_Symbols.kicad_sym) を Document/KiCad/9.0/symbols にコピーし、KiCadの設定からシンボルライブラリを追加してください。  
カラープロファイルは[Drafting_Color.json](Drafting_Color.json) を AppData/Roaming/kicad/9.0/symbols にコピーし、KiCadの設定から選択してください。 
詳しいKiCadの使い方は[公式ドキュメント](https://docs.kicad.org/9.0/ja/kicad/kicad.html)等を参照してください。  

このシンボルを使ったサンプルは[こちら](sample)です。  

## 作成例  
回路図エディターの表示オプション でフォントをArialに変更しています。  
カラープロファイルを設定した状態でプロットしています。  
 
CMOSオペアンプ  
<img src="doc/schematic1.png" width="500">  

論理回路など  
<img src="doc/schematic2.png" width="500">  