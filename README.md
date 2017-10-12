#### 结构介绍
```
graph LR
A[project] -->B[pom.xml]
A -->C[src]
C -->D[test]
C -->E[main]
D -->F[jmeter]
D -->G[resources]
F -->H[jmx脚本文件]
G -->I[报告模板文件]
I -->J[jmeter.results.shanhe.me.xsl]
I -->K[jmeter-results-detail-report_21.xsl]
```
#### 运行步骤
```
graph TD
A[git remote] -->|远程连接|B(git地址)
B -->|init仓库,fetch文件|c(workpace/project)
c -->|verify pom.xml|d(build)
d -->|html report/send email|e(over)

```