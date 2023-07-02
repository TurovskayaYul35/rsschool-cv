# Yuliya Turovskaya

## Contacts
    * email: turovskaya.yuliya35@gmail.com
    * skype: turon4ik
    * telegram: @Vasilllisssa

## Summary
   

## Skills
    HTML, CSS, JS, GIT

## Code example
```
function towelSort (matrix) {
    let array = [];

    if(matrix === undefined){
        return array;
    }

    for(i=0; i<matrix.length; i++){
        if(i%2 === 0){
            for(j=0; j<matrix[i].length; j++){
                array.push(matrix[i][j])
            }
        } else{
            for(j=matrix[i].length-1; j>=0; j--){
                array.push(matrix[i][j])
            }
        }
    }

    return array;
}
```

## Education

* Belarusian National Technical University, 2012
* Course JavaScript/DOM/Interfaces for beginners, [JavaScript.info](https://javascript.info/)


