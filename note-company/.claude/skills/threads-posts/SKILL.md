---
name: threads-posts
description: note記事へ集客するThreads投稿を1週間分作る。社長が「Threadsの投稿を作って」「宣伝して」と言ったとき、または /threads-posts で使う。
argument-hint: "[記事のfinal.mdのパス(省略すると最新の記事)]"
---

# Threads集客投稿づくり

対象記事:$ARGUMENTS

1. 記事が指定されていなければ、`articles/` の中で一番新しい `final.md` を使う。記事がなければ、`brand/profile.md` のテーマでフォロワーを増やすための投稿を作る
2. 社長に、記事のnote URLが決まっているか聞く。まだなら `【noteのURL】` と仮置きする
3. `threads-marketer` に、記事のパスとURLを渡して7日分の投稿を作らせる
4. 出来上がった投稿のうち、すべて500文字以内か、有料部分の中身を出しすぎていないかを確認する
5. 社長には、ファイルの場所と、特におすすめの投稿を2つ見せる

投稿は社長がThreadsアプリから行う(このチームは投稿しない)。
