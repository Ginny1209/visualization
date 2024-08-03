# Data Visualization

## Assignment 4: Final Project

### Excel-three year trend line chart
 

  > What software did you use to create your data visualization?
	I used the built-in function of Microsoft Excel to create the data visualization. 

    > Who is your intended audience? 
    	Individuals who are interested in the trend of hourly pay in different occupations over three years from 2013 to 2015, 
	for example employees whose occupation is listed, job seekers, HR,employer, students who is choosing their future careers

    > What information or message are you trying to convey with your visualization? 
    	The message conveyed by the visualization is to show the trend of average hourly rates of different occupations from different regions of Ontario from 2013 to  2015. 
    	It can tell which occupation's hourly rate has increased or decreased.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    	Added the axis labels, grids,legends and enlarge the fonts
	Used colorblind-friendly colors to ensure the chart is accessible
	Make the beginning axis value from 0 dollar to 15 dollars so we can clearly see the trend as the change is not that obvious over the three years.
	Added Alt-text as the text box, tried to use the built-in function but it seems you have to use accessible model to get in to see it
	Used the average rate of all the regions of Ontario by converting the original data to pivot table.
	Keep it simple and focused with less elements.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    	Share the original data and the chart in the excel file with comments about how I clean the date and the pivot table as the source of the chart. 
	So all the color codes, font size, font can be found in the document.

    > How did you ensure that your data visualization is accessible?  
    	Used Paul Tol's Color Schemes:(Blue: #0072B2Orange: #D55E0Green: #009E73) to accommodate individuals with color vision deficiencies.
	Added alt text in the alt-text function as well as a text box as the alt-text can only be read on accessible mode. 
	Avoided overlapping labels and ensured enough spacing between bars and text.


    > Who are the individuals and communities who might be impacted by your visualization?  
    	Individuals who were working in certain occupation lists in the data from 2013 to 2015 could have a reference of their own wage to the market.
	Employers and HR who are evaluating their labor cost/budget  to new hires or current employees.
	Economists and policy makers who are studying labor cost market
	Students who are seeking to join a occupation/industry with better financial prospect


    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    	After I cleaned all the averages, or totals that are not considered as unique data. All features left are Year, Geography, Occupation, and Wage Rate.
	To avoid complexity and focus on overall trends,I exclude the geography breakdown, and use the average wage rate of all the province as the final average wage.


    > What ‘underwater labour’ contributed to your final data visualization product?
	  Cleaning data by removing the excessive informan and make a pivot table as the source of data visualization
	  Adjusting the font size,adding axis label, add chart title,legends
	  Add alt-text, changing the colorblind-friendly color palette
	  Change the y axis starting from 15 dollars to make the chart more concise and focused

	
 
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
