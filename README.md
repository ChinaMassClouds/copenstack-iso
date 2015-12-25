# copenstack-iso
乾云云管平台开源版cOpenstack是基于openstack(juno)的开源IaaS云计算管理平台。cOpenstack包括一个基于web的简单易用的部署平台和功能增强的openstack组件。

<b>源码说明</b>

部署master节点的源码
</br>https://github.com/ChinaMassClouds/copenstack-server </br>
部署client节点的源码
</br>https://github.com/ChinaMassClouds/copenstack-client
</br>涉及修改的组件源码，位于mcos-juno分支中
</br>https://github.com/ChinaMassClouds/nova
</br>https://github.com/ChinaMassClouds/horizon
</br>https://github.com/ChinaMassClouds/ceilemeter

<b>使用说明</b>

使用copenstack的iso镜像安装部署服务器，通过web部署平台部署openstack平台。此版本部署平台支持allinone模式，将所有openstack组件安装到一台物理节点，以及多节点模式，支持将controller、database、rabbitmq、neutron、cinder独立部署。

web部署平台默认帐号admin/admin。部署完成后系统默认三个管理员权限帐号sysadmin/admin、auditadmin/admin、appradmin/admin。

部署iso下载地址：http://open.massclouds.com:8086/downloads/MCOS-Openstack-deploy-V1.0.iso

<b>功能说明</b>

1、对openstack的异构接管进行了增强，通过dashboard界面能够方便的配置接管乾云cCenter、VMWare vCenter虚拟化平台，能够直接接管VMWare vCenter平台已有的虚机；

2、实现了灵活的多用户角色，具备系统管理员、审批管理员、审计管理员、普通用户，可在此基础上扩展用户权限；

3、使用ceilemeter组件对虚拟化平台进行监控，能够实时展现物理机、虚机的CPU、网络、磁盘IO的占用量，通过配置告警策略实现邮件告警；

4、简单的自助服务流程，实现了云资源（云主机、云硬盘）的申请、审批流程；

问题反馈：zhao_jda@massclouds.com
