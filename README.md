<h1 align="center">
    2023년 소인수 강좌
</h1>

<p align="center">
    <a>코드 실행 직후</a>
    <img src="https://github.com/osuRedstar/Redstar-Cron.py/blob/seongpo.s210189/img/1.코드실행%20직후.png"/>
    <a>코드 실행중-1</a>
    <img src="https://github.com/osuRedstar/Redstar-Cron.py/blob/seongpo.s210189/img/2.코드%20실행중-1.png"/>
    <a>코드 실행중-2</a>
    <img src="https://github.com/osuRedstar/Redstar-Cron.py/blob/seongpo.s210189/img/3.코드%20실행중-2.png"/>
    <a>디스코드 결과 출력-1</a>
    <img src="https://github.com/osuRedstar/Redstar-Cron.py/blob/seongpo.s210189/img/4.디스코드%20결과%20출력-1.png"/>
    <a>디스코드 결과 출력-2</a>
    <img src="https://github.com/osuRedstar/Redstar-Cron.py/blob/seongpo.s210189/img/5.디스코드%20결과%20출력-2.png"/>
    <a>디스코드 결과 출력-3</a>
    <img src="https://github.com/osuRedstar/Redstar-Cron.py/blob/seongpo.s210189/img/6.디스코드%20결과%20출력-3.png"/>
</ps>
# Redstar
Redstar에 맞게 수정함

# Cron
The cron job write by Python. Based on Akatsuki's cron job and adjusted somethings.


## Features
+ Recalculate the total PP value of users in all modes and vanilla, relax
+ Recalculate ranks (all modes and vanilla, relax)
+ Update total score
+ Remove expired donor badges
+ Add donor badges
+ Calculate user total playcount
+ Send the progress of Cron Job to discord webbook
+ Multiple send webhooks support
+ Schedule System


## Setup
First, install the requirements.
```
$ python3 -m pip install -r requirements.txt
```
Once that's finished, you can go ahead and make a config file, by doing:
```
$ cp ./config.sample.ini ./config.ini
$ nano config.ini
```
Then you can go ahead and change the needed stuff in there.

If you want to send webhooks to multiple, you can add `, `   between webhook urls in config file.
```
ex) DISCORD_WEBHOOK = https://discord.com/api/webhooks/123456/QWEQWE, https://discord.com/api/webhooks/456456/ASDASD
```


And the last thing you have to do, is running the cron job
```
$ python3 cron.py
```

If there's any issues during setup and runninng the cron job, feel free to post an issue <3

## Original Repo
[ORIGINAL | cmyui - Akatsuki-cron-py](https://github.com/cmyui/Akatsuki-cron-py) \
[Ainu fork | osuthailand - ainu-cron-py](https://github.com/osuthailand/ainu-cron-py) \
[Debian fork | osuDebian - Cron](https://github.com/osuDebian/Cron) \
[Redstar fork | osuRedstar - Redstar-Cron.py](https://github.com/osuRedstar/Redstar-Cron.py)
