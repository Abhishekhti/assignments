## Counter without setInterval

Without using setInterval, try to code a counter in Javascript. There is a hint at the bottom of the file if you get stuck.




let i=1;
function counter(){
   console.log(i);
   i++;
   setTimeout(counter,1000);
}
setTimeout(counter,1000);



































































(Hint: setTimeout)