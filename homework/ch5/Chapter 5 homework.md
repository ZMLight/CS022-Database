## Chapter 5 homework

**Name:** Zhang Yupeng

**Student ID:** 5130309468
 


$I(model) \leftarrow PC(model,speed)$ AND $speed \geq 3.00$


$I(hd) \leftarrow PC(model1,hd)$ AND $PC(model2,hd)$ AND $model1 <> model2$


$R(model) \leftarrow PC(moedl,speed)$ AND $speed \geq 2.80$

$R(model) \leftarrow Laptop(model,speed)$ AND $speed \geq 2.80$

$I(maker) \leftarrow Product(maker, model1)$ AND $Product(maker, model2)$ AND $R(model1)$ AND $R(model2)$ AND $model1 < > model2$

 


$I(a,b) \leftarrow S(b,c)$

$J(a,b) \leftarrow R(a,b)$

$K(a,b) \leftarrow I(a,b)$ AND $J(a,b)$
 