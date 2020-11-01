Want to run an AlphaGo strength Go bot by yourself? Believe me, it just that easy. In just 1 or 2 clicks and within a minute, you can have a Super Human level Go Bot running under your control. You don't need to spend thousand dollars on fancy GPU. 

All thanks to David Wu(Lightvector) who made this possible with his open source Go programs - KataGo and also Google Research Project Colab.

## OGS KataBot English Version:

https://colab.research.google.com/drive/19SMIBuxTNoONn14yck5kSt06mdp3w4BA?usp=sharing

## KGS KataBot English Version:

https://colab.research.google.com/drive/1mz1RE3ri0EZuVRd80aiNbJN_38wcRbI8?usp=sharing

## 奕客 KataBot 中文版:

https://colab.research.google.com/drive/1UXnozWXqGT19P6Gtou_AT9o79qHmfBAG?usp=sharing

国内的朋友可以使用“谷歌访问助手”或者其他办法连上Colab。 https://www.tianqiweiqi.com/google-helper.html

## OGS KataBot 日本語版:

https://colab.research.google.com/drive/1KLyTSP9NhWNyBlWSsMRqaBagxIWWzAnx?usp=sharing

## OGS KataBot 한국어판: 

https://colab.research.google.com/drive/1QcTfKOxsNUTL0A7RxDtBh3S3Uiud4ukH?usp=sharing


## SSH version iKataGo Client:

(@kinfkong网友帮忙做了一个SSH版本） 可以通过SSH连接到本地客户端如 Sabaki，Lizzie， Katrain等等 

https://colab.research.google.com/drive/1BT4GAlHC1p0gEtujp3EtAYgFSPIjLzxs?usp=sharing

https://github.com/kinfkong/ikatago-client

https://github.com/kinfkong/katago-colab/



## Original Release: July 12, 2020 (If you need more control and want to learn how to build KataGo, please follow below instructions)

## English Version:

Anyone can now run KataGo on OGS online-go.com  with Google Colab for Free. Please access below notebook file and SAVE AS YOUR OWN COPY. 

https://colab.research.google.com/drive/1vw8mzMs9aVwT025AV95FnIb8TgC3IMyH?usp=sharing

You may need to manually switch the $KATAGO_BACKEND with CUDA or OPENCL depending on what GPU you get with colab. It's the first line of Step 2 and default with "OPENCL"

  KATAGO_BACKEND="OPENCL"

For T4 recommend to use CUDA. For P100, P4 and K80 recommend to use OPENCL. First run !nvidia-smi see what GPU you get and then change CUDA/OPENCL accordingly.

The gtp_example.cfg file on this repo can be downloaded to your local pc and uploaded manually to colab folder KataGo/cpp using the folder icon on the left panel. See screenshot attached.

To run a bot on online-go.com, you need to first register an account on OGS and get an API Key for the bot account. Details please refer to gtp2ogs documentation below:
https://github.com/online-go/gtp2ogs

Please update your Bot Name <ogsBotName>  and Bot API Key <ogsBotApikey> in this line of code:
!nodejs /usr/lib/node_modules/gtp2ogs/gtp2ogs.js --username <ogsBotName> --apikey <ogsBotApikey> 

For more information about KataGo and latest updates, please check here:
https://github.com/lightvector/KataGo

Can also run bot on yikeweiqi.com. Please download config.json file to your local pc and update with your yikeweiqi.com account name and password and upload to Colab folder /KataGo/cpp/yk-linker/
https://home.yikeweiqi.com/ 

Supporting Google Colab by becoming a Colab Pro Member. With $10/month you get faster GPUs (T4 and P100) and longer run times.



## 中文版：

现在，任何人都可以免费使用Google Colab在online-go.com （OGS）或者是奕客围棋上运行KataGo。请访问下面的笔记本文件并另存为自己的副本。

https://colab.research.google.com/drive/1QoOakkD-5dHzxqGxcOUB8VAgRJ3cRzi0?usp=sharing

您可能需要在下面的代码行中手动切换CUDA / OPENCL，具体取决于您通过colab获得的GPU。

KATAGO_BACKEND="OPENCL"

对于T4，建议使用CUDA。对于P100，P4和K80，建议使用OPENCL。首先运行！nvidia-smi，查看您所获得的GPU，然后相应地更改CUDA / OPENCL。

可以将此存储库上的gtp_example.cfg文件下载到本地PC，然后使用左侧面板上的文件夹图标将其手动上载到colab文件夹KataGo / cpp。请参阅所附的屏幕截图。

要在online-go.com上运行AI，您需要先在OGS上注册一个AI帐户并获取该AI帐户的API密钥。详细信息请参考下面的gtp2ogs文档：
https://github.com/online-go/gtp2ogs

请在以下代码行中更新您的AI帐户名称<ogsBotName>和AI帐户API密钥<ogsBotApikey>：
！nodejs /usr/lib/node_modules/gtp2ogs/gtp2ogs.js --username <ogsBotName> --apikey <ogsBotApikey>

有关KataGo和最新更新的更多信息，请访问下面链接：
https://github.com/lightvector/KataGo

也可以在奕客围棋上运行。请将config.json文件下载到本地计算机，更改里面的奕客围棋帐户名和密码，然后上传到Colab文件夹/ KataGo / cpp / yk-linker /
https://home.yikeweiqi.com/

通过成为Colab Pro会员来支持Google Colab。 每月10美元，您可以获得更快的GPU（T4和P100）和更长的运行时间。



## 日本語版:

https://colab.research.google.com/drive/1yOsJCd2h5yNMORt2UtSj1cFtNyqpWmFe?usp=sharing



## 한국어판: (Tranlated with Google translate. Please excuse me if any translation errors)

https://colab.research.google.com/drive/14gWYc3D4FsUGf_euYBxpVOJ16mK5feEP?usp=sharing


Tag: Alpha Zero, Alpha Go, Muzero, Leela Zero, Fine Art, Golaxy, Crazy Stone, Zen, Handol, ELF