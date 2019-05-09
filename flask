from flask import Flask,request
app = Flask(__name__)


@app.route('/')
def hello():
    param=request.args.get('zeki')
    return "Hello World!"+str(param)

if __name__ == '__main__':
    app.run(port=5000)
