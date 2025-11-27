# intangibleculture
非遗文化管理系统 非遗系统 非遗文化传承系统 计算机毕业设计

所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。


<font style="color:rgb(17, 124, 238);">🎈</font><font style="color:rgb(17, 124, 238);">系统亮点：协同过滤算法、快递物流API、支付宝沙盒支付、webSocket实时通讯、可分享链接、Echarts图形化分析；</font>

# <font style="color:rgb(72, 179, 120);">一.系统开发工具与环境搭建</font>
## <font style="color:rgb(38, 38, 38);">1.系统设计开发工具</font>
<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">后端使用Java编程语言的Spring boot框架</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">项目架构：B/S架构</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">运行环境：win10/win11、jdk17</font>

<font style="color:rgb(38, 38, 38);"></font>



<font style="color:rgb(38, 38, 38);"></font><font style="color:rgb(72, 179, 120);">前端：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：框架Vue.js；UI库：ElementUI；   
</font><font style="color:rgb(38, 38, 38);">开发工具：Visual Studio Code；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">后端:</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Java语言、mybatis plus、Spring boot框架；   
</font><font style="color:rgb(38, 38, 38);">开发工具：IDEA 2024版本；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">数据库：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库：mysql5.7/8.0 </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库工具：Navicat12版本；</font>

---

# <font style="color:rgb(72, 179, 120);">二.系统实现（部分截图）</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237612970-2a56c0c1-d0d6-4bb4-8d08-767d9059ec0f.png)

## 2.1 用户
### 2.1.1 首页
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237621848-dae979d7-742b-4567-a093-9bc9f8871137.png)

### 2.1.2 话题详情
![](https://cdn.nlark.com/yuque/0/2025/jpeg/45326128/1764237635022-61a3c7bc-8803-433a-a531-5c27b4e7a15b.jpeg)

### 2.1.3非遗文化
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237638963-661c53b5-1bc9-46af-a084-834d8a8a23da.png)

### 2.1.4 文化详情
![](https://cdn.nlark.com/yuque/0/2025/jpeg/45326128/1764237655653-301b78f0-73dc-4c30-bcfb-1b54ea53de58.jpeg)

### 2.1.5 文创品
![](https://cdn.nlark.com/yuque/0/2025/jpeg/45326128/1764237664542-0da95664-a8d0-42e1-988c-6f60b8a09285.jpeg)

### 2.1.6文创品详情
![](https://cdn.nlark.com/yuque/0/2025/jpeg/45326128/1764237667514-6c18e23d-6d7b-456f-9225-42d8dde44428.jpeg)

### 2.1.7 购买
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237689066-9e9b9c88-b731-4d71-bf44-d690c6d53efb.png)

### 2.1.8 我的订单
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237693762-fd7b27ed-1728-42f2-a3e5-0f7eda00df06.png)

### 2.1.9 购物车
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237700633-b81f8666-dc67-4f3b-a302-9488a21eb1b0.png)

### 2.1.10 店铺详情
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237703834-945ddade-2f12-42fd-849e-5b9187e83930.png)

### 2.1.11 传承人
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237707071-7bc3bfe2-8c77-4738-9ff3-409c7b785892.png)

### 2.1.12 传承人详情
![](https://cdn.nlark.com/yuque/0/2025/jpeg/45326128/1764237717970-22731a40-a5e2-428b-bbf7-dceca6409552.jpeg)

### 2.1.13 非遗视频
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237722733-9238a4f3-1600-493d-ba8b-5b1099703692.png)

### 2.1.14 非遗视频详情
![](https://cdn.nlark.com/yuque/0/2025/jpeg/45326128/1764237726386-09da763b-ca3d-4afe-94d9-be6a1bcf1854.jpeg)

![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237730134-eb22daf4-57eb-4651-a3c7-8b28d8522dcb.png)

### 2.1.15交流论坛
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237733310-fbe37309-b113-4101-834a-72391c09ad16.png)

### 2.1.16 系统通知
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237735915-fbdf5ec4-0bd9-403b-ae07-e696873ab0a7.png)

### 2.1.17 聊天
### ![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237738495-49826727-44e2-4809-a01c-9197525a13ad.png)
### 2.1.18 个人中心
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237741296-23e8de65-8dcb-4d0d-8451-a0b27c646893.png)

### 2.1.19 收货地址
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237743746-a3b6b5c8-612e-48f1-bdb1-0ad5ceab9ad7.png)

## 2.2 管理员
### 2.2.1 非遗综合统计
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237746550-9ccaab16-64af-46f1-bf6c-f02dceb04f8d.png)

### 2.2.2 用户管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237749567-aa3d6045-074d-4dd8-ab37-5e304714615f.png)

### 2.2.3  店铺信息
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237752095-c9d433c7-2e30-4eca-9128-2836f2b24e6b.png)

### 2.2.4 文创品分类
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237754352-271328ba-ea71-4ea5-b87f-684cd9e2350c.png)

### 2.2.5 文创品维护
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237757467-91790b36-79ff-4042-995e-e908fe9b6fe6.png)

### 2.2.6 库存记录
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237759809-32815fbc-7e11-43e7-a58d-a64aabe16972.png)

### 2.2.7 商家订单
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237762704-6b08d18b-9976-412e-887e-6bafb35bec16.png)

### 2.2.8 话题
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237765486-cbb9f347-c714-436c-b1f7-05aaa8f36788.png)

### 2.2.9 话题统计
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237767405-750fedd8-66f8-4fa4-ba95-fa54adec4cbd.png)

### 2.2.10 话题综合统计
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237769855-486d0645-8be0-4570-9ef3-9df38c08343d.png)

### 2.2.11 非遗文化类别
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237772081-60a528d2-e494-45f5-9c34-a0f25b0de313.png)

### 2.2.12 非遗文化
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237774669-cd3f5925-9fc9-4d59-bb56-f3a6c1c34831.png)

### 2.2.13 传人
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237776940-6051a7e7-1cbb-46a7-abed-0dacd28c223f.png)

### 2.2.14 视频展览类型
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237779454-c9945ccd-0289-49f6-99a0-30c486b5ba08.png)

### 2.2.15 视频展览
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237781973-92f79409-2681-4dbc-ba9a-c9adc341f8a3.png)

### 2.2.16系统通知
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237784254-38be23e1-ebff-4a71-852a-4fb2b2814719.png)

# <font style="color:rgb(72, 179, 120);">三.系统代码结构截图</font>
## <font style="color:rgb(38, 38, 38);">3.1 前端</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237787201-b2adfa91-b4d7-482f-8a26-dfcd312b40d8.png)

## <font style="color:rgb(38, 38, 38);">3.2 后端</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237789721-0f79d5c8-2033-4000-9f3c-6319e0ca8175.png)

## <font style="color:rgb(38, 38, 38);">3.3 数据库</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1764237791381-ba099b4b-84e3-41b1-95d5-f6950c4b1435.png)

# <font style="color:rgb(72, 179, 120);">四.</font><font style="color:rgb(26, 173, 25);">源码获取</font>
<font style="color:rgb(0, 0, 0);">1.原创系统非商用，非开源，非无偿。</font>

<font style="color:rgb(0, 0, 0);">2.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>

###  
