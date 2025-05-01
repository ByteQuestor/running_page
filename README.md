## 个人使用

```shell
npm install -g --force corepack && corepack enable && pnpm install
python run_page/keep_sync.py $phone $password --with-gpx
pnpm develop --host 0.0.0.0

python run_page/gen_svg.py --from-db --title "TT" --type github --athlete "TT" --special-distance 10 --special-distance2 20 --special-color yellow --special-color2 red --output assets/github.svg --use-localtime --min-distance 0.5

python run_page/gen_svg.py --from-db --title "T3" --type github --athlete "T4" --output assets/grid.svg --min-distance 1.0 --special-color yellow --special-color2 red --special-distance 20 --special-distance2 40 --use-localtime
```
需要修改这里
```shell
进入 GitHub 仓库页面。
点击 Settings 选项卡。
选择 Actions -> General。
在 Workflow permissions 部分，选择 Read and write permissions。
```