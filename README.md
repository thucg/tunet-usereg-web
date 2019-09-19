# tunet-usereg-web
仅包含准入代认证功能。修复了 usereg.tsinghua.edu.cn 准入代认证的若干 Bug

## 使用说明

浏览器打开 [https://thucg.github.io/tunet-usereg-web/](https://thucg.github.io/tunet-usereg-web/) 使用，该页面由 GitHub Pages 托管

你的**登录凭据直接从你本机发送到** auth4.tsinghua.edu.cn 的准入认证接口，我们不会收到你输入的凭据

无法在校外使用准入代认证，因为校外无法从本机访问 auth4.tsinghua.edu.cn

## 修复了官方准入代认证的哪些 Bug

 - [x] 登录失败后，再次登录会报错用户名不存在
 - [x] 登录失败时，错误提示信息不全
 - [x] 如果用 HTTPS 访问 usereg.tsinghua.edu.cn，准入代认证会访问错误的端口
 - [x] CSS 引用了不存在的图片
