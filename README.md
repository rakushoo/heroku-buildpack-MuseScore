# heroku-buildpack-MuseScore
HerokuサーバーにMuseScore(3.4.2)をダウンロードするためのBuildpack
/app/tool 以下にコピーします。

# 使用方法

Step 1: Heroku Dashboard -> (App name) -> Settings -> Buildpacks の Add buildpack を押下してリポジトリを追加  
Step 2: コマンドラインから環境変数を追加  
$> heroku config:add BUILDPACK_URL=https://github.com/rakushoo/heroku-buildpack-MuseScore.git
