### 创建验证码
```
  VeriCode::create()
```

### 获取
```
session_start();
$sess_code = $_SESSION['code'];
```

### composer 阿里云镜像
-- 所有项目都会使用该镜像地址：
```
composer config -g repo.packagist composer https://mirrors.aliyun.com/composer/
```
-- 取消配置：
```
composer config -g --unset repos.packagist
```
