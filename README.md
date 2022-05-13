# Blocto - localStorage - Safari Issue:

I've discovered this issue on iOS and Mac Safari with blocto when using localStorage config, it works on Chrome. (Haven't tested other browsers)

1. ```cd``` into dir
2. ```npm i```
3. ```npm start```
4. open safari and go to ```localhost:3000```
6. login with blocto (connect)
7. try clicking <b>update</b> number -> blocto screen should pop up normally
8. close safari
9. open safari and go to ```localhost:3000```
10. try pressing <b>update</b> number again -> (blocto acts as it's logged in but confirmation screen is spinning forever)

![image](https://user-images.githubusercontent.com/80688826/168252292-d2273061-10e1-4a2b-a3c1-127a53b151b1.png)

