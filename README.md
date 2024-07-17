# Pandas-to-cuDF-Performance-Comparison
"A repository for comparing the performance of Pandas and cuDF with a focus on accelerating data processing using cuDF's pandas API."
This notebook is all about showing the incredible speed boost you can get by switching from regular Pandas to the GPU-accelerated cuDF library, without changing a single line of your existing code!

Highlights:
Getting Started:

First, we make sure an NVIDIA GPU is available.
Then, we import the necessary libraries, including cudf and plotly-express.
Loading Data:

We download a hefty dataset on NYC parking violations for 2022 to work with.
Pandas on CPU:

Using Pandas, we analyze the dataset to find the most common parking violations by state, the types of vehicles most often ticketed, and how violations vary by day of the week.
These operations take several seconds to complete.
cuDF on GPU:

We switch to cuDF and re-run the same analyses.
The result? Operations that took seconds now complete in milliseconds! It’s incredibly fast.
Visualizations and Third-party Integrations:

We create visualizations using Plotly, seamlessly integrating cuDF.
Even third-party libraries benefit from the GPU acceleration with cudf.pandas enabled.
Conclusion:
With cudf.pandas, you can supercharge your data analysis on a GPU with zero code changes. Just load the extension and watch your workflows fly!
Link for more data
https://rapids.ai/cudf-pandas/

