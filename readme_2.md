





# 若紫,夕顔,松風 共通 ケース・組込みビルドガイド
若紫は以下の特徴を備えるマクロパッドです。
- テンキー配列の10キー
- 3つのロータリーエンコーダー（プッシュボタン付き）
- 4つのトグルスイッチによる機能変更（レイヤー変更）
- 現在の機能把握に便利なLED
インジケーター
- 自由に柄など（0.5mm以下の紙など）をあしらえるカスタムプレート（夕顔、松風、若紫のみ）
- ※作例では千代切り紙（バックストリートファクトリー製）を使用した例です。キットには同梱されません。  

ファームウェアはQMK/Vial対応です。  

vialのソフトウェアから自由にキーマップを変更可能です。 <br/>



## 組み立てにあたって

<img width="1024" height="768" alt="5E71160D-2920-4F10-9ACA-105B6139C252_1_105_c" src="https://github.com/user-attachments/assets/0c5dab31-8806-4757-b30f-486f515857ba" />
<br/>
本キットには基板完成済みの通常版と基板の組み立てが必要なチャレンジキットがあります。<br/>
→こちら<br/>
https://github.com/Eromis-keeb/hiyokochan_f10_wakamurasaki/blob/ac473d99715d367bfb3ebd06d90718eca4af67bc/README.md <br/>
通常版の場合も最初から最後まで読むことである程度仕組みが解るので読んで頂いたほうが良いと思います。<br/>

## 必要な物

### キット付属のもの

部品|個数
--|--
若紫 基板(完成)|x1
トッププレート（アクリル）|x1
ミドルプレート上|x1
ミドルプレート下|x1
カスタムミドルプレート上|x1
カスタムミドルプレート下|x1
ボトムプレート（アクリル）|x1
スペーサー（9mm）|x6
トップ用ネジ（5mm）|x6
ボトム用ネジ（8mm）|x6
脚用ネオジムマグネット(穴あき)|x4
脚用マグネットカバー|x4
取っ手付きケース|x1
ケース用ネオジムマグネット|x4
ケース用マグネットカバー|x4


### 各自用意するもの
部品|個数
--|--
MXキースイッチ |x10
MXキーキャップ |x10
ロータリーエンコーダーノブ（直径17mmくらいまで）|x3



部品はTALPKEYBOARDさん、遊舎工房さん、秋月電子通商さん、マルツオンラインさんで調達しています。<br/>
<br/>
<br/>
## 組み立て
基板部分は若紫基板を使用して解説していきますが、どのモデルでも内容は同じなので適宜読み替えてください。hiyokochanシリーズとは基板共用なので全く同じです。<br/>
ところどころ別基板の写真が使われいる箇所がありますが、こちらも適宜読み替えて眼の前の基板と照らし合わせて組み立てを行ってください。
<br/>

### 1.ボトムプレートの組み立て
#### 1-1.脚の組み立て<br/>
ボトムプレートを組み立てていきます。<br/>
<br/>
<br/>

<img width="1024" height="768" alt="3B385812-37E2-4249-B79A-B397F9491C2E_1_105_c" src="https://github.com/user-attachments/assets/353951be-cd65-4993-b83c-48145d3f97c3" /> <br/>
<br/>
<br/>

まず初めにマグネット脚を組み立てます。<br/>
<img width="1024" height="768" alt="BAB4D48F-6B53-43CD-A5A4-15063EB05923_1_105_c" src="https://github.com/user-attachments/assets/04ffae0a-1a61-4eda-823b-e327d368c84b" /> <br/>
ネオジムマグネット（穴あき）４つ、マグネット脚用カバー４つ、ボトム用ネジ（８mm）４つ用意します。<br/>
<br/>
<br/>

マグネット脚用カバーの表裏を確認します。<br/>
<img width="4032" height="3024" alt="3D85E10E-7033-4DA5-844B-C60AE2930741_1_201_a" src="https://github.com/user-attachments/assets/5bbe2c71-aa01-46a5-9705-5eb852528da1" /> <br/>
でこぼこした面が底面、若干穴が広くなっている方が上面です。<br/>
<br/>
<br/>

ネオジムマグネット（穴あき）をカバーに嵌め込みます。<br/>
<img width="3024" height="4032" alt="7386E9FB-65FB-4E94-9F0C-DC86050F54E5_1_201_a" src="https://github.com/user-attachments/assets/12fde933-7fd9-48ba-992e-bc86391891bb" /> <br/>
上面（穴の広い方）を上に穴あきマグネットの窪んでいる方が上になるように嵌め込みます。<br>
<br/>
<br/>

持ち上げた時にマグネットが落下しないのが正解の向きです。<br/>
<img width="768" height="1024" alt="89FED13F-75E0-4C19-8C53-208BA437D89F_1_105_c" src="https://github.com/user-attachments/assets/63d47d40-c4c0-43c9-8848-d719e3885b3a" /> <br/>
<br/>
<br/>

