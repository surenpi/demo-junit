该项目旨在提供一种轻松的方法来体验 Jenkins 流水线。

根据不同的使用场景，我们提供了一些 Jenkinsfile：
sdsdsd
|文件|需求|描述|
|---|---|---|
|[Jenkinsfile-junit-k8s](Jenkinsfile-junit-k8s)|需要有一个带 `maven` 标签的代理节点。这个节点必须是在一个包含 `java` 容器的 pod 中。|生成 junit 报告。|
|[Jenkinsfile-input](Jenkinsfile-input)|任何类型的节点。|需要用户输入，然后流水线才可以继续。|

查看更多 https://jenkins-zh.cn/about/course/#1
