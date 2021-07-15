# Part 1

## Steps :-
1. Cloning the Github Repository made for this part.
<pre><code>git clone https://github.com/scimaths/MLOps_Assignment.git</code></pre>

2. Initializing the repository (with both ```git``` and ```dvc```).
<pre><code>git init
dvc init</code></pre>

3. Setting the cache to a folder outside this repository.
<pre><code>dvc cache /external_cache</code></pre>

4. Adding tracking of the downloaded CSV file.
<pre><code>dvc add data/creditcard.csv</code></pre>

5. Tracking the ```.dvc``` file with ```git```.
<pre><code>git add data/creditcard.csv.dvc data/.gitignore</code></pre>

6. Adding the S3 remote to this repository.
<pre><code>dvc remote add -d storage s3://mlops-ass2-200050148/dvcstore</code></pre>

7. Tracking the created ```config``` file with ```git```.
<pre><code>git add .dvc/config</code></pre>

8. Setting the access keys for the remote repository.
<pre><code>dvc remote modify --local storage access_key_id '$$$'
dvc remote modify --local storage secret_access_key '$$$'</code></pre>

9. Pushing the local copy of data to the S3 remote repository.
<pre><code>dvc push</code></pre>


Note that the ```git commit``` commands have been skipped, but have been used at required positions.

## Github Repository Link :-
[MLOps_Assignment (scimaths)](https://github.com/scimaths/MLOps_Assignment)

# Part 2

Random Forest Classifier - Accuracy : 0.9996137776061234, Weighted F1 Score : 0.8804347826086957

Decision Tree Classifier - Accuracy : 0.9993328885923949, Weighted F1 Score : 0.7956989247311828

