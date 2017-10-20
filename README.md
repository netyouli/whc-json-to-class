# whc-json-to-class

-  The whc-json-to-class is the javascript plug-in that automatically converts the json string to the corresponding language model class

DEMO
==============
[Demo演示](http://47.93.2.130/jsonModel/?type=0)

[我的个人网站](http://47.93.2.130/)

![](https://github.com/netyouli/jsonToClass/blob/master/demo.png)

Require
==============
JavaScript ES6

Support Languages
==============
WHCParserLanguage.Swift

WHCParserLanguage.SwiftClass

WHCParserLanguage.SwiftSexyJson

WHCParserLanguage.SwiftSexyJson

WHCParserLanguage.SwiftSexyJsonClass

WHCParserLanguage.OC

WHCParserLanguage.Java

WHCParserLanguage.CNet

Usage
==============

```JavaScript
    ///  例如json生成swift模型类
    ///  For example, json generates the swift model class
    
    let language = WHCParserLanguage.Swift;
    let json_parser = new WHCJsonParser(language);
    let results = json_parser.startParser(json_str);
    

    /// results 是数组，如果生成语言为OC那么results[0]为头文件内容      results[1]为实现类内容
    /// Results is an array, and if the generated language is OC then results[0] is the header file content results[1] for the implementation of the class content
```
Prompt
==============
The json conversion python and kotlin language models are not currently available and have good Suggestions

Licenses
==============
All source code is licensed under the MIT License.

