# Deep Interest Network for Click-Through Rate Prediction

<img src="https://raw.githubusercontent.com/sxy22/notes_pic/main/image-20211228155707880.png" alt="image-20211228155707880"  />



## Base Model(Embedding&MLP)

![image-20211228160008265](https://raw.githubusercontent.com/sxy22/notes_pic/main/image-20211228160008265.png)

## The structure of Deep Interest Network

Instead of expressing all user’sdiverse interests with the same vector, DIN adaptively calculatethe representation vector of user interests by taking into considerationthe relevance of historical behaviors w.r.t. candidate ad. Thisrepresentation vector varies over different ads.



![image-20211228163218777](https://raw.githubusercontent.com/sxy22/notes_pic/main/image-20211228163218777.png)

+ 这里的ei好像是第i个good的embedding，与上面的记号不同



# TRAINING TECHNIQUES

## Mini-batch Aware Regularization

![image-20211229153900945](https://raw.githubusercontent.com/sxy22/notes_pic/main/image-20211229153900945.png)

![image-20211229154553028](https://raw.githubusercontent.com/sxy22/notes_pic/main/image-20211229154553028.png)

## Data Adaptive Activation Function

![image-20211229154805730](https://raw.githubusercontent.com/sxy22/notes_pic/main/image-20211229154805730.png)

![image-20211229154902435](https://raw.githubusercontent.com/sxy22/notes_pic/main/image-20211229154902435.png)