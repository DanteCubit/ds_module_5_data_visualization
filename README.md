
In this challenge, I processed data from a recent study on drug treatments for Squamous Cell Carcinoma (SCC) in 249 mice to generate technical reports containing tables and figures.

Initially, I consolidated separate DataFrames of mouse metadata and study results into a unified DataFrame. I then performed data cleaning by identifying and eliminating duplicate entries.

After the data cleaning phase, I created a final DataFrame where the drug regimen served as the index column. Within this DataFrame, I computed statistical measures including mean, median, variance, standard deviation, and SEM of the tumor volume.

Subsequently, I visualized the data by generating bar charts illustrating Mouse ID/Timpoints for each drug regimen and pie charts depicting the distribution of female versus male mice in the study.

To further analyze the data, I conducted quartile calculations to detect outliers. Additionally, I produced box plots, line plots, scatter plots, and a linear regression model to gain insights from high-level data.

Throughout the process, my tutor assisted in refining the code for setting up dependencies, data files, and constructing the summary statistics table DataFrame and aggregation method. Moreover, my TA provided valuable feedback on reviewing and refining quartiles, outliers, and box plots. Lastly, AskBCS Learning Assistant aided in correcting the model code for the linear regression task model = st.linregress(capomulin_average['Weight (g)'],capomulin_average['Tumor Volume (mm3)']).