カバーに嵌め込んだマグネット脚にネジを入れます。<br/>
<img width="768" height="1024" alt="1E1E7649-2C07-46B9-9E78-ABA967FD5426_1_105_c" src="https://github.com/user-attachments/assets/f0f2959b-1438-411e-9f47-ddf04c2cad5e" /> <br/>
<br/>
<br/>

<img width="3024" height="4032" alt="1E1E7649-2C07-46B9-9E78-ABA967FD5426_1_201_a" src="https://github.com/user-attachments/assets/67a77d89-b6a7-4ed2-907b-5e2d0e8b20aa" /> <br/>
<br/>
<br/>

マグネットの窪みにネジ頭がはまるように差し込みます。<br/>
<img width="768" height="1024" alt="22C73C22-2449-4EC3-9B27-5FEA223553B6_1_105_c" src="https://github.com/user-attachments/assets/0c04971e-b00a-4a38-a797-aad67548f0a9" /> <br/>
持ち上げた際にネジが落下しなければ正解の向きです。<br/>
<br/>
<br/>

同様に残り３つを作成します。<br/>
<img width="1024" height="768" alt="7019172F-A643-4C4D-9239-FC0337A2584E_1_105_c" src="https://github.com/user-attachments/assets/cdf6bb52-05e5-4771-b01e-3125df0587c0" /> <br/>
マグネット脚のできあがり。<br/>
<br/>
<br/>

#### 1-2.スペーサー取り付け<br/>
<img width="1024" height="768" alt="354A4D05-CDDB-4463-B3B3-B86F9B601560_1_105_c" src="https://github.com/user-attachments/assets/44908989-16b5-4e3b-becb-fef16dad86a5" /> <br/>
ボトムプレートと１−１で作成したマグネット脚を用意します。<br/>
<br/>
<br/>

ボトムプレートのシートを剥がします。<br/>
<img width="4032" height="3024" alt="B7173BBF-B541-4CDE-928F-803535075C77_1_201_a" src="https://github.com/user-attachments/assets/fbd69656-92b2-49e0-b0b3-2522296bb691" /> <br/>
裏表があるので気をつけてください。切り欠きが左側に来る状態が正しい向きです。<br/>
<br/>
<br/>

６箇所にスペーサーを取り付けていきます。<br/>
<img width="4032" height="3024" alt="06A1CAE0-88FF-4FC0-A884-6E38A3CE27E6_1_201_a" src="https://github.com/user-attachments/assets/952a828e-1677-4766-b8f5-746c1f144c82" /> <br/>
青枠部分の６箇所にスペーサーをネジで取り付けます。<br/>
ボトム用ネジ（8mm）を２本用意します。 <br/>
<br/>
<br/>

中央の２箇所にスペーサーを取り付けます。<br/>
<img width="4032" height="3024" alt="8A3CE902-C2DF-4C0B-9669-FC1B9F5914F4_1_201_a" src="https://github.com/user-attachments/assets/2bdb6795-25c9-448c-96d6-c83a75b8a407" /> <br/>
ボトムプレートの切り欠きが左側に来る状態で表が上面、逆側が底面です。<br/>
<br/>
<br/>

上面側にスペーサー、底面側からネジを差し込みます。<br/>
<img width="3024" height="4032" alt="73D179DD-903A-45F3-9622-4AB4DF6DA667_1_201_a" src="https://github.com/user-attachments/assets/fd69f4e4-6a0d-499a-8f7e-024bbc2786bc" /> <br/>
<br/>
<img width="768" height="1024" alt="A90B3763-A033-40C1-B452-C1A9FFA496CD_1_105_c" src="https://github.com/user-attachments/assets/9a87e66a-9697-4e07-94cb-d3c4db4b1ee8" /> <br/>
裏面側からドライバーでネジ止めします。しっかり締めてください。<br/>
<br/>
<br/>

スペーサーを取り付けた所 <br/>
<img width="768" height="1024" alt="A3B33F6C-48F6-4448-9350-AA5F5ACF295B_1_105_c" src="https://github.com/user-attachments/assets/67c84eb1-ed15-4b77-a7e1-ab70589e4c4e" /> <br/>
同じように中央下側にもスペーサーを取り付けます。<br/>
<br/>
<br/>

１−１で作成したマグネット脚を同じ要領で四隅に取り付けます。<br/>
<img width="4032" height="3024" alt="EB479EC1-0327-469C-B976-D223C7D51619_1_201_a" src="https://github.com/user-attachments/assets/428c91da-891b-464b-8c44-a6953195c951" /> <br/>
裏表を間違えないように気をつけましょう。 <br/>
<br/>
<br/>


<img width="768" height="1024" alt="11F68660-5C6A-451B-9645-E2E7F07E6B88_1_105_c" src="https://github.com/user-attachments/assets/764f96f7-0917-48d6-914f-b040d91bc28a" /> <br/>
<br/>
<br/>

