# Ansibleでlampサーバを構築するサンプル
Ansibleでlampをインストールするサンプルです。
対象OSはAmazon Linux 2015.09です。
S3cmdを使用して、ログとファイルとDMPのバックアップを行います。
また、mackerelを利用してApacheのプロセス監視、ポート監視を行います。

'''
ansible-playbook -i hosts site.yml -c paramiko
'''
な感じで使います。