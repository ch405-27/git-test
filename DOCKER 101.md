# DOCKER  🐋

> Docker is a computer program that performs operating-system-level virtualization, also known as “containerization”.

Docker is a popular tool to make it easier to build, deploy and run applications using containers. 

Containers allow us to package all the things that our application needs like such as libraries and other dependencies and ship it all as a single package. In this way, our application can be run on any machine and have the same behavior.

## What is a Container? 

![image-20200514034827754](C:\Users\CH405\AppData\Roaming\Typora\typora-user-images\image-20200514034827754.png)



A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

**THIS IS A BASICALLY WHAT A CONTAINER IS**

1. It's a bundle of a dependencies and libraries of an application.
2. This allows the application to be shipped in a single package.
3. This enables the application to behave like a literal ==Container== making applications as an plug and play solutions that can be switched out and inserted in any environment. 

> Docker Containers are based on LXC. 
>
> **Linux Container**  *(LCX)* 
>
> LXC is an operating-system-level virtualization method for running multiple isolated Linux systems on a control host using a single Linux kernel. 
>
> > LXC is a container technology which gives you lightweight Linux containers and Docker is a single application virtualization engine based on containers.  **They may sound similar but are completely different.**
> >
> > LXC behaves as a lightweight VM while Docker containers are restricted to a single application by design.
> >
> > You can log in to your LXC container, treat it like an OS and install your application and services and it will work as expected. You can't do that in a Docker container. The Docker base OS template is pared down to a single app environment and is stripped down to it's bare bone.

 

