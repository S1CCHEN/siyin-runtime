# siyin-runtime

司音 SStudio 的训练运行时（RVC 引擎底座）发行包。

内容：内嵌 Python 3.12 + torch(CUDA) + Applio 源码 + 四份推理底座权重
（ContentVec / RMVPE / HiFi-GAN 48k G/D）。

客户端引导页点「安装底座」会自动下载、校验 SHA256 并解压到
`%LOCALAPPDATA%\Siyin Studio\runtime\rvc`。

三个 zip 依次解压到同一目录即为手动部署（路径不重叠，顺序无关）。
