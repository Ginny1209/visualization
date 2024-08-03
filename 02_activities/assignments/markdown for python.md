# Data Visualization

## Assignment 4: Final Project

### Python-BOX PLOT:

- Link for data source,
- 
	Wage rates by occupation https://data.ontario.ca/dataset/wage-rates-by-occupation

    > What software did you use to create your data visualization?
    > 
	Python, specifically the Matplotlib and Seaborn libraries

    > Who is your intended audience?
    > 
	The intended audience are individuals who are interested in wage distribution across different occupations in different Ontario regions.
    
    > What information or message are you trying to convey with your visualization?
    > 
	The box plot compares the wage distributions across different occupations in different regions from 2013 to 2015, highlighting differences in central tendencies, variability, and the presence of outliers.
 	It seems that the management roles are one of the widest ranges, indicating significant variability in wages within this category. The wages range from around $35 to $45. 
  	Sales and service occupations have one of the smallest ranges, with wages clustered closely together, indicating less variability. The wages range from around $10 to $15,which is among the minimum wage. 
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    >
  Cleaned the original dataset and kept the most core valued data. For X-axis,use the hourly rate .For Y axis, divide the occupations into major classes.Choose a colorblind-friendly palette to ensure accessibility. 

	
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    >
    Record all the process of data cleaning and visualization code in python fileUsing publicly accessible libraries like Matplotlib and Seaborn. Comment to the code to record my steps


    > How did you ensure that your data visualization is accessible?
    > 
	Used a color palette accessible to colorblind individuals.
	Added Alt-text, clearly label all the elements
	defined font sizes and styles that are easy to read.
	Class the over 100 jobs into major 10+ occupation categories

    
    > Who are the individuals and communities who might be impacted by your visualization?
    > 
	Job seekers or students who are choosing their future careers will realize what type of occupations have better financial prospects than others.
	They will be aware of the significant wage differences between top-skilled workers and lower or average workers within the same occupation.
	For employers and HR, they would have a better bench mark for their compensation benchmark.
	For policy makers, they can get some insights on the income gap across different occupations.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    >
    	After I cleaned all the averages, or totals that are not considered as unique data.All features are Year, Geography, Occupation, and Wage Rate, but for this one I excluded the year and Geography.  Because it focuses on the overall wage distribution across different occupations without considering year-to-year variations.Since the plot is focusing on the overall wage distribution across various occupations without comparing different regions within Ontario,


    > What ‘underwater labour’ contributed to your final data visualization product?
    > 
	 Data cleaning was made before the data cleaning in the code which kept all the occupation categories instead of the detailed occupations. 
  	I removed all the “annual pay”semi-monthly pay” etc but to keep them standardized as hourly pay.Also removed the null data.


 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
