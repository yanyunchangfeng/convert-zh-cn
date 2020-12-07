## 介绍 convert-zh-ch 通用工具类
-----------------------------

       convert-zh-ch 是一个通用的工具类 用来把汉字简体转换成拼音或者五笔的简码 全面支持ts和js 

## 安装

        npm i convert-zh-cn --save 
        yarn add convert-zh-cn 

## 使用

、、、 import {makeWb,pinyin} from 'convert-zh-cn';

           /**   
            * [ makeWb 汉字简体转五笔简码]    
            * 
            * @param {str} [接收一个字符串]  
            * @return {makeResult:string} [返回一个五笔简码字符]  
            */
                    makeWb('徐') // T  把汉字转换成五笔简码 [字母全为大写 如需转换可自行处理]  
            /**  
            * [ pinyin 汉字简体转拼音简码]   
            * 
            * @param {str} [接收一个字符串]  
            * @return {result:string} [返回一个五笔简码字符]   
            */

            // pinyin.getCamelChars('徐') //X 把汉字转换成拼音简码     
            // pinyin.getFullChars('徐)  //XU 把汉字转换成拼音全拼  [拼音首字母为大写 如需转换可自行处理]

、、、

## 版本提升 1.0.4
   1. 修复了一些bug 如在输入非汉字简体等其他符号转五笔时报错的情况     
   2. 自动处理了输入内容前后以及中间空格的问题     
   3. 统一处理汉字转拼音全大写转换
   4. 完善了ts类型文件和文档说明  


## 开源许可证
     MIT
