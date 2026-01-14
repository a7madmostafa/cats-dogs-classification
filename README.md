# cats-dogs-classification

## Create Environment

1- Initialize the environment
```
 uv init
 ```

2- Create the environment with python 3.10
```
uv venv --python=3.10
```

3- Activate the environment
```
.venv\Scripts\activate
```

4- Install the requirements

```
uv pip install -r requirements.txt
```


## Dealing with Github (in case of Large Files)

1- Create a new repository on github
2- Clone the repository
3- Add the files to the repository
4- from the command line:

```
git lfs install
git lfs track "*.keras"
git add .
git commit -m "initial commit"
git push
```
