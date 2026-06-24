# AI Agent 资讯

自动收集大模型与 Agent 相关的技术文章及论文，按时间整理并部署到 GitHub Pages。

## 内容格式

每篇文章/论文按以下格式记录（Markdown 表格）：

| 研究方向 | 大概讲了什么 | 文章链接 |
|---------|------------|---------|
| 示例方向 | 简要描述文章核心内容 | [标题](链接) |

## 目录结构

```
docs/
  YYYY-MM/
    YYYY-MM-DD.md    # 按日期归档的资讯
```

## 收集来源

### AI 公司技术博客
- OpenAI: https://openai.com/blog/
- Anthropic: https://www.anthropic.com/news
- Google DeepMind: https://deepmind.google/discover/blog/
- Google AI: https://blog.google/technology/ai/
- Meta AI: https://ai.meta.com/blog/
- Microsoft Research: https://www.microsoft.com/en-us/research/blog/
- Hugging Face: https://huggingface.co/blog
- Mistral AI: https://mistral.ai/news/
- Cohere: https://cohere.com/blog
- NVIDIA AI: https://blogs.nvidia.com/blog/category/deep-learning/
- xAI: https://x.ai/blog

### 论文来源
- arXiv (cs.CL / cs.AI / cs.MA): https://arxiv.org/list/cs.CL/recent
- Hugging Face Papers: https://huggingface.co/papers
- Papers with Code: https://paperswithcode.com/

## 自动化

- 每 3 小时自动抓取最新资讯，去重后按日期归档
- 提交并推送到 GitHub 远程仓库
- 通过 GitHub Actions 自动部署到 GitHub Pages

## 部署

站点地址：https://chyuan-cuihongyuan.github.io/agent-info/
