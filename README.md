# Android-LogUtil
***
为了方便在项目中调试，自定义一个日志工具，可以在开发阶段正常打印日志，项目上线后不删代码即可实现停止打印日志

***
### 方法
> LogUtil.v ("TAG", "verbose");
>
> LogUtil.d ("TAG", "debug");
>
> LogUtil.i ("TAG", "info");
>
> LogUtil.w ("TAG", "warn");
>
> LogUtil.e ("TAG", "error");

### 控制日志打印行为
    修改静态变量level的值，就可以自由控制日志的打印行为。
  
  
 >  ``` public static final int level = VERBOSE; ```
 > 
 >    打印所有日志
  
 >  ``` public static final int level = DEBUG; ```
 > 
 >    打印DEBUG以上级别的日志
  
 >  ``` public static final int level = NOTHING; ```
 > 
 >    停止打印所有日志
