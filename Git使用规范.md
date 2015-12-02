
> 2015-12-02 补充内容  
> 2015-04-01 创建

# 开发工作流

采用 `git-flow` 进行开发，并进行适当多调整。

git-flow 规范：
<http://danielkummer.github.io/git-flow-cheatsheet/index.zh_CN.html>

# 提交commit log

- 按照完成功能的程度，尽快提交，多提交
- 尽量功能拆解，细分成小块，多提交
- 不要多个功能一起提交
- 日志由三部分组成：动词，功能模块，变更说明
 
例如：修改（动词）：出租车1.6(功能模块)，结束行程后推送抽奖界面URL(变更说明)

# 提交动词

> 增加     ( 新增加的功能 )<br />
> 修复     ( 修复bug )<br />
> 修改     ( 完成的任务，需求变更，任务发生变化 )<br />
> 更新     ( 完成的任务，由于第三方模块变化而做的变化 )<br />
> 改进     ( 功能改进，完善 )<br />
> 完成     ( 完成某项功能 )<br />
> 打包/发布     ( 客户端打包构建结果，并标记版本号 )<br />

如：`修改：出租车1.6，结束行程后推送抽奖界面URL`

# 其他
读一份好的git commit log，就像读一部长篇小说，一部鲜活的历史。  
祝大家都愉快的使用Git

# 参考文献
- git-flow @Vincent Driessen <http://danielkummer.github.io/git-flow-cheatsheet/index.zh_CN.html>
- git - 简明指南 <http://rogerdudler.github.io/git-guide/index.zh.html>


