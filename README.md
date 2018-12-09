# Kinesis Data Analytics for Java Application Demo

借助Amazon Kinesis Data Analytics for Java Applications，AWS用户可以使用Java程序来处理和分析流数据，该服务使得用户能够快速创建和运行针对流数据的Java代码，用来做时间序列分析，或者提供实时仪表板、创建实时指标等。

用户可以使用基于Apache Flink（一种用于处理数据流的流行框架和引擎）的开源库在Kinesis Data Analytics中构建Java应用程序。Kinesis Data Analytics服务为Flink应用程序提供底层基础架构，处理核心组件，如配置计算资源、并行计算、自动扩展和应用程序备份（检查点和快照）。用户可以使用Flink高阶编程功能如operator，source和sink，与自己托管的Apache Flink使用方式完全相同。

要开始使用Kinesis Data Analytics for Java Applications，首先需要创建一个Kinesis Data Analytics应用程序，该应用程序可以连续读取和处理流数据，然后，依照用户的习惯选择熟悉的IDE编写Java代码，并使用实时流数据进行测试，最后将代码部署到AWS平台。
