A/B testing (also known as bucket testing, split-run testing, or split testing) is a user-experience research methodology.[1] A/B tests consist of a randomized experiment that usually involves two variants (A and B),[2][3][4] although the concept can be also extended to multiple variants of the same variable. It includes application of statistical hypothesis testing or "two-sample hypothesis testing" as used in the field of statistics. A/B testing is a way to compare multiple versions of a single variable, for example by testing a subject's response to variant A against variant B, and determining which of the variants is more effective.[5]

Overview
"A/B testing" is a shorthand for a simple randomized controlled experiment, in which several samples (e.g. A and B) of a single vector-variable are compared.[1] These values are similar except for one variation which might affect a user's behavior. A/B tests are widely considered the simplest form of controlled experiment, especially when they only involve two variants. However, by adding more variants to the test, its complexity grows.[6]

A/B tests are useful for understanding user engagement and satisfaction of online features like a new feature or product.[7] Large social media sites like LinkedIn, Facebook, and Instagram use A/B testing to make user experiences more successful and as a way to streamline their services.[7]

Today, A/B tests are also being used for conducting complex experiments on subjects such as network effects when users are offline, how online services affect user actions, and how users influence one another.[7] A/B testing is used by data engineers, marketers, designers, software engineers, and entrepreneurs, among others.[8] Many positions rely on the data from A/B tests, as they allow companies to understand growth, increase revenue, and optimize customer satisfaction.[8]

Version A might be used at present (thus forming the control group), while version B is modified in some respect vs. A (thus forming the treatment group). For instance, on an e-commerce website the purchase funnel is typically a good candidate for A/B testing, since even marginal-decreases in drop-off rates can represent a significant gain in sales. Significant improvements can be sometimes seen through testing elements like copy text, layouts, images and colors,[9] but not always. In these tests, users only see one of two versions, since the goal is to discover which of the two versions is preferable.[10]

Multivariate or multinomial testing is similar to A/B testing, but may test more than two versions simultaneously or use more controls. Simple A/B tests are not valid for observational, quasi-experimental or other non-experimental situations—commonplace with survey data, offline data, and other, more complex phenomena.

Some claim A/B testing to be a change in philosophy and business strategy in certain niches, though the approach is identical to a between-subjects design, which is commonly used in a variety of research traditions.[11][12][13] A/B testing as a philosophy of web development brings the field into line with a broader movement toward evidence-based practice. The benefits of A/B testing are considered to be that it can be performed continuously on almost anything, especially since most marketing automation software now typically comes with the ability to run A/B tests on an ongoing basis.

Common test statistics
"Two-sample hypothesis tests" are appropriate for comparing the two samples where the samples are divided by the two control cases in the experiment. Z-tests are appropriate for comparing means under stringent conditions regarding normality and a known standard deviation. Student's t-tests are appropriate for comparing means under relaxed conditions when less is assumed. Welch's t test assumes the least and is therefore the most commonly used test in a two-sample hypothesis test where the mean of a metric is to be optimized. While the mean of the variable to be optimized is the most common choice of estimator, others are regularly used.

For a comparison of two binomial distributions such as a click-through rate one would use Fisher's exact test.

Assumed distribution	Example case	Standard test	Alternative test
Gaussian	Average revenue per user	Welch's t-test (Unpaired t-test)	Student's t-test
Binomial	Click-through rate	Fisher's exact test	Barnard's test
Poisson	Transactions per paying user	E-test[14]	C-test
Multinomial	Number of each product purchased	Chi-squared test	G-test
Unknown		Mann–Whitney U test	Gibbs sampling
Challenges
When conducting A/B testing, the user should evaluate the pros and cons of it to see if it aligns best with the results that they're hoping for.

Pros: Through A/B testing, it is easy to get a clear idea of what users prefer, since it is directly testing one thing over the other. It is based on real user behavior so the data can be very helpful especially when determining what works better between two options. In addition, it can also provide answers to very specific design questions. One example of this is Google's A/B testing with hyperlink colors. In order to optimize revenue, they tested dozens of different hyperlink hues to see which color the users tend to click more on.

Cons: There are, however, a couple of cons to A/B testing. Like mentioned above, A/B testing is good for specific design questions but it can also be a downside since it is mostly only good for specific design problems with very measurable outcomes. It could also be a very costly and timely process. Depending on the size of the company and/or team, there could be a lot of meetings and discussions about what exactly to test and what the impact of the A/B test is. If there's not a significant impact, it could end up as a waste of time and resources.

In December 2018, representatives with experience in large-scale A/B testing from thirteen different organizations (Airbnb, Amazon, Booking.com, Facebook, Google, LinkedIn, Lyft, Microsoft, Netflix, Twitter, Uber, and Stanford University) attended a summit and summarized the top challenges in a SIGKDD Explorations paper.[15] The challenges can be grouped into four areas: Analysis, Engineering and Culture, Deviations from Traditional A/B tests, and Data quality.

History
It is difficult to definitively establish when A/B testing was first used. The first randomized double-blind trial, to assess the effectiveness of a homeopathic drug, occurred in 1835.[16] Experimentation with advertising campaigns, which has been compared to modern A/B testing, began in the early twentieth century.[17] The advertising pioneer Claude Hopkins used promotional coupons to test the effectiveness of his campaigns. However, this process, which Hopkins described in his Scientific Advertising, did not incorporate concepts such as statistical significance and the null hypothesis, which are used in statistical hypothesis testing.[18] Modern statistical methods for assessing the significance of sample data were developed separately in the same period. This work was done in 1908 by William Sealy Gosset when he altered the Z-test to create Student's t-test.[19][20]

