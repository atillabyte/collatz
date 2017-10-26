## The Collatz Conjecture
```javascript
$$=(_,$)=>_<$?_:$$(_-$,$);
$=(_,_$,__)=>__>~~[]?$(_+_$,_$,__+~[]):_;
$_=(_,$,__)=>_<$?__:$_(_-$,$,__-~[]);
__=(_,_$)=>_==-~[]?_$:__($$(_,-(~[]+~[]))==~~[]?$_(_,-(~[]+~[]),~~[]):$(~~[],_,-(~[]+~[]+~[]))-~[],_$-~[]);
__(100,0);
```


##### because, why not?
```brainfuck
+++++ +++++[>+++++ +++++<-]>>>++<<
[[->+>-[>+>>]>[+[-<+>]>+>>]<<<<<<]
>>[-]<[-]>>[>>+<<-]>>>[-]+>[-]
<<[<[>>>>++<<<<-]>>>>+
[<<<<<<<<+++>>>>>>>>-]<<<<<<<<+>>>>>-]>
[<<[<<<<+>>>>-]>>->]<<<<<<<
->[-]+>[-]<<[+>-]>[<[-]>->]<<>>++<<
<+>]+<
```

##### HAI CAN HAS COLLATZ?
```lolcode
HAI 1.2
	VISIBLE "GIMME INPUT PLS: ", I HAS A HOI ITZ 0, GIMMEH HOI
	
	I HAS A COUNTR ITZ 0
	IM IN YR LUPZ UPPIN YR COUNTZ WILE DIFFRINT HOI AN 1
		BOTH SAEM MOD OF HOI AN 2 AN 0, O RLY?
			YA RLY, HOI R QUOSHUNT OF HOI AN 2
			NO WAI, HOI R SUM OF PRODUKT OF HOI AN 3 AN 1
		OIC, COUNTR R COUNTZ
	IM OUTTA YR LUPZ	
	VISIBLE SUM OF COUNTR AN 1
KTHXBYE 
```