# Bogdan Ivanilov

### Junior Frontend Developer

****

## Contact information:

* **Discord**: BogdanIvanilov#3232
* **Telegram**: @BogdanIvanilov

## Some information about me

My name is Bogdan, I am 14yo. My way in programming started with python, I studied it for about two years without much achievements. My first programms: a calculator, a search for products in different stores, a program showing the dollar and euro exchange rates. On the First of June, 2022, I started studying at rsschool for the profession of frontend developer. Graduated from stage 0 with a certificate and moved to stage 1.

## Skills:

* **HTML**
* **CSS**
* **JavaScript**
* **Git&Github**

## Courses:

* **RS Schools Course ""JavaScript/Front-end. Stage 0"**

[Certificate](https://app.rs.school/certificate/5vfeln8y)

* **Rs Schools Course ""JavaScript/Front-end. Stage 1"(in progress)**

## Code example

Task: To do this, you must first count the 'mini-wins' on your ticket. Each subarray has both a string and a number within it. If the character code of any of the characters in the string matches the number, you get a mini win. Note you can only have one mini win per sub array.

Once you have counted all of your mini wins, compare that number to the other input provied (win). If your total is more than or equal to (win), return 'Winner!'. Else return 'Loser!'.

URL: https://www.codewars.com/kata/57f625992f4d53c24200070e

```
function bingo(ticket, win){
	let miniwins = 0;
	for(let a of ticket){
		if(a[0].includes(String.fromCharCode(a[1]))){
			miniwins++;
		}
	}
	if(miniwins >= win){
		return 'Winner!';
	}else{
		return 'Loser!';
	}
}
```

## Languages:

* **Russian(native)**
* **English(pre-intermediate)**
* **Ukrainian(basic)**
