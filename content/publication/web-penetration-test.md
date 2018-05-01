+++
title = "01. Web脆弱性診断"
date = ""

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [""]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "<h4>Webアプリケーション脆弱性診断とは</h4><p>ここでいうWebアプリケーションの脆弱性とは、いわゆる典型的なクロスサイトスクリプティング(XSS)やクロスサイトリクエストフォージェリ(CSRF)等のような典型的な脆弱性もですが、それ以外にもアプリケーション特有のロジックミスによる脆弱性も含みます。アプリケーション特有のロジックミスとは、例えば「本来ユーザーAしか見えてはいけないページが、権限設定のミスによりユーザーBにも見えてしまった(個人情報漏洩)」のようなものです。Webの脆弱性診断というと前者のようなもののみに焦点が当たりますが、現在ではそのような典型的な脆弱性はフレームワークやライブラリにより事前に対策が打たれていることが多くなります。一方で、実装や設計のミスによる脆弱性は見過ごされがちですが、被害は典型的な脆弱性同様に大きくなりうる可能性があります。</p><h4>成果物について</h4><p>成果物としては、脆弱性の一覧表とその対策、リスクの大きさなどを一覧できるものを作成し共有します。脆弱性診断を行って問題が発見されても正しい修正方法が開発者にわかりやすく伝わらなければ意味がありません。また、問題が見つかったとしても重要なものでなければ経営判断として修正を行わないという判断もあるかと思います。そのような場合にリスクの大きさと修正方針が明確でなければ意味がないと考えています。</p> <h4>その他</h4><p>細かな要望や条件のもと予算や期間との兼ね合いに柔軟に対応できます。脆弱性診断は大手の企業等に安価でお願いした場合には事前のヒアリングや規模感のフィッティング等から含めて、事前準備が大変な割にはツールを自動で回した結果が得られるだけになったり、もしくは精緻に脆弱性を網羅的に発見しようとした場合などには高額になりがちです。私の場合は個人ですので、チームにセキュリティ担当がジョインしているかのような状態で貢献することが可能ですし、「ここは決済機能なので重点的に見ておきたい」等の要望には比較的応えられると思っています。セキュリティは日々移り変わりゆくものという性質があり、パフォーマンスとしては基本的にはベストエフォートとなります。<p>"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = [""]

# Links (optional).


# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "headers/mother_board.jpg"
caption = ""

+++
