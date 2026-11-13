# ai-studio-fonts（私有）

AI Studio 成片字幕与行迹地图用的字体，仅供本人在自己的机器之间同步，请勿公开或转发。

- `Libian.ttc`：隶变（Libian SC，index 0）——诗名、诗句、片尾整首诗、地图标题
- `Songti.ttc`：宋体（index 1 = Songti SC Bold，index 4 = STSong Regular）——片头第二行等

字体版权归常州华文（SinoType），随 macOS 授权，不得再分发。

## Linux 安装

```bash
mkdir -p ~/.local/share/fonts
tar -xzf ai-studio-fonts.tar.gz -C ~/.local/share/fonts
mv ~/.local/share/fonts/ai-studio-fonts ~/.local/share/fonts/ai-studio
cd ~/.local/share/fonts/ai-studio && sha256sum -c SHA256SUMS
```
