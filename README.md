# HessianPoc_Generator-0.1.1
woodpecker插件生成hessian利用payload
收集了网上师傅们挖的一些Hessian利用链条，为了利用方便写了一个`woodpecker`插件生成反序列化包，并添加头，可以直接发包使用。

woodpecker框架地址:http://woodpecker.gv7.me/

#### 1、DNS链测试（jdk中任意静态方法调用）

![image-20230918143105137](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/6342afe8-ad11-4717-9722-df951459499f)


![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/3f4b576a-3a34-4e95-b1d2-ede4e809ecd7)


#### 2、写文件链测试

目标路径需要绝对路径

![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/2d334e29-40d3-487f-8f0b-5f2007d22a87)


![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/273f3ae7-9e95-4082-a683-7325f4a67c4f)


#### 3、类加载测试

![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/2623c80c-1365-4a02-9a42-1f4939317940)


![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/e3d704b1-6a68-493e-9e3f-0000040e0e4e)


![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/20877bb8-a8e5-4433-885d-4c56e4c1eb93)


#### 4、fastjson执行系统命令测试

依赖fastjson且仅支持linux系统

![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/a36f457b-a7de-4fc7-85ce-a851d79bbf2c)


![图片](https://github.com/1ucky7/HessianPoc_Generator-0.1.1/assets/145323730/98071ea9-27b5-4a31-bca5-fb4a1cfd4330)


### 参考

https://xz.aliyun.com/t/11961

https://flowerwind.github.io/2023/04/17/%E8%AE%B0%E6%9F%90%E6%AC%A1%E5%AE%9E%E6%88%98hessian%E4%B8%8D%E5%87%BA%E7%BD%91%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E5%88%A9%E7%94%A8-md/

https://blog.wanghw.cn/security/hessian-deserialization-jdk-rce-gadget.html
