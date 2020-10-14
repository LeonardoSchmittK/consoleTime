# Console time 

---
     console.time();

     (function sumNumber(...values){
      return console.log(values.reduce((total,item)=>total+item,0))
     })(2*2,3)

     console.timeEnd();

---