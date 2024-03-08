# buildbase

主に時雨胴で扱うビルドスクリプトのテンプレート

好きなタイミングで buildbase.py を各リポジトリにコピーして、

```python
from buildbase import (
    cd,
    install_sora,
)
```

のように記述して利用します。
