# SVMParamerterOptimization
This project aims to explore the effectiveness of Support Vector Machines (SVM) in solving classification problems, with a focus on parameter optimization. In this project, we have taken a dataset and created 10 random samples to train and test our SVM model. Our goal was to identify the best SVM parameters that can yield the highest accuracy for each of the 10 samples.

We used the Scikit-learn library in Python to implement our SVM model and optimize its parameters. The dataset we used for this project was Mushroom Data Set. After splitting the dataset into 10 random samples, we trained and tested our SVM model using various parameter combinations.

The final result of our project is a table that shows the accuracy of each of the 10 samples, along with the best SVM parameters that yielded the highest accuracy. This table can be used as a reference for future classification problems that require SVM parameter optimization.

Feel free to explore the code and results in this repository, and please let us know if you have any questions or feedback.
# Dataset Description

This data set includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family (pp. 500-525). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like leaflets three, let it be'' for Poisonous Oak and Ivy.
# Attribute Information

   1. cap-shape: bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s
2. cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s
3. cap-color: brown=n,buff=b,cinnamon=c,gray=g,green=r, pink=p,purple=u,red=e,white=w,yellow=y
4. bruises?: bruises=t,no=f
5. odor: almond=a,anise=l,creosote=c,fishy=y,foul=f, musty=m,none=n,pungent=p,spicy=s
6. gill-attachment: attached=a,descending=d,free=f,notched=n
7. gill-spacing: close=c,crowded=w,distant=d
8. gill-size: broad=b,narrow=n
9. gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e, white=w,yellow=y
10. stalk-shape: enlarging=e,tapering=t
11. stalk-root: bulbous=b,club=c,cup=u,equal=e, rhizomorphs=z,rooted=r,missing=?
12. stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s
13. stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s
14. stalk-color-above-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o, pink=p,red=e,white=w,yellow=y
15. stalk-color-below-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o, pink=p,red=e,white=w,yellow=y
16. veil-type: partial=p,universal=u
17. veil-color: brown=n,orange=o,white=w,yellow=y
18. ring-number: none=n,one=o,two=t
19. ring-type: cobwebby=c,evanescent=e,flaring=f,large=l, none=n,pendant=p,sheathing=s,zone=z
20. spore-print-color: black=k,brown=n,buff=b,chocolate=h,green=r, orange=o,purple=u,white=w,yellow=y
21. population: abundant=a,clustered=c,numerous=n, scattered=s,several=v,solitary=y
22. habitat: grasses=g,leaves=l,meadows=m,paths=p, urban=u,waste=w,woods=d

# Source

Origin:

Mushroom records drawn from The Audubon Society Field Guide to North American Mushrooms (1981). G. H. Lincoff (Pres.), New York: Alfred A. Knopf

Donor:

Jeff Schlimmer (Jeffrey.Schlimmer '@' a.gp.cs.cmu.edu)

# Results

After applying SVM on the 10 random samples of the dataset, we were able to achieve an accuracy of 48.1%. We also identified the best SVM parameters for each sample, which allowed us to achieve even higher accuracy in some cases.

Furthermore, we conducted a sensitivity analysis on the dataset to determine which features had the greatest impact on the accuracy of the model.

Overall, our project demonstrates the effectiveness of SVM for predicting the outcome of our model. Our results can be used to inform future research on this topic and may also have practical applications for researchers for studying more in this field.

# Comparitive performance of Optimized-SVM with 10 samples
Sample 	Accuracy 	    Kernel 	Nu 	    C
1   	0.7528 	         rbf     0.5 	1
2 	    0.7339 	        linear 	0.1 	2
3 	    0.7892 	        rbf 	0.1 	1
4 	    0.7839      	poly 	0.5 	1
5 	    0.7889      	poly 	0.1 	3
6 	    0.7123      	linear 	0.5 	2
7 	    0.7345      	sigmoid 0.2 	1
8 	    0.7929      	linear 	0.1 	1
9 	    0.7555 	        rbf 	0.1 	2
10  	0.7833 	        sigmoid 0.1 	3

# Convergence graph of best SVM(Sample 3)
![image](https://user-images.githubusercontent.com/90544418/233167137-1bcd8e9a-8559-4049-9744-9dd1de9dd13b.png)

