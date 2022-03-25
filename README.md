# Data
This is a library that enables you to analyze and visualize readscan and camscan images of blood smear and their coco annotations.


Analyze overwritwes a database in data_analysis.csv when called for the current task.


Visualize produces side by side comparative images corresponding to task_name and task_id with and without annotations.

Example usage has been mentione in trial/data.ipynb

>>data.analysis(25)

<img width="329" alt="image" src="https://user-images.githubusercontent.com/102033982/160119354-3ea1be09-d593-4b16-8fc1-ce8f32e74a4f.png">


>>data.analysis(102)


<img width="260" alt="image" src="https://user-images.githubusercontent.com/102033982/160119213-6ece2211-8c5a-422e-ad6e-27c9d63158b1.png">


>>data.visualize(102,44)

<img width="461" alt="image" src="https://user-images.githubusercontent.com/102033982/160119443-b399b589-db05-40e3-9533-90c22d59c633.png">

>>data.visualize(126,17)

<img width="458" alt="image" src="https://user-images.githubusercontent.com/102033982/160119557-e9a0f90f-80cf-42f2-82d3-e12b946c8e4b.png">
