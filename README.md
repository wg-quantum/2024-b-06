# はじめに
当リポジトリは [2024年度「IBM Community Japan ナレッジモール研究」](https://www.ibm.com/ibm/jp/ja/ibmcommunityjapan-wg-theme.html)
におけるワーキンググループ（以下WG） **「2024-B-06：量子コンピューターの活用研究」** の研究成果物です。

# コンテンツ
1. [報告資料]() (後ほどアップロードします)
    
    ナレッジモール研究での成果報告に使用した資料です。当WGの研究内容の概要についてはこちらの資料をご覧ください。
  
2. [Qiskit 1.x コード対応](https://github.com/wg-quantum/2024-b-06/tree/main/Qiskit_1_0/toc.md)

    [「量子コンピューター初学者向けの量子コンピュータの頭の中――計算しながら理解する量子アルゴリズムの世界」](https://gihyo.jp/book/2023/978-4-297-13511-9)を輪読し、コードを Qiskit 1.x にUpdateしました。
    
3. [量子機械学習](https://github.com/wg-quantum/2024-b-06/tree/main/QML)
    
    量子ニューラルネットワークについて、パラメーターチューニングの手法について研究を行いました。
    
4. [量子セルオートマトン](https://github.com/wg-quantum/2024-b-06/tree/main/QCA/toc.md) と[量子ウォーク](https://github.com/wg-quantum/2024-b-06/tree/main/QW/toc.md)

     - Qiskit1.xで初めて「1次元量子セルオートマトン」、「2次元量子セルオートマトン」を実装しました。
     - Qiskit1.xで「1次元2状態アダマールウォーク」を実装し、発展課題として、量子検索用の教材のコードも修正しました。
     

    
<br><br><br>
***
本資料の著作権は、⽇本アイ・ビー・エム株式会社（IBM Corporationを含み、以下、IBMといいます。）に帰属します。


ワークショップ、セッション、および資料は、IBMまたはセッション発表者によって準備され、それぞれ独⾃の⾒解を反映したものです。
それらは情報提供の⽬的のみで提供されており、いかなる参加者に対しても法律的またはその他の指導や助⾔を意図したものではなく、ま
たそのような結果を⽣むものでもありません。本資料に含まれている情報については、完全性と正確性を期するよう努⼒しましたが、「現
状のまま」提供され、明⽰または暗⽰にかかわらずいかなる保証も伴わないものとします。本資料またはその他の資料の使⽤によって、あ
るいはその他の関連によって、いかなる損害が⽣じた場合も、IBMまたはセッション発表者は責任を負わないものとします。 本資料に含ま
れている内容は、IBMまたはそのサプライヤーやライセンス交付者からいかなる保証または表明を引きだすことを意図したものでも、IBM
ソフトウェアの使⽤を規定する適⽤ライセンス契約の条項を変更することを意図したものでもなく、またそのような結果を⽣むものでもあ
りません。

本資料でIBM製品、プログラム、またはサービスに⾔及していても、IBMが営業活動を⾏っているすべての国でそれらが使⽤可能であるこ
とを暗⽰するものではありません。本資料で⾔及している製品リリース⽇付や製品機能は、市場機会またはその他の要因に基づいてIBM独
⾃の決定権をもっていつでも変更できるものとし、いかなる⽅法においても将来の製品または機能が使⽤可能になると確約することを意図
したものではありません。本資料に含まれている内容は、参加者が開始する活動によって特定の販売、売上⾼の向上、またはその他の結果
が⽣じると述べる、または暗⽰することを意図したものでも、またそのような結果を⽣むものでもありません。 パフォーマンスは、管理さ
れた環境において標準的なIBMベンチマークを使⽤した測定と予測に基づいています。ユーザーが経験する実際のスループットやパフォー
マンスは、ユーザーのジョブ・ストリームにおけるマルチプログラミングの量、⼊出⼒構成、ストレージ構成、および処理されるワーク
ロードなどの考慮事項を含む、数多くの要因に応じて変化します。したがって、個々のユーザーがここで述べられているものと同様の結果
を得られると確約するものではありません。

記述されているすべてのお客様事例は、それらのお客様がどのようにIBM製品を使⽤したか、またそれらのお客様が達成した結果の実例と
して⽰されたものです。実際の環境コストおよびパフォーマンス特性は、お客様ごとに異なる場合があります。
IBM、IBM ロゴは、 ⽶国やその他の国におけるInternational Business Machines Corporationの商標または登録商標です。他の製品名お
よびサービス名等は、それぞれIBMまたは各社の商標である場合があります。現時点での IBM の商標リストについては、
ibm.com/trademarkをご覧ください。


問合せ窓口：IBM 沼田 (kifumi@jp.ibm.com)  

© Copyright IBM Corp. 2024

