<h1>P-Values: What they are and how to interpret them</h1>
<h2>P-Values:What they are</h2>
P-Values are numbers, between 0 and 1, that quantify how confident we should take a situation over others.
The closer a p-value is to 0, the more confidence we have about the situation.

But how small a p-value have to be before we are sifficiently confident? In other words, what threshold can we use to make a good decision?

In practice, a commonly used threshold is .05, it means that if there is no difference between situations, and if we did this exact same experiment a bunch of times, then only 5% of those experoments would result in the wrong decision.

Getting a small p-value when there is no difference is called <b>False Positive</b>.

In other words, if there is no difference between situations, 5% time we do the experiment, we'll get a p-value less than 0.05, aka a <b>False Positive</b>.

<b>Note:</b><br>
if it is extremely important that we are correct decide a situation, then we use a smaller threshold, like <b>0.00001</b>.<br>
Using a threshold of 0.00001 means we would only get a <b>False Positive</b> once every 100,000 experiments.

Likewise, if it is not important that we are correct decide a situation, then we can use a larger threshold, like <b>0.2</b>.<br>
Using a threshold of 0.2 means we are willing to get <b>False Positive</b> 2 times out of 10.<br>

That said, the most common threshold is 0.05 because trying to reduce the number of <b>False Positive</b> below 5% often costs more than it is worth.

P-value helps us decide a thing, but doesnot tells us how different the situations are from each others.