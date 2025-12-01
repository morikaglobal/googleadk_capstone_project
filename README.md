# Price Calculation agent for a bakery store

agent for a bakery that can capture basic customer info, greet the customer and works out item price with tax based on the purchase type

https://github.com/morikaglobal/googleadk_capstone_project/blob/main/calculation_agent_for_bakery_store.ipynb

Problem Statement --
In Japan where I live, it is often confusing to work out the total price of item in bakery shops as different consumption tax rate is applied based on your purchase type of whether you eat in (consumption tax rate is 10%) or take items home (consumption tax rate is 8%).

This can be confusing especially for foreign tourists who may not be familiar with how different consumption tax is applied based on consumption tax, also due to lack of labour resources, many small bakeries are now using unmanned cash registers with touch panels and registers need to ask the customer and capture purchase type (is the customer taking breads home? or having purchased items in store?) in order to work out which consumption tax rate to apply to the item prices.

I wanted to create a simple agent that automates the total item price calculation flow with some greeting/interaction with the customer so that agent not only solves the problem, but also captures customer name and country (where the customer is from) to make the purchase interaction more friendly and less routine-ish and also allows the bakery shops to capture where the customer is from (as my city in Japan is rapidly attracting more foreign tourists so the shop can find out from which countries the customers are visiting from) and eventually use the stored captured data to anayze what items are popular with customers from certain countries.

Why agents? --
Instead of making the purchase flow continuous routine flow on typical purchase touch panel finger movements of choosing among buttons to push (multiple choice), I thought interactive agent can capture customer information and purchase details via natural customer interaction and conversation with natural language processing

What I created --
I created the calculation agent with 3 custom function tools including the session state management for memory

If I had more time, this is what I'd do --
if I had more time, I would improve the agent by allowing the agent to capture mulitple purchase items at the same time.

Another thing is as the agent captures where the customer is from, I want the agent to greet the customer in their own native language (For an example, if the customer says he or she is from Germany, I want the agent to reply with a German greeting or a short message)
