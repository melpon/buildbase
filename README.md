# buildbase

主に時雨胴で扱うビルドスクリプトのテンプレート

自身のリポジトリ上で

```bash
curl -LO https://raw.githubusercontent.com/melpon/buildbase/master/buildbase.py
```

のようなコマンドで buildbase.py をダウンロードして、

```python
from buildbase import (
    cd,
    install_sora,
)
```

のように記述して利用します。
