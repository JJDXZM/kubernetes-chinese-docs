# 示例: 分部署任务队列 Celery, RabbitMQ和Flower
## 介绍
Celery是基于分布式消息传递的异步任务队列。它可以用来创建一些执行单元（例如，一个任务），这些任务可以同步，异步的在一个或者多个工作节点执行。

Celery基于Python实现。

因为Celery基于消息传递，需要一些叫作消息代理的中间件（他们用来在发送者和接受者之间处理传递的消息）。