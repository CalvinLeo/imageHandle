## 图片处理相关

### 大图加载
#### CATiledLayer技术
https://www.jianshu.com/p/ee0628629f92

### 图片合成

### 图片压缩

### 图片滤镜

#### 模糊效果

UIVisualEffectView 苹果系统自带的类，可以很好地实现高斯模糊的效果

使用方式：

```
UIBlurEffect *blur = [UIBlurEffect effectWithStyle:UIBlurEffectStyleLight];
UIVisualEffectView *effectview = [[UIVisualEffectView alloc] initWithEffect:blur];
effectview.frame = CGRectMake(0, 0, self.view.frame.size.width, self.img.frame.size.height);
[self.img addSubview:effectview];
```
