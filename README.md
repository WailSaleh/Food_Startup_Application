# User Behavior for Food Startup's Application 🍲📱

I work at a startup that sells food products. Need to analyze user behavior for the company's application.

First, study the sales funnel. Find out how users get to the purchase stage. Do users really get to this stage? How many are stuck in the previous phases? Which steps in particular?

Next, view the results of the A/A/B test. (Read on for more information on A/A/B testing). Designers would like to change the fonts of the entire app, but managers fear that users will find the new design intimidating. They decide to make the decision based on the results of an A/A/B test.

Users are divided into three groups: Two control groups receive the old fonts and one test group receives the new ones. Find out which set of sources produces the best results.

The creation of two A groups has certain advantages. We can adapt a principle according to which we will only be confident in the accuracy of our tests when the two control groups are similar. If there are significant differences between the A groups, it can help us uncover factors that can skew the results. Comparing control groups also tells us how much time and data we'll need when running other tests.

You'll use the same dataset for general analysis and A/A/B analysis. In real projects, experiments are carried out constantly. Analysts study the quality of an application using general data, without paying attention to users' participation in experiments.

**logs_exp_us.csv:**

*EventName: Event name*

*DeviceIDHash: Unique user identifier*

*EventTimestamp: time of the event*

*ExpId: Experiment number: 246 and 247 are the control groups, 248 is the test group*
