<p align="center"><a href="https://twitter.com/Aprender_alemao"><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/twitter.png" alt="Twitter" title="Twitter" width="50"/></a><a href="https://www.facebook.com/estudaralemao/"><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/facebook.png" alt="Facebook" title="Facebook" width="50"/></a><a href="https://www.instagram.com/estudaralemao/"><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/instagram.png" alt="Instagram" title="Instagram" width="50"/></a><a href="https://www.youtube.com/c/wwwqueroestudaralemaocombr"><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/youtube.png" alt="YouTube" title="YouTube" width="50"/></a><a href="https://api.whatsapp.com/send?phone=5511989782756&text=I%20want%20to%20know%20..."><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/whatsapp.png" alt="WhatsApp" title="WhatsApp" width="50"/></a><a href="https://www.queroestudaralemao.com.br"><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/website.png" alt="WWW" title="WWW" width="50"/></a><a href="https://br.pinterest.com/chucrutehans/"><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/pinterest.png" alt="Pinterest" title="Pinterest" width="50"/></a><a href="mailto:aulasparticularesdealemaosp@gmail.com?subject=I%20want%20to%20know%20...%20"><img src="https://cdn.jsdelivr.net/gh/dmhendricks/signature-social-icons/icons/round-flat-filled/50px/mail.png" alt="E-Mail" title="E-Mail" width="50"/>
</a>


<p align="center">
<a href=https://github.com/hansalemaos/string2markup><img src="https://img.shields.io/badge/author-hansalemaos-black"/></a>
<a href=https://www.queroestudaralemao.com.br><img src="https://img.shields.io/badge/from-queroestudaralemao.com.br-darkgreen"/></a>
<a href=#><img src="https://img.shields.io/badge/for-Windows-black"/></a>
<a href=https://codeload.github.com/liangjingkanji/DrakeTyporaTheme/zip/refs/heads/master><img src="https://img.shields.io/badge/Theme-Drake-black"/></a>
<a href=https://github.com/dmhendricks/signature-social-icons><img src="https://img.shields.io/badge/Social-Icons-darkgreen"/></a>
</p><br><!--  -->


# string2markup
Made to format strings for kivy/kivymd (MIT)
<br>Just download use 
```
pip install string2markup
```

```
from string2markup import S2M
print(S2M('haddd').b.u.color((255,255,255,255)))
print(S2M('haddd').b.u.color((255,255,255)))
print(S2M('haddd').b.u.color((1,1,1)))
print(S2M('haddd').b.u.color('#ffffff').sub.s.size(12))

output:
[color=#ffffff][u][b]haddd[/b][/u][/color]
[color=#ffffff][u][b]haddd[/b][/u][/color]
[color=#ffffff][u][b]haddd[/b][/u][/color]
[size=12][s][sub][color=#ffffff][u][b]haddd[/b][/u][/color][/sub][/s][/size]
```
