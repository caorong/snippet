
# import 非site-package 的lib

sys.path.append('../you-get/src')

# 16进制

hex(123)


# [install local package](https://stackoverflow.com/questions/14159482/pip-install-a-local-git-repository)

```
pip install -e .
or
python setup.py install develop
```

