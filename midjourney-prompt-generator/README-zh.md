##  Midjourney Prompt Generator
[En](https://github.com/jesselau76/GPT-Prompts/blob/main/midjourney-prompt-generator/README.md) | [中文说明](https://github.com/jesselau76/GPT-Prompts/blob/main/midjourney-prompt-generator/README-zh.md)

Midjourney Prompt Generator是一个为Midjourney的图像生成AI设计的提示生成器。同时，它还可以充当专业摄影师助手，为拍摄任何对象或场景提供关键元素，并推荐合适的知名摄影师。

### 如何使用

从[此链接](https://github.com/jesselau76/GPT-Prompts/blob/main/midjourney-prompt-generator/midjourney-prompt-generator.txt) 拷贝到chatGPT,建议打开一个NEW CHAT

这个[推文](https://twitter.com/jesselaunz/status/1641593211213975552?s=20)有完整演示。

然后可以随时向chatGPT发送以下命令之一，TA将以所需输出进行回应：

#### /rs

-   生成5个随机摄影场景，并将其翻译成中文。

![Screenshot_20230331_132249](https://user-images.githubusercontent.com/40444824/228998059-1ea482b7-bbb2-48ff-9abe-c9fdf880d392.png)

#### /load "[scene]"

-   返回一个带有关键元素的提示，用于拍摄指定场景的照片。
-   关键元素应包括最合适的相机型号。
-   每个关键元素之间应用逗号分隔。

![Screenshot_20230331_132741](https://user-images.githubusercontent.com/40444824/228998103-70d9c647-bdfe-47ed-bd8c-1ffeebe96882.png)

#### /load [number]

-   此命令充当 /load "[/rs结果编号]"。

#### /pg "[scene]"

-   此命令生成一个字符串，其中包含输入内容和最合适的世界著名摄影师的姓名。

![Screenshot_20230331_133900](https://user-images.githubusercontent.com/40444824/228998148-3c9a99f8-5855-4807-9d11-e929d39a1fd2.png)

#### /pg [number]

-   此命令充当 /pg "[/rs结果编号]"。

![Screenshot_20230331_133433](https://user-images.githubusercontent.com/40444824/228998179-c15d32ef-4baa-4e58-980d-7c4ec237d9ef.png)

#### /lookinglike

![Screenshot_20230331_135004](https://user-images.githubusercontent.com/40444824/228998206-a3854415-8ba0-4cf9-ad8e-df8b0ae90ff0.png)

-   此命令生成五个带有“看起来像”著名演员姓名的字符串。

### 免责声明

Midjourney Prompt Generator是一个提供基于其AI模型的创意建议和推荐的工具。AI接受的知识截止日期为2021年9月，可能不包括摄影领域的最新进展或趋势。用户在使用生成的提示时，应将其视为灵感来源，并进行自己的研究，运用自己的判断。

在生成图片时，请始终尊重遵守当地法律法规。Midjourney Prompt Generator的创建者对由该工具生成的任何误用或不当内容概不负责。

### 致谢

本工具中使用的AI模型基于OpenAI开发的GPT-4架构。
