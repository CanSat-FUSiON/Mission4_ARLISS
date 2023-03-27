# Mission4_ARLISS
これはCanSatチームFUSiONがMission4でARLISS2023への出場を目的として使用するリポジトリです。

こちらにFUSiON Mission4で使用したCodeを保管してください。

編集方法


A．ローカルで編集する場合（push, cloneなどはオンライン下でのみ使用可能）


    1．自分のPCに「git clone」というコマンドを使いリモートリポジトリをローカル環境にコピー

    2．VS code(ない人はインストールおすすめ)でファイルを開き、新しいブランチを切って編集

    3．編集したものをCommitし、リモートリポジトリへpush

    4．githubのMission2のページに移動し、pull requests の New pull request をクリック。左側のブランチをmain、右側のブランチを自分のブランチに設定

    5．Create pull request をクリックしリクエストを作成（writeのとこに何を変えたのか書いておくとよい）

    6．本当はよくないが、そのまま自分でMerge pull request をクリック（本来は別の人にチェックしてもらってからだけど、編集のスピードを上げるため自己判断でmergeを許可）

    7．Mergeした後はブランチを消す（残っていても問題はないが、あまり乱立するとわかりにくいので、僕は毎回消しています）

    8．ラズパイ側でgit cloneを実践。二回目からはgit pull. sshの設定を行っているとスムーズです）


B．リモートで編集する場合


    1．ブランチ選択で新たなブランチを作るか、使用したいブランチを選択

    2．ファイルを選び編集

    3．A．と同じ手順でpull request を作成、merge

    4．ラズパイでgit clone or git pull
