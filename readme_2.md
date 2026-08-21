





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


<img width="4032" height="3024" alt="8A3CE902-C2DF-4C0B-9669-FC1B9F5914F4_1_201_a" src="https://github.com/user-attachments/assets/2bdb6795-25c9-448c-96d6-c83a75b8a407" />

<img width="3024" height="4032" alt="73D179DD-903A-45F3-9622-4AB4DF6DA667_1_201_a" src="https://github.com/user-attachments/assets/fd69f4e4-6a0d-499a-8f7e-024bbc2786bc" />

<img width="768" height="1024" alt="A90B3763-A033-40C1-B452-C1A9FFA496CD_1_105_c" src="https://github.com/user-attachments/assets/9a87e66a-9697-4e07-94cb-d3c4db4b1ee8" />

<img width="768" height="1024" alt="A3B33F6C-48F6-4448-9350-AA5F5ACF295B_1_105_c" src="https://github.com/user-attachments/assets/67c84eb1-ed15-4b77-a7e1-ab70589e4c4e" />

<img width="4032" height="3024" alt="EB479EC1-0327-469C-B976-D223C7D51619_1_201_a" src="https://github.com/user-attachments/assets/428c91da-891b-464b-8c44-a6953195c951" />

<img width="768" height="1024" alt="11F68660-5C6A-451B-9645-E2E7F07E6B88_1_105_c" src="https://github.com/user-attachments/assets/764f96f7-0917-48d6-914f-b040d91bc28a" />

<img width="3024" height="4032" alt="F68B0DB4-A6A4-4C87-B431-0A353CD92024_1_201_a" src="https://github.com/user-attachments/assets/fb58c93f-dda7-4226-b0ef-500fe9196612" />

<img width="3024" height="4032" alt="F91956F6-4891-46D9-A6E8-1D585448960E_1_201_a" src="https://github.com/user-attachments/assets/1cea6db0-23e9-46aa-b5fc-30ddb5c18472" />







### 2.基板の組み付け

### 3.トッププレートの取り付け

### 4.仕上げ

### ５.取っ手付きケースの組み立て
