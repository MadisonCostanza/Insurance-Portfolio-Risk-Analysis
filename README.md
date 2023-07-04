# Insurance-Portfolio-Risk-Analysis

**The following situation was presented to me in a take-home Analytical Assessment for a job interview at a risk analytics company:**

Got Your Back Insurance recently used our Winter Storm model to determine the
expected yearly losses for 2 of their portfolios. Each portfolio contains one or more insurance policies
that cover the company’s insured properties. The analysis ran smoothly, but the client is having issues
deciphering the results and what they mean for their business. 

The client expressed that it would be helpful to see calculations of the different risk metrics their output contains. Each calculation, also
referred to as an exhibit, will have its own table in an excel file that details how the final output was
determined. The excel will be sent to the client to help them develop a deeper understanding of their
exposure. We knows that client data can often contain errors or abnormalities and has asked you to
clean the data, prepare a set of exhibits, and answer a set of questions. The loss output provided by the
client can be found in Analytical_Assessment_Data.csv.

Any assumptions or changes to the data you make during this analysis should be clearly stated in the
deliverables outlined below. The definitions section will help to guide your analysis and the data
cleaning process. This assignment can be completed in the coding language of your choice.

**Tasks for the Assessment:**

1. For each state in the output file, find the total insured value (TIV) and number of risks.
2. Which 5 counties contain the largest total insured value (TIV) for construction code WD10?

3. For each portfolio, find the 10 postal codes that are the most susceptible to damage from winter
storms.
4. For each Pennsylvania postal code, find the breakdown of total insured value (TIV), risk count,
and average annual loss (AAL) by building height band.

**Questions to be answered are as follows:**

1. Does one of the portfolios appear to be more vulnerable to damage from winter storm? If so,
which one? Explain your reasoning and any analysis you conducted to support your conclusion.

2. Which factors appear to have the greatest influence on AAL? Explain your reasoning and any
analysis you conducted to support your conclusion.

**Deliverables**

This assignment has 3 deliverables:
1. A formatted excel workbook with:
a. A read me sheet that states any assumptions made during the analysis
b. Exhibits containing the desired outputs described in the Tasks section. The number of
sheets used to display the output exhibits is up to you.

2. A document with:
a. Your answers to the Questions
i. Answer to each question should be 1-2 paragraphs in length
b. Explanations of how you cleaned the data and completed each Tasks
i. Each explanation should be a few sentences long

3. File(s) containing the code written to conduct the analysis. If you did the assignment in Excel,
you should provide a workbook that contains the work you did to complete each task/question.
Each task and question should be on its own sheet.

**Definitions:**

LocationID: A unique identifier for each location in the loss output file.

Portfolio: A numeric indicator for which portfolio a given location belongs to.

State: The state the location is in.

County: The county the location is in.

Postal Code: The postal code the location is in.

Building Value: The insured value of the building at the location.

Other Value: The insured value of other structures at the location, not including the main building.

Contents Value: The insured value of the contents of the building at the location.

Time Element Value: The insured value for cost endured by being displaced from the location.

Total Insured Value (TIV): The sum of the building value, other value, contents value, and time element
value at each location.

Risk Count: The number of insured risks at a given location. Each location in the loss output file is
assumed to have a risk count of 1.

Occupancy Code: The type of building structure, such as a house or office building, at the location. The
table in Appendix A outlines the meanings of occupancy codes found in the provided data.

Construction Code: The materials used to build the structure at the location. The table in Appendix B
outlines the meanings of construction codes found in the provided data.

Stories: The number of stories the building at the location has. We use the following building height
bands:

• Small: Buildings with 1 to 3 stories

• Medium: Buildings with 4 to 7 stories

• Large: Buildings with 8 or more stories

Year Built: The year the building at the location was built. We use the following year built bands:

• Old: Built before 1980

• Average: Built between 1980 and 2000

• New: Built after 2000

Average Annual Loss (AAL): The average total claims amount Got Your Back Insurance pays to a location
each year as a result of winter storm damage.

Appendix A:

Occupancy Code Description

ATC-00: Unknown

ATC-01: Single Family Housing

ATC-02: Multi-Family Housing

ATC-37: General Commercial

ATC-38: General Industrial

Appendix B:

Construction Code Description

WD00: Wood

WD10: Wood – Wood Frame

MS00: Masonry

MS10: Masonry - Unreinforced

CN00: Concrete

CN10: Concrete - Reinforced

MH00: Mobile Home

MH10: Mobile Home – No Tie-Down
