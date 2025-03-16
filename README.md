# DSV_Assignments
Assignment 1: NumPy Basics
1.	Create a 1D NumPy array with values from 10 to 50.
2.	Generate a 2D array (4x4) with random integers between 1 and 100.
3.	Create an array of 10 elements, all initialized to zero except the fifth element, which should be 1.
4.	Create a NumPy array with values ranging from 0 to 20 and reverse it.
________________________________________
Assignment 2: Array Manipulations
1.	Reshape a given 1D array of size 12 into a 3x4 matrix.
2.	Concatenate two given arrays: 
3.	A = np.array([1, 2, 3])
4.	B = np.array([4, 5, 6])
5.	Stack two given 2D arrays vertically and horizontally.
6.	Split the given array [10, 20, 30, 40, 50, 60] into three equal parts.
________________________________________
Assignment 3: Mathematical Operations
1.	Compute the sum, mean, standard deviation, and variance of a NumPy array.
2.	Multiply a given array by a scalar value of 5.
3.	Compute the dot product and cross product of two given vectors.
4.	Find the determinant and inverse of a given 2x2 matrix.
________________________________________
Assignment 4: Indexing and Slicing
1.	Extract all even numbers from an array [10, 15, 20, 25, 30, 35, 40, 45].
2.	Extract the first column of a 3x3 matrix.
3.	Replace all odd numbers in an array with -1 without using loops.
4.	Select all elements from a NumPy array greater than 50.
________________________________________
Assignment 5: Boolean and Conditional Operations
1.	Given an array [5, 10, 15, 20, 25, 30], return a boolean array where each element is True if it is greater than 15.
2.	Find indices of all elements greater than 50 in a given array.
3.	Replace all negative numbers in an array with zero.
4.	Count the number of non-zero elements in an array.
________________________________________
Assignment 6: Broadcasting and Advanced Operations
1.	Add a scalar value of 10 to a 1D array using broadcasting.
2.	Multiply a 3x3 matrix with a 1D array.
3.	Normalize an array (convert values to range 0 to 1).
4.	Compute the row-wise sum and column-wise sum of a 4x4 matrix.
Assignment 7: Randomization and Statistical Operations
1.	Generate a 5x5 matrix with random integers between 50 and 100.
2.	Create a NumPy array of 100 random numbers following a normal distribution with a mean of 50 and a standard deviation of 10.
3.	Find the median, mode, and range of a given NumPy array.
4.	Compute the correlation coefficient between two arrays.
________________________________________
Assignment 8: Sorting and Searching
1.	Sort a given NumPy array in ascending and descending order.
2.	Find the index of the maximum and minimum values in an array.
3.	Search for a specific value in a NumPy array and return its index.
4.	Remove duplicate elements from a given NumPy array.
________________________________________
Assignment 9: Linear Algebra Operations
1.	Solve the following system of linear equations using NumPy: 2x+3y=52x + 3y = 5 4x+y=64x + y = 6 
2.	Compute the eigenvalues and eigenvectors of a given 2x2 matrix.
3.	Find the rank of a given matrix.
4.	Perform matrix multiplication without using np.dot().
________________________________________
Assignment 10: Image Processing with NumPy
1.	Load an image as a NumPy array and display its shape.
2.	Convert an RGB image into a grayscale image using NumPy operations.
3.	Flip an image vertically and horizontally using NumPy slicing.
4.	Extract the red channel from an RGB image and display it separately.
________________________________________
Assignment 11: Advanced NumPy Operations
1.	Create a NumPy structured array with three fields: name (string), age (int), and score (float).
2.	Implement a function to compute the moving average of a given NumPy array with a window size of 3.
3.	Find the cumulative sum and cumulative product of a given array.
4.	Implement element-wise exponentiation without using NumPy’s built-in power function.

________________________________________
1. Stock Market Analysis
Problem: Analyze stock prices to calculate trends and volatility.
📌 Tasks:
•	Load stock price data (CSV file) using numpy.loadtxt().
•	Compute the daily percentage change in stock prices.
•	Find moving averages (7-day, 30-day) using numpy.convolve().
•	Identify the days with the highest and lowest stock prices.
________________________________________
2. Weather Data Processing
Problem: Analyze temperature variations in a city over the past year.
📌 Tasks:
•	Load the dataset containing daily temperature records.
•	Compute the average monthly temperature using NumPy slicing.
•	Find the hottest and coldest days of the year.
•	Detect temperature outliers using NumPy’s statistical functions.
________________________________________
3. Customer Segmentation in E-Commerce
Problem: Identify high-value customers for personalized marketing.
📌 Tasks:
•	Load a dataset containing customer purchase amounts.
•	Compute average spending per customer.
•	Use NumPy filtering to segment customers into low, medium, and high spenders.
•	Find the top 5% of customers with the highest purchases.
________________________________________
4. Sports Performance Analysis
Problem: Analyze player performance in a football (soccer) league.
📌 Tasks:
•	Load match data (e.g., goals, assists, passes).
•	Compute total goals scored per player using NumPy aggregation.
•	Find the most consistent player by calculating standard deviation in goals per match.
•	Rank players based on their performance using numpy.argsort().
________________________________________
5. Image Processing for Object Detection
Problem: Manipulate image data for basic preprocessing.
📌 Tasks:
•	Load an image as a NumPy array using PIL.Image and convert it to grayscale.
•	Normalize pixel values (0 to 1) for deep learning models.
•	Apply edge detection using Sobel filtering with NumPy convolution.
•	Resize the image using slicing and interpolation techniques.
________________________________________
6. Fraud Detection in Banking Transactions
Problem: Identify suspicious transactions using statistical analysis.
📌 Tasks:
•	Load transaction data (amount, location, time).
•	Compute mean and standard deviation of transaction amounts.
•	Identify transactions that are 3 standard deviations above the mean as potential fraud.
•	Sort transactions by amount and detect anomalies.
________________________________________
7. Sentiment Analysis on Social Media
Problem: Analyze public sentiment using word frequency.
📌 Tasks:
•	Load a dataset of tweets or product reviews.
•	Convert text into a word frequency matrix using NumPy.
•	Identify the most commonly used words.
•	Compute TF-IDF (Term Frequency-Inverse Document Frequency) using NumPy.
________________________________________
8. Transportation Route Optimization
Problem: Optimize delivery routes for an e-commerce company.
📌 Tasks:
•	Load distance matrices for multiple delivery locations.
•	Compute the shortest path using NumPy’s mathematical functions.
•	Use broadcasting to calculate time taken for different speed limits.
•	Find the best warehouse location by computing average distance to customers.

