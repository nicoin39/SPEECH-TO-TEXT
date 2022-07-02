# SPEECH-TO-TEXT
SPEECH TO TEXT（Google-API）の備忘録

①pythonスクリプト毎にos設定が必要。
<p>import os<p>

②pythonスクリプト毎にos設定が必要。
os.environ['GOOGLE_APPLICATION_CREDENTIALS'] = 'pra.json'

③pipインストール。3を付けること。
!pip3 install --upgrade google-cloud-speech

④mp3もしくはwavで音声ファイルを用意する。16000Khzで。
