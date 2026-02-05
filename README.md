<h2>📊 Dataset & Analysis</h2>

<p>
The project uses the <b>Algerian Forest Fire Dataset</b> to analyze fire-related patterns
and predict outcomes based on environmental and meteorological conditions.
</p>

<ul>
  <li>Exploratory Data Analysis (EDA)</li>
  <li>Feature Engineering (FE)</li>
  <li>Data cleaning and preprocessing</li>
  <li>Fire-related pattern analysis</li>
  <li>Feature normalization using <code>StandardScaler</code></li>
</ul>

<hr>

<h2>🧠 Models Trained</h2>

<p>The following regression models were trained and evaluated individually:</p>

<ul>
  <li>Linear Regression</li>
  <li>Lasso Regression</li>
  <li><b>Ridge Regression (Selected)</b></li>
  <li>ElasticNet Regression</li>
</ul>

<p>
Each model was trained using cross-validation and evaluated using:
</p>

<ul>
  <li>Mean Absolute Error (MAE)</li>
  <li>R<sup>2</sup> Score</li>
</ul>

<p>
Based on consistent performance and better generalization,
<b>Ridge Regression</b> was selected as the final model.
</p>

<hr>

<h2>💾 Model Artifacts</h2>

<p>The following trained objects are serialized using Pickle and used in deployment:</p>

<ul>
  <li><code>Models/ridge.pkl</code> – Trained Ridge Regression model</li>
  <li><code>Models/scaler.pkl</code> – Fitted StandardScaler</li>
</ul>

<hr>

<h2>🚀 Tech Stack</h2>

<ul>
  <li>Python</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Scikit-learn</li>
  <li>Flask</li>
  <li>HTML (Jinja Templates)</li>
</ul>

<hr>

<h2>▶️ How to Run the Application Locally</h2>

<h3>1️⃣ Clone the Repository</h3>

<pre>
git clone &lt;your-repository-url&gt;
cd End-to-End-Project
</pre>

<h3>2️⃣ Create and Activate Conda Environment</h3>

<pre>
conda create -n e2e python=3.10 -y
conda activate e2e
</pre>

<h3>3️⃣ Install Dependencies</h3>

<pre>
pip install -r requirements.txt
</pre>

<h3>4️⃣ Run the Flask Application</h3>

<pre>
python application.py
</pre>

<hr>

<h2>🌐 Access the Application</h2>

<p>
Open a browser and visit:
</p>

<pre>
http://localhost:5000/
</pre>

<p>
For cloud deployment, replace <code>localhost</code> with your server's public IP or domain.
</p>

<hr>

<h2>📁 Project Structure</h2>

<pre>
End-to-End-Project/
│
├── Models/                # Pickled ML model & scaler
├── templates/             # HTML templates
├── NoteBook/              # EDA & model training notebooks
├── application.py         # Flask application
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
├── .gitignore
</pre>

<hr>

<h2>☁️ Deployment</h2>

<ul>
  <li>Designed for deployment on AWS (EC2 / Elastic Beanstalk)</li>
  <li>Dependencies installed using <code>requirements.txt</code></li>
  <li>No virtual environment files are pushed to GitHub</li>
</ul>

<hr>

<h2>📌 Key Learnings</h2>

<ul>
  <li>End-to-end machine learning workflow</li>
  <li>Regression model comparison and evaluation</li>
  <li>Cross-validation techniques</li>
  <li>Model serialization using Pickle</li>
  <li>Flask-based ML deployment</li>
  <li>Professional Git and environment management</li>
</ul>

<hr>

<h2>✨ Future Improvements</h2>

<ul>
  <li>Improve UI/UX</li>
  <li>Add input validation</li>
  <li>Store models in cloud storage (AWS S3)</li>
  <li>Add logging and monitoring</li>
  <li>Dockerize the application</li>
</ul>

<hr>

<h2>👤 Author</h2>

<p>
<b>Sagar Rai</b><br>
Machine Learning | Data Science | Flask
</p>
