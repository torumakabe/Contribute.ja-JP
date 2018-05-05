---
title: docs.microsoft.com に投稿する方法
description: この記事では、docs.microsoft.com にコンテンツを投稿するさまざまな方法の概要を説明します。
author: billwagner
ms.author: wiwagn
manager: wpickett
ms.date: 01/17/2018
ms.prod: non-product-specific
ms.topic: contributor-guide
ms.custom: external-contributor-guide
ms.openlocfilehash: bc6f9c314eda5f0d950da049374a7a157f16782a
ms.sourcegitcommit: de6e6b6ca641fdd5b30eb46deee9ac3a500089ef
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2018
---
# <a name="how-to-contribute-to-docsmicrosoftcom"></a>docs.microsoft.com に投稿する方法

[docs.microsoft.com](https://docs.microsoft.com) を構成するコンテンツを改善する作業に参加するには、次のようないくつかの方法があります。

- [案件を作成します](#create-issues)。これは、新しい記事を勧めるときや、既存の記事を改善したいときに行います。
- 記事を[クイック編集します](#quick-edits)。GitHub オンライン エディターで小規模な変更を加えることができます。
- [新しい記事の下書きをレビューします](#review-new-articles)。この目的は、質と技術的な正確さの確保です。
- トピックのコンテンツ発展に協力したい場合に、[新しい記事を新規作成します](#create-new-articles)。
- 重要な概念の説明に役立つコード サンプルを向上させるために、サンプルを[更新](#update-samples)または[作成](#create-samples)します。

この記事では、さまざまな投稿の方法、投稿のための各タスクを達成する方法、そのような各タスクの詳細情報を指すポインターを検索する方法について説明します。

パブリック リポジトリは [GitHub](https://wwww.GitHub.com) でホストされています。  ドキュメント リポジトリに参加するために、GitHub のアカウントを作成する必要があります。

また、ドキュメントを更新するためにテキスト エディターも必要になります。 [Visual Studio Code](https://www.visualstudio.com/code) をお勧めします。 [Markdown](https://daringfireball.net/projects/markdown/syntax) 構文の基本を理解している必要があります。

サンプルの追加または変更を行う場合は、開発環境が必要です。 PC および Mac では [Visual Studio](https://www.visualstudio.com)、すべてのプラットフォームが対象になる場合は [Visual Studio Code](https://www.visualstudio.com/code) をお勧めします。

## <a name="create-issues"></a>案件を作成する

記事の中に脱落または誤りを見つけた場合は、その記事に対して案件を作成します。 正しい場所を見つけるにはブラウザーで [編集] ボタンをクリックするのが最も簡単な方法です。適切なパブリック GitHub リポジトリ内の記事ソースが表示されます。 ここで、アドレス バーから、記事のソースの URL を取得できます。 [Create Issue]\(案件の作成\) をクリックして、記事に対して新しいイシューを作成します。

> [!NOTE]
> 入力の誤りや文法の問題など、小規模な編集で修正できる問題が見つかった場合は、ソースを編集するためのブラウザーを使用して[修正内容を送信](#quick-edits)すると、ユーザーおよび Microsoft 双方の作業時間を節約することができます。

ほとんどのパブリック リポジトリには、新しいイシュー用のテンプレートが含まれており、これを利用すると、ユーザーは問題解決に必要な情報を容易に提供できます。

必要としている情報が見つからない場合は、新しいイシューを投稿することもできます。 プロセスは同じで、パブリック ドキュメント リポジトリのいずれかに対して新しい案件を作成します。 どのような内容を探していたのか、行いたかったことは何だったのか、見つけた記事はなぜ期待どおりのものでなかったのかをお知らせください。

## <a name="review-new-articles"></a>新しい記事をレビューする

新しいソフトウェア (CTP またはベータ版の可能性あり) で作業する場合、大抵はテクノロジを検証できるようにドキュメントが作成されています。 ユーザーはパブリック リポジトリでインプロセス ドキュメントを探すことができます。 コメントをお寄せいただくと、リリース前の品質向上に貢献することができます。

新しい記事は、[GitHub フロー](https://guides.github.com/introduction/flow/) プロセスによりパブリックでレビューされます。 ドキュメント リポジトリのいずれかを参照し、開いているプル要求 (PR) を確認します。 開いているプル要求に対するコメントおよびレビューをお寄せください。 それにより、運用開始後のフィードバックを待たずに、最初のリリースからより質の高いコンテンツを発行することができます。

技術的な正確さ、説明のわかりやすさ、および文法的な精度を改善する方法を探しています。

## <a name="quick-edits"></a>クイック編集する

クイック編集は、ブラウザー ベースのエディターを使用して小規模な修正を加える方法です。 スペルまたは文法の小さな誤り、あるいは名前に誤りのある API を見つけた場合は、PR を編集および送信すると、イシューの作成を省略することができます。

任意の記事で、[編集] ボタン (通常はページの右上にある) をクリックし、編集して、ページの下部にある [Submit PR]\(PR の送信\) をクリックします。 Microsoft ではその PR をレビューし、毎日の PR レビューを行うときにマージします。

## <a name="create-new-articles"></a>新しい記事を作成する

自分が熱心に取り組んでいる概念を他のユーザーにも説明する必要がある場合は、記事を作成して PR を送信することができます。

新しい記事の作成は時間のかかる作業であり、皆さまが費やす時間と貢献に感謝しています。 始めからガイドラインおよびスタイルに確実に従っていただけるように、Microsoft が初期の段階からプロセスに関与します。 次の手順をお勧めします。

1. 不足している内容および対処方法を説明する[案件を作成](#create-issues)します。
1. イシューに対してコメントします。これにより、作業を行いたい旨を連絡し、記事の概要と要約を提示します。
1. それに対して Microsoft からの提案が返されます。 それには、関連記事へのリンク、サンプルに関する提案、または記事の整理方法が含まれる場合があります。
1. Microsoft からの同意が得られたら、リポジトリをフォークし、作業を開始します。
1. プロセスの初期段階で、PR を開きます。タイトルの先頭に "[WIP]" と表示されます。
1. 中心的な共同作成者のうち一人から最初のフィードバックが提供されます。
1. 作成を続け、さらなるフィードバックに対応する準備ができたら、最初の下書きをレビューしたユーザーを @-mention します。
1. 最終的なレビューの準備ができたら、"[WIP]" を削除します。
1. フィードバックに応答します。
1. 中心的な共同作成者によって PR がマージされます。

そのリストから展開するだけの価値を持つポイントがいくつかあります。 一般的に、Microsoft では [GitHub フロー](https://guides.github.com/introduction/flow/)に従って、できるだけ早期にコンテンツをレビューします。 このようにして、Microsoft は記事が配置される目次内の場所、閲覧者が新しい記事から取得する利点、作成されるサンプルのスコープについて同意します。 記事の作成に膨大な時間が費やされる前に、早い段階で必要な軌道修正することができます。

## <a name="update-samples"></a>サンプルを更新する

サンプルの中には場合によっては、推奨されなくなった方法を使用して、いくつか前のリリースで元々作成されているものがあります。 このようなサンプルの更新に協力いただく場合があります。 あるいは、変数名の簡単な変更によって、説明のわかりやすさが向上することにお気づきになる場合もあります。

各記事に表示されているサンプル コードは、ビルドされたプログラムの一部であり、ほとんどのプログラムは Microsoft の CI システムでテストされています。

小規模な更新を行うには、適切なリポジトリ内でソースを見つけ、ブラウザーでコードの変更を行い、PR を送信します。 変更は CI システムによってビルドされます。そのビルドが完了したら、Microsoft で PR をマージします。

大規模な変更の場合は、リポジトリをフォークし、好みの開発環境で変更を行います。 変更が意図したとおりに動作するように、必ずいくつかのテストを追加してください。 PR を送信すると、Microsoft によりレビューされます。

すべてのコード変更において、変更するサンプル コードに対する既存のコード規則に従います。 サンプル リポジトリ コーディング標準は、対応する製品チームのものを反映します。 特定のガイダンスについては、各リポジトリを確認してください。

> [!NOTE]
> Microsoft 自体が、このガイダンスに従うことに取り組んでいます。 サンプルの中には以前の標準に従っていて、まだ更新されていないものがあります。 Microsoft では実行するサンプル コード全体をテスト済みの動作サンプルから表示するという目標に取り組んでいます。

## <a name="create-samples"></a>サンプルを作成する

概念またはシナリオを実証する新しいサンプルを作成することもできます。 どのサンプルにも、その重要な情報を説明する記事を添付する必要があります。

新しいサンプルが既存の記事を補完するものである場合は、その記事内にサンプルへの参照を追加します。 そうでない場合は Microsoft とともに、サンプルが付属された[記事を協力して作成](#create-new-articles)していただきます。

すべての場合に、サンプル コードは関連する製品チームで使用されているコーディング規則に従います。 ただし、例外が 1 つあります。記事の中に暗黙的に型指定 (`var` で宣言) された変数の宣言がある場合、それらの変数に対しては、わかりやすさを重視して明示的に型指定された変数を使うことがほとんどです。

開発プロセスの早い段階で Microsoft がコードを確認できるように、[新しい記事](#create-new-articles)の前半のセクションで概説したサンプル プロセスに従ってください。