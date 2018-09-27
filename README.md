# STM32 PNG DECODER

## 项目说明
- 解码器为 [uPNG](https://github.com/cyang812/upng)
- 测试平台：STM32F469NIH6
- 测试环境：IAR 7.80.4

## 特性
- 支持从文件中或数据 buffer 中读入 PNG 数据.
- 使用 fatfs 从文件中读取 PNG 数据解码, `dec_png()`.
- 从数据流中读取 png 数据解码, `dec_png_buf()`.
- 支持解码到指定 buffer 或者动态分配空间.
- 支持输出竖直翻转后的图片.

## 资源
- 解码 320 \* 240 的 png， 输出 RGB888 的 BMP, 大致需要 400多K ram。
