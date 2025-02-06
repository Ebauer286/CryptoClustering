# CryptoClustering

I completed this assignment with the assistance of tutoring sessions with Carlos Gattorno.

Error code received on line 15 C:\Users\Ebaue\anaconda3\envs\dev\lib\site-packages\sklearn\cluster\_kmeans.py:1446: UserWarning: KMeans is known to have a memory leak on Windows with MKL, when there are less chunks than available threads. You can avoid it by setting the environment variable OMP_NUM_THREADS=1.
  warnings.warn( 
  Added "import os" and set the environment to os.environ['OMP_NUM_THREADS'] = '1' in accordance with warning message however it did not fully resolve the warning but code still runs. 
