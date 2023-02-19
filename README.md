## yuketangHelper_FOR_IEU

### 雨课堂网课脚本代码

我们雨课堂的网站是：https://plaieu.yuketang.cn/pro/portal/home/  
本项目基于[heyblackC/yuketangHelper](https://github.com/heyblackC/yuketangHelper)，经过修改university-id、university_id，uv_id等参数适配IEU的雨课堂，希望能给大家带来帮助。

## 须知
- 脚本假定使用者具有基本的计算机知识，懂得cookie，会按F12进入开发者模式，且会运行Python代码  
- 两个脚本都是将csrftoken和sessionid更改成自己登录后的cookie中对应的字段后即可运行
![cookies示例](cookie.png)
- 我知道大佬有很多，请别喷我写的代码，然后也希望一起协同完善呀！

## 跨校使用
1. 更改代码中学校的网站地址：https://xxx.yuketang.cn/....(xxx为自己学校的)
2. 根据登录后cookie里的university_id值，更改代码中university-id、university_id、uv_id  





# 非常感谢heyblackC