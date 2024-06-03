## docsify

Based on docsify

https://docsify.js.org/#/zh-cn/cover

## Start the service

docsify serve . /docs

https://zeroone001.github.io/robotdemo.github.io/#/

## Repository address

https://github.com/BerserkerRider/robot.github.io

## gittalk

Plugin for displaying the contents of GitHub issues

https://github.com/gitalk/gitalk

### Install

https://github.com/gitalk/gitalk#install

```js
var gitalkConfig = {
    clientID: “a2bdae5457402030fb6b”,
    clientSecret: “c1c9ce6f3334a85f5456b602ca138dee038fd414”,
    repo: “robotdemo.github.io”,
    owner: “zeroone001”,
    admin: [“zeroone001”],
    perPage: 20,


    pagerDirection: “last”, // distractionFreeMode: false
    distractionFreeMode: false, proxy: ''
    proxy: 'http://192.168.31.16:8011'
};
const gitalk = new Gitalk({
    clientID: 'GitHub Application Client ID', clientSecret: 'GitHub Application Client ID', clientSecret: 'GitHub Application Client ID', proxy: '' }; const gitalk = new Gitalk({
    clientSecret: 'GitHub Application Client Secret', repo: '', // The ThemeSecret(GitHub Application)
    repo: 'https://github.com/zeroone001/robotdemo.github.io/tree/master', // The repository of store comments, owner: 'zeroone001', // The repository of store comments.


    id: location.pathname, // Ensure uniqueness and length less than 50
    distractionFreeMode: false // Facebook-like distraction free mode
})

gitalk.render('gitalk-container');
``

## Third party login

https://www.ruanyifeng.com/blog/2019/04/github-oauth.html

## Open source

https://github.com/doocs/doocs.github.io

Translated with DeepL.com (free version)
```
