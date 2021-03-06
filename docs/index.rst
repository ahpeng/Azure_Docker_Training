.. _rst_vsalm-hoc

容器化DevOps数据中心
===========================

.. |stub-icon| unicode:: U+1F527

.. attention::
    
    文档内容将与Docker v1.12.1保持同步，请确保你所使用的Docker版本与本文档的适用范围一致，再参照本文档进行Docker的安装和配置，以防出现联系过程中系统不对称导致的问题。
    
    
    本文档提供2个主要版本:
    
    - stable: 稳定版本
    - latest: 最新版本，持续更新。
    

概述
-----

现代软件开发和计算机技术的快速发展造成了大量异构系统的出现，这给应用开发，测试和部署都带来了巨大的复杂度，如何有效的管理这种复杂度同时保持开发和运维的效率是急待解决的问题。容器化技术在主机时代已经被证明是非常有效的应用隔离技术，可以帮助企业有效的利用计算资源，同时提供很好的敏捷特性。随着Linux在企业级系统中应用的增多，虚拟化的广泛使用和云计算的兴起，Docker这种围绕容器技术构建的工具/生态系统被广泛接受，成为解决异构系统上应用开发和运维问题的最佳选择，同时也为企业构建混合云数据中心提供了更好的选择和可能性。

Docker所代表的容器化分布式数据中心运维方案同时也带来了一些新的问题，比如应用编排，集群管理，作业控制，资源监控等。当前的解决方案主要有Apache Mesos, Kubernetes和Swarm;其中Swarms是Docker官方集群编排解决方案，并内置于Docker 1.12版本中。

世纪互联运营的 Microsoft Azure 是在中国大陆独立运营的公有云平台，采用微软服务于全球的 Azure 技术，为客户提供全球一致的服务质量保障。一直以来微软与Docker都保持了紧密的合作关系，并在Azure中内置了很多针对企业级DevOps数据中心的解决方案，如：虚拟网络，对象存储以及专门针对docker优化的容器服务。

DevOps可以帮助企业提升研发和运维效率，围绕用户价值改进研发流程。本培训将借助VSTS/TFS所提供的源码，项目管理能力和自动化能力，配合Azure和Docker Swarm的自动化运维能力，向您展示如何在云端构建一套全部容器化的DevOps工具链。

:更新日期: |today|
:作者: **Lean-soft** 
:主页: `DevOps Hub <http://devopshub.cn>`_


内容
-----

.. toctree::
    :titlesonly:
    
    Hands-On Lab/index 
    

常见问题
---------
.. toctree::
    :titlesonly:
    
    trouble-shooting/index


