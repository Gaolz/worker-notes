### 2020-10-26
1. User 修改
  User.find_by_email('joseen@client.com.au').update_attribute(:email,'a@a.com')
User.find_by_email('a@a.com').update_attribute(:password,'123123123')

2. 测试地址
  http://solarbrain.client.com.au/

3. 错误：(soapenv:Server.userException) You have entered an invalid email address or password 
  修正：在侧边栏 "Settings" -> "Netsuite Accounts" 中删除已有用户并新建下面的用户
    user: mao@client.com.au 
    pass: Overtrue2020!!!

### 2020-10-27

1. 做 commit 时， commit 以需求编号作为前缀，如： `GDAND-772`

### 2020-11-04

1. 测试数据库地址：mysql2://greendealqa:z4cEDD13GdDpLqGRPEtP@greendeal-test-db-instance.c6wqcb8wmf0v.ap-southeast-2.rds.amazonaws.com:3306/ebiz_test?pool=64

### 2020-11-12
#### 下面主要是针对 staging 服务器上面的操作

1. 登陆到测试服务器：`sshtest`

2. 进入到 `ebiz` 项目的步骤
  a. `cd osw_staging_docker`; `ebiz_web_sh`

3. `staging` 分支编译完之后，更新代码
  `cd osw_staging_docker`; `make update`

4. 重新启动 ebiz 项目下面的所有服务
  `cd osw_staging_docker`; `make restart-all `