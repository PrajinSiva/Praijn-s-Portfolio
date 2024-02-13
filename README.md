# First-project
This is my first project in the journey for learning data analytics and implementing my skills and knowledge in real world .
python
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def index():
    return render_template('index.html')

if __name__ == '__main__':
    app.run(debug=True)
