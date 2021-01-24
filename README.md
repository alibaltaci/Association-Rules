# Association Rules
![basket](https://user-images.githubusercontent.com/71599944/105632564-dba9a200-5e64-11eb-9839-f1996b0a1d34.png)

# Business Problem

What are Association Rules?

It is a rule-based machine learning technique used to find patterns (relationships, structures) in data.

You may have come across these applications in the following ways: "those who bought that product also bought this product" or "those who viewed that ad also looked at these ads" or "we created a playlist for you" or "the recommended video for the next video".

These scenarios are the most common scenarios we will encounter within the scope of e-commerce data science data mining studies.

Many e-commerce companies around the world or companies, platforms like Spotify, Amazon, Netflix use recommendation systems.

So what do these association analyzes do?

# Apriori Algorithm:

It is the most used method in this field.

Association rule analysis is performed by examining some metrics:

X: item Y: item N: total purchase

**Support:**

Support(X, Y) = Freq(X,Y)/N

**Confidence:**

Confidence(X, Y) = Freq(X,Y) / Freq(X)

**Lift:**

Lift = Support (X, Y) / ( Support(X) * Support(Y) )

# Let's interpret the table (for Grocery Store) 

![table](https://user-images.githubusercontent.com/71599944/105632730-d567f580-5e65-11eb-97bd-b9aa01e3d9d2.png)


* **0 (MILK - BREAD):**

Support: Milk and bread were observed together in 20% of shopping.

Confince: 80% of those who bought milk also bought bread.

Lift: Milk sales increase bread sales 1.23 times.

* **4 (MAGGIE - TEA):**

Support: Maggie and Tea were observed together in 20% of shopping.

Confince: 80% of those who bought Maggie also bought Tea.

Lift: Maggi sales increase Tea sales 2.29 times.

# REFERENCES

**Reference Notebook:** https://www.kaggle.com/mariekaram/apriori-association-rule

**Dataset:** https://www.kaggle.com/shazadudwadia/supermarket

**Articles:**

https://www.kdnuggets.com/2016/04/association-rules-apriori-algorithm-tutorial.html

https://michael.hahsler.net/research/recommender/associationrules.html

http://www.saedsayad.com/association_rules.htm

https://ab.org.tr/ab16/bildiri/46.pdf