With the growth of the internet, new ways to sample populations have become available. Google engineers ran their first A/B test in the year 2000 in an attempt to determine what the optimum number of results to display on its search engine results page would be.[5] The first test was unsuccessful due to glitches that resulted from slow loading times. Later A/B testing research would be more advanced, but the foundation and underlying principles generally remain the same, and in 2011, 11 years after Google's first test, Google ran over 7,000 different A/B tests.[5]

In 2012, a Microsoft employee working on the search engine Microsoft Bing created an experiment to test different ways of displaying advertising headlines. Within hours, the alternative format produced a revenue increase of 12% with no impact on user-experience metrics.[4] Today, companies like Microsoft and Google each conduct over 10,000 A/B tests annually.[4]

Many companies now use the "designed experiment" approach to making marketing decisions, with the expectation that relevant sample results can improve positive conversion results.[citation needed] It is an increasingly common practice as the tools and expertise grow in this area.[21]

Examples
Email marketing
A company with a customer database of 2,000 people decides to create an email campaign with a discount code in order to generate sales through its website. It creates two versions of the email with different call to action (the part of the copy which encourages customers to do something — in the case of a sales campaign, make a purchase) and identifying promotional code.

To 1,000 people it sends the email with the call to action stating, "Offer ends this Saturday! Use code A1",
and to another 1,000 people it sends the email with the call to action stating, "Offer ends soon! Use code B1".
All other elements of the emails' copy and layout are identical. The company then monitors which campaign has the higher success rate by analyzing the use of the promotional codes. The email using the code A1 has a 5% response rate (50 of the 1,000 people emailed used the code to buy a product), and the email using the code B1 has a 3% response rate (30 of the recipients used the code to buy a product). The company therefore determines that in this instance, the first Call To Action is more effective and will use it in future sales. A more nuanced approach would involve applying statistical testing to determine if the differences in response rates between A1 and B1 were statistically significant (that is, highly likely that the differences are real, repeatable, and not due to random chance).[22]

In the example above, the purpose of the test is to determine which is the more effective way to encourage customers to make a purchase. If, however, the aim of the test had been to see which email would generate the higher click-rate – that is, the number of people who actually click onto the website after receiving the email – then the results might have been different.

For example, even though more of the customers receiving the code B1 accessed the website, because the Call To Action didn't state the end-date of the promotion many of them may feel no urgency to make an immediate purchase. Consequently, if the purpose of the test had been simply to see which email would bring more traffic to the website, then the email containing code B1 might well have been more successful. An A/B test should have a defined outcome that is measurable such as number of sales made, click-rate conversion, or number of people signing up/registering.[23]

A/B testing for product pricing
A/B testing can be used to determine the right price for the product, as this is perhaps one of the most difficult tasks when a new product or service is launched. A/B testing (especially valid for digital goods) is an excellent way to find out which price-point and offering maximize the total revenue.

Political A/B testing
A/B tests have also been used by political campaigns. In 2007, Barack Obama's presidential campaign used A/B testing as a way to garner online attraction and understand what voters wanted to see from the presidential candidate.[24] For example, Obama's team tested four distinct buttons on their website that led users to sign up for newsletters. Additionally, the team used six different accompanying images to draw in users. Through A/B testing, staffers were able to determine how to effectively draw in voters and garner additional interest.[24]

HTTP Routing and API feature testing

HTTP Router with A/B testing
A/B testing is very common when deploying a newer version of an API.[25] For real-time user experience testing, an HTTP Layer-7 Reverse proxy is configured in such a way that, N% of the HTTP traffic goes into the newer version of the backend instance, while the remaining 100-N% of HTTP traffic hits the (stable) older version of the backend HTTP application service.[25] This is usually done for limiting the exposure of customers to a newer backend instance such that, if there is a bug on the newer version, only N% of the total user agents or clients get affected while others get routed to a stable backend, which is a common ingress control mechanism.[25]

Segmentation and targeting
A/B tests most commonly apply the same variant (e.g., user interface element) with equal probability to all users. However, in some circumstances, responses to variants may be heterogeneous. That is, while a variant A might have a higher response rate overall, variant B may have an even higher response rate within a specific segment of the customer base.[26]

For instance, in the above example, the breakdown of the response rates by gender could have been:

Gender	Overall	Men	Women
Total sends	2,000	1,000	1,000
Total responses	80	35	45
Variant A	
50
/
1,000
 (5%)	
10
/
500
 (2%)	
40
/
500
 (8%)
Variant B	
30
/
1,000
 (3%)	
25
/
500
 (5%)	
5
/
500
 (1%)
In this case, we can see that while variant A had a higher response rate overall, variant B actually had a higher response rate with men.

As a result, the company might select a segmented strategy as a result of the A/B test, sending variant B to men and variant A to women in the future. In this example, a segmented strategy would yield an increase in expected response rates from 
5
%
=
40
+
10
500
+
500
{\textstyle 5\%={\frac {40+10}{500+500}}} to 
6.5
%
=
40
+
25
500
+
500
{\textstyle 6.5\%={\frac {40+25}{500+500}}} – constituting a 30% increase.

If segmented results are expected from the A/B test, the test should be properly designed at the outset to be evenly distributed across key customer attributes, such as gender. That is, the test should both (a) contain a representative sample of men vs. women, and (b) assign men and women randomly to each “variant” (variant A vs. variant B). Failure to do so could lead to experiment bias and inaccurate conclusions to be drawn from the test.[27]

This segmentation and targeting approach can be further generalized to include multiple customer attributes rather than a single customer attribute – for example, customers' age and gender – to identify more nuanced patterns that may exist in the test results.
