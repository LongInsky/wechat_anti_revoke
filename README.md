# wechat_anti_revoke
patch wechat(for pc) to anti revoke message
微信PC版 反撤回补丁。能够显示群聊、私聊中的撤回信息

[微信pc版官方下载地址](https://pc.weixin.qq.com/)
[思路来源](https://www.v2ex.com/t/525542)


## 微信测试版 2.6.7.32
材料：
WeChatWin.dll 版本:2.6.7.32 大小:21,509,792字节 sha1:A02519C1007EE6723947C262C720D63C619F633E

步骤：
十六进制编辑器（ winhex、010editor 等）修改 00251F26 75->74

产出：
WeChatWin.dll 版本:2.6.7.32 大小:21,509,792字节 sha1:F3007471CA8734C29783C25F0BB49949A783A44


## 微信 2.6.6.28
材料：
WeChatWin.dll 版本:2.6.6.28 大小:20,273,824字节 sha1:0B19CB17A62C3EA0EFCE0FB675A1D3B17845CBA3

步骤：
十六进制编辑器（ winhex、010editor 等）修改 0024A58E 75->74

产出：
WeChatWin.dll 版本:2.6.6.28 大小:20,273,824字节 sha1:260948656725446B818EA668273CEFF02DDFB44D