<h2> Data set:- <a href = "https://docs.google.com/spreadsheets/d/1-31wL1vkNU8-yxfc2ItAX6KE4Re7RuUP/edit?usp=sharing&ouid=107093923581893374366&rtpof=true&sd=true">Click here for link</h2>

<h2>Objective:</h2>
<p>Segment customers based on purchasing behavior using K-Means clustering.</p>

<h2>Data Source:</h2>
<p>Transaction records from an Excel file, preprocessed for missing values and outliers.</p>

<h2>Key Metrics:</h2>
<ul>
    <li><strong>Recency:</strong> Days since the last purchase.</li>
    <li><strong>Frequency:</strong> Number of purchases.</li>
    <li><strong>Monetary:</strong> Total spending.</li>
</ul>

<h2>Data Processing:</h2>
<ul>
    <li>Removed transactions with null Customer IDs.</li>
    <li>Filtered out transactions with negative quantities and prices.</li>
    <li>Converted invoice dates to datetime format.</li>
</ul>

<h2>Normalization:</h2>
<p>Applied MinMaxScaler to normalize Recency, Frequency, and Monetary values.</p>

<h2>Optimal Clusters:</h2>
<p>Determined the optimal number of clusters (4) using the Elbow method and Silhouette scores.</p>

<h2>Cluster Analysis:</h2>
<ul>
    <li><strong>Cluster 0: Best Customers</strong> - Recent, frequent, high spenders.</li>
    <li><strong>Cluster 1: Big Spenders</strong> - Moderately recent, high spenders, less frequent.</li>
    <li><strong>Cluster 2: Loyal Customers</strong> - Moderately recent, regular buyers with moderate spending.</li>
    <li><strong>Cluster 3: Lost Cheap Customers</strong> - Least recent, infrequent, low spenders.</li>
</ul>

<h2>Visualization:</h2>
<p>Created bar graphs to display average RFM values for each cluster.</p>

<h2>Segmentation Map:</h2>
<p>Labeled clusters for targeted marketing strategies.</p>

<h2>Output:</h2>
<p>Final segmented data ready for analysis and targeted marketing.</p>





