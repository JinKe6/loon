#!name=哔哩哔哩
#!desc=净化去广告
#!icon=https://gitlab.com/lodepuly/iconlibrary/-/raw/main/App_icon/120px/Bilibili.png

[Rewrite]
^https?:\/\/(app|api)\.bilibili\.com\/x\/(v2\/splash\/show|vip\/ads\/materials) - reject

[Script]
http-response ^https?:\/\/app\.bilibili\.com\/x\/v2\/splash\/list script-path=https://github.com/JinKe6/quanx/raw/refs/heads/main/scripts/bilibili.js, requires-body=true, timeout=60, tag=bilibili

http-response ^https?:\/\/app\.bilibili\.com\/x\/v2\/feed script-path=https://github.com/JinKe6/quanx/raw/refs/heads/main/scripts/bilibili.js, requires-body=true, timeout=60, tag=bilibili

http-response ^https?:\/\/app\.bilibili\.com\/x\/resource\/show\/tab script-path=https://github.com/JinKe6/quanx/raw/refs/heads/main/scripts/bilibili.js, requires-body=true, timeout=60, tag=bilibili

http-response ^https?:\/\/api\.bilibili\.com\/pgc\/page\/(cinema|bangumi) script-path=https://github.com/JinKe6/quanx/raw/refs/heads/main/scripts/bilibili.js, requires-body=true, timeout=60, tag=bilibili

http-response ^https?:\/\/api\.live\.bilibili\.com\/xlive\/app-interface\/v2\/index script-path=https://github.com/JinKe6/quanx/raw/refs/heads/main/scripts/bilibili.js, requires-body=true, timeout=60, tag=bilibili

http-response ^https?:\/\/app\.bilibili\.com\/x\/v2\/account\/(mine|ipad) script-path=https://github.com/JinKe6/quanx/raw/refs/heads/main/scripts/bilibili.js, requires-body=true, timeout=60, tag=bilibili

[MITM]
hostname = *.bilibili.com
