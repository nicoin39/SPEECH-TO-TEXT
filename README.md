# SPEECH-TO-TEXT
SPEECH TO TEXT（Google-API）の備忘録

<strong>①pythonスクリプト毎にos設定が必要。</strong>
<p>import os</p>

<strong>②pythonスクリプト毎にos設定が必要。</strong>
<p>os.environ['GOOGLE_APPLICATION_CREDENTIALS'] = 'pra.json'</p>

<strong>③pipインストール。3を付けること。</strong>
<p>!pip3 install --upgrade google-cloud-speech</p>

<strong>④mp3もしくはwavで音声ファイルを用意する。</strong>
<p>16000Khzで。</p>
