## OAI RAN向けConfig一覧
Open Mobile Network Infra Meetup 2の発表「OAI Master v1.2.2にスマホにつないだ結果」で使用したConfigになります．


- OAI-eNBの起動設定

|  無線機  |  帯域幅  |  BAND  |  Configファイル名  |
| ---- | ---- | ---- | ---- |
|  USRP B210  |  5MHz  |  3  |  enb.band3.tm1.25PRB.usrpb210.conf  |
|  USRP B210  |  10MHz  |  3  |  enb.band3.tm1.50PRB.usrpb210.conf  |
|  USRP B210  |  20MHz  |  3  |  enb.band3.tm1.100PRB.usrpb210.conf  |
|  BladeRF x115  |  5MHz  |  3  |  enb.band3.tm1.25PRB.bladerf.conf  |
|  BladeRF x115  |  10MHz  |  3  |  enb.band3.tm1.50PRB.bladerf.conf  |
|  BladeRF x115  |  20MHz  |  3  |  enb.band3.tm1.100PRB.bladerf.conf  |
|  LimeSDR mini  |  5MHz  |  3  |  enb.band3.tm1.25PRB.limemini.conf  |

- LimeSDR mini用 RF device設定Config

    limesdrmini.ini
