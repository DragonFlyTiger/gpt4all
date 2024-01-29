<h1 align="center">GPT4All</h1>

<p align="center">开源大语言模型，可以在本地CPU和几乎任何GPU上运行</p>

<p align="center">
<a href="https://gpt4all.io">GPT4All 官方站点和模型库</a>
</p>

<p align="center">
<a href="https://docs.gpt4all.io">GPT4All 文档</a>
</p>

<p align="center">
<a href="https://discord.gg/mGZE39AS3e">在线讨论</a>
</p>

<p align="center">
<a href="https://python.langchain.com/en/latest/modules/models/llms/integrations/gpt4all.html">🦜️🔗 Langchain官方后台</a> 
</p>

<p align="center">
GPT4All 运行在我们的合作伙伴 <a href="https://www.paperspace.com/">Paperspace</a>提供的计算资源上.
</p>

<p align="center">
  <img width="600" height="365" src="https://user-images.githubusercontent.com/13879686/231876409-e3de1934-93bb-4b4b-9013-b491a969ebbc.gif">
</p>
<p align="center">
在M1 MacOS设备上运行(视频未加速!)
</p>

## GPT4All: 开源激动人心的大语言模型的生态系统。

> [!重要]
> GPT4All v2.5.0及更新版本仅支持GGUF格式(.gguf)的模型。以前版本的GPT4All(.bin扩展名)使用的模型将不再使用。

GPT4All是一个生态系统，运行**强大的** **可定制化的**大型语言模型，可在消费级CPU和任何GPU上本地化运行。请注意，您的CPU需要支持[AVX 或 AVX2 指令](https://en.wikipedia.org/wiki/Advanced_Vector_Extensions)。

在 [文档](https://docs.gpt4all.io) 中了解更多.

GPT4All模型是一个3GB - 8GB的文件，您可以下载并插入GPT4All开源软件生态系统。**Nomic AI**支持并维护这个软件生态系统，以加强质量和安全性，同时带领任何个人或企业轻松培训和部署他们自己的激动人心的大语言模型。

### 最新动态 ([问题追踪](https://github.com/orgs/nomic-ai/projects/2))
- **October 19th, 2023**: GGUF Support Launches with Support for:
    - Mistral 7b base model, an updated model gallery on [gpt4all.io](https://gpt4all.io), several new local code models including Rift Coder v1.5
    - [Nomic Vulkan](https://blog.nomic.ai/posts/gpt4all-gpu-inference-with-vulkan) support for Q4_0, Q6 quantizations in GGUF.
    - Offline build support for running old versions of the GPT4All Local LLM Chat Client.
- **September 18th, 2023**: [Nomic Vulkan](https://blog.nomic.ai/posts/gpt4all-gpu-inference-with-vulkan) launches supporting local LLM inference on AMD, Intel, Samsung, Qualcomm and NVIDIA GPUs.
- **August 15th, 2023**: GPT4All API launches allowing inference of local LLMs from docker containers.
- **July 2023**: Stable support for LocalDocs, a GPT4All Plugin that allows you to privately and locally chat with your data.


### Chat Client
Run any GPT4All model natively on your home desktop with the auto-updating desktop chat client. See <a href="https://gpt4all.io">GPT4All Website</a> for a full list of open-source models you can run with this powerful desktop application.

Direct Installer Links:

* [macOS](https://gpt4all.io/installers/gpt4all-installer-darwin.dmg)

* [Windows](https://gpt4all.io/installers/gpt4all-installer-win64.exe)

* [Ubuntu](https://gpt4all.io/installers/gpt4all-installer-linux.run)

Find the most up-to-date information on the [GPT4All Website](https://gpt4all.io/)

### Chat Client building and running

* Follow the visual instructions on the chat client [build_and_run](gpt4all-chat/build_and_run.md) page

### Bindings

* <a href="https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-bindings/python/README.md">:snake: Official Python Bindings</a> [![Downloads](https://static.pepy.tech/badge/gpt4all/week)](https://pepy.tech/project/gpt4all)
* <a href="https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-bindings/typescript">:computer: Official Typescript Bindings</a>
* <a href="https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-bindings/golang">:computer: Official GoLang Bindings</a>
* <a href="https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-bindings/csharp">:computer: Official C# Bindings</a>
* <a href="https://github.com/nomic-ai/gpt4all/tree/main/gpt4all-bindings/java">:computer: Official Java Bindings</a>

### Integrations

* 🗃️ [Weaviate Vector Database](https://github.com/weaviate/weaviate) - [module docs](https://weaviate.io/developers/weaviate/modules/retriever-vectorizer-modules/text2vec-gpt4all)

## Contributing
GPT4All welcomes contributions, involvement, and discussion from the open source community!
Please see CONTRIBUTING.md and follow the issues, bug reports, and PR markdown templates.

Check project discord, with project owners, or through existing issues/PRs to avoid duplicate work.
Please make sure to tag all of the above with relevant project identifiers or your contribution could potentially get lost.
Example tags: `backend`, `bindings`, `python-bindings`, `documentation`, etc.

## Technical Reports

<p align="center">
<a href="https://gpt4all.io/reports/GPT4All_Technical_Report_3.pdf">:green_book: Technical Report 3: GPT4All Snoozy and Groovy </a>
</p>

<p align="center">
<a href="https://static.nomic.ai/gpt4all/2023_GPT4All-J_Technical_Report_2.pdf">:green_book: Technical Report 2: GPT4All-J </a>
</p>

<p align="center">
<a href="https://s3.amazonaws.com/static.nomic.ai/gpt4all/2023_GPT4All_Technical_Report.pdf">:green_book: Technical Report 1: GPT4All</a>
</p>

## Citation

If you utilize this repository, models or data in a downstream project, please consider citing it with:
```
@misc{gpt4all,
  author = {Yuvanesh Anand and Zach Nussbaum and Brandon Duderstadt and Benjamin Schmidt and Andriy Mulyar},
  title = {GPT4All: Training an Assistant-style Chatbot with Large Scale Data Distillation from GPT-3.5-Turbo},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/nomic-ai/gpt4all}},
}
```
