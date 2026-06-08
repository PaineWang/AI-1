

# AI真人短剧制作基础知识（2026版）

# 一、AI创作全流程认知
在实际工作中：

```text
LLM（大语言模型）
负责：
思考、创意、剧本、分镜、提示词

Image Model（图片模型）
负责：
角色图、场景图、道具图、故事板

Video Model（视频模型）
负责：
动态镜头生成

后期软件
负责：
剪辑、配音、字幕、特效
```

---

# 二、大语言模型（LLM）

## 什么是大语言模型

Large Language Model

简称：

```text
LLM
```

作用：

```text
理解文字
分析内容
推理思考
创意生成
剧本创作
分镜设计
提示词生成
知识问答
```

对于短剧行业：

大语言模型最重要的价值是：

```text
帮助人思考
帮助人创作
帮助人找灵感
帮助人写提示词
```

你可以：

```text
上传剧本
上传文档
上传图片
上传分镜

然后让AI分析
```

---

# 三、主流大语言模型
<img width="330" height="330" alt="ChatGPT-Logo svg" src="https://github.com/user-attachments/assets/6c9ffea8-a508-4f8c-bb3a-53919c3e9838" />


## 1.ChatGPT（推荐）

公司：

OpenAI

官网：

[ChatGPT官网](https://chatgpt.com?utm_source=chatgpt.com)

特点：

```text
综合能力最强

创意能力强
剧本能力强
提示词能力强
推理能力强

适合：
短剧
小说
世界观设计
分镜设计
提示词生成
```

推荐指数：

```text
首选这个模型
```

---

<img width="330" height="75" alt="Google_Gemini_logo_2025 svg" src="https://github.com/user-attachments/assets/0e99e30f-24af-44b4-a42b-1e678bb46008" />

## 2.Gemini（推荐）

公司：

[Google Gemini](https://gemini.google.com?utm_source=chatgpt.com)

所属：

[Google](https://www.google.com?utm_source=chatgpt.com)

特点：

```text
超长上下文

文件分析能力强

图片理解能力强

适合：
文档分析
资料整理
长篇内容总结
```

推荐指数：

```text
次选
```

---
<img width="1511" height="850" alt="what-is-claude-ai-3528943545200277l-77872966344016_l" src="https://github.com/user-attachments/assets/1d5c22ad-29b3-4408-96be-d2ca59030dc1" />


## 3.Claude

公司：

[Anthropic](https://www.anthropic.com?utm_source=chatgpt.com)

官网：

[Claude官网](https://claude.ai?utm_source=chatgpt.com)

特点：

```text
长文本能力强

写作能力优秀

代码能力强

适合：
长剧本
小说
策划案
```

推荐指数：

```text
这个有点麻烦，需要美区账号才可以使用
```

---
<img width="120" height="120" alt="Kimi-logo-2025" src="https://github.com/user-attachments/assets/79b09ec8-345f-406a-ae06-83d6d53ab5b3" />


## 4.Kimi

公司：

Moonshot AI

官网：

[Kimi官网](https://kimi.com?utm_source=chatgpt.com)

特点：

```text
中文体验优秀

长文本优秀

联网搜索能力强
```

推荐指数：

```text
比较仔细，写出来的东西很细，像一个认真的中学生
```

---
<img width="330" height="97" alt="Qwen_Logo svg" src="https://github.com/user-attachments/assets/66ffc4d7-4a0f-4de5-ba41-34d3fe5a5636" />

## 5.通义千问（Qwen）

公司：

[阿里云通义千问](https://tongyi.aliyun.com?utm_source=chatgpt.com)

特点：

```text
中文能力强

开源生态强

代码能力不错
```

推荐指数：

```text
还行，简单的中文理解很好
```

---

<img width="250" height="54" alt="DeepSeek_logo svg" src="https://github.com/user-attachments/assets/e212b828-56a9-4622-ba97-9ae621efb5c0" />

## 6.DeepSeek

公司：

DeepSeek

官网：

[DeepSeek官网](https://www.deepseek.com?utm_source=chatgpt.com)

特点：

```text
推理能力强

成本低

开源生态强
```

推荐指数：

```text
分镜能力比较差
```

---
<img width="250" height="250" alt="Doubao_logo" src="https://github.com/user-attachments/assets/d5ae24b3-c774-4fd7-aeec-5a5c27b6f5f6" />

## 7.豆包

公司：

ByteDance

官网：

[豆包官网](https://doubao.com?utm_source=chatgpt.com)

特点：

```text
中文体验好

适合日常办公
```

推荐指数：

```text
小傻瓜
```

---
<img width="400" height="400" alt="d009b3de9c82d158ccbf915912560ed8bc3eb035e49c_url" src="https://github.com/user-attachments/assets/ebffd899-e389-4122-a393-447ac3cba2cc" />

 
## 8.腾讯元宝

公司：

Tencent

官网：

[腾讯元宝](https://yuanbao.tencent.com?utm_source=chatgpt.com)

特点：

```text
整合腾讯生态

适合办公场景
```

推荐指数：

```text
★★★☆☆
```

---

# 四、图片模型（Image Model）

## 图片模型能做什么

### 文生图

Text To Image

```text
输入文字

生成图片
```

例如：

```text
一个站在废墟中的男人

电影级光影

末日风格
```

↓

生成图片

---

### 图生图

Image To Image

```text
上传参考图

重新生成
```

例如：

```text
上传角色图

换服装
换背景
换动作
```

---

### 局部重绘

Inpainting

```text
修改局部区域

不影响整体
```

例如：

```text
修改头发

修改衣服

修改背景
```

---

# 五、图片模型底层原理

简化理解：

```text
文字
 ↓

文字编码

 ↓

向量特征

 ↓

随机噪声

 ↓

不断降噪

 ↓

生成图像
```

扩散模型（Diffusion）

核心过程：

```text
加噪

降噪

重建
```

---

## 图片模型工作流程

```text
Prompt

↓

文本编码

↓

向量特征

↓

随机噪声

↓

几十次降噪

↓

最终图片
```

因此：

```text
提示词越清晰

结果越稳定
```

---

# 六、主流图片模型

<img width="720" height="450" alt="1_qjzbN39hK7o4OMgDtnpXJQ" src="https://github.com/user-attachments/assets/beb4879a-94e4-4eb8-9a8a-8cb43688e1b2" />

## 1.Nano Banana（推荐）

公司：

Google

特点：

```text
目前最强图像编辑之一

参考图能力极强

一致性极强

人物保持能力强
```

推荐指数：

```text
★★★★★
```

([Android Central][1])

---

## 2.Seedream

公司：

ByteDance

官网：

[即梦Dreamina](https://jimeng.jianying.com?utm_source=chatgpt.com)

特点：

```text
中文表现优秀

文字生成能力强

海报能力强

电商能力强

中文字体能力强
```

Seedream 5.0 基本不使用

推荐指数：

```text
基本不使用
```

---
<img width="1080" height="800" alt="chatgpt_PNG15" src="https://github.com/user-attachments/assets/957572be-2a57-4d3b-b09e-62ab4768a342" />

## 3.GPT Image

公司：

OpenAI

官网：

[OpenAI Images](https://platform.openai.com/docs/guides/image-generation?utm_source=chatgpt.com)

正式模型：

```text
GPT-Image
GPT-Image-1
GPT-Image-1.5
```

特点：

```text
理解能力极强

修改能力极强

文字理解极强

创意能力优秀
```

OpenAI 的 GPT Image 系列属于原生多模态图像生成模型，同时支持生成与编辑。([OpenAI平台][3])

推荐指数：

```text
首选生成人物，场景，道具
```

---
<img width="150" height="150" alt="NewProject_3_12363811-5b1a-41df-9200-7e62dcabf820_1080x1080" src="https://github.com/user-attachments/assets/7e4c1335-ad44-4c28-9821-a76da24ed7a0" />


## 4.FLUX

公司：

Black Forest Labs

官网：

[FLUX官网](https://blackforestlabs.ai?utm_source=chatgpt.com)

特点：

```text
真人效果优秀

艺术风格优秀

开源生态强
```

推荐指数：

```text
生成人物
```

---

<img width="250" height="250" alt="Astronaut_Riding_a_Horse_(SD3 5) webp" src="https://github.com/user-attachments/assets/d70ff64f-4a90-4bcb-b552-e57cd419e765" />

## 5.Stable Diffusion

公司：

Stability AI

官网：

[Stable Diffusion](https://stability.ai?utm_source=chatgpt.com)

特点：

```text
完全开源

可本地部署

可训练LoRA
```

推荐指数：

```text
★★★★☆
```

---

<img width="960" height="960" alt="Midjourney_Emblem svg" src="https://github.com/user-attachments/assets/d5ccf104-c8ea-4775-9e3e-502aa76f4bf3" />

## 6.Midjourney 

公司
Midjourney, Inc.

官网
 [https://www.midjourney.com](https://www.midjourney.com) |

特点
 **闭源**云端服务 <br>作品艺术性高，在构图、色彩、光影方面表现突出 <br>**SaaS化云端托管**，用户无需配置硬件即可使用<br>2025年底更新的V7版本已提供**每日免费生成额度**，并取消强制使用门槛，可通过网页版直接登录使用 |

 ---

<img width="330" height="97" alt="Qwen_Logo svg" src="https://github.com/user-attachments/assets/66ffc4d7-4a0f-4de5-ba41-34d3fe5a5636" />

## 6.Qwen-Image

公司：

阿里巴巴

官网：

[通义官网](https://tongyi.aliyun.com?utm_source=chatgpt.com)

特点：

```text
中文优秀

海报优秀

电商优秀
```

推荐指数：

```text
★★★★☆
```

---

# 七、视频模型（Video Model）

## 视频模型是什么

本质：

```text
连续生成很多张图片

再预测下一帧

形成视频
```

---

## 视频模型输入方式

### 文生视频

Text To Video

```text
输入文字

生成视频
```

---

### 图生视频

Image To Video

```text
上传图片

生成视频
```

---

### 视频参考

Video Reference

```text
上传参考视频

学习运动规律
```

---

### 首尾帧

First Frame + Last Frame

```text
上传开始画面

上传结束画面

自动补全中间镜头
```

---

### 多图参考

Multi Image Reference

```text
角色图

场景图

道具图

站位图

故事板
```

一起输入

保证一致性

---


# 八、主流视频模型

<img width="800" height="450" alt="01b5ebc2-982d-45cb-b9f9-859cc04ca700_Frame 3447" src="https://github.com/user-attachments/assets/7735cda5-9d7e-4a91-a4b1-7af18528978d" />


## 1.Seedance（当前推荐）

公司：

ByteDance

特点：

```text
运动稳定

镜头语言优秀

人物一致性强

电影感强
```

版本：

```text
Seedance 2.0
Seedance 2.0 Fast
```

Fast版：

```text
速度更快

成本更低

质量略低
```

Seedance 2.0 支持文本、图片、视频、音频等多模态输入，并支持大量参考素材控制。([arXiv][4])

推荐指数：

```text
★★★★★
```

---

## 2.Veo

公司：

Google

官网：

[Google Veo](https://deepmind.google/technologies/veo/?utm_source=chatgpt.com)

特点：

```text
镜头理解强

物理规律强

电影感极强
```

推荐指数：

```text
★★★★★
```

---

## 3.Sora

公司：

OpenAI

官网：

[Sora](https://sora.com?utm_source=chatgpt.com)

特点：

```text
世界模拟能力强

长镜头能力强

创意能力强
```

推荐指数：

```text
★★★★★
```

---
<img width="1000" height="516" alt="kling-3 0" src="https://github.com/user-attachments/assets/18f26997-7015-4c5b-b3eb-1f8817c88692" />


## 4.Kling（可灵）

公司：

Kuaishou

官网：

[可灵AI](https://klingai.com?utm_source=chatgpt.com)

特点：

```text
国内使用广泛

人物运动优秀

图生视频优秀
```

推荐指数：

```text
★★★★☆
```

---
<img width="720" height="360" alt="0_39W9JOcIFH4caWGy" src="https://github.com/user-attachments/assets/d917d75b-11c5-45d7-868f-9382d9324037" />


## 5.Runway Gen

公司：

Runway

官网：

[Runway](https://runwayml.com?utm_source=chatgpt.com)

特点：

```text
导演工具丰富

影视制作成熟

专业团队常用
```

推荐指数：

```text
★★★★☆
```

---

## 6.开源视频模型
<img width="767" height="101" alt="截屏2026-06-08 14 43 18" src="https://github.com/user-attachments/assets/f755e36e-304e-4aca-bb26-140b846f81d9" />


### 腾讯混元 Video

公司：

Tencent

官网：

[腾讯混元](https://hunyuan.tencent.com?utm_source=chatgpt.com)

特点：

```text
开源

可私有部署
```

---
<img width="550" height="320" alt="bA3XT1x4_1GkHd776287kw2H963hm4h6" src="https://github.com/user-attachments/assets/82eac6f2-52f9-4d4c-a84d-a3cfe33b2c70" />

### Wan（万相）

公司：

Alibaba

官网：

[Wan AI](https://wan.video?utm_source=chatgpt.com)

特点：

```text
开源

国内生态活跃
```

---
<img width="1156" height="760" alt="LTX-2 3-Cover" src="https://github.com/user-attachments/assets/4f23bac6-1683-4879-918f-f714966f96d9" />


### LTX Video

公司：

Lightricks

官网：

[LTX Studio](https://ltx.studio?utm_source=chatgpt.com)

特点：

```text
速度快

硬件要求低
```

---

# 九、AI短剧团队推荐工具组合

## 解析剧本

```text
ChatGPT
Gemini
Kimi
Deepseek
```

---

## 提示词

```text
ChatGPT
Gemini
```

---

## 角色图

```text
Nano Banana
GPT Image
z-image-trubo
```

---

## 场景图

```text
Nano Banana
GPT Image
FLUX
MJ
```

---

## 分镜图

```text
GPT Image
Nano Banana
```

---

## 视频生成

```text
Seedance 2.0
Kling
```

---

# 十、短剧公司新人必须记住的核心认知

```text
AI不会替代导演

AI不会替代编剧

AI不会替代审美

AI只会放大人的能力
```

真正决定作品质量的顺序：

```text
审美
↓
创意
↓
镜头设计
↓
提示词
↓
模型
```

模型再强，

如果没有：

```text
导演思维
镜头语言
叙事能力
审美能力
```

依然做不出好短剧。

对于AI真人短剧团队来说：

```text
ChatGPT / Gemini
负责思考

Seedream / GPT Image
负责出图

Seedance / Veo / Sora
负责出视频

人
负责创意与审美
```

这才是目前AI影视制作最接近真实生产流程的认知框架。

