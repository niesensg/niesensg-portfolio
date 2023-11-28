# niesensg-portfolio
This repository includes dashboards and data visualizations from several of my classes, including STA 309 and BIO 485.

education_dashboard:
This is the final dashboard from my midterm project for STA309. Given a dataset with math and reading proficiency scores of US students as well as demographic data for US school districts, I decided to focus on my home state of Missouri, highlighting the relationship between poverty and academic performance.

heart_dashboard:
This final project for STA309 worked with heart disease data had two parts. As students are still given a similar assignment, I have only uploaded the dashboard from the Part 2.
In Part 1 of this project, I modeled the risk of heart disease based on the variables present in the data. I achieved this by using a 5-fold cross validation study with 10 repeats as well as using RandomForest. I determined which variables were most important using RandomForest's importance values.
In Part 2, I created several data visualizations in order to create a dashboard about cardiovascular health risks. I focused on the variables with the highest importance values: Cholesterol, Age, and Fasting Blood Sugar. The final dashboard was saved as a png file.

differential_expression_heatmaps:
This data visualization was created for my final presentation in BIO 485, Principles of Bioinformatics. My partner and I chose the 3rd project option, differential gene expression analysis by RNA-Seq. We performed differential gene expression analysis of Mus musculus using both RSEM and Kallisto-DESeq2, focusing on genes involved in eye development. This required us to use Miami’s supercomputer cluster. Additionally, I conducted some data cleaning and analysis in R, which I also used to produce several data visualizations. I chose to take the log of the transcripts per million in order to make it easier for our classmates to visualize the differences in gene expression between the two cell types, Epithelial and Fiber, as well as the two differential gene expression tools, Kallisto and RSEM. Although a red and blue color palette is traditional, I chose to use different shades of red, yellow, and blue in order to make the visualization more accessible to color-blind classmates. As part of this project, in addition to presenting our results to the class, we also produced a literature review.
