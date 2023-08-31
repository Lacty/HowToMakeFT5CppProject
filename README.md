# HowToMakeFT5CppProject
日本語やでこれ  
1. DLLプロジェクト作成
2. FT5/Exam/Indi/C++のサンプルをプロジェクトにコピペ
3. ファイル名をプロジェクト名に変更
4. defファイル内のライブラリ名を変更
5. コピペしたファイルをソリューションに追加
6. ビルドx64からx86にDebugからReleaseに
7. プロジェクトのプロパティC++/コード生成/ランタイムライブラリをMTに変更
8. リンカー/入力/モジュール定義ファイルに<project>.def入力
9. C++/言語/準拠モード いいえ(/premissive)に変更
10. <project>.cppに#include "pch.h"追加
11. dllmain.cpp内をコメントアウト
