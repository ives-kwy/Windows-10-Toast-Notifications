## 创建环境

会自动安装 `setuptools` 和 `wheel` 。
```
conda create -n toast python=3.6.7 pip=9.0.3
```

## 生成 wheel
```
python setup.py bdist_wheel
```

创建环境后，执行打包命令就能在 dist 中得到新的 whl。
