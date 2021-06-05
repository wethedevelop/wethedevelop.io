# wethedevelop.io

## 简介
[WeTheDevelop.io](https://github.com/wethedevelop/wethedevelop.io)是一块技术试验田，他的目标是尽可能的使用最新最有趣的技术去搭建一个类似于v2ex的开源技术社区。

[WeTheDevelop.io]并不是一个“正经”的项目，如果一个技术栈足够“有趣”，让程序员们乐意去使用，他就会被采用进来。后端的微服务，链路追踪，服务网格，K8S，日志服务；前端的微架构，全新编写的双向绑定，等等。

## 口号

叠最厚的buff，挨最痛的打。

## 架构图

![架构图](struct.png)

项目整体文档: [https://github.com/wethedevelop/wethedevelop.io](https://github.com/wethedevelop/wethedevelop.io)

网关服务: [https://github.com/wethedevelop/gateway](https://github.com/wethedevelop/gateway)

账号微服务: [https://github.com/wethedevelop/account](https://github.com/wethedevelop/account)

proto接口描述文件: [https://github.com/wethedevelop/proto](https://github.com/wethedevelop/proto)

## 采用新技术的一个常见步骤

假设我们要采用jager（猎人）来做链路追踪。

0. 你想采用技术，你决定成为这个技术的owner（负责人）
1. 你要把jager的库整合到这个项目中，在比较经典的场景里插入链路追踪需要的埋点代码。
    1.1 截图链路追踪图，拓扑图，对jager的效果做一个介绍，描述他的好处，放在pull request中提上来。
    1.2 初步审批，合入测试分支，我们在测试环境搭建jager需要的环境，然后重现上述描述的场景，获得效果和数据。
2. 编写更为完整的技术文档，方便后面的人能跟上你的技术栈采用。
3. 测试完毕、文档完善、这个技术栈可以被做下去，社区会同意合入代码。
4. 运维同学部署到生产环境，成为生态的一部分。
5. 永远 希望你能保证这个技术栈能继续使用下去，而不是从此荒废了。如果荒废了的技术，有可能在后面被剔除出去。

## 里程碑

1. 网站上线，具有投稿的能力（还未）

## 现在我们已经采用的技术

#### 微服务

# wethedevelop.io

## Introduction
[WeTheDevelop.io](https://github.com/wethedevelop/wethedevelop.io) is a technology testing field, and its goal is to use the latest and most interesting technologies as much as possible to build an open source technology community similar to V2EX.

[WeTheDevelop.io] is not a "serious" project. If a technology stack is "interesting" enough for programmers to use, it will be adopted. Back end micro service, link tracking, service grid, kubernete, log service; The front-end micro architecture, the newly written two-way binding, and so on.

## Slogan

Stack the thickest buff and get the most painful beating!

## Struct diagram

![架构图](struct.png)

Overall project docs: [https://github.com/wethedevelop/wethedevelop.io](https://github.com/wethedevelop/wethedevelop.io)

Gateway service: [https://github.com/wethedevelop/gateway](https://github.com/wethedevelop/gateway)

Account micro service: [https://github.com/wethedevelop/account](https://github.com/wethedevelop/account)

Proto interface description file: [https://github.com/wethedevelop/proto](https://github.com/wethedevelop/proto)

## Step to adopte new technology

Suppose we use jager for link tracking.

0. You want to adopt the technology, and you decide to become the owner of the technology
1. You need to integrate jager package into this project, and insert the embedded code needed for link tracking in a more classic scenario.
    1.1 Screenshot, link tracking diagram, topology diagram, the effect of jager to do an introduction, describe his benefits, put it in the pull request.
    1.2 After preliminary approval, we join the test branch. We build the environment that jager needs in the test environment, and then reproduce the scene described above to obtain the effect and data.
2. Write more complete technical docs, so that the people behind can keep up with your technology stack.
3. After the testing, the docs is complete, and the technology stack can be built, the community will agree to merge the code.
4. O&M are deployed to the production environment and become a part of the ecology.
5. I always hope you can guarantee that this technology stack will continue to be used instead of being abandoned. If abandoned technology, it may be eliminated later.

## Milepost

1. Website online, with the ability to contribute (not yet)

## Now we have adopted the technology

#### Micro service
