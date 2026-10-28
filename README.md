<h1>📊 Project Title</h1>
<h2>Credit Risk & Loan Portfolio Analysis</h2>
<hr>
<h1>📋 Project Overview</h1>
<p>The <b>Credit Risk & Loan Portfolio Analysis</b> project focuses on analyzing loan application, customer profiles, and repayment records to evaluate lending performance, identify credit risk pattern, and monitor repayment behavior.</p>
<p>Using <b>SQL, Python (Pandas), Power BI</b>, this project explores loan approval trends, approved loan amounts, borrower credit score, debt-to-income ratios, and repayment performance. The analysis aims to identify customer segment with higher observed delinquency, evaluate collection efficiency, and understand how loan performance varies across loan types and employment categories.</p>
<p>The project demonstrate and end-to-end data analytics workflow, from data preparation and SQL based analysis to business intelligence reporting, with the goal of supporting data-driven decisions in credit risk monitoring and loan portfolio management. </p>
<hr>
<h1>🎯 Business Problem</h1>
<p>A lending service company has experienced growth in loan application across multiple loan categories and customer segments. However, management lacks a consolidated analytical view of loan approval patterns, applicant creditworthiness, repayment performance, and portfolio delinquency. </p>
<p>Loan application data, customer profile, and repayment records are maintained in separate datasets. This makes it difficult to identify relationship between borrower characteristics, lending decision, and subsequent repayment outcomes. </p>
<p>The company needs a data driven approach to evaluate portfolio quality, identify patterns associated with later or missed payments, compared loan performance across branches and loan types, and understand whether lending is concentrated in higher risk customer segments. </p>
<h2>Business Objectives</h2>
<ol>
  <li>Evaluate loan approval performance.</li>
  <li>Identify credit risk indicators.</li>
  <li>Analyze repayment behavior. </li>
  <li>Assess portfolio performance.</li>
</ol>
<hr>
<h1>🛠️ Tools Used</h1>
<ul>
  <li>SQL (Data Analysis)</li>
  <li>Python (Pandas) (Data Cleaning)</li>
  <li>Power BI (Dashboard Development)</li>
</ul>
<hr>
<h1>📈 KPIs</h1>
<ol>
  <li>Total Loan Application</li>
  <li>Loan Approval Rate (%)</li>
  <li>Total Approved Loan Amount</li>
  <li>Delinquency Rate (%)</li>
  <li>Collection Rate (%)</li>
</ol>
<hr>
<h1>🔍 SQL Analysis</h1>
<p>What is the total number of loan applications, and what is the overall loan approval rate?</p>
<img src="./Images/photo 1.png" width="750">
<img src="./Images/photo 1.1.png" width="750">
<p>Which loan types account for the highest total approved loan amount?</p>
<img src="./Images/photo 2.png" width="750">
<p>Which credit score bands have the highest delinquency rates?</p>
<img src="./Images/photo 3.png" width="750">
<p>What is the collection rate, and how many repayments fall into each overdue aging category?</p>
<img src="./Images/photo 4.png" width="750">
<img src="./Images/photo 4.1.png" width="750">
<hr>
<h1>📷 Dashboard Preview</h1>
<img src="./Images/credit dashboard 1.png" width="900">
<img src="./Images/credit dashboard 2.png" width="900">
<img src="./Images/credit dashboard 3.png" width="900">
<hr>
<h1>💡 Key Insights</h1>
<ol>
  <li>The overall loan approval rate is <b>71.34%</b>, with 5,952 approved applications compared with 2,391 rejected applications. Personal loans contribute the highest approved loan amount at approximately <b>0.72B</b>.</li>
  <li>The delinquency rate is high across all displayed credit score bands, ranging from <b>80.89%</b> to <b>80.87%</b>. The Very Good credit score band shows the highest rate at 83.87%, while the Good band shows the lowest at 80.89%.</li>
  <li>Self-employed applicants have the highest displayed delinquency rate at <b>83.50%</b>, followed by business owners at 83.39%. Unemployed applicants show the lowest rate at 81.73%.</li>
  <li>The reported collection rate is <b>84.41%</b>. The monthly chart also shows that the amount paid is below the amount due in every displayed month, indicating a collection gap in the reported data.</li>
  <li>The repayment dashboard records <b>6390</b> paid repayments, compared with <b>1352</b> late, 981 partial, 776 missed, and 401 overdue repayments. Late payments are the largest category after paid repayments.</li>
</ol>
<hr>
<h1>🚀 Recommendations</h1>
<ol>
  <li>Review rejection patterns to understand the main reasons for unsuccessful applications and monitor personal loan exposure to maintain a balanced loan portfolio.</li>
  <li>Investigate repayment histories and other factors, such as DTI ratio and loan amount, to understand these patterns. Validate the delinquency calculation before using it for lending decisions.</li>
  <li>Analyze income stability, affordability, DTI ratios, and repayment history across employment groups. Avoid treating employment type alone as a predictor of an individual's creditworthiness.</li>
  <li>Monitor unpaid balances monthly, investigate persistent collection gaps, and prioritize follow-up for overdue accounts based on days past due and outstanding amounts.</li>
  <li>Introduce repayment-status monitoring and overdue-aging reports to identify accounts requiring timely follow-up. Separate temporary delays from persistent missed payments to improve collection prioritization.</li>
</ol>
