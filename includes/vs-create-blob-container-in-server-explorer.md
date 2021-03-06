Visual Studio の **サーバー エクスプローラー**を使用すると、Azure ストレージ キューを作成できます。

![サーバー エクスプ ローラーの BLOB][Image1]

1. **[表示]** メニューの **[サーバー エクスプローラー]** を選択します。
2. サーバー エクスプローラーで、サブスクリプションの **[Azure]** ノードを展開し、**[Storage (ストレージ)]** ノードと Azure Storage 接続サービスで指定したストレージ アカウントのノードを展開します。
3. **[キュー]** ノードを選択して、コンテキスト メニューから **[キューの作成]** を選択します。
4. コンテナーの名前を入力し、 **[OK]**を選択します。   

既定では、新しいコンテナーはプライベートなので、このコンテナーから BLOB をダウンロードするにはストレージ アクセス キーを指定する必要があります。 コンテナー内のファイルを公開する場合は、**サーバー エクスプローラー**でコンテナーを選択し、`F4` を押して **[プロパティ]** ウィンドウを表示します。 **[パブリック読み取りアクセス]** を **[BLOB]** に設定します。 パブリック コンテナー内の BLOB は、インターネットに接続しているすべてのユーザーが表示できますが、変更または削除できるのは、適切なアクセス キーを持っているユーザーだけです。

[Image1]: ./media/vs-create-blob-container-in-server-explorer/vs-storage-create-blob-containers-in-Server-Explorer.png

<!--HONumber=Jan17_HO3-->


