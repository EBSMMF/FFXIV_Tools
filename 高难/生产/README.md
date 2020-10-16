## 基础依赖

[鲶鱼精邮差](https://nga.178.com/read.php?tid=19724323)

**FF14版本5.21/5.25**

## 基本原理

鲶鱼精邮差 提供ACT用宏的方式

## 属性要求

作业随意

加工必须大于2629(个人认为非必要，越高越好)

CP必须为638(头,衣服,手需要打CP，增加宏容错率)

其中食物为血色五海杂烩汤，药水为魔匠药水。

期望搓出来的概率 43.75% (47.4237947%)

## 原理(**非原创**)

起手宏1
```
/ac "闲静" <wait.3>
/ac "俭约加工" <wait.3>
/ac "俭约加工" <wait.3>
/ac "专心加工" <wait.3> 
```
当使用起手宏之后会出现2种不同的情况，根据不同的情况选择起手宏2

专心失败，倒掉 50%

专心成功，继续

起手宏2
```
/ac "掌握" <wait.2>
/ac "崇敬" <wait.2>
/ac "高速制作" <wait.3>
/ac "高速制作" <wait.3>
/ac "最终确认" <wait.2>
/ac "高速制作" <wait.3>
/ac "最终确认" <wait.2>
/ac "高速制作" <wait.3>
/ac "秘诀"  <wait.2>
```

当使用起手宏之后会出现4种不同的情况，根据不同的情况选择终止宏

情况A：如果四个高速成功了3-4个
进度宏A：
```
/ac "阔步" <wait.2>
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "掌握" <wait.2>
/ac "阔步" <wait.2>
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "秘诀" <wait.2>
/ac "俭约加工" <wait.3>(如果CP≥156)
/ac "阔步" <wait.2> 
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "阔步" <wait.2>
/ac "比尔格的祝福" <wait.3>
/ac "精密制作" 
/ac "制作"
```

情况B：如果只成功了两个高速
进度宏B
```
/ac "阔步" <wait.2>
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "掌握" <wait.2>
/ac "阔步" <wait.2>
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "秘诀" <wait.2>
/ac "阔步" <wait.2> 
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "阔步" <wait.2>
/ac "比尔格的祝福" <wait.3>
/ac "崇敬" <wait.2>
/ac "精修" 
/ac "俭约" 
/ac "高速制作" <wait.3>
/ac "俭约" 
/ac "高速制作" <wait.3>
/ac "高速制作" <wait.3>
/ac "高速制作" 
```

情况C：如果只成功了一个高速
进度宏C
```
/ac "改革" <wait.2>
/ac "俭约加工" <wait.3>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "掌握" <wait.2>
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "阔步" <wait.2>
/ac "改革" <wait.2>
/ac "观察" <wait.3>
/ac "注视加工" <wait.3>
/ac "阔步" <wait.2>
/ac "比尔格的祝福" <wait.3>
/ac "俭约" <wait.2>
/ac "崇敬" <wait.2>
/ac "高速制作" <wait.3>
/ac "高速制作" <wait.3>
/ac "高速制作" <wait.3>
/ac "高速制作" <wait.3>
```

情况D：当你使用完起手宏2，如果一次都没成功，倒掉