取り付け完了状態（上面） <br/>
<img width="3024" height="4032" alt="F68B0DB4-A6A4-4C87-B431-0A353CD92024_1_201_a" src="https://github.com/user-attachments/assets/fb58c93f-dda7-4226-b0ef-500fe9196612" /> <br/>
<br/>
<br/>

取り付け完了状態（底面） <br/>
<img width="3024" height="4032" alt="F91956F6-4891-46D9-A6E8-1D585448960E_1_201_a" src="https://github.com/user-attachments/assets/1cea6db0-23e9-46aa-b5fc-30ddb5c18472" /> <br/>
これでボトムプレートは完成です。<br/>
<br/>
<br/>






### 2.基板の組み付け
#### ２-1.ミドルプレートの取り付け<br/>
<br/>
<br/>

1ー2までに作ったボトムプレートにミドルプレートを組み付けていきます。<br/>
<img width="1024" height="768" alt="4AC758EF-DF96-43F8-9C15-A85DCB240132_1_105_c" src="https://github.com/user-attachments/assets/ddc1873d-ca1a-4cc1-8f5e-cdf2704ee5f7" /> <br/>
ミドルプレート下を用意します。<br/>
このとき必要であればカスタムプレートなどを使用することもできます。<br/>
<br/>
<br/>

ミドルプレートをボトムプレートに乗せてスペーサーを差し込む形で組み付けます。 <br/>
<img width="4032" height="3024" alt="ECCCB265-FFF9-4933-B97E-25517A3C1AF2_1_201_a" src="https://github.com/user-attachments/assets/f18d44e3-0a57-4fda-b74d-533ddf546bdb" /> <br/>
隙間がないように差し込んでください。 <br/>
![IMG_7154](https://github.com/user-attachments/assets/aa1b5fc9-c2e2-4aa2-a70f-e9af4f91dc79)<br/>
<br/>
<br/>

※上記の差し込みを行う際、固くて差し込みにくい場合は無理せず以下の写真のように
ミドルプレートの各スペーサ穴をボトムプレートを使って予め差し込みやすくしてから
全体を差し込むとすんなり入ると思います。<br/>
無理に強行するとアクリルが割れます。<br/>
注意して差し込んでください。 <br/>
![IMG_7155](https://github.com/user-attachments/assets/d451e68c-95c6-4c60-9c7d-0b79141ccdcf)<br/>

<br/>
<br/>
 
<img width="768" height="1024" alt="95E9BBB1-7182-4DC9-8EB6-4A8C3A51A9C3_1_105_c" src="https://github.com/user-attachments/assets/cccda228-ea41-4ff3-b087-1599144630d5" />

<img width="1024" height="768" alt="6B176C75-2DBB-4626-890A-CAA626E52C60_1_105_c" src="https://github.com/user-attachments/assets/928c76b7-14b7-4cfa-9c53-25ea9e101aec" />

<img width="4032" height="3024" alt="1A9771D5-B89D-4186-951F-3F35BF6891DC_1_201_a" src="https://github.com/user-attachments/assets/bb549cc6-12a9-44b7-bd5a-2d7fc0eacb51" />

<img width="1024" height="768" alt="5F996B35-2EB8-46E6-895A-13D9396B8370_1_105_c" src="https://github.com/user-attachments/assets/ec564f0c-ef99-4af3-8a1f-cdb4e8cf22ee" />

<img width="1024" height="768" alt="C4C1BBCA-E06A-4CC3-8A23-4ED69EC36C55_1_105_c" src="https://github.com/user-attachments/assets/872390b0-6c0b-4314-8e46-92af54281ee6" />

<img width="3024" height="4032" alt="B6B88341-4A60-4F40-BCDE-0DD99C9A1979_1_201_a" src="https://github.com/user-attachments/assets/27acf7cd-e01d-4427-a29b-8e9b1eb6d0cd" />

<img width="3024" height="4032" alt="E6C1EC1D-FC48-492A-9375-8FF296193F0D_1_201_a" src="https://github.com/user-attachments/assets/68b1f75b-d092-4b85-97e5-7f70ca76412a" />

<img width="4032" height="3024" alt="54F33E00-9C45-4D0A-9A91-1E4CA626B3E7_1_201_a" src="https://github.com/user-attachments/assets/b9733988-e75c-448d-a7d0-4dbf5c38fe67" />



<img width="4032" height="3024" alt="54F33E00-9C45-4D0A-9A91-1E4CA626B3E7_1_201_a" src="https://github.com/user-attachments/assets/a8c3316d-5968-4bfc-9045-da56afb47043" />

<img width="1024" height="768" alt="194D1A51-03DD-4769-A544-EFDD2E293FFC_1_105_c" src="https://github.com/user-attachments/assets/12c5db06-fe4f-499d-9803-441c0e6573c8" />






























### 3.トッププレートの取り付け

### 4.仕上げ

### ５.取っ手付きケースの組み立て
