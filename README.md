# k8s-kubeadm
kubernetes的kubeadm部署配置文件

### 文件说明

- **addons**

> kubernetes的插件，比如calico和dashboard。

- **configs**

> 包含了部署集群过程中用到的各种配置文件。

- **scripts**

> 包含部署集群过程中用到的脚本，如keepalive检查脚本。

- **global-configs.properties**

> 全局配置，包含各种易变的配置内容。

- **init.sh**

> 初始化脚本，配置好global-config之后，会自动生成所有配置文件。