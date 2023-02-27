# Common Commands

## nodejs
```shell
yarn config set registry https://registry.npmmirror.com/
pnpm config set registry https://registry.npmmirror.com/
npm config set registry https://registry.npmmirror.com/
```

## scoop
```shell
iwr -useb https://gitee.com/glsnames/scoop-installer/raw/master/bin/install.ps1 | iex
```

## Yunzai - Bot
```shell
-----bot运行必须依赖-----
apt install libatspi2.0-0 libasound2 libcairo2 libpango-1.0-0 libgbm1 fonts-noto
apt install libxrandr2 libxfixes3 libxdamage1 libxcomposite1 libxkbcommon0 libcups2
apt install libatk-bridge2.0-0 libatk1.0-0 libnspr4 libnss3
-----ldd检测出来的但是bot运行缺不需要的，并且apt也search不到-----
libsmime3
libnssutil3
```
