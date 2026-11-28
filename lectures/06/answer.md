# 第6回 解答

## 演習

<!-- [tool call] の行は、表示された行をそのまま貼り付けてください。終わらなかった STEP は、空欄のままでかまいません。 -->

- STEP 1 のツールの名前：glossary_search_glossary
- STEP 2 の [tool call]：glossary_search_glossary({'query': '3レベル'})
- STEP 3 の [tool call]：fetch_fetch({'url': 'https://modelcontextprotocol.io/'})
- STEP 4 の [tool call]：aws_aws___search_documentation({'search_phrase': 'Amazon S3 バージョニング 概要'})
- 気づき・疑問：

## 宿題

<!-- 基礎・実装・発展のどれか1つに取り組めば完了です。 -->

- 取り組んだレベル：基礎
- やったこと：MCPサーバーとしてget_lecture_summaryが呼び出されることを確認する
- 結果：無事に動作することを確認できた
- 気づき・疑問：生成AIツールでデータを繋ぐ際に便利に利用しているが、その裏側を知ることができて大変学びになった。便利なものは共通化されて利用者側は助かるが、提供者側は差別化要素がなくなるので、そこはどう考えるべきか、難しいと感じた。
