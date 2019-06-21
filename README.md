``` python
from app import db, create_app
db.create_all(app=create_app())
```

``` python
export FLASK_APP=app
```

``` bash
flask run
```