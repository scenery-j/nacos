# バグの報告方法

If any part of the Nacos project has bugs or documentation mistakes, please let us know by [issueを開く][Nacos-issue]. We treat bugs and mistakes very seriously and believe no issue is too small; anyone can handle it. Before creating a bug report, please check that an issue reporting the same problem does not already exist.

To make the bug report accurate and easy to understand, please try to create bug reports that are:

- Specific. Include as many details as possible: which version, what environment, what configuration, etc. If the bug is related to running the Nacos server, please attach the Nacos log (the starting log with Nacos configuration is especially important).

- Reproducible. Include the steps to reproduce the problem. We understand some issues might be hard to reproduce, please includes the steps that might lead to the problem. If possible, please attach the affected Nacos data dir and stack strace to the bug report.

- Unique. Do not duplicate the existing bug report.


It may be worthwhile to read [Elika Etemad’s article on filing good bug reports][filing-good-bugs] before creating a bug report.

We might ask for further information to locate a bug. A duplicated bug report will be closed.

[etcd-issue]: https://github.com/etcd-io/etcd/issues/new
[filing-good-bugs]: http://fantasai.inkedblade.net/style/talks/filing-good-bugs/

# バグ報告の送信方法Nacosプロジェクトのいずれかの部分に問題またはドキュメントの間違いがある場合は、[issueを開く][Nacos-issue] でお知らせください。私たちはバグと間違いを非常に真剣に受け止め、どんな小さな問題でも重要だと考えています。ただし、バグ報告を作成する前に、同じ問題を報告するissueが既に存在しないか確認してください。

エラーレポートを正確かつ理解しやすくするために、次のようなエラーレポートを作成してみてください：

- 詳細に具体的に。可能な限り多くの詳細を含めてください：バージョン、環境、設定など。エラーがNacosサーバーの実行に関連している場合は、Nacosのログ（特にNacos設定を含む起動ログ）を添付してください。

- 再現可能。問題を再現する手順を含めてください。一部の問題は再現が難しい場合があることを理解していますが、問題につながる可能性のある手順を含めてください。可能であれば、影響を受けたNacosデータディレクトリとスタックトレースをバグ報告に添付してください。

- 重複しない。既存のバグ報告を複製しないでください。

バグ報告を作成する前に、[良いバグ報告の送信についてのElika Etemadの記事][Elika Etemadについて提交好错误报告的文章] [良いバグ報告のアーカイブ][归档好错误] を読むことをお勧めします。これがあなたにインスピレーションを与えるでしょう。

バグを特定するために追加情報を求める場合があります。重複したバグ報告は閉じられます。

[etcd-issue]：https：//github.com/etcd-io/etcd/issues/new
[filing-good-bugs]：http：//fantasai.inkedblade.net/style/talks/filing-good-bugs/