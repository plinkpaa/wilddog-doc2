title: WDGVideoLocalStreamOptions
---

本地视频流配置。

## 属性

### audioOn

**定义**

```objectivec
@property (assign, readwrite, nonatomic) BOOL audioOn;
```

**说明**

本地视频流的音频开关。默认为开。

</br>

---

### videoOption

**定义**

```objectivec
@property (assign, readwrite, nonatomic) WDGVideoConstraints videoOption;
```

**说明**

视频质量选项。默认为 `WDGVideoConstraintsStandard` 。

</br>

---

## 方法

### -init

**定义**

```objectivec
- (nonnull instancetype)init;
```

**说明**

使用默认配置初始化。默认配置为音频开启，视频质量使用 `WDGVideoConstraintsStandard` 选项。

**返回值**

`WDGVideoLocalStreamOptions`实例。

</br>

---

## 常量

### WDGVideoConstraints

**说明**

视频质量选项。

- WDGVideoConstraintsOff: 关闭视频
- WDGVideoConstraintsLow: 视频尺寸 352x288
- WDGVideoConstraintsStandard: 视频尺寸 640x480
- WDGVideoConstraintsHigh: 视频尺寸 1280x720
