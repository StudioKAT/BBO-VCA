# BBO&VCA マニュアル（日本語）
![BBO&VCA_Front](../../Images/BBO&VCA_v1.0_Front.jpeg)

## 概要

**BBO&VCA** は、Ieaskul F. Mobenthey の Denum と [crucFX Utility BBO](https://github.com/d42kn355/BoundsBounceOscillator) にインスパイアされた「バウンズ・バウンス・オシレーター（Bounds Bounce Oscillator）」です。  
この回路は、「バウンス（Bounce）」と「バウンズ（Bounds）」という、2つの概念を軸に動作します。  
ボールが2つの壁の間を行き来して跳ねている様子をイメージしてください。バウンスはボールのスピード、バウンズはその2つの壁の距離です。  
このオシレーターでは、バウンスを大きくすると周波数が上がり、バウンズを狭めると振幅が下がる代わりに周波数はさらに上がります。つまり、壁を近づけると、ボール（信号）の移動が速くなるという構造です。  
**BBO&VCA** は、バウンスとバウンズをそれぞれ独立して調整・変調でき、主出力からは常に三角波が出力されます。また、もう1つの出力からは矩形波が得られます。  
さらに、レンジスイッチにより3つの動作範囲を選択できます：
- 標準オーディオレート
- 低オーディオレート
- LFOレート

出力される三角波と矩形波は、それぞれ専用のリニアVCAを通して出力されており、外部CVやノブで音量（振幅）をコントロールできます。  


## 仕様

- **フォーマット**：Eurorack  
- **幅**：8 HP  
- **奥行き**：25 mm  
- **消費電流**：+12V: 30mA / -12V: 30mA  

> ※ ケーブルの赤いラインが -12V に接続されるようにしてください。  
> 誤って接続すると、モジュールが故障する可能性があります。  
> **電源投入前にケーブルの向きを必ず確認してください。**


## 各部の機能
![BBO&VCA_Explanation](../../Images/BBO&VCA_v1.0_Ex.jpg)

1. **BNC LIN**  
   バウンス（Bounce）の基準位置や速度（レート）を設定するノブです。

2. **BNC EXP**  
   BNC EXP IN に接続されたCV信号の影響度を調整するアッテヌバーターです。ノブ中央で無効、時計回りで正極性、反時計回りで逆極性のモジュレーションが適用されます。

3. **BND LIN**  
   バウンズ（Bounds）の基準位置や速度（レート）を設定するノブです。

4. **BND EXP**  
   BND EXP IN に接続されたCV信号の影響度を調整するアッテヌバーターです。ノブ中央で無効、時計回りで正極性、反時計回りで逆極性のモジュレーションが適用されます。

5. **TRI LV**  
   三角波の音量（振幅）を調整するノブです。

6. **SQR LV**  
   矩形波の音量（振幅）を調整するノブです。

7. **RANGE**  
   発振レンジを切り替えるスイッチです。以下の3段階があります：  
   - 標準オーディオレート  
   - 低オーディオレート  
   - LFOレート

8. **BNC LIN IN**  
   バウンス（Bounce）のリニアCV入力です。

9. **BNC EXP IN**  
   バウンス（Bounce）のエクスポネンシャルCV入力です。

10. **BND LIN IN**  
   バウンズ（Bounds）のリニアCV入力です。

11. **BND EXP IN**  
   バウンズ（Bounds）のエクスポネンシャルCV入力です。

12. **TRI VCA IN**  
   三角波の音量を制御するためのCV入力です。

13. **TRI OUT**  
   三角波の出力端子です。

14. **SQR VCA IN**  
   矩形波の音量を制御するためのCV入力です。

15. **SQR OUT**  
   矩形波の出力端子です。


> ※ 本モジュールは 1V/oct の標準CVピッチ制御には対応していません。



## ライセンス

この作品は [Creative Commons 表示 - 継承 4.0 国際 (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.ja) の下でライセンスされています。


## クレジット

- **Designed by**：StudioKAT  
- **Website**：[https://www.studiokat.jp/](https://www.studiokat.jp/)  
- **GitHub**：[https://github.com/StudioKAT](https://github.com/StudioKAT)  
- **X（旧Twitter）**：[https://x.com/StudioKAT_synth](https://x.com/StudioKAT_synth)  
- **Instagram**：[https://www.instagram.com/studiokat_modular/](https://www.instagram.com/studiokat_modular/)


## 更新履歴

- `2025-07-17`：v1.0 リリース  
