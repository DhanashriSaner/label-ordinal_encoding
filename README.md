<h1> Label/ encoding</h1>
<br>
In label encoding in Python, we replace the categorical value with a numeric value between 0 and the number of classes minus 1. If the categorical variable value contains 5 distinct classes, we use (0, 1, 2, 3, and 4).
<br>
<h3>Challenges with Label Encoding</h3>
Country names do not have an order or rank. But, when label encoding is performed, the country names are ranked based on the alphabets. Due to this, there is a very high probability that the model captures the relationship between countries such as India < Japan < the US.<br>
This is something that we do not want! So how can we overcome this obstacle? Here comes the concept of One-Hot Encoding.
