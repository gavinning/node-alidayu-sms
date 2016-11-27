Alidayu SMS
---

### Install
```sh
npm i alidayu-sms --save
```

### Usage
```js
const Alidayu = require('alidayu-sms');
const alidayu = new Alidayu(clientOption, smsOption);

alidayu.send({
    name: 'gavinning',
    time: '2016-11-11 11:11:11',
    tel: 13000000000
})
.then(res => console.log(res))
.catch(err => console.error(err))
```

clientOption
```js
{
     'appkey' : 'appkey' ,
     'appsecret' : 'secret' ,
     'REST_URL' : ' http://gw.api.taobao.com/router/rest '
}
```

smsOption
```js
{
     'extend' : '' ,
     'sms_type' : 'normal' ,
     'sms_free_sign_name' : '' ,
     'sms_param' : "" ,
     'rec_num' : '13000000000' ,
     'sms_template_code' : ""
}
```
