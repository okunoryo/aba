#実行方法

##プログラムの機能

*排出の検知(LED)

*自動メール送信

-------

##実行の前の設定

1. ラズベリーの時間の設定

コマンド : `sudo date -s "08/01 8:00 2014"`

修正して入力

2. cron設定（プログラムを自動実行にする）

コマンド: `crontab -e`

	書き足す→  `00 * * * * sudo python siri_save_kai.py`

