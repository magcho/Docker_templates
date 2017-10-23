# Docker_templates

## webServer_php_sql_phpmyadmin

````http://localhost:80/```でアクセスできます。リポジトリのルートがHTMLの公開ディレクトリです。


phpmyadminにアクセスしたい場合は、```http://localhost:8080/```でアクセスできます。sqlのデータはディレクトリに保存されているので、再起動時も残ったままだし、gitで管理できます。

**このブランチのデータでは、セキュリティの事情で使えない機能が多いです。ModRewriteとか**使いないなら別ブランチにあるよ。