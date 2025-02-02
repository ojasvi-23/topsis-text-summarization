<h1>Overview</h1>
<p>Text summarization is a vital NLP task that condenses large texts into meaningful summaries. This project compares multiple text summarization models, helping users choose the best one based on performance metrics.</p>

<h2>Key Features</h2>
<h3>Metrics Considered:</h3>
<ul>
    <li>Evaluation based on BLEU Score, Semantic Coherence, Factual Accuracy, and Content Coverage.</li>
</ul>

<h3>Methodology - TOPSIS:</h3>
<ul>
    <li>The Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) ranks models based on similarity to the ideal and dissimilarity from the worst-case solution.</li>
</ul>

<h3>Models Evaluated:</h3>
<ul>
    <li>Includes popular pre-trained models like <code>facebook/bart-large-cnn</code>, <code>t5-large</code>, <code>sshleifer/distilbart-cnn-12-6</code>, <code>google/pegasus-large</code>, and <code>allenai/led-large-16384-arxiv</code>.</li>
</ul>

<h2>Project Structure</h2>
<ul>
    <li><strong>train.csv</strong>: Training dataset.</li>
    <li><strong>evaluation_results.csv</strong>: Evaluation metrics for models.</li>
    <li><strong>topsis_results.csv</strong>: Final ranked results.</li>
</ul>

<h2>How to Run</h2>
<pre>
git clone https://github.com/yatharthgautam123/-Pretrained-model-Comparison-for-Text-Summarization-using-Topsis.git
</pre>

<h2>Results and Analysis</h2>
<p>Check ranked results in <code>topsis_results.csv</code>:</p>
<table>
    <tr>
        <th>Model</th>
        <th>BLEU Score</th>
        <th>Semantic Coherence</th>
        <th>Factual Accuracy</th>
        <th>Content Coverage</th>
        <th>TOPSIS Score</th>
        <th>Rank</th>
    </tr>
    <tr>
        <td>facebook/bart-large-cnn</td>
        <td>0.3488</td>
        <td>0.6557</td>
        <td>0.4583</td>
        <td>0.3716</td>
        <td>0.7561</td>
        <td>3</td>
    </tr>
    <tr>
        <td>t5-large</td>
        <td>0.3398</td>
        <td>0.7553</td>
        <td>0.4573</td>
        <td>0.4089</td>
        <td>0.8154</td>
        <td>2</td>
    </tr>
    <tr>
        <td>sshleifer/distilbart-cnn-12-6</td>
        <td>0.3053</td>
        <td>0.7083</td>
        <td>0.5217</td>
        <td>0.4839</td>
        <td>0.8651</td>
        <td>1</td>
    </tr>
    <tr>
        <td>google/pegasus-large</td>
        <td>0.3617</td>
        <td>0.7071</td>
        <td>0.4206</td>
        <td>0.3630</td>
        <td>0.7264</td>
        <td>4</td>
    </tr>
    <tr>
        <td>allenai/led-large-16384-arxiv</td>
        <td>0.1529</td>
        <td>0.2439</td>
        <td>0.2841</td>
        <td>0.1864</td>
        <td>0</td>
        <td>5</td>
    </tr>
</table>

<h2>License</h2>
<p>MIT License</p>
<pre>
&copy; 2024 Yatharth Gautam

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), 
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software.
</pre>

<h2>About</h2>
<p>No description, website, or topics provided.</p>

<h2>Resources</h2>
<ul>
    <li><strong>Readme</strong></li>
    <li><strong>Activity</strong></li>
</ul>

<h2>Community</h2>
<ul>
    <li><strong>⭐ Stars:</strong> 0</li>
    <li><strong>👀 Watchers:</strong> 1</li>
    <li><strong>🍴 Forks:</strong> 0</li>
</ul>

<h2>Repository Status</h2>
<ul>
    <li><strong>📌 Releases:</strong> No releases published</li>
    <li><strong>📦 Packages:</strong> No packages published</li>
</ul>

<h2>Languages</h2>
<ul>
    <li>Jupyter Notebook (100%)</li>
</ul>

