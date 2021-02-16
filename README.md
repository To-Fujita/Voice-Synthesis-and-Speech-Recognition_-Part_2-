# Voice Synthesis and Speech Recognition (Part-2)
These are part-2 of voice synthesis and speech recognition programs. In this part, I had created some programs by HTML and JavaScript. It is also the language that can be recognized is only Japanese.

## 1. Description
　無料で使用可能な音声合成と音声認識プログラムの（その２）をお届けします。　本プログラムは、HTMLとJavaScriptで作成しました。　音声合成／音声認識エンジンは、Web Speech APIを使用しました。　また、日本語のセパレータ、形態素解析エンジンには、「TinySegmenter」あるいは「RakutenMA」を使用しています。　さらに、「Web AI」のマルコフ連鎖で適当な文章を作成するバージョンや「Bot UI」を使用したバージョンも作成しました。　なお、ニュースや天気予報、ウキペディアの検索が可能な人工無脳を試みたい方は、[Voice Synthesis and Speech Recognition (Part-1)](https://github.com/To-Fujita/Voice-Synthesis-and-Speech-Recognition_-Part_1-)をご覧ください。  

## 2. Details and Demo
　本プログラムは、４つのパートから構成されており、上記「Code」から一括ダウンロードできます。　また、次のメニューからそれぞれのデモを確認することができます。　これらのデモは、Windows10日本語版で動作を確認していますが、Android版も追加しました。　以下にそれぞれのパートについて説明します。  
 [デモ・メニュー](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/index.html)  

### 2-1: 音声合成
　「Voice_Synthesis.html」が入力された文字を読み上げるだけのシンプルなプログラムです。　本プログラムは、色々なプラウザに対応しており、プラウザによって使用できる音声が異なりますので、お楽しみください。　なお、一般的な設定では、日本語と英語に対応しています。　次のリンクで音声合成のデモが確認できます。  
[音声合成のデモへのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/Voice_Synthesis.html)  

### 2-2: 音声認識
　「Voice_Recognition.html」が標準入力デバイスであるマイクから入力された音声を文字で表示するプログラムです。　使用できるプラウザは、現在のところGoogle Chromeのみのようです。　また、一般的な設定では、日本語の音声認識にのみ対応しており、次のリンクでデモが確認できます。　なお、Windows10とAndroidでWeb Speech APIあるいはGoogle Chromeの挙動が若干異なるようですので、Windows10用とAndroid用のデモをそれぞれ準備しました。  
[音声認識（Windows10用）のデモへのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/Voice_Recognition.html)  
[音声認識（Android用）のデモへのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/Voice_Recognition_Android.html)  

### 2-3: 音声合成と音声認識を使用した人工無脳との会話（TinySegmenter 版）
　「Voice_Synthesis_and_Recognition_001.html」がTinySegmenterを使用した人工無脳との会話プログラムです。　簡単な人工無脳ですので、シナリオに沿った受け答えしかできませんが、ご自身で会話データを作成し読み込ませることで拡張できるようにしています。　会話データは、「./Data/Talk_List_002.csv」を参考に、エクセル等でA列にあなたの言葉や質問を、B列以降に人工無脳からの返答を数個記載（任意の返答がランダムに返されることになる）して作成して下さい。　なお、作成した会話データは、csv形式、Shift-JISでローカルに保存して下さい。　プログラムの上部にファイル選択がありますので、そこから作成した会話データを読み込むことになります。　次のリンクであいさつ程度に対応した簡易人工無脳のデモが確認できます。  
　また、「Web AI」のマルコフ連鎖でのランダムな文章作成及び「Bot UI」を使用したデモも作成してみました。  
[TinySegmenterによる人工無脳のデモ（Windows10用）へのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/Voice_Synthesis_and_Recognition_001.html)  
[TinySegmenterによる人工無脳のデモ（Android用）へのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/Voice_Synthesis_and_Recognition_001_Android.html)  
[TinySegmenter, Web AI and Bot UIによる人工無脳のデモ（Windows10／Android用）へのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/TinySegmenter_Markov_001.html)  

### 2-4: 音声合成と音声認識を使用した人工無脳との会話（RakutenMA 版）
　「Voice_Synthesis_and_Recognition_002.html」がRakutenMAを使用した人工無脳との会話プログラムです。　形態素解析エンジンが異なるだけで、扱いは上記2-3項と同様です。　次のリンクでWindows10用とBot UI使用版それぞれの音声認識のデモが確認できます。  
[RakutenMAによる人工無脳のデモ（Windows10用）へのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/Voice_Synthesis_and_Recognition_002.html)  
[RakutenMA and Bot UIによる人工無脳のデモ（Windows10／Android用）へのリンク](https://to-fujita.github.io/Voice-Synthesis-and-Speech-Recognition_-Part_2-/Voice_Synthesis_and_Recognition_002_Android.html)  

### おまけ：
　フリーの形態素解析エンジンには、「Kuromoji」もありますが、詳細な形態素解析が可能で辞書が充実している分処理が重くなるようで、上記と同様なプログラムでは反応が一拍遅れてしまいました。  

## 3. Reference
[Web Speech API](https://developer.mozilla.org/ja/docs/Web/API/Web_Speech_API)：　音声合成・音声認識エンジン  
[RakutenMA](https://github.com/rakuten-nlp/rakutenma/blob/master/README-ja.md)：　形態素解析エンジン  
[TinySegmenter](http://chasen.org/~taku/software/TinySegmenter/)：　形態素解析エンジン  
[Kuromoji](https://www.atilika.com/ja/kuromoji/)：　形態素解析エンジン  
[Voice Synthesis and Speech Recognition (Part-1)](https://github.com/To-Fujita/Voice-Synthesis-and-Speech-Recognition_-Part_1-)：　Visual StudioとSystem.Speechによる音声合成・音声認識プログラム  
[Web AI](https://crocro.com/write/web_ai/wiki.cgi)：　JavaScriptライブラリ「Web AI」  
[Bot UI](https://github.com/botui/botui)：　手軽にチャットボットを作ることができるjavascriptライブラリ  

## 4. License
MIT  

## 5. Author
[T. Fujita](https://github.com/To-Fujita)  
