# ComfyUI-RVC
a comfyui custom node for [Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI.git)

## 如何使用
对于Linux，确保 `ffmpeg` 可以在终端工作。

```
apt update
apt install ffmpeg
```
对于Windows,可以用[WingetUI](https://github.com/marticliment/WingetUI)自动安装 `ffmpeg` 

then!
```
git clone https://github.com/CFTL/ComfyUI-RVC.git
cd ComfyUI-RVC
pip install -r requirements.txt
```
`weights` 将自动从 huggingface 下载！请确保您的网络连接到了 huggingface，或者尝试按照 [hf-mirror](https://hf-mirror.com/) 配置您的环境。


## 感谢列表
- [Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI.git)
