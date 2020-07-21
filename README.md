介绍 convert-zh-ch 通用工具类
-----------------------------

       convert-zh-ch 是一个通用的工具类 用来把汉字转换成拼音或者五笔的简码 全面支持ts和js 

### 安装

        npm i convert-zh-cn --registry http://121.41.18.62:8081/repository/npm-public/ ( 仓库地址为公司私有npm仓库)
        yarn add convert-zh-cn --registry http://121.41.18.62:8081/repository/npm-public/ ( 仓库地址为公司私有npm仓库)

### 使用

、、、 import {makeWb,pinyin} from 'convert-zh-cn';

           /**   
            * [ makeWb 拼音转五笔简码]    
            * 
            * @param {str} [接收一个字符串]  
            * @return {makeResult:string} [返回一个五笔简码字符]  
            */
                    makeWb('徐') // 把汉字转换成五笔简码 T [字母全为大写 如需转换可自行处理]  
            /**  
            * [ pinyin 拼音转五笔简码]   
            * 
            * @param {str} [接收一个字符串]  
            * @return {result:string} [返回一个五笔简码字符]   
            */

            // pinyin.getCamelChars('徐') //把汉字转换成拼音简码 X     
            // pinyin.getFullChars('徐)  //把汉字转换成拼音全拼 Xu (拼音首字母为大写 如需转换可自行处理)  

、、、

开源许可证
----------

MIT
