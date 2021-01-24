# Google Summer Of Code 2021 for Casbin

Note: the organization application for GSoC 2021 is not started yet. This page only tracks for potential ideas of Casbin for GSoC 2021. We will apply for it but it does NOT mean that Casbin will definitely be selected as a participating organization for GSoC 2021.

Moreover, there are some significant changes like the smaller project size in GSoC 2021, see details at GSoC official site: https://opensource.googleblog.com/2020/10/google-summer-of-code-2021-is-bringing.html

## What is Google Summer Of Code?

Google Summer of Code (GSoC) is a global program held by Google to bring students into open source software development. Students work with an open source organization on a 3 month programming project during their break from school. See more details at: https://summerofcode.withgoogle.com/

## How we select students:

The student will be more likely selected if he/she:

1. Contribute to Casbin related project before.
2. Familiar with the techniques required by the idea he selected.
3. Show the previous code related to the idea on personal website or GitHub.
4. Provide a personal website and descriptions for previous work/projects.
5. Provide demo sites for the previous projects if possible.
6. Provide a resume/CV.

## Get started

1. Choose an idea from our list: https://github.com/casbin/SummerOfCode2021
2. Send your resume/CV in PDF to: admin@casbin.org
3. Do a self-introduction in: https://gitter.im/casbin/gsoc
4. Get familiar with the existing code, try to solve opened issues for your chosen idea's repo before & after application deadline.
5. If you have questions, you can ask the mentor of the idea via GitHub or Gitter.
6. Submit your proposal in [GSoC official site](https://summerofcode.withgoogle.com/). The deadline is TBD.

## Ideas

- [Casbin Core Engine (Golang)](#casbin-core-engine-golang)
- [Casbin for Java](#casbin-for-java)

### Casbin Core Engine (Golang)

#### Description

Extend the Casbin model/policy grammar to support more features in Casbin core engine. This will first be done in Golang Casbin. Possibly applied to other language implementations.

Some issues to work on:

1. support pattern function in 3rd args of g: https://github.com/casbin/casbin/issues/337
2. Resolve policy conflicts: https://github.com/casbin/casbin/issues/338
3. Scaling ABAC Rules: https://github.com/casbin/casbin/issues/354
4. Explain enforcement by informing matched rules: https://github.com/casbin/casbin/issues/355
5. Make GetImplicitPermissionsForUser Deep: https://github.com/casbin/casbin/issues/357

#### Requirements

1. Golang
2. Other languages that Casbin is written with

#### Mentor

[Yang Luo](https://github.com/hsluoyz), Casbin founder

### Casbin for Java

#### Description

In Java world, Apache Shiro and Spring Security are very popular security frameworks. We need to find ways to wrap jCasbin into a middleware of the above both, so Shiro and Spring users can use jCasbin without much migration efforts.

Another work is to develop jCasbin' middleware for most popular Java web frameworks, like how we did it for Golang: https://casbin.org/docs/en/middlewares

Some issues to work on: https://github.com/casbin/jcasbin/issues 

#### Requirements

1. Java
2. Other languages that Casbin is written with

#### Mentor

[Zhengjin Fang](https://github.com/fangzhengjin), Casbin member, [Yang Luo](https://github.com/hsluoyz), Casbin founder
