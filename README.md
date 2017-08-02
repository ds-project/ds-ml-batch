# ds-ml-batch
Machine Learning batch processing repo on Azure Function

use python 3.5.2

Both Azure SDK and pymsql library are required.

```
> cd /d/home/site/tools/
> python -m pip install azure 
> python -m pip install pymysql 
```

Then, put some configs on file(also possible to modify some path properly) and run this function.
If azure function do correctly, you will see this response 

```json
"Success Batch Job"
```
