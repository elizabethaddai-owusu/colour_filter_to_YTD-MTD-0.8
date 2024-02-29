# colour_filter_to_YTD-MTD-0.8
I updated a logic that set the colour YTP/MTD rates that are &lt;80% to red.  

## issue at hand
Chemical and Additives MTD growth rate is above 80%, but for YTD it is less than 80% so it should be red.



![image](https://github.com/elizabethaddai-owusu/colour_filter_to_YTD-MTD-0.8/assets/80754883/b7fa204b-513b-454c-ba00-8e79edb6c716)



![image](https://github.com/elizabethaddai-owusu/colour_filter_to_YTD-MTD-0.8/assets/80754883/7dc99500-a4a1-4f64-9f1a-0093f8f0416e)


This is because the used AND operation means the two conditions should be true before it comes as red, but that is not what we want. 


![image](https://github.com/elizabethaddai-owusu/colour_filter_to_YTD-MTD-0.8/assets/80754883/e09cda22-ec6e-4fac-ad68-c2c070cc4400)




## solution


For the updated logic, the condition will be applied independently to each MTD/YTP if it is true, i.e if each YTD/MTD is <80% independently before the color will show.


![image](https://github.com/elizabethaddai-owusu/colour_filter_to_YTD-MTD-0.8/assets/80754883/b5146981-cef7-403e-a373-e67704bef2ed)

