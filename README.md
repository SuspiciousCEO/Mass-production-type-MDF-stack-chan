# 量産型MDFｽﾀｯｸﾁｬﾝ

![2023-03-27_22-08-37_863](https://user-images.githubusercontent.com/88123439/231469222-6e2311c2-8570-445a-b4b6-2f0818143eed.jpeg)![2023-03-30_22-56-36_258](https://user-images.githubusercontent.com/88123439/231470215-a5d5a515-c3e0-4a81-9a26-0253a7b09d8a.jpeg)



これはスーパーカワイイロボット [ｽﾀｯｸﾁｬﾝ(Stack-chan)](https://github.com/meganetaaan/stack-chan)
を量産しやすいように筐体ボディケースをMDF2.5mm厚用に設計したものです。
可能なかぎり、オリジナルのｽﾀｯｸﾁｬﾝSG90版筐体ボディとの動作の互換性を持たせています。
筐体ボディは共通部分が多いので、他の派生ｽﾀｯｸﾁｬﾝ（たとえば[AIｽﾀｯｸﾁｬﾝ](https://github.com/robo8080/M5Unified_StackChan_ChatGPT)
など）でもそのまま使うことが可能でしょう。

※写真は開発途中のものです。

## 特徴

オリジナルの[3Dプリンター版ｽﾀｯｸﾁｬﾝ](https://github.com/meganetaaan/stack-chan/tree/dev/v1.0/case)に比べ以下の点が優れています。


![2023-03-30_19-45-50_679](https://user-images.githubusercontent.com/88123439/231469448-95a8341f-9e66-4a44-88da-187a032ded01.jpeg)![2023-03-30_19-45-04_290](https://user-images.githubusercontent.com/88123439/231469620-78870211-7d06-4f7f-933a-b4ba650461ca.jpeg)

![2023-03-30_19-36-18_647](https://user-images.githubusercontent.com/88123439/231469720-89add461-9cec-4f34-a300-df104f1e76e5.jpeg)![2023-03-30_19-46-54_690](https://user-images.githubusercontent.com/88123439/231469815-e8aab340-1a15-4d4a-8f9c-dbc2f8350d69.jpeg)



### 組み立てと分解が簡単
**小学生高学年でも作れそうなレベルを目指しました。**
たとえ破損したとしてもそのパーツの部分だけを追加で用意することで、全体のパーツを無駄にすることなく組み立てを再開することが可能です。
後述しますが、材料が安価なので失敗に対しての心構えが楽ですし、予備を多めに用意したとしても予算を圧迫しません。


### 適度な難易度とスピード感
材料が揃っていれば慣れてくると大人なら30分ぐらいで物理的な組み立て完了が可能。
失敗や手戻りがあったとしても、マスキングテープを剥がせばいいだけなので、特にパーツが痛むこともなく再開できます。
接着剤だと、固まり切ったらやり直しが難しいでしょうからこうはいきません。
あらかじめ時間枠が決まっている授業やワークショップなどでの活用に適しています。


### 圧倒的な生産性
レーザー加工機でパーツを切り出して用意するのに、一体につき10分もかかりません。(20Wくらいの出力ができる機種を想定)
3Dプリンター版を出力した場合、一体につき約半日〜1日の時間が必要となります。
また3Dプリンターによる造形物出力は、時には失敗することもあります。
期日までにまとまった数を用意することが必要な教育現場において、生徒全員に行き渡らせる必要がある教材を3Dプリンター出力に頼るのは不安が残りますが、
この量産型であればそういった懸念を払拭できます。


### 安い！コストパフォーマンス良好
筐体ボディ部分がMDF2.5mm厚板A5サイズで1枚に収まるので、極めて安価。
これ以外に組み立てで必要となる部品。すなわち頭脳部分になるマイコンM5Stackとサーボモーター類に予算を振り分けることが可能です。


### 安全性について
パーツさえそろっていれば、ボンドや接着剤類を使わなくても組み立てが可能。（もちろん使ってもOK）
組み立てに必要な道具はマスキングテープとプラスドライバー、あとお好みで結束バンドを。
刃物を使ったりしないのでケガをしにくいです。


### カスタマイズできる
子供達でも扱いが容易な3DCADソフトウェアのTinkercadで[プロジェクトデーター](https://www.tinkercad.com/things/7WoQx0e2Eym)を公開しているので、
その気になれば自由に再設計が可能です。


### 木のぬくもり感と後加工が容易
MDFは木材と紙の両方の雰囲気があるので、絵具などで色塗したり。ハサミなどであとからチョキチョキも可能。
キリやピンバイス（ハンドドリル）で穴あけも容易です。
紙を貼り合わせる場合でも水性のりでくっつくので接着剤を必要としません。
組み立て後も、カスタマイズの自由度が高いので自分ならではのオリジナル作品にすることができます。


### 持ち運びしやすい
組み立てやすくて、分解しやすいので、マスキングテープを剥がせば再び平面状にすることが可能。
よって普通郵便やメール便などで低コストに発送が可能です。
オリジナル版は約5cm立方サイズよりも小さくすることができないので、発送方法は少し考える必要があります。






## 欠点（ただし解決策や妥協点はあり）
![2023-03-22_16-26-15_848](https://user-images.githubusercontent.com/88123439/231473435-e7ad9e66-5ca3-4298-9d2b-3b3a74d1366d.jpg)


### レーザー加工機が必要
あらかじめ、レーザー加工機でMDF板からパーツを切り出す必要があります。
（もちろんカッターナイフを使って手で切り出すことも可能かもしれませんがおすすめしません。）
レーザー加工機は個人宅で所有運用するには敷居が高いものですが、
教育機関やFab施設やホームセンターなどでも加工を請け負う場所が増えています。
それら加工業者などに依頼すれば比較的安価に切り出し加工が可能です。


### 精度がすこしゆるい。
ハンドメイドなのでどうしても精度が甘くなりがちですが、ある程度ユルくても問題なく動くのであまり気にしなくてもいいです。


### 全てのサーボモーターに適合するかはやってみなければわからない
SG90というホビー向けサーボモーターは類似品が多く出回っており、入手性が良好な反面、おかげで動作やサイズに個体差やばらつきがあり、相性問題が発生します。必ずしも挙動やサイズ寸法がまったく同じというわけにはなっていません。


## 必要なもの
![2023-03-27_23-02-36_383](https://user-images.githubusercontent.com/88123439/231471070-ed12b323-3a51-44d7-9b58-38c871a4b7a3.jpeg)


1). 本データーで切り出したMDF2.5mm厚パーツ一式、（2.5mm厚であればベニア等でも可）

2). M5Stack CORE2（構成がほぼ同一のAWS版やおそらくBasicでも可）

3). SG90系サーボモーター2個

4). [専用基板](https://github.com/akita11/Stack-chan_Takao_Base)

5). Groveケーブル

6). M3x8mmナベネジ3本

7). M3x18mmナベネジ4本

8). M3ナット2個

9). M3x6mmタップタイトねじPナベ4本

10). SG90系サーボモーター2個

