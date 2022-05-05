# Auto-Zoom-in
Macの標準アプリ「Automater」を使って、授業の時間になったらZoomに入って入室チャットを打ちます<br>
Demoではアプリを直接実行していますが、実際はカレンダーに登録して定期実行させます

## Demo
※Auto_Zoom_in.appを実行した後の処理は自動で実行されています
![auto_zoom_in](https://user-images.githubusercontent.com/70145199/166935434-ed8dbb41-bd54-4bab-849b-72a4ed69f302.gif)

## Requirement
#### 動作環境
PC：MacBook Air (M1, 2020)<br>
OS：macOS Monterey (version 12.3)<br>
software：Automator (version 2.10), カレンダー (version 11.0)

## Usage
#### 設定手順
1. AutomaterでAuto_Zoom_in.appを開く
2. ”シェルスクリプトを実行”の部分を参加したいミーティングの内容に変更
3. 任意の名前で保存
4. カレンダーに登録
#### 補足
**”シェルスクリプトを実行”の部分を参加したいミーティングの内容に変更**

![シェルスクリプトを実行](https://user-images.githubusercontent.com/70145199/166946363-51e54c05-6d42-4546-96ed-f2fad587e8a4.png)<br>

**カレンダーに登録**

![カレンダー登録1](https://user-images.githubusercontent.com/70145199/166946766-5d5b279f-1d2c-4d54-8404-2a00ecd07eee.png)
![カレンダー登録2](https://user-images.githubusercontent.com/70145199/166946783-ee5cf661-24e6-4f5b-b556-6bacf378eb30.png)

## Note
Macのスリープや電源が落ちている場合は、実行直前にスリープ解除・起動するようにスケジュールを設定する必要があります

![バッテリースケジュール](https://user-images.githubusercontent.com/70145199/166949844-eb507e4e-039e-4c5e-b80b-e38e352703ba.png)

## Date
* 2022/05/05
