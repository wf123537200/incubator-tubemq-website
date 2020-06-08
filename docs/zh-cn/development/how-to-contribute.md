# 如何参与贡献
## 0. 前言

Apache TubeMQ社区欢迎大家为Apache TubeMQ做贡献，您可以通过很多方式为TubeMQ项目成长贡献一份力量：
 - 贡献文档：浏览文档可以加深您对TubeMQ的了解，一旦发现文档写得不清晰或逻辑混乱的地方，可以订正、修改、补充或[联系我们](mailto:dev@tubemq.apache.org)
 - 贡献代码：欢迎大家为TubeMQ社区贡献代码
    - 欢迎您认领Open状态的[Issues](https://issues.apache.org/jira/projects/TUBEMQ/issues)和未完成的特性，提交PR，成为贡献者之一
    - 如果您在使用过程中发现有些功能无法满足您的需求或出现问题，请在Issues中记录
 - 参与邮件讨论：您可以参与dev邮件列表的任何讨论，或者发送任何疑问到dev邮件列表
 - 参与Issue讨论：您可以在任一[Issues](https://issues.apache.org/jira/projects/TUBEMQ/issues)下发表您的建议
 - Review代码：您可以在[GitHub](https://github.com/apache/incubator-tubemq/pulls)上看到所有贡献者提交的PR，您可以Review他们的代码并发表您的建议
> 欢迎大家提交Bug反馈、改进、新功能及PR，具体参与贡献流程可参考该指引。

## 1. 主要链接
- 官网：https://tubemq.apache.org/
- 代码库：https://github.com/apache/incubator-tubemq
- 官网代码库：https://github.com/apache/incubator-tubemq-website
- JRIA任务管理：https://issues.apache.org/jira/projects/TUBEMQ/issues

## 2. 订阅TubeMQ邮件列表
   详见[如何订阅邮件列表](how-to-subscribe.md)

## 3. 注册Jira账号

Apache TUBEMQ使用Apache官方提供的任务管理平台对TubeMQ相关的任务进行管理，JIRA的使用详见[JIRA使用指南](how-to-use-jira.md)

## 4. 提交Bug反馈/特性/改进/文档

> Apache TUBEMQ使用Apache官方提供的任务管理平台对TubeMQ相关的任务进行管理，详见：https://issues.apache.org/jira/projects/TUBEMQ/issues

### 4.1 创建issue
详见[JIRA使用指南](how-to-use-jira.md)
### 4.2 如何提交Bug/特性/改进
在您提交特性/改进前，应该注意以下几点：
  - 请先确认该特性/改进是否被其他人已经提交
  - 一个通俗易懂的标题来阐述你提交的Bug/提交特性/改进
  - 如果是Bug则详细描述该bug产生的原因，如果能够复现，请尽量提供完整的重现步骤
  - 如果是特性，那么该特性应该有广泛的适用性，适用于大部分用户，最好能够提供详尽的设计文档
  - 如果是改进，尽可能描述清楚此改进所带来的益处

具体步骤：
- 创建issue，描述清楚问题
- 如果你要解决该issue则将issue assign到自己名下，如果你仅仅是提交Bug/特性/改进，并没有时间去贡献代码，则assignne设置为空
- 如果是比较大的特性/改进，尽量先输出设计文档，供其他人review
- 编码，编码完成后，提交代码，参考：[代码提交指南](how-to-commit.md)

### 4.3 如何贡献文档
TubeMQ项目的所有文档将在[官网](https://tubemq.apache.org/)展示，所有的文档都保存在官网代码库的[docs](https://github.com/apache/incubator-tubemq-website/tree/master/docs)文件夹下。
贡献的文档包括：
- 编写与TubeMQ相关的文档
- 将中文文档翻译成英文文档
- 将英文文档翻译成中文文档

具体步骤：
- 查看官网，确认你认为需要补充的文档，包含中英文文档
- 创建issue，描述清楚问题, Component请选择：website
- 撰写文档，完成后提交文档，参考：[代码提交指南](how-to-commit.md)

### 5. 如何认领Bug/特性/改进/文档

在TubeMQ的issue列表中，有很多由其他人创建的issue并未被修复，如果你感兴趣的话，可以认领这些issue。认领步骤如下：
  - 在该issue下留言，表达想认领该任务的想法
  - 如果提交者没有意见，则将该issue assign到自己名下并及时更新进度
  - 如果是比较大的特性，尽量先输出设计文档，供其他人review
  - 开发代码并提交代码至github，提交代码流程参考：[代码提交指南](how-to-commit.md)

**如果你是第一次参与TubeMQ项目，可能该issue无法Assign给自己，此时你可以发邮件至：dev@tubemq.apache.org或联系TubeMQ的PPMC申请加入TubeMQ的contributor列表，加入后即可Assign其他issue给自己**

您的任何贡献都可以帮助Apache TubeMQ项目成长，如果您刚接触TubeMQ，您可以先从简单的任务入手，循序渐进，甚至可以逐渐成长为Apache TubeMQ的Committer；