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