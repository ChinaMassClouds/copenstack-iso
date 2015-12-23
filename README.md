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

<b>功能说明</b>

1、乾云cCenter、VMWare vCenter、kvm异构平台接管，直接通过web管理界面配置，简单方便。支持接管VMWare vCenter已有的虚机；

2、系统管理员、审计管理员、审批管理员、普通用户多用户角色；

3、云资源（云主机、云硬盘）申请、审批流程；

4、物理机、虚拟机，CPU、网络、磁盘IO资源使用实时监控；

5、告警策略配置，支持配置邮件告警；
