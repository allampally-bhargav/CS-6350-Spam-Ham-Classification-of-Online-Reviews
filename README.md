# CS-6350-Spam-Ham-Classification-of-Online-Reviews
Built a new system for spam classification by analyzing the latent criteria of reviews from the yelp Dataset and implemented it using Gaussian Mixture, Soft k-means and Sentiment Analysis Algorithms in PySpark thereby deploying it on AWS cloud using EC2



1. Extract the zip file.
2. Login into AWS Educate Account and open EMR and S3 bucket.
3. Open new jupyter notebook and start cluster to run this notebook.  
4. Open Spam Classification file into jupyter notebook and clear kernel and run all cells.
5. We can run data pre processing file using two input files - business.json and reviews.json and create a csv file after pre processing and pass it as input to the spam classification file

 So, these are the Inputs for data preprocessing:
	S3 link for business.json: https://bigdaaassignmentbucket.s3.amazonaws.com/yelp_academic_dataset_business.json(Object URL)
	S3 link for reviews.json: https://bigdaaassignmentbucket.s3.amazonaws.com/yelp_academic_dataset_review.json (Object URL)


Final Input File for the spam classification:
-------------------
Input file S3 link: https://bigdaaassignmentbucket.s3.amazonaws.com/Reviews.csv (Object URL)


Output File
-------------------
S3 bucket link to the final output

Final Output : https://bigdaaassignmentbucket.s3.amazonaws.com/out/Output_Final.zip
