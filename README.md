# [jjdxm_retrofit-converter-fastjson][project] #

### Copyright notice ###

我在网上写的文章、项目都可以转载，但请注明出处，这是我唯一的要求。当然纯我个人原创的成果被转载了，不注明出处也是没有关系的，但是由我转载或者借鉴了别人的成果的请注明他人的出处，算是对前辈们的一种尊重吧！

虽然我支持写禁止转载的作者，这是他们的成果，他们有这个权利，但我不觉得强行扭转用户习惯会有一个很好的结果。纯属个人的观点，没有特别的意思。可能我是一个版权意识很差的人吧，所以以前用了前辈们的文章、项目有很多都没有注明出处，实在是抱歉！有想起或看到的我都会逐一补回去。

从一开始，就没指望从我写的文章、项目上获得什么回报，一方面是为了自己以后能够快速的回忆起曾经做过的事情，避免重复造轮子做无意义的事，另一方面是为了锻炼下写文档、文字组织的能力和经验。如果在方便自己的同时，对你们也有很大帮助，自然是求之不得的事了。要是有人转载或使用了我的东西觉得有帮助想要打赏给我，多少都行哈，心里却很开心，被人认可总归是件令人愉悦的事情。

站在了前辈们的肩膀上，才能走得更远视野更广。前辈们写的文章、项目给我带来了很多知识和帮助，我没有理由不去努力，没有理由不让自己成长的更好。写出好的东西于人于己都是好的，但是由于本人自身视野和能力水平有限，错误或者不好的望多多指点交流。

项目中如有不同程度的参考借鉴前辈们的文章、项目会在下面注明出处的，纯属为了个人以后开发工作或者文档能力的方便。如有侵犯到您的合法权益，对您造成了困惑，请联系协商解决，望多多谅解哈！若您也有共同的兴趣交流技术上的问题加入交流群QQ： 548545202

## Introduction ##

### 这是一个自定义的常用的工具类库，主要包括了UtilsManager、FileUtils、LogUitls、UIUtils、ListUtils、MD5Utils、RopUtils、RegexUtils、MediaUtils、SPUtils等常用的工具类 ###

## Features ##

### 用于监听当前接收到的短信信息 ###
### 过滤接收到的短信，得到自己想要的内容 ###

## Screenshots ##

## Download ##

[demo apk下载][downapk]

Download or grab via Maven:

	<dependency>
	  <groupId>com.dou361.retrofit2</groupId>
	  <artifactId>jjdxm-retrofit-converter-fastjson</artifactId>
	  <version>x.x.x</version>
	</dependency>

or Gradle:

	compile 'com.dou361.retrofit2:jjdxm-retrofit-converter-fastjson:x.x.x'

历史版本：

    compile 'com.dou361.retrofit2:jjdxm-retrofit-converter-fastjson:1.0.0'

jjdxm-retrofit-converter-fastjson requires at minimum Java 9 or Android 2.3.


[架包的打包引用以及冲突解决][jaraar]

## Proguard ##

类库中使用consumerProguardFiles属性，它指定了编译时，库自动引入的混淆规则。也就是说应用打包时候会自动的寻找库里的混淆文件，不需要手工配置了。


[AndroidStudio代码混淆注意的问题][minify]

## Get Started ##

###step1###

    compile('com.dou361.retrofit2:jjdxm-retrofit-converter-fastjson:1.0.0') {
     //   exclude group: 'com.squareup.retrofit2', module: 'retrofit'
     //   exclude group: 'com.squareup.okhttp3', module: 'okhttp'
     //   exclude group: 'com.alibaba', module: 'fastjson'
    }


## More Actions ##

## ChangeLog ##



## About Author ##

#### 个人网站:[http://www.dou361.com][web] ####
#### GitHub:[jjdxmashl][github] ####
#### QQ:316988670 ####
#### 交流QQ群:548545202 ####


## License ##

    Copyright (C) dou361, The Framework Open Source Project
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
     	http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

## (Frequently Asked Questions)FAQ ##
## Bugs Report and Help ##

If you find any bug when using project, please report [here][issues]. Thanks for helping us building a better one.




[web]:http://www.dou361.com
[github]:https://github.com/jjdxmashl/
[project]:https://github.com/jjdxmashl/jjdxm_retrofit-converter-fastjson/
[issues]:https://github.com/jjdxmashl/jjdxm_retrofit-converter-fastjson/issues/new
[downapk]:https://raw.githubusercontent.com/jjdxmashl/jjdxm_retrofit-converter-fastjson/master/apk/app-debug.apk
[lastaar]:https://raw.githubusercontent.com/jjdxmashl/jjdxm_retrofit-converter-fastjson/master/release/jjdxm-retrofit-converter-fastjson-1.0.0.aar
[lastjar]:https://raw.githubusercontent.com/jjdxmashl/jjdxm_retrofit-converter-fastjson/master/release/jjdxm-retrofit-converter-fastjson-1.0.0.jar
[icon01]:https://raw.githubusercontent.com/jjdxmashl/jjdxm_retrofit-converter-fastjson/master/screenshots/icon01.png
[icon02]:https://raw.githubusercontent.com/jjdxmashl/jjdxm_retrofit-converter-fastjson/master/screenshots/icon02.png
[jaraar]:https://github.com/jjdxmashl/jjdxm_ecodingprocess/blob/master/架包的打包引用以及冲突解决.md
[minify]:https://github.com/jjdxmashl/jjdxm_ecodingprocess/blob/master/AndroidStudio代码混淆注意的问题.md