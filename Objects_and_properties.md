# Objects and Properties

1. In Arrays order matters a lot but in object it doesn't.

2. In objects we use {} but in arrays we use [].

3. declaring an object  
    > var jane = new object();  
    > jane.firstName = 'Jane';  
    > jane['lastName'] = 'Smith';  
    
4. From the above example we can add the element to the object in 2 ways ***jane.firstName*** and ***jane['lastName']***.

5. Also we can create a object literal using
    > var john = {
    >     firstName : 'John';
    >     lastName : 'Smith';
    >     Job : 'teacher';
    >  }
    
6. we can access the elements from objects using ` console.log(john.firstName); or console.log(john['lastName']); `

7. We can also mutate the object using ` john.job = 'designer'; or john['job'] = 'designer'; `
