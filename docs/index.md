---
hide:
  - navigation
---
# bert-vits2和vits对比合成效果展示
#### 以下测试文本均采用标日上册第19课课文，确保测试文本不在训练集内，保证对比的可靠性
#### 其中bert-vits2使用的最新发布版本2.1.0，微调跑了3万步，vits同样跑了3万步

|  角色(训练语料日语10分钟)   | 测试文本  | 合成语音 | bert-vits2-合成语音 |
|  ----  | ----  | ----  | ----  |
| 慧慧（为美好世界献上祝福） | その 品物に 触らないで ください。 请不要碰那个货物！| <audio controls><source src="./audio/huihui_1.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_1.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | あっ,すみません。 啊，对不起。 | <audio controls><source src="/website/audio/huihui_7.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_7.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | 李さん,いっしょに食事に行きませんか?  李小姐，一起去吃饭么？| <audio controls><source src="/website/audio/huihui_8.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_8.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | すみません.今日は早く帰って,レポートをか書かなければなりません. 对不起。今天我得早点回去写报告。| <audio controls><source src="/website/audio/huihui_9.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_9.wav" type="audio/mpeg"></audio> |
| 慧慧（为美好世界献上祝福） | 先生,もう薬を飲まなくてもいいですか?  大夫，可以不吃药了吗?| <audio controls><source src="/website/audio/huihui_10.wav" type="audio/mpeg"></audio> | <audio controls><source src="./audio/bert-vits2_huihui_10.wav" type="audio/mpeg"></audio> |