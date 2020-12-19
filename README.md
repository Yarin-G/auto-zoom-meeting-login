<p align="center">
  <img src="https://camo.githubusercontent.com/3f9d1f717974430cff1b747471a93fc833a87fbdf5d5b3e4c7f4da34325d280e/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3738363730383939323239383331393931322f3738393839343734313435373130393033322f62616e6e65722e6a7067" width="750px">
</p>
<br>

## Automatic Meeting Join
a simple python script which joins your zoom meeting.<br>
the script will join without audio and without audio so you can keep sleeping

## Requirements
* python 3.6 or higher (https://www.python.org/)
* pip
* Clone this repository
* Download requirements using `pip install -r requirements.txt`
* run `python auto.py`

## Setup
* go to `meetings.xlsx` file and add your meetings<br>
***you have two options:***<br>
(1) join with meeting link (leave the `Meetting id` and `Meeting Passcode` empty)<br>
           **or**<br>
(2) join with meeting id and meeting passcode (leave the `Meetting Link` empty, in case meeting has no passcode leave it empty)<br>
* make sure to fill in `auto.py` the `Xl_FILE_PATH` and `ZOOM_PATH`