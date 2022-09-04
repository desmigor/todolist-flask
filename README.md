# Todolist App in Flask

This works with `Python v3.8` and up.

## How To Run
1. Install `virtualenv`:
```
$ pip install virtualenv
```

Or for Updated version of pip

```
$ pip3 install virtualenv
```

2. Open a terminal in the project root directory and run:
```
$ virtualenv env
```

3. Then run the command:
```
Windows: $ .\env\Scripts\activate
Unix: $ source env/bin/activate
```

4. Then install the dependencies:
```
$ (env) pip install -r requirements.txt
```

5. Finally start the web server:
```
$ (env) python app.py
```

This server will start on port 5001. You can change this in `app.py` by changing the following line to this:

```python
if __name__ == "__main__":
    app.run(port=<desired port> , debug=True)
```

## Final Look

![alt text](/images/ui-shoot.png)
