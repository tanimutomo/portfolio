+++
title = "GANonymizer: 物体検出敵対的生成を統合した映像匿名化手法"
date = 2018-08-24T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["谷村朋樹", "河野 慎", "米澤 拓郎", "中澤 仁"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = "研究報告ユビキタスコンピューティングシステム"
publication_short = "UBI"

# Abstract and optional shortened version.
abstract = "街の様子を映した映像を分析することで，街の状態を自動で把握，予測することが可能となる．しかし，街の映像には人や車などのプライバシーに関する物体が含まれているため，無加工の状態でネットワークに送信 ・ 共有したり，利用することは難しい．結果，プライバシー情報が含まれる可能性のある映像は有効活用されないまま，消去されている．本研究では，映像からプライバシーに関する物体を自動で検知し，そもそもそこに存在しなかったかごとく映像上から消去する GANonymizer を提案する．提案手法では，まず入力画像から深層学習を用いた物体検出技術を用いて，人や車などのプライバシーに関する物体を検出する．そして敵対的生成ネットワークを用いて，検出した物体を取り除いた画像を生成し，元の画像に合成する．本研究では，実際の街を走る車から撮影した画像に適用し，その結果について報告する．"
abstract_short = "本研究では，映像からプライバシーに関する物体を自動で検知し，そもそもそこに存在しなかったかごとく映像上から消去する GANonymizer を提案する．提案手法では，まず入力画像から深層学習を用いた物体検出技術を用いて，人や車などのプライバシーに関する物体を検出する．そして敵対的生成ネットワークを用いて，検出した物体を取り除いた画像を生成し，元の画像に合成する．"

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["プライバシ保護", "都市画像・動画", "匿名化", "深層学習"]

# Links (optional).
url_pdf = "https://ipsj.ixsq.nii.ac.jp/ej/index.php?active_action=repository_view_main_item_detail&page_id=13&block_id=8&item_id=191009&item_no=1"
# url_preprint = ""
url_code = "https://github.com/tanimutomo/ganonymizer"
# url_dataset = "#"
# url_project = ""
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# [image]
#   # Caption (optional)
#   caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
# 
#   # Focal point (optional)
#   # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
#   focal_point = ""
+++

