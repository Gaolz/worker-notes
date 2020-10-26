1. User 修改
  User.find_by_email('joseen@client.com.au').update_attribute(:email,'a@a.com')
User.find_by_email('a@a.com').update_attribute(:password,'123123123')

2. 测试地址
  http://solarbrain.client.com.au/

3. 错误：(soapenv:Server.userException) You have entered an invalid email address or password 
  修正：在侧边栏 "Settings" -> "Netsuite Accounts" 中删除已有用户并新建下面的用户
    user: mao@client.com.au 
    pass: Overtrue2020!!!