## 概述
css的盒子模型分为标准盒子模型（box-sizing:content-box）和IE盒子模型（box-sizing:boder-box）两种。
两种盒子模型都包含了margin、border、padding、content四个部分，不同之处在于对盒子宽度（width）和高度（height）设置时的体现。

### 标准盒子模型

![image](https://user-images.githubusercontent.com/13334260/29959195-ca772de0-8f28-11e7-9535-4405e27384ac.png)

**备注**
在标准模型中设置width和height只包含content，不包含padding和border。


### IE盒子模型

![image](https://user-images.githubusercontent.com/13334260/29959207-d62f9f6e-8f28-11e7-8e51-749d2c1b9e81.png)

**备注**
在IE盒子模型中设置width和height包含content、padding和border三个部分。
