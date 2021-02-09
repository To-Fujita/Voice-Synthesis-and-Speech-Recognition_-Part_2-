# Voice Synthesis and Speech Recognition (Part-2)
These are part-2 of voice synthesis and speech recognition programs. In this part, I had created some programs by HTML and JavaScript. It is also the language that can be recognized is only Japanese.

## 1. Description
　無料で使用可能な音声合成と音声認識プログラムの（その２）をお届けします。　本プログラムは、HTMLとJavaScriptで作成しました。　音声合成／音声認識エンジンは、Web Speech APIを使用しました。　また、人工無脳用形態素解析エンジンには、「TinySegmenter」および「RakutenMA」を使用しました。

## 2. Details and Demo
　本プログラムは、４つのパートから構成されており、上記「Code」から一括ダウンロードできます。　また、次のメニューからそれぞれのデモを確認することができます。　以下にそれぞれのパートについて説明します。  
 [デモ・メニュー]()  

### 2-1: 音声合成
「Voice_Synthesis.html」が入力された文字を読み上げるだけのシンプルなプログラムです。　本プログラムは、色々なプラウザに対応しており、プラウザによって使用できる音声が異なりますので、お楽しみください。　なお、一般的な設定では、日本語と英語に対応しています。　次のリンクで音声合成のデモが確認できます。  
[音声合成のデモへのリンク]()  

### 2-2: 音声認識
「Voice_Recognition.html」が標準入力デバイスであるマイクから入力された音声を文字で表示するプログラムです。　使用できるプラウザは、現在のところGoogle Chromeのみのようです。　また、一般的な設定では、日本語の入力にのみ対応しています。　次のリンクで音声認識のデモが確認できます。  
[音声認識のデモへのリンク]()  

### 2-3: 音声合成と音声認識を使用した人口無脳との会話（TinySegmenter 版）
「Voice_Synthesis_and_Recognition_001.html」がTinySegmenterを使用した人口無脳との会話プログラムです。　簡単な人口無脳ですので、シナリオに沿った受け答えしかできませんが、ご自身で会話データを作成し読み込ませることで拡張できるようにしています。　会話データは、「.Data/Talk_List_002.csv」を参考に、エクセル等でA列にあなたの言葉や質問を、B列以降に人口無脳からの返答を数個記載（任意の返答がランダムに返されることになる）して作成してください。　なお、作成した会話データは、csv形式、Shift-JISでローカルに保存して下さい。　プログラムの上部にファイル選択がありますので、そこから作成した会話データを読み込むことになります。　次のリンクで人口無脳のデモが確認できます。  
[TinySegmenterによる人工無脳のデモへのリンク]()  

### 2-4: 音声合成と音声認識を使用した人口無脳との会話（RakutenMA 版）
「Voice_Synthesis_and_Recognition_002.html」がRakutenMAを使用した人口無脳との会話プログラムです。　形態素解析エンジンが異なるだけで、扱いは上記2-3項と同様です。　次のリンクで音声認識のデモが確認できます。  
[RakutenMAによる人工無脳のデモへのリンク]()  

### おまけ：
フリーの形態素解析エンジンには、「Kuromoji」もありますが、辞書が充実している分処理が重くなるようで上記と同様なプログラムでは、一拍遅れてしまいましたので、ここでは掲載しません。  

## 3. Reference
[Web Speech API](https://developer.mozilla.org/ja/docs/Web/API/Web_Speech_API)
[RakutenMA](https://github.com/rakuten-nlp/rakutenma/blob/master/README-ja.md) 形態素解析エンジン  
[TinySegmenter](http://chasen.org/~taku/software/TinySegmenter/) 形態素解析エンジン  
[Kuromoji](https://www.atilika.com/ja/kuromoji/)形態素解析エンジン  

## 4. License
MIT  

## 5. Author
[T. Fujita](https://github.com/To-Fujita)  
