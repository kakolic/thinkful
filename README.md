this is how you write a function

```js
function newSkills () {

}

writing for loops  and function and scope 
function getTotalGoals (goals ){
    let sum = 0;
    for (let i= 0; i < goals.length; i++) {
        sum = sum + goals[i];
    }
    return sum;
}
getTotalGoals[(0,1,2]);


multiple Loops


function CountLikesByTopic(people.topic){
    let counter = 0;

    for (let i= 0; i < people.length; i++) {
        for (j=0; j < people[i].likes.length; j++){
            if (people[i]. topic[j]=== topic) {
                counter++; 
            }
            return counter;
        }
        
    } 
}

