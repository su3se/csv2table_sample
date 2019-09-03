# csv2table_spg
JQueryを使ってCSVファイルをHTMLで呼び出して表示するスクリプトのサンプルパッケージ

# コード
```
<script>  
$(function(){  
  $('#table_disp').csv2table('list.csv');  
});  
</script>  
  
<div id="table_disp"></div>
```
※IDを変更して使ってください。<br>
※ファイル名を変更するとほかのファイルを指定できます。
