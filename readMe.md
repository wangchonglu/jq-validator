
**seajs模块：jquery表单验证插件**

##使用demo如下：

首先引用
require('path／jq-validator')

定义必填、必填提示语
<input type="text" required  required-msg="不能为空呦！！"  validate-msg="如果没有required-msg将会取该提示语，如果都没有，插件将会有默认提示语返回"
  validate-isEmail validate-isEmail-msg="对应提示语，该属性可以没有"
  validate-isPhone validate-isPhone-msg="对应提示语，该属性可以没有"
  validate-isNumber validate-isNumber-msg="对应提示语，该属性可以没有"
  validate-isTel validate-isTel-msg="对应提示语，该属性可以没有"
  validate-reg="正则表达式"  validate-isReg-msg="对应提示语，该属性可以没有"

  validate-maxLength="20"   validate-maxLength-msg="对应提示语，该属性可以没有"
  validate-minLength="5"   validate-minLength-msg="对应提示语，该属性可以没有"

  />


