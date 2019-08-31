# Noodl-Component-Ambient

　NoodlでAmbientからデータを取得するコンポーネントです。

# サンプルフローの読み込み

 Noodlを起動し、プロジェクトの読み込みを行います。  

（１）　GithubからNoodl-Component-Ambientをダウンロードし解凍  

（２）　Noodlにプロジェクトを読み込む  
　　解凍したフォルダ内の「Ambient」を読み込みます。  

 ・Version 1.3.1  
　「Add exeternal project」

 ・Version 1.4.0  
 　「CREATE NEW PROJECT」→　「Add existing project」

 （３）読み込んだプロジェクトを開くとサンプルフローが展開される  

 # サンプルフロー
  サンプルフローは画面のタップをトリガとして、Ambientからデータを取得しコンソールに表示します。  
 事前にAmbientのチャネルを作成し、データを登録しておく必要があります。
 
 # コンポーネントの読み込み
 　他のプロジェクトにAmbientコンポーネントを読み込む方法です。  
  
  ・Version 1.3.1  
　「Library」→「Import local project」  
 　Choose components to importでAmbientにチェックしimport。
  
 ・Version 1.4.0  
 　「Library」  
  　Ambientプロジェクトを選択。  
   　ComponentのAmbientをチェックしimport。  

 # コンポーネントの説明  

　【入力】  
 　・Fetch      ：Ambientからデータを取得するトリガ  

　【出力】  
 　・data       ：取得したデータがJSON形式で出力されます  

　【プロパティ】  
 　・Channel ID ：　AmbentのチャンネルID  
 　・Read key   ：　Ambientの対象チャンネルのリードキー  
 　・Write key  ：　Ambientの対象チャンネルのライトキー（使用していません）  
 　・n          ：　データを取得する件数  

# ライセンス
　MIT License
 

