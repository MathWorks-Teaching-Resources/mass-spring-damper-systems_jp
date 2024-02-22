# バネマスダンパーシステム [![View Mass-Spring-Damper Systems on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://jp.mathworks.com/matlabcentral/fileexchange/96822-mass-spring-damper-systems) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=raacampbell/shadedErrorBar) 
**Curriculum Module**  
_R2020bで作成。R2020b以降のバージョンでも使用可能_

<img src="https://user-images.githubusercontent.com/81383420/122805177-c65f6500-d296-11eb-9684-5f1f70b4ea03.gif" width="350">

## 説明 ##
This repository contains a Japanese version of a published repository "Mass-Spring-Damper-Systems" (https://github.com/MathWorks-Teaching-Resources/Mass-Spring-Damper-Systems)

このカリキュラムではバネマスダンパーシステムを探求するためのインタラクティブな[ライブスクリプト](https://www.mathworks.com/products/matlab/live-editor.html)と[Simulink&reg; モデル](https://www.mathworks.com/products/simulink.html) が含まれています。学生はガイド付きの演習を行いながら、バネマスダンパーモデルの作成し動かします。自動車のサスペンションによる振動減衰、地震に対する建物の応答といった二つの応用例を用いることで、モデルの作成・操作することに興味を持ってもらいます。
課題全体を通して、学生はSimulinkモデルを使用しながら、物理システムの動力学を学ぶことができます。最後の課題では、変位信号のパワースペクトルを計算することで、バネマスダンパーの建物モデルの共振周波数を同定します。これらの課題は、講義の一部、教育現場での活動として、また授業外のインタラクティブな課題としても活用することができます。

**学習目標**
- 自由物体図を作成し、バネマスダンパーシステムの運動方程式を導出する
- 重り、バネ、ダンパーを振動物理系の構成要素として関連付ける
- Simulinkで常微分方程式を解くモデルを作成する
- Symbolic Math Toolboxを使用し、Simulinkモデルの作成を補助する
- 1、2、nの自由度を持つSimulinkのバネマスダンパーモデルを完成させる
- パラメータ値とバネマスダンパーシステムの運動状態を関連付ける
- 車両のサスペンションモデルの減衰を要求性能を満たすように調整する
- バネマスダンパーの建物モデルの共振モードを同定する

ライブスクリプト内の説明を見ながら、演習を進めていきます。
各ライブスクリプトは、セクションごとに実行することができます。スクリプトやセクションの実行を途中で停止するには（例えば、アニメーションの進行中に止めたいときなど）、MATLABツールストリップの"ライブエディタ"タブにある「実行」セクションの［停止］ボタンを使用します。

## 推奨入門コンテンツ ##
[MATLAB 入門](https://matlabacademy.mathworks.com/details/matlab-onramp/gettingstarted) – MATLABの基礎を学べる2時間の無料入門チュートリアル
<br>
[Simulink 入門](https://matlabacademy.mathworks.com/details/simulink-onramp/simulink) –　Simulinkの基礎を学べる2時間の無料入門チュートリアル

## 詳細 ##

**`massSpringDamper.mlx, massSpringDamperSoln.mlx`**  
Simulinkで、1自由度のバネマスダンパーをモデル化する方法を教えるインタラクティブなスクリプト。学生は自身の知識を応用して、自動車のサスペンションシステムの減衰を調整します。
## ##
**`doubleMassSpringDamper.mlx, doubleMassSpringDamperSoln.mlx`**  
Simulinkで、2自由度のバネマスダンパーをモデル化する方法を教えるインタラクティブなスクリプト。学生は自分の知識を応用して、2階建て建物モデルの共振周波数を同定します。
## ##
**`multipleMassSpringDamper.mlx, multipleMassSpringDamperSoln.mlx`**  
このレッスンでは、Simulinkモデルのベクトル化やSpectrum Analyzerブロックを使ったパワースペクトルの計算など、より高度なスキルを学びます。(英語のみ、日本語翻訳予定あり)

## ##
**`models/`**  
ライブスクリプト内で使用されるSimulinkモデル。演習用のモデルと完成したソリューションも含まれています。

## 使用製品 ##
MATLAB&reg;, Symbolic Math Toolbox&trade;, Simulink

## ライセンス ##
このモジュールのライセンスは、GitHubのレポジトリ内の[LICENSE.TXT](license.txt) ファイルにおいて利用可能です。

## サポート ##
日本語版のお問い合わせは[MathWorks Japan カスタマーサクセス部](mailto:cse-jp@groups.mathworks.com)までお願いいたします。
<br>
Have any questions or feedback? Contact the <a href="mailto:onlineteaching@mathworks.com">MathWorks online teaching team</a>.

# #
_Copyright 2021 The MathWorks, Inc._
