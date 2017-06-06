# git-practice2
## Git勉強会用のブランチです。

*Conflict*

1.HEADを起点としてトピックブランチ(topic-branchA,topic-branchB)を作成してください。  
2.topic-branchAで以下の作業を行ってください。  
2-1.text.txtの1行目に"Heaｒt to Heart"と記載しコミットしてください。  
2-2.text.txtに2行目に"アルプス技研は、人と人との心のつながりを大切にしています。"と記載しコミットしてください。  
3.topic-branchBに切り替えてください。  
4.topic-branchBで以下の作業を行ってください。  
4-1.text.txtの1行目に"人と人の心のつながりや"を記載しコミットしてください。  
4-2.text.txtの2行目に"心のふれ合いは"を記載しコミットしてください。  
5.masterブランチへtopic-branchAの内容をマージしてください。  
　※マージコミットを作成するようにしてください。  
6.masterブランチへtopic-branchBの内容をマージしてください。  
7.コンフリクトが発生した場合は文章が成り立つようにコンフリクト解消を実施してください。  

*Amend/rebase*

1.HEADを起点としてトピックブランチ(topic-branchC)を作成してください。
2.topic-branchCで以下の作業を行ってください。
2-1.text2.txtの1行目に"相手への思いやりの心からである。"と記載しコミットしてください。
2-2.2で記載した内容は誤りがあるため、"相手への真の思いやりの心からである。"と修正しコミットしてください。
　なお、追加コミットではなく直前のコミットを修正する形で対応してください。
2-3.text2.txtの2行目に"～経営理念より～"と記載しコミットしてください。
2-4.3,4でコミットした内容を1つのコミットとして纏めてください。

*cherry-pick*

1.masterブランチへ切り替えてください。
2.topic-branchCのコミット内容をcherry-pickしてください。
