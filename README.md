# Ali_Khatami_JS3(Learning from the video of Dave Gray)

### Strings

![j37](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/a5240516-ca64-406d-a916-8c7d89997db2)

Here click the extension icon <br>

![j38](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/87e44c40-4fc3-437b-bf64-3f438d8fbc73)

Then here we will write Live server and install the extension <br>

![j39](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/3c8d5cd1-66ef-4f9f-9c55-4fbea185ef92)

Then we will click here Go Live option <br>

![j40](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/ec7d64b5-5506-46a3-938f-5531383240b7)

Here then new webpage will come and here 127.0.0.1 is the internal ip address of the computer <br>

It can also be referred to as the localhost <br>

The ip address will be followed by a colon and a port number <br>

The benefit of live server extension is that browser will reload our changes every time we saved <br>

We need not always go to browser window to click the refresh button <br>


![j1](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/374335aa-1ec0-40d4-9473-9f6c6d85f997)

In the above string variable we use the keyword ```const``` <br>

We are not using the keyword ```let``` because we are not gonna reassign the <br>
value of this variable <br>

![j2](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/78eeabb5-d07e-4eee-92a7-29010c1f1ffd)

by usig the above code we gonna look at the length property <br>

The length proprety will return the number of character in the string <br>

![j3](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/5d168ae6-789e-4ba2-b8ba-3f6079cdc802)


here we can see it returned ```7``` as output <br>

![j4](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/7224e476-6e31-484a-a461-6cde22c939c4)
 here now we find the length property of a sentence 

 Now we look at the string methods <br>

 
The string methods use dot notataion <br>


![j5](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/ffe4b5c8-13a7-40bc-92d0-d76029ceb824)

the code is given below :

```
const myVariable = "Khatami";

console.log(myVariable.charAt(2));

```

the character at method above returns the character of the particular posistion we provide <br>


It is to note that position counts start at zero intesd of 1 <br>


![j6](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/a1fc19a0-bc5f-4eec-ad2f-299fb7e034fb)

code :
```
console.log(myVariable.indexOf("ami"));

```

the above returns the position of the first occurance within a string <br>


![j7](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/89c03891-b66c-4b6f-96f4-1f430dd581be)
here one ```i``` at 2nd position and another ```i``` at 5th position<br>
so it gonna return the position of ```i``` at 2nd <br>

![j8](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/d59e211c-113e-49a2-bef2-2340e984ffee)

now if here we use ```iam``` it will return 5 <br>






![j9](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/92130140-921c-490b-8ead-86fafe5bccba)


The slice method accepts staring and ending position parameter and returns character <br>
from the staring postion to the ending position <br>

![j10](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/80fcdd44-fd25-4d24-8170-a7c50442f2f4)

if the ending posutuion is not provided it will return all characters from <br>
the staring position to the ending position <br>

![j11](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/d25fb012-7b96-4387-89a2-ec8e432a8eb0)
Code:
```
console.log(myVariable.toUpperCase());

```

the above makes  all charcters of the string to Uppercase and it does not require  a parameter <br>
but requires a parantheses <br>


![j12](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/9a004dc9-a838-4c1d-9cc7-464242304227)

Code:
```
console.log(myVariable.toLowerCase());

```
the above returns all character of the string to lowercase <br>


![j13](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/57b44b48-9cf7-4890-84d0-de8a371962ca)

Code:

```
console.log(myVariable.includes("aja"));

```

the above returns booolean if any character or any  group of character is not availabr it will return false <br>


![j14](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/5da9396d-a4f5-422a-a56d-1d0fb8698d1a)

code:

```
console.log(myVariable.split("t"));

```
here spilt method will split the string based onn the character we provide <br>

![j16](https://github.com/C191068/Ali_Khatami_JS3/assets/89090776/1d63eddd-430b-4d45-873f-413ea08bb6cf)

if we give only empty quote it will give each character as a separate string in the resulting array <br>

















