---
layout: post
author: fabiand
description: This is a weekly update from the KubeVirt team - including the holiday backlog update.
navbar_active: Blogs
pub-date: January 19
pub-year: 2018
category: updates
comments: true
---

This is a weekly update from the KubeVirt team - including the holiday
backlog update.

We are currently driven by

-   Being easier to be used on Kubernetes and OpenShift

-   Rework out architecture

-   Getting dependencies into shape (storage)

-   Improve the user-experience for users (UI, deployment)

<!-- more -->
Within the last weeks we achieved to:

-   Drop of HAProxy and redeisng of console access (@davidvossel)
    (<https://github.com/kubevirt/kubevirt/pull/618>)

-   Dockerized builds to make sure the build env matches the runtime env
    (@rmohr and others)
    (<https://github.com/kubevirt/kubevirt/pull/647>)

-   OwnerReference fixes (@alukiano)
    (<https://github.com/kubevirt/kubevirt/pull/642>)

-   OfflineVirtualMachineDesign documentation (@petrkotas)
    (<https://github.com/kubevirt/kubevirt/pull/641>)

-   Further RBAC improvements (@gbenhaim)
    (<https://github.com/kubevirt/kubevirt/pull/640>)

-   **User-Guide**

    -   The guide saw many updates also for planned stuff

    -   Update to reflect v0.2.0 changes (@rmohr)
        (<https://github.com/kubevirt/user-guide/pull/12>)

    -   NodeSelector and affinity (@rmohr)
        (<https://github.com/kubevirt/user-guide/pull/15>)

    -   Hardware configuration (@rmohr)
        (<https://github.com/kubevirt/user-guide/pull/14>)

    -   Volumes and disks (@rmohr)
        (<https://github.com/kubevirt/user-guide/pull/13>)

    -   Cloud-Init (@davidvossel)
        (<https://github.com/kubevirt/user-guide/pull/10>)

-   **API Reference**

    -   Now updated regularly (@lukas-bednar)
        (<https://github.com/kubevirt/kubevirt/pull/643>)
        <https://kubevirt-incubator.github.io/api-reference/content/index.html>

-   **Demo**

    -   Got updated to v0.2.0 (@fabiand)

    -   But an issue with virtctl was introduced

    -   <https://github.com/kubevirt/demo>

-   **UI**

    -   The WIP KubeVirt provider for ManageIQ was showcased
        (@masayag @pkliczewski)

    -   <https://github.com/ManageIQ/manageiq-providers-kubevirt/>

    -   <https://www.youtube.com/watch?v=9Gf2Nv7h558>

![miq 2018
01](https://gist.githubusercontent.com/fabiand/417615d509badb8bff7d6f6a0d736df6/raw/e63ef729acd78c92940699004b2bdb54cf9874e1/miq-2018-01.png)

-   **UI**

    -   The Cockpit plugin makes some progress (@mlibra):

![02](https://gist.githubusercontent.com/fabiand/417615d509badb8bff7d6f6a0d736df6/raw/16796e942793fbab48398c78c600ea7eabd7413a/02.png)

-   **Ansible**

    -   Move to stable kubevirt release manifests (@gbenhaim)
        (<https://github.com/kubevirt-incubator/kubevirt-ansible/pull/37>)

    -   Many improvements to make it work seamlessly
        (@gbenhaim @lukas-bednar)

In addition to this, we are also working on:

-   Decentralize the architecture (@davidvossel)
    (<https://github.com/kubevirt/kubevirt/pull/663>)

-   Implement VirtualMachinePresets (@stu-gott)
    (<https://github.com/kubevirt/kubevirt/pull/652>)

-   virtctl fixes (@davidvossel and @awels)
    (<https://github.com/kubevirt/kubevirt/pull/648>)

-   Move to q35 machine type (@mpolednik)
    (<https://github.com/kubevirt/kubevirt/pull/650>)

-   Allow deploying OpenShift in vagrant (@alukiano)
    (<https://github.com/kubevirt/kubevirt/pull/631>)

-   **User-Guide**:

-   Offline Virtual Machine docs (@petrkotas)
    (<https://github.com/kubevirt/user-guide/pull/9>)

-   Persistent Virtual Machines (@stu-gott)
    (<https://github.com/kubevirt/user-guide/pull/11>)

Take a look at the pulse, to get an overview over all changes of this
week: <https://github.com/kubevirt/kubevirt/pulse>

Finally you can view our open issues at
<https://github.com/kubevirt/kubevirt/issues>

And keep track of events at our calendar
[18pc0jur01k8f2cccvn5j04j1g@group.calendar.google.com](https://calendar.google.com/embed?src=<link xl:href=)"&gt;https://calendar.google.com/embed?src=<18pc0jur01k8f2cccvn5j04j1g@group.calendar.google.com>&lt;/link&gt;

If you need some help or want to chat you can find us on
<irc://irc.freenode.net/#kubevirt>
