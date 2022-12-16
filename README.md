## 内容

[Ansible AWXとGitLabを組合わせて構成管理の仕組みを構築](https://qiita.com/tkubota/items/3742e85687361bcd410c)で使用したAnsible Playbookの一例です。

<img width="767" alt="スクリーンショット 2022-12-16 18 53 03" src="https://user-images.githubusercontent.com/102895466/208072339-9a2c48b7-c2cc-4486-ad74-3fbdb8bfdeaf.png">

## PlayBook

| PlayBook| 説明 |
| ------ | ------ |
| Cisco-Get-Config.yml | CiscoのConfigを取得する |
| Cisco-Get-Status.yml | CiscoのPortステータス情報を取得する |
| VyOS-Get-Config.yml | VyOSのConfigを取得する |
| vSphere-Get-VM.yml | vSphereの仮想マシン情報を取得する |

## 使用方法
上記AWX環境や```ansible-playbook```コマンドで実行します。

別途```inventory file```などの準備が必要です。
