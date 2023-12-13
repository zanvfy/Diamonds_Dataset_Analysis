# Diamonds Dataset Analysis

## **Abstract**

Diamonds are solid form of the element carbon which are arranaged in a crystal structure. A diamond is one of the best known and most sought after gemstones. Diamonds have been used as jewellery .Polished diamonds prices vary widely depending on carat, color , clarity and cut sometimes referred as the 4Cs. In contrast to precious metal, there is no universal price per gram for diamonds. Rough diamond has been historically impacting the mining companies .The industry is now more distrubuted resulting in a higher percentage of diamond sales taking place in the form of auctions and other forms of open-market sales. Since Diamonds varies with price we consider linear regression in this project.


## **Objective**

To analyze the price of the diamond dataset with respect to parameters such as carat, cut, clarity, color, depth and volume of diamond. It also determines the importance of those parameters and variations considering various factor.

## **Hypothesis**
* The price value might defer due to variation in cut, clarity and carat.
* The price would have no effect on variation in color.
* The table(avg percentage of width) of diamond doesn’t effect with other parameters.
* The depth may vary with respect to clarity and hence vary with price.
* The carat value has the most significant role

## **Inference**
While doing the project we estimated that the y and z can also play a vital role the pricing.On further investigation we get to know that the parameter y and z does not contribute to the price as the R sq value does not change in its presence or absence.
Besides the above stated hypothesis we also considered that depth might play as a factor in contributing towards the price of the diamond. This hypothesis was proved wrong as the R sq value does not change with its presence or absence.

## **Conclusion**
With the onset of the project the parameter carat was considered the most essential phenomena in contributing to the price.This hypothesis proved to be correct due to the variation of the R sq value(decrease) in dataset that included and not included carat for its analysis.
Furthermore we also stated that the cut, clarity plays a vital role in the pricing. This was proved wrong due to the constant value of R sq.
Apart from this we concluded that the colour does not play a factor in the pricing thus proving our stated hypothesis correct.
The last possibility that was considered was the non-contribution of table towards the value. This hypothesis was proved wrong due to variation in the R sq value in its presence and absence.

### Note: This analysis is for the given dataset only, in real world the analysis might come out different from our conclusion