11). マスキングテープ

12). +ドライバー

13). 結束バンド （お好みで。）

14). 木工ボンド（マスキングテープの強度では不満がある場合はお好みで。）



## 組み立て方（マスキングテープ版）
![2023-03-30_13-33-27_398](https://user-images.githubusercontent.com/88123439/232264226-dc6654e1-4166-4e64-844f-9b2ada9fabfc.jpg)

### パーツAを2枚重ねて貼り合わせる
![2023-03-30_19-28-26_104](https://user-images.githubusercontent.com/88123439/232264286-fbd5c89c-6da0-4651-bced-31276eb0a246.jpg)![2023-03-30_19-29-24_195](https://user-images.githubusercontent.com/88123439/232264327-1dc44ae8-5d24-4adf-bc49-75982cd4d52e.jpeg)![2023-03-30_19-30-24_535](https://user-images.githubusercontent.com/88123439/232264351-e2e72e4f-6a6f-46eb-bbd3-53d54685ef76.jpeg)

### パーツAを骨組みにして、パーツB・C・Dを組み合わせて貼る。

![2023-03-30_19-32-27_696](https://user-images.githubusercontent.com/88123439/232264659-9ea55862-f7de-47bc-8203-5b34fca06c08.jpeg)![2023-03-30_19-34-46_718](https://user-images.githubusercontent.com/88123439/232264661-e63681d9-eeee-4a89-9a67-6cead25c1098.jpeg)![2023-03-30_19-35-06_923](https://user-images.githubusercontent.com/88123439/232264672-2ecac8e1-5f0c-40d7-8b04-5b970245bcec.jpeg)

### パーツE・F・Eをはさんで貼る。

![2023-03-30_19-37-04_293](https://user-images.githubusercontent.com/88123439/232264814-24d81307-ce8a-4a4e-a8c0-ace8c51ffcdd.jpeg)![2023-03-30_19-38-57_710](https://user-images.githubusercontent.com/88123439/232264820-1108a2e6-2dbe-4aae-9321-c45176d77bc2.jpeg)![2023-03-30_19-37-54_783](https://user-images.githubusercontent.com/88123439/232264823-708c9fe1-02a5-4664-b8aa-c30e96ad9bc0.jpeg)

### パーツHに[専用基板](https://github.com/akita11/Stack-chan_Takao_Base)を取り付ける

![2023-04-06_11-33-05_987](https://user-images.githubusercontent.com/88123439/232265124-4144b662-440d-44d0-87a1-c39f16deffec.jpg)![2023-04-06_11-33-12_381](https://user-images.githubusercontent.com/88123439/232265125-c6610e6e-2eb2-4cbe-9978-81d20dd47099.jpg)![2023-04-06_11-33-58_831](https://user-images.githubusercontent.com/88123439/232265127-bef63392-c8bd-46ac-9418-e57b5f999c29.jpg)
輪っかの形をしているスペーサーを間にはさみながら、M3x6ネジとナットを使って締め付けます。

外側＞ [M3x6ネジ] | [パーツH] | [スペーサー] | [専用基板] | [ナット] ＜内側

### G・H・I・J・Kを組み合わせて箱状態にする。

![2023-03-30_19-41-57_109](https://user-images.githubusercontent.com/88123439/232322111-44bdd356-63cb-40b5-889f-ea0756abc146.jpeg)![2023-03-30_19-43-58_409](https://user-images.githubusercontent.com/88123439/232322118-2613f12d-e428-43f7-a288-04808d7ad398.jpeg)![2023-03-30_19-44-11_916](https://user-images.githubusercontent.com/88123439/232322124-136e9b81-c1ec-4624-8021-5dc293ab4ab9.jpeg)

### 足部分（パーツE・F・E）にサーボホーンをネジで固定。

![2023-03-30_21-45-32_912](https://user-images.githubusercontent.com/88123439/232323156-ca4d74e7-a597-4944-b571-f202a7b7efae.jpeg)![2023-03-30_21-45-50_967](https://user-images.githubusercontent.com/88123439/232323162-2351beef-1063-47de-a32b-a4bb4af07198.jpeg)![2023-03-30_21-41-33_830](https://user-images.githubusercontent.com/88123439/232323148-a71ddc15-0a4e-4586-8df4-668b48c0338a.jpeg)

サーボホーンの向きに注意。真ん中の形状をよく見て、細かいギザギザが中央部分にあるのがサーボモーター内側になります。
このとき使うサーボモーターに付属しているネジは、先が少し尖っているので注意。


## その他


　
![2023-03-30_23-06-10_814](https://user-images.githubusercontent.com/88123439/231471900-3f551857-daca-4650-81e2-2d26484ee344.jpeg)
![2023-03-30_22-53-32_547](https://user-images.githubusercontent.com/88123439/231471967-ed2aaa7c-20ae-427c-8d21-c72a00f34ac6.jpeg)


量産型ロボットの様式美として、稼働範囲の自由度を上げるために、動力線を一部筐体ボディ外部に露出させてあります。
