
# import 非site-package 的lib

sys.path.append('../you-get/src')

# 16进制

hex(123)


# [install local package](https://stackoverflow.com/questions/14159482/pip-install-a-local-git-repository)

安装本地 repo 到本地python site-package
```
pip install ./
```

在 site-package 加一个软连 到本地dist 目录
```
pip install -e .
```

同上
```
python setup.py install develop
```

