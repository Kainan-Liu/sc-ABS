![framework](https://github.com/Kainan-Liu/scanba/assets/146005327/f00271b3-276a-45ea-9897-d341fae74124)

## Dependencies
- torch==1.13.0
- torchvision==0.14.1
- anndata==0.10.3
- numpy==1.19.2
- scanpy==1.9.6
- scipy==1.9.3
- pandas==1.5.2
- setuptools==59.5.0

## Architecture
```lua
Model/
|-- Net/
|   |-- __init__.py/
|   |-- _net.py
|   |-- _unit.py
|   |--classifier.py
|   |--discriminator.py
|   |--generator.py
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
|-- __init__.py
|--  _pretrain.py
|-- _utils.py
|-- align.py
|-- correct.py
|-- detect.py
|-- Model.py
|-- subtyping.py
|-- LICENSE
```

## Tested environment
- **CPU: Intel(R) Xeon(R) Platinum 8255C CPU @ 2.50GHz**
- **Memory: 256 GB**
- **System: Ubuntu 20.04.5 LTS**
- **Python: 3.9.15**
