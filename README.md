このリポジトリには、Googleのカスタム検索エンジンを使用して特定のキーワードで検索し、  
結果をWordドキュメントに保存し、Googleドライブにアップロードするpythonスクリプトです。

  
Step.1: google custom search engine APIを有効にし、APIkeyとIDを設定する。

 ブラウザで[google cloud plat form](https://cloud.google.com/free?utm_source=google&utm_medium=cpc&utm_campaign=japac-JP-all-ja-dr-BKWS-all-core-trial-EXA-dr-1605216&utm_content=text-ad-none-none-DEV_c-CRE_602341359562-ADGP_Hybrid%20%7C%20BKWS%20-%20EXA%20%7C%20Txt%20~%20GCP%20~%20General_core%20brand-KWID_43700071566406792-aud-1644542956268%3Akwd-26415313501&userloc_1009365-network_g&utm_term=KW_google%20cloud%20platform&gclid=CjwKCAjwov6hBhBsEiwAvrvN6Eqgy3VztdEsdwjtgHS7rL05V0zvy0K7Iuv90bsXry1e3w71hwhlBhoCO_oQAvD_BwE&gclsrc=aw.ds)のダッシュボードページを開きます。  
 
 <img src="description_imag1.png" width="600">

 ヘッダーにある表示中のプロジェクト（プルダウンメニュー）をクリックします。
 
 
![](gifgif.gif)  


google custom search APIを有効化する 

![](createapikey.gif)



APIkeyを作成する　ここで作成したkeyをpythonコードのyour keyに貼り付けます
![createapikey1](https://user-images.githubusercontent.com/97029186/233791652-bbf63141-65f5-4de0-abef-53dabb714184.gif)

プログラム可能な検索エンジンページにアクセスします。

https://programmablesearchengine.google.com/controlpanel/all

![id](https://user-images.githubusercontent.com/97029186/233792768-6363d1cb-7d7e-474b-9473-57e024e30579.gif)

ここで取得したIDをpythonコードに添付します。


![createapikey2](https://user-images.githubusercontent.com/97029186/233791751-ca45f94f-5de5-46c1-a288-57ebdae5913e.gif)

下記のnotbookボタンからcoogle colabo notbookを開きます。



[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rRwrLEe7iIgoe_P-bsjCNtKbNANOvwI9?usp=sharing)

ノートブックをgoogle driveにコピーします。（いつでもgoogledriveから使うことができるようになる）
<img width="709" alt="Screen Shot 2023-04-23 at 12 25 33 AM" src="https://user-images.githubusercontent.com/97029186/233793218-bfaa62ce-eaac-47b9-ab55-f4d4de5777b9.png">

最初のコードを実行し、googleドライブとの接続を許可します。（これは毎回行う必要がある）
<img width="546" alt="drive" src="https://user-images.githubusercontent.com/97029186/233793638-4a8a4e12-e467-4a67-8e8b-40360dd808c7.png">

先ほど作成したapikeyとidをコードに添付します。


<img width="491" alt="key id" src="https://user-images.githubusercontent.com/97029186/233793722-4fe20f9d-3d6c-40fa-92bc-b2bc60083fce.png">

出力データを保存したいgoogleドライブのフォルダのIDをコードに添付します。  
googleドライブのフォルダに移動し、URLをコピー（このURLが保存先のIDになります）
<img width="972" alt="driveidpage" src="https://user-images.githubusercontent.com/97029186/233793815-f1318617-037f-4b82-8dd5-cf4c335dfbf5.png">

コピーしたIDを下記の箇所に添付します。


<img width="576" alt="driveid" src="https://user-images.githubusercontent.com/97029186/233793837-ff1ebc20-780d-4e8e-a444-1cfe4f7436fa.png">

順番に実行してフォルダに出力結果が保存されていることを確認してください。　　

エラーが出た時はそのエラーをchatgptに添付して、修正コードや必要なモジュールを指示にしたがいインストールしてください。



