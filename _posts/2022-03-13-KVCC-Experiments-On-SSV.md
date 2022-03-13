



## 1.直接计算SSV的时候neighbor交集如何处理？

![image-20220217145645357](..\images\image-20220217145645357.png)

solution

![image-20220225081614778](..\images\image-20220225081614778.png)

## 2.如何更准确地利用lemma11, 12计算SSV？

![image-20220217145658098](..\images\image-20220217145658098.png)

## 3.怎么平衡计算SSV的花费与其带来的sweep的收益？

CA-AstroPh.txt	

k=11(20% kmax)

![image-20220225081653786](..\images\image-20220225081653786.png)

k=23(40% kmax)，compute SSV every step

![image-20220225100606184](..\images\image-20220225100606184.png)

compute SSV  once

![image-20220225101023937](..\images\image-20220225101023937.png)



VCCE：



![image-20220225100758816](..\images\image-20220225100758816.png)



只计算flow<k的LOC-CUT部分

![image-20220225101931632](..\images\image-20220225101931632.png)



只计算flow<k的LOC-CUT部分

![image-20220225102253043](..\images\image-20220225102253043.png)



flow>=k,

2491

2297

# ~~Conclusion~~

~~SSV能sweep的LOC-CUT大部分是flow<k的情况，这部分耗时不多，所以效果不显著~~



# New Data

CA-AstroPh.txt	

![image-20220302193632171](..\images\image-20220302193632171.png)

K=23



![image-20220301223551137](..\images\image-20220301223551137.png)



K=34

![image-20220301224006815](..\images\image-20220301224006815.png)

K=11

![image-20220301230102079](..\images\image-20220301230102079.png)

![image-20220304105700895](..\images\image-20220304105700895.png)





web-Stanford.txt

K=28(40%)

![image-20220302184635041](..\images\image-20220302184635041.png)

![image-20220302190112386](..\images\image-20220302190112386.png)





