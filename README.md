# Camera-timer
基于C++的opencv制作的定时相机，可用于希沃白板上给同学拍大头照的🤣👌
### 配置文件
```bash
config.json
{
      "c": 0,            //摄像头选择
      "w": 1280,         //摄像头宽度
      "h": 720,          //摄像头高度
      "wait_s": 10,      //每次拍照格外间隔时间
      "imgchoose": 1,    //拍照时间模式选择.
                         //0为wait_s秒拍一次,
                         //1为使用imgtimelist区间拍摄
      "imgtimelist": [   //拍照时间区域.格式:日期时分/时分/分.格式需要对应
     [ 2051502, 2051530],//开始2月05号15时02分——结束2月05号15时30分
     [ 440, 520 ]        //开始4时40分——结束5时20分
       ]
} 
```
## Contributors

[![Contributors](https://contributors-img.web.app/image?repo=Xpercent-YX/Xpercent-YX)](https://github.com/Xpercen/Camera-timer/graphs/contributors)
