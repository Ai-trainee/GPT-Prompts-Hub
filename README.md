[![🌟 GPT Prompts Hub 🌟](https://your-logo-url-here.png)](https://github.com/your-repository-link-here)

*

*[成为我们的赞助商，您的徽标将出现在这里和prompts.chat！](https://github.com/sponsors/your-username-here/sponsorships?sponsor=your-username-here&tier_id=your-tier-id-here)
**

---

欢迎来到 "GPT Prompts Hub" 存储库！探索并分享高质量的 ChatGPT 提示词。培养创新性内容，提升对话体验，激发创造力。我们极力鼓励贡献独特的提示词。

在 "GPT Prompts Hub" 项目中，我们的核心关注点是优化每一轮对话的提示词，尤其是高阶提示词和思维链的开发。我们的目标是远离传统的角色扮演模式，转而专注于深化对话质量和探索更复杂的对话结构。

此外，我们还致力于构建程序化的 GPT 提示词，使其更适合高级应用和自动化程序构建。这种独特的定位使我们的项目成为那些对于高级
GPT 应用和复杂对话结构感兴趣的用户和开发者的理想选择。

**[在GitHub上查看](https://github.com/your-repository-link-here)**

---

### 使用 AI 创建您自己的提示

我基于[提示工程指南](https://platform.openai.com/docs/guides/prompt-engineering)
为大模型撰写了以下提示词段落。通过直接将这段提示词输入大模型，您就能生成自己的提示词。请注意，对于gpt4模型，这种输入方法效果较好，而其他模型可能无法产生您期望的理想效果。：
> 让我们一起改进创建高质量提示的过程。按照[提示工程指南](https://platform.openai.com/docs/guides/prompt-engineering)
> 中概述的策略，我寻求您的帮助，以制作提示，确保准确和相关的响应。我们可以这样做:
>
> 1. **输入请求**:请问我想转换为优化提示符的具体自然语言语句是什么?
> 2. **参考最佳实践**:利用提示工程文档中的指导方针，使您的理解与已建立的最佳实践保持一致。
> 3. **任务分解**:解释将自然语言语句转换为结构化提示所涉及的步骤。
> 4. **深思熟虑的应用**:分享你如何将这六项战略原则应用到所提供的声明中。
> 5. **工具利用率**:指出可能用于增强提示制作的任何其他资源或工具。
> 6. **测试和改进计划**:概述如何测试精心制作的提示，以及可能需要哪些迭代改进。
>
> 考虑到这几点，请提示我为我们的提示优化任务提供自然语言输入。
>
此外，如需深入学习，请查阅官方的[提示工程指南](https://platform.openai.com/docs/guides/prompt-engineering)。

---

### 使用 GPT-API-Free

**GPT-API-Free** 是一个开源项目，提供免费的 ChatGPT API Key，支持 GPT-4 API（免费）。ChatGPT 国内可用免费转发 API，直连无需代理。可以搭配
ChatBox 等软件/插件使用，极大降低接口使用成本：

- **付费升级选项：** 如果您需要更多服务，比如语音 TTS（文字转语音）、视觉识别，或是最新的 GPT-4 模型，项目也提供了付费升级选项。

> 该项目的详细信息可在 [GPT-API-Free GitHub](https://github.com/your-username/GPT-API-Free) 上查看。

![GPT-API-Free Screenshot](https://your-screenshot-url-here.png)

---

# A Prompts

## Custom instructions
#### How would you like ChatGPT to respond?
```markdown
1.You are a top programming expert who provides precise answers, avoiding ambiguous responses.

Identify any complex or difficult-to-understand descriptions in the provided text. Rewrite these descriptions to make
them clearer and more accessible. Use analogies to explain concepts or terms that might be unfamiliar to a general
audience. Ensure that the analogies are relatable, easy to understand.

In addition, Please provide at least one relevant suggestion for an in-depth question after answering my question to
help me explore and understand this topic more deeply.

Take a deep breath，Let's work this out in a step by step way to be sure we have the right answer. If there's a perfect
solution, I'll tip $200!
```
<img src="img.png" alt="img" width="250">

## 让gpt回答的更简单

```markdown
1. 在你觉得比较让人难以理解的描述后面，如果有必要的话，加入一段: ”一种容易理解的方式描述，也许可以使用类比?

2. 你能以一种任何人都能理解的简单方式来解释这些概念吗?请避免使用专业术语，给出一个清晰、直接的解释，让没有该领域背景的人也能很容易地理解。
```

## 不要省略代码
```markdown
你的思路和代码框架挺不错的，但是我现在需要你来写完整的代码！不是仅仅给出框架和思路，不是我来根据你的框架来写代码！不要在你提供的代码中故意省略，代码应该遵循编码的最佳实践。至关重要的是，没有遗漏任何重要部分，并且代码已经准备好进行部署，包括客户端代码。
请提供一个完整的代码示例，确保代码结构完备，遵循最佳实践，可以直接进行部署，包括客户端代码
```
# GPTS Prompts