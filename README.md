# BBO&VCA
![BBO&VCA_Front](Images/BBO&VCA_v1.0_Front.jpeg)

## 概要 / Overview

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
> ※ 1V/oct の標準CVピッチ制御には対応していません。

**BBO&VCA** is a "Bounds Bounce Oscillator" inspired by Ieaskul F. Mobenthey's *Denum* and the [crucFX Utility BBO](https://github.com/d42kn355/BoundsBounceOscillator).  
This circuit operates based on two key concepts: **Bounce** and **Bounds**.  
Imagine a ball bouncing back and forth between two walls. The **Bounce** represents the speed of the ball, and the **Bounds** represent the distance between the two walls.  

In this oscillator, increasing the Bounce raises the frequency. Narrowing the Bounds further increases the frequency but reduces the amplitude.  
In other words, when the walls are brought closer together, the ball (i.e., the signal) travels faster, resulting in a higher pitch.

**BBO&VCA** allows independent control and modulation of both Bounce and Bounds.  
The main output always produces a triangle wave, while the secondary output provides a square wave.  

A range switch allows you to select from three operating ranges:
- Standard audio rate  
- Low audio rate  
- LFO rate  

Both the triangle and square waves are routed through dedicated linear VCAs, allowing you to control their amplitude (volume) via knobs or external CV.

> *Note: This module does not support standard 1V/oct pitch tracking.*



## 仕様 / Spec
- Format: Eurorack
- Function: Oscillator / LFO
- Current needs: +12V: 30mA, -12V: 30mA
- Width: 8 HP
- Depth: 25mm (including power connector)


## 販売 / Sales

StudioKATオフィシャルショップで販売しています。(日本国内限定)  
 https://www.studiokat.jp/items/113562094
 

## ライセンス / License

この作品は [Creative Commons 表示 - 継承 4.0 国際 (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.ja) の下でライセンスされています。  
This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).


## クレジット / Credits

- Designed by : StudioKAT
- Website : https://www.studiokat.jp/
- GitHub : https://github.com/StudioKAT
- X(Twitter) : https://x.com/StudioKAT_synth
- Instagram : https://www.instagram.com/studiokat_modular/

## 更新履歴 / Changelog

- `2025-07-17` Released version 1.0