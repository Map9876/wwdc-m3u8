# wwdc-m3u8


打开网页 https://www.apple.com/apple-events/
直接长按播放的按钮，可复制出链接
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/m3u8/vod_index-joowRJLcCBPCthnkzxWwyZCUDqDsNaCG.m3u8，里面含所有分辨率的m3u8链接

https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/m3u8/vod_asl_index-TYggQaxUyWuQWGBnCdiYvsAmTguaWJuG.m3u8

https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_540p_2000/prog_index.m3u8

https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_540p_2000/iframe_index.m3u8

https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_600/prog_index.m3u8

https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/audio_main_en_2ch_aac_128/prog_index.m3u8


https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_4500/prog_index.m3u8

https://events-delivery.apple.com/0105cftwpxxsfrpdwklppzjhjocakrsk/m3u8/vod_asl_index-VarXEuYrcgUoooHZBgdsQwETDYdXjqsx.m3u8

上面几个都是不同分辨率视频链接，能获取到如下内容：

```
……

#EXTINF:6.00600,                           #EXT-X-BITRATE:102
sdr_avc_540p_2000_922.m4s                  #EXTINF:6.00600,                           #EXT-X-BITRATE:95                          sdr_avc_540p_2000_923.m4s                  #EXTINF:2.06873,                           #EXT-X-BITRATE:39                          sdr_avc_540p_2000_924.m4s
…………

```


https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/m3u8/vod_index-joowRJLcCBPCthnkzxWwyZCUDqDsNaCG.m3u8
from：https://forums.macrumors.com/threads/wwdc-2025-spoiler-free-video-stream-video-posted.2458423/
↑上面链接可以获取到如下内容：

