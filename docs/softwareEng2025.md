---
layout: page
title: "software Eng. lecture note"
permalink: /docs/softwareEng2025
---

# ソフトウェア工学 2025

## 第1回：ガイダンス
- スケジュール説明
- 実務から体系化された知見のため、ソフトウェア開発に携わった経験が無いとイメージが湧きにくい

## 第2回：ソフトウェア工学概論
- ソフトウェアの定義：実行されることによって必要な特性、機能、性能を提供する命令群　など
- ソフトウェアの特徴：新しい環境や技術のニーズを満たすよう適応しなければならない　など
- Hookerの７原則
- コストの種類
## 第3回：ソフトウェアライフサイクル
- ニーズの発生、要件定義書をまとめる、ソフトウェアの開発、実稼働、保守運用、サービスの終了などを1つのサイクルとしている。
- 要件定義で書くべき内容
    システムの目的
    システムの概要
    システムの機能
    システム構成（システム構成図、ソフトウェアブロック図）
    目標性能
    他システムとのインターフェイス仕様
    運用面の注意事項
    制限事項
    拡張性
    開発スケジュール
    開発体制
    納品物        など、実現する機能、しない機能を明確にする。
- 設計：要件定義書から設計書へ
- 制作：設計書に従ってシステムを構築
- テストとデバッグ：バグを早期に発見・対処する

## 第4回：プロジェクト・ソフトウェア分析
- プロジェクト：有期性、独自性
- フォアキャスティング・バックキャスティング：インプット視点とアウトプット視点
- ソフトウェア分析：見える化する
- QCDの優先度
- ソフトウェアの評価基準、品質管理：コードの物量、Hyrumの法則
- 開発プロセス：ウオーターフォール型開発プロセス,スパイラルモデル,アジャイルプロセス,スクラム,カンパン,XP,リスク駆動形開発プロセス

## 第5回：プロジェクト・ソフトウェア分析
- WBS:プロジェクト目標を達成し、必要な要素成果物を生成するために、プロジェクトチームが実行する作業を、要素成果物を主体に階層的に要素分解したもの
- スコープを明確にして、大きな作業をグルーピングする。グルーピングした作業の相互関連を考え、各グループの作業を洗い出す。

## 第6回：第5回の続き

## 第7回：コーディング
- コードは読まれることが多いため、読みやすいコードを書くことが必須
- コーディングの規則の1つとしてPEP8が挙げられる。
- flake8、pvlintなどのチェックツールが存在する

## 第8回：バージョン管理
- ファイルを誰が、いつ、どのように変更したかを管理しておくことで多数のメンバーと共同でコード開発ができる
- gitは分散管理型のバージョン管理システム

## 第9回：外部講師による講演

## 第10回：learning git branching
- gitのコマンドを学んだ
- gitコマンドは修正系、リモート系、ブランチ系にまとめられる

## 第11回：Github
- Githubはリモートレポジトリのホスティングサービスの1つ
- Githubでのソフトウェア・エンジニアリングについて学んだ
- Github演習

## 第12回：CI/CD
- CI:Continuous Integration
- コード変更を共有リポジトリに頻繁に統合するプロセスで、自動テストとビルドを定期的に実行し、バグの早期発見と修正を可能にする
- CD:Continuous Delivery
- コード変更をテスト環境や本番環境に自動的にデプロイするプロセス
- flake8を使用

## 第13回：CI/CDの実践
- Githubにあるリモートレポジトリの内容をwebpageとして公開することができる。更新はCI/CDにより自動化
- Jekyll