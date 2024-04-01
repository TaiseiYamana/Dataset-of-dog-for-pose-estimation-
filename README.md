# 柴犬の姿勢推定:Open Poseで実験

![inference](https://github.com/TaiseiYamana/Siba_inu_pose_estimation/assets/54575368/8a5abd5f-28b9-4331-bb65-a09b45860059)
<img src="https://github.com/TaiseiYamana/Siba_inu_pose_estimation/assets/54575368/8a5abd5f-28b9-4331-bb65-a09b45860059" width="400">


## データセット詳細
<img width="673" alt="スクリーンショット 2020-02-14 1 47 19" src="https://user-images.githubusercontent.com/54575368/94964736-307f8080-0535-11eb-8d45-cfc759bf609c.png">
上図のようにMSCOCOの形式でアノテーションをしています。  

https://drive.google.com/drive/folders/1Z-f1gLIG3Wu5af_nlYagRipoKX1g7Cu-?usp=sharing  

上記のGoogle DriveのURLから自由にダウンロードしてくだいさい。よければダウンロードの目的をIssuesに投稿して欲しいです。

Open Poseの学習にも使用できますが、データ数が少ないので学習ができるかわかりません。

* 作成したデータセット数

| | Image & Annotation|
| :-: | :-: |
| Train| 210 |
| Verification| 30 |  


* アノテーションに使用したツール

COCO Anotater:
https://github.com/jsbroks/coco-annotator

<img width="1406" alt="スクリーンショット 2020-10-03 5 07 10" src="https://user-images.githubusercontent.com/54575368/94967077-5f97f100-0539-11eb-999f-a58b4b8608d6.png">
