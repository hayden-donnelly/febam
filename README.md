# FEBAM
PyTorch implementation of Feature Extracting Bidirectional Associative Memory (FEBAM).

<img src="./images/febam_architecture.jpg" width="700px"></img>

## Docker Environment
Building image:
```
docker-compose build
```

Starting container/environment:
```
docker-compose up -d
```

Opening a shell in container:
```
docker-compose exec febam bash
```

Instead of opening a shell, you can also go to http://localhost:8888/ to access a Jupyter Lab instance running inside the container.

Stopping container/environment:
```
docker-compose down
```


## Citation
```bibtex
@INPROCEEDINGS{chartier_giguere_renaud_lina_proulx,
    author={Chartier, Sylvain and Giguere, Gyslain and Renaud, Patrice and Lina, Jean-Marc and Proulx, Robert},
    booktitle={2007 International Joint Conference on Neural Networks}, 
    title={FEBAM: A Feature-Extracting Bidirectional Associative Memory}, 
    year={2007},
    pages={1679-1684},
    doi={10.1109/IJCNN.2007.4371210}
}
```
