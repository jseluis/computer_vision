# deep_learning
 Computer Vision Algorithms and Applications

<p>Output some text from Python in <strong>Markdown</strong>:
<code>python
from sklearn.datasets import load_iris
from sklearn import tree
iris = load_iris()
clf = tree.DecisionTreeClassifier()
clf = clf.fit(iris.data, iris.target)
clf.predict_proba(iris.data[:1, :])</code></p>
