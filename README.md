# HTML, CSS, Bootstrap
<p align="center">
    <img src="https://img.shields.io/badge/HTML5-c0c0c0.svg?logo=html5&style=flat">
    <img src="https://img.shields.io/badge/CSS3-1572B6.svg?logo=css3&style=flat">
    <img src="https://img.shields.io/badge/Bootstrap%204.6.0-563D7C.svg?logo=bootstrap&style=flat">
</p>

```
まとめ
    HTML（Hyper Text Markup Language）
        ・大抵開始タグがあり、終了タグがある。（一部終了タグがないものもある。imgタグやinputタグなど）

        ・絶対に必要なタグ
            DOCTYPE
                HTML5を使用しますよ、という宣言。
            htmlタグ
                HTMLを書いていきますよ
            headタグ
                ブラウザに認識してほしい情報を書いていきますよ
            bodyタグ
                ユーザーに閲覧してほしい情報を書いていきますよ

        ・覚えておくべき重要なタグ
            aタグ
                <a href="https://nexseed.net/">ネクシードへのリンク（タブ内）</a>
                <a href="https://nexseed.net/" target="_blank">ネクシードへのリンク（別タブ）</a>

            imgタグ
                <!-- 画像が置いてあるURLを指定する方法 -->
                <img src="https://nexseed.net/blog/wp-content/uploads/2018/07/headernew2.jpg">

                <!-- 画像が置いてあるパスを指定する方法 -->
                <img src="../images/sample.png">

                <!-- 本来どんな画像が表示されるか説明する -->
                <img src="" alt="NexSeed ロゴ">

        ・外部CSSファイルの読み込み
            <link rel="stylesheet" href="style.css"> style.cssを読み込む。
            <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/....style.css"> CDNで外部サイトのstyle.cssを読み込む。

    CSS（Cascading Style Sheets）
        HTMLタグにインラインでCSSをあてることもできるが、HTML内に<style></style>の中にCSSを書くこともできる。
        メンテナンス性が高いため、実務ではCSSファイルとして切り出し、HTMLから読み込むことが多い。

        セレクタ・タグ/id/class
            body {}でbody全体にcssをあてる。
            div p {}でdiv内のpタグ全部にcssをあてる。
            #idName {}でid="idName"にcssをあてる。
            .class_name {}でclass="class_name"にcssをあてる。

        bootstrap
            https://getbootstrap.com/

                (グリッドシステム)
                xs sm md lg xl
                .container > .row > col-?-?
                https://github.com/NexSeed00/Bootstrap_basic
```