```
~ $ curl https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/m3u8/vod_index-joowRJLcCBPCthnkzxWwyZCUDqDsNaCG.m3u8 #EXTM3U
#EXT-X-VERSION:6                           #EXT-X-INDEPENDENT-SEGMENTS                                                           #-- subtitles --                           #EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="Deutsch",AUTOSELECT=YES,FORCED=NO,LANGUAGE="de",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/de/de.m3u8"                                #EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="English",AUTOSELECT=YES,FORCED=NO,LANGUAGE="en",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/en/en.m3u8"                                #EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="Español",AUTOSELECT=YES,FORCED=NO,LANGUAGE="es",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/es/es.m3u8"
#EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="Français",AUTOSELECT=YES,FORCED=NO,LANGUAGE="fr",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/fr/fr.m3u8"
#EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="日本語",AUTOSELECT=YES,FORCED=NO,LANGUAGE="ja",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/ja/ja.m3u8"
#EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="한국어",AUTOSELECT=YES,FORCED=NO,LANGUAGE="ko",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/ko/ko.m3u8"
#EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="Português (Brasil)",AUTOSELECT=YES,FORCED=NO,LANGUAGE="pt-br",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/pt-br/pt-br.m3u8"
#EXT-X-MEDIA:TYPE=SUBTITLES,GROUP-ID="subs",NAME="简体中文",AUTOSELECT=YES,FORCED=NO,LANGUAGE="zh",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/cc/zh/zh.m3u8"


#-- audio-stereo-aac-128 main --
#EXT-X-MEDIA:TYPE=AUDIO,LANGUAGE="en",NAME="English",AUTOSELECT=YES,DEFAULT=YES,CHANNELS="2",GROUP-ID="audio-stereo-aac-128",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/audio_main_en_2ch_aac_128/prog_index.m3u8"

#-- audio-atmos-eac3-640 main --
#EXT-X-MEDIA:TYPE=AUDIO,LANGUAGE="en",NAME="English",AUTOSELECT=YES,DEFAULT=YES,CHANNELS="16/JOC",GROUP-ID="audio-atmos-eac3-640",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/audio_main_en_16ch_atmos_640/prog_index.m3u8"

#-- audio-stereo-aac-128 ad --
#EXT-X-MEDIA:TYPE=AUDIO,LANGUAGE="en",NAME="English Audio Descriptions",AUTOSELECT=YES,DEFAULT=YES,CHANNELS="2",GROUP-ID="audio-stereo-aac-128",CHARACTERISTICS="public.accessibility.describes-video",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/audio_ad_en_2ch_aac_128/prog_index.m3u8"

#-- audio-atmos-eac3-640 ad --
#EXT-X-MEDIA:TYPE=AUDIO,LANGUAGE="en",NAME="English Audio Descriptions",AUTOSELECT=YES,DEFAULT=YES,CHANNELS="16/JOC",GROUP-ID="audio-atmos-eac3-640",CHARACTERISTICS="public.accessibility.describes-video",URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/audio_ad_en_16ch_atmos_640/prog_index.m3u8"



#-- sdr avc 540p @ 2000 --
#EXT-X-STREAM-INF:BANDWIDTH=2800087,AVERAGE-BANDWIDTH=1559625,VIDEO-RANGE=SDR,CODECS="avc1.64001f,mp4a.40.2",RESOLUTION=960x540,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_540p_2000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=746238,AVERAGE-BANDWIDTH=260401,VIDEO-RANGE=SDR,CODECS="avc1.64001f",RESOLUTION=960x540,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_540p_2000/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=3309771,AVERAGE-BANDWIDTH=2070087,VIDEO-RANGE=SDR,CODECS="avc1.64001f,ec-3",RESOLUTION=960x540,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_540p_2000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=746238,AVERAGE-BANDWIDTH=260401,VIDEO-RANGE=SDR,CODECS="avc1.64001f",RESOLUTION=960x540,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_540p_2000/iframe_index.m3u8"


#-- sdr avc 360p @ 600 --
#EXT-X-STREAM-INF:BANDWIDTH=930842,AVERAGE-BANDWIDTH=610728,VIDEO-RANGE=SDR,CODECS="avc1.64001e,mp4a.40.2",RESOLUTION=640x360,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_600/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=275523,AVERAGE-BANDWIDTH=106050,VIDEO-RANGE=SDR,CODECS="avc1.64001e",RESOLUTION=640x360,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_600/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=1440526,AVERAGE-BANDWIDTH=1121190,VIDEO-RANGE=SDR,CODECS="avc1.64001e,ec-3",RESOLUTION=640x360,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_600/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=275523,AVERAGE-BANDWIDTH=106050,VIDEO-RANGE=SDR,CODECS="avc1.64001e",RESOLUTION=640x360,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_600/iframe_index.m3u8"


#-- sdr avc 360p @ 1200 --
#EXT-X-STREAM-INF:BANDWIDTH=1736845,AVERAGE-BANDWIDTH=911738,VIDEO-RANGE=SDR,CODECS="avc1.64001e,mp4a.40.2",RESOLUTION=640x360,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_1200/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=342628,AVERAGE-BANDWIDTH=138162,VIDEO-RANGE=SDR,CODECS="avc1.64001e",RESOLUTION=640x360,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_1200/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=2246529,AVERAGE-BANDWIDTH=1422200,VIDEO-RANGE=SDR,CODECS="avc1.64001e,ec-3",RESOLUTION=640x360,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_1200/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=342628,AVERAGE-BANDWIDTH=138162,VIDEO-RANGE=SDR,CODECS="avc1.64001e",RESOLUTION=640x360,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_360p_1200/iframe_index.m3u8"


#-- sdr avc 720p @ 3000 --
#EXT-X-STREAM-INF:BANDWIDTH=4114545,AVERAGE-BANDWIDTH=2330671,VIDEO-RANGE=SDR,CODECS="avc1.64001f,mp4a.40.2",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_3000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1185495,AVERAGE-BANDWIDTH=407533,VIDEO-RANGE=SDR,CODECS="avc1.64001f",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_3000/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=4624229,AVERAGE-BANDWIDTH=2841133,VIDEO-RANGE=SDR,CODECS="avc1.64001f,ec-3",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_3000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1185495,AVERAGE-BANDWIDTH=407533,VIDEO-RANGE=SDR,CODECS="avc1.64001f",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_3000/iframe_index.m3u8"


#-- sdr avc 720p @ 4500 --
#EXT-X-STREAM-INF:BANDWIDTH=6207332,AVERAGE-BANDWIDTH=2727640,VIDEO-RANGE=SDR,CODECS="avc1.64001f,mp4a.40.2",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_4500/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1315505,AVERAGE-BANDWIDTH=441441,VIDEO-RANGE=SDR,CODECS="avc1.64001f",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_4500/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=6717016,AVERAGE-BANDWIDTH=3238102,VIDEO-RANGE=SDR,CODECS="avc1.64001f,ec-3",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_4500/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1315505,AVERAGE-BANDWIDTH=441441,VIDEO-RANGE=SDR,CODECS="avc1.64001f",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_720p_4500/iframe_index.m3u8"


#-- sdr avc 1080p @ 6000 --
#EXT-X-STREAM-INF:BANDWIDTH=7909249,AVERAGE-BANDWIDTH=4646796,VIDEO-RANGE=SDR,CODECS="avc1.640028,mp4a.40.2",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_6000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2491541,AVERAGE-BANDWIDTH=803010,VIDEO-RANGE=SDR,CODECS="avc1.640028",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_6000/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=8418933,AVERAGE-BANDWIDTH=5157258,VIDEO-RANGE=SDR,CODECS="avc1.640028,ec-3",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_6000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2491541,AVERAGE-BANDWIDTH=803010,VIDEO-RANGE=SDR,CODECS="avc1.640028",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_6000/iframe_index.m3u8"


#-- sdr avc 1080p @ 8500 --
#EXT-X-STREAM-INF:BANDWIDTH=11442457,AVERAGE-BANDWIDTH=5531793,VIDEO-RANGE=SDR,CODECS="avc1.640028,mp4a.40.2",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_8500/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2787991,AVERAGE-BANDWIDTH=874589,VIDEO-RANGE=SDR,CODECS="avc1.640028",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_8500/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=11952141,AVERAGE-BANDWIDTH=6042255,VIDEO-RANGE=SDR,CODECS="avc1.640028,ec-3",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_8500/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2787991,AVERAGE-BANDWIDTH=874589,VIDEO-RANGE=SDR,CODECS="avc1.640028",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_avc_1080p_8500/iframe_index.m3u8"


#-- sdr hvc 540p @ 1930 --
#EXT-X-STREAM-INF:BANDWIDTH=2633385,AVERAGE-BANDWIDTH=1017662,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L90.B0,mp4a.40.2",RESOLUTION=960x540,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_540p_1930/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=666376,AVERAGE-BANDWIDTH=177982,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L90.B0",RESOLUTION=960x540,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_540p_1930/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=3143069,AVERAGE-BANDWIDTH=1528124,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L90.B0,ec-3",RESOLUTION=960x540,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_540p_1930/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=666376,AVERAGE-BANDWIDTH=177982,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L90.B0",RESOLUTION=960x540,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_540p_1930/iframe_index.m3u8"


#-- sdr hvc 360p @ 1090 --
#EXT-X-STREAM-INF:BANDWIDTH=1608199,AVERAGE-BANDWIDTH=591684,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L63.B0,mp4a.40.2",RESOLUTION=640x360,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_360p_1090/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=312444,AVERAGE-BANDWIDTH=96820,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L63.B0",RESOLUTION=640x360,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_360p_1090/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=2117883,AVERAGE-BANDWIDTH=1102146,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L63.B0,ec-3",RESOLUTION=640x360,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_360p_1090/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=312444,AVERAGE-BANDWIDTH=96820,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L63.B0",RESOLUTION=640x360,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_360p_1090/iframe_index.m3u8"


#-- sdr hvc 720p @ 2900 --
#EXT-X-STREAM-INF:BANDWIDTH=4146987,AVERAGE-BANDWIDTH=1566995,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L93.B0,mp4a.40.2",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_2900/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1221789,AVERAGE-BANDWIDTH=275324,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L93.B0",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_2900/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=4656671,AVERAGE-BANDWIDTH=2077457,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L93.B0,ec-3",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_2900/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1221789,AVERAGE-BANDWIDTH=275324,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L93.B0",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_2900/iframe_index.m3u8"


#-- sdr hvc 720p @ 4080 --
#EXT-X-STREAM-INF:BANDWIDTH=5321803,AVERAGE-BANDWIDTH=1640883,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L120.B0,mp4a.40.2",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_4080/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1238370,AVERAGE-BANDWIDTH=280868,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L120.B0",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_4080/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=5831487,AVERAGE-BANDWIDTH=2151345,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L120.B0,ec-3",RESOLUTION=1280x720,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_4080/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=1238370,AVERAGE-BANDWIDTH=280868,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L120.B0",RESOLUTION=1280x720,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_720p_4080/iframe_index.m3u8"


#-- sdr hvc 1080p @ 5400 --
#EXT-X-STREAM-INF:BANDWIDTH=7416913,AVERAGE-BANDWIDTH=2934739,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0,mp4a.40.2",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_5400/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2361449,AVERAGE-BANDWIDTH=509715,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_5400/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=7926597,AVERAGE-BANDWIDTH=3445201,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0,ec-3",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_5400/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2361449,AVERAGE-BANDWIDTH=509715,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_5400/iframe_index.m3u8"


#-- sdr hvc 1080p @ 7000 --
#EXT-X-STREAM-INF:BANDWIDTH=9138895,AVERAGE-BANDWIDTH=3113669,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0,mp4a.40.2",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_7000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2659597,AVERAGE-BANDWIDTH=523002,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_7000/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=9648579,AVERAGE-BANDWIDTH=3624131,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0,ec-3",RESOLUTION=1920x1080,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_7000/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=2659597,AVERAGE-BANDWIDTH=523002,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L123.B0",RESOLUTION=1920x1080,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1080p_7000/iframe_index.m3u8"


#-- sdr hvc 1440p @ 8100 --
#EXT-X-STREAM-INF:BANDWIDTH=10629706,AVERAGE-BANDWIDTH=4605810,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L150.B0,mp4a.40.2",RESOLUTION=2560x1440,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1440p_8100/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=3360692,AVERAGE-BANDWIDTH=779131,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L150.B0",RESOLUTION=2560x1440,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1440p_8100/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=11139390,AVERAGE-BANDWIDTH=5116272,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L150.B0,ec-3",RESOLUTION=2560x1440,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1440p_8100/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=3360692,AVERAGE-BANDWIDTH=779131,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L150.B0",RESOLUTION=2560x1440,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_1440p_8100/iframe_index.m3u8"


#-- sdr hvc 2160p @ 11600 --
#EXT-X-STREAM-INF:BANDWIDTH=15723593,AVERAGE-BANDWIDTH=7832289,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0,mp4a.40.2",RESOLUTION=3840x2160,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_11600/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=7430804,AVERAGE-BANDWIDTH=1294902,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0",RESOLUTION=3840x2160,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_11600/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=16233277,AVERAGE-BANDWIDTH=8342751,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0,ec-3",RESOLUTION=3840x2160,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_11600/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=7430804,AVERAGE-BANDWIDTH=1294902,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0",RESOLUTION=3840x2160,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_11600/iframe_index.m3u8"


#-- sdr hvc 2160p @ 16800 --
#EXT-X-STREAM-INF:BANDWIDTH=21365026,AVERAGE-BANDWIDTH=9710987,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0,mp4a.40.2",RESOLUTION=3840x2160,FRAME-RATE=29.970,AUDIO="audio-stereo-aac-128",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_16800/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=7430844,AVERAGE-BANDWIDTH=1453374,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0",RESOLUTION=3840x2160,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_16800/iframe_index.m3u8"

#EXT-X-STREAM-INF:BANDWIDTH=21874710,AVERAGE-BANDWIDTH=10221449,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0,ec-3",RESOLUTION=3840x2160,FRAME-RATE=29.970,AUDIO="audio-atmos-eac3-640",SUBTITLES="subs"
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_16800/prog_index.m3u8
#EXT-X-I-FRAME-STREAM-INF:BANDWIDTH=7430844,AVERAGE-BANDWIDTH=1453374,VIDEO-RANGE=SDR,CODECS="hvc1.2.20000000.L153.B0",RESOLUTION=3840x2160,URI="https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_16800/iframe_index.m3u8"

~ $
```


2025年最大：
https://events-delivery.apple.com/0705ssefukzgmvtafvdghmccmofevkcb/vod_main_tbRmxUmgfZUDgixPtvpuvDHQcDAUqvUq/sdr_hvc_2160p_16800/prog_index.m3u8

2024年：
https://events-delivery.apple.com/1505clvgxdwlbjrjhxtjdgcdxaiabvuf/m3u8/vod_index-LHDoZDhTrsKLsbrZKqYpbWraixsWQHkw.m3u8
来自：https://forums.macrumors.com/threads/wwdc-2024-spoiler-free-video-stream-video-posted.2428607/

其他：
https://github.com/dmthomas/AppleVideoDownloadScripts/blob/main/WWDC25/2160p/WWDC25-Keynote-2160p.sh
