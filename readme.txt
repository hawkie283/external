CSS PROPRIETY
1 ELEMENT <------ style1,2,3
same weight(tag s tag,class vs class id vs id)
li{
    color:red;

}
...
li{
    color:green;
}
LAST-WINS
--------------------
<p class="first texts">lorem....</p>
----------------
.first{
    color:white;

}
.texts{
    color:green;
}
2.SIMPLE PRIORITY RULE
Inline>#id>.class>:pseudo>tag>parent>default(stilul primit by default de browser)
Cu cit stilul dat este mai apropiat de element,cu atit este mai prioritar.

3.COMPLEX SELECTORS
(css specifity search google imagine) inlinestyle =1000puncte id=100puncte class atribute psuedo=10p element=1 punct
#container .content .col p{
   //121 puncte
}
#container div .col p{
    //112 puncte
}
