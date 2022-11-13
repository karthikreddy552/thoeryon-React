# thoeryon-React
1.what is the difference between Props and State?
A.State:To Maintain the data inside the component.
  prop:Its is used to pass the data to the component
2.Explain the useState API?
A.The useState() is a Hook that allows you to have state variables in functional components . so basically useState is the ability to encapsulate local state in a functional component.
3.Explain the how map, filter, reduce work ?
A.map → Executes a function on each element of an array. Every element of the array is passed to the callback function and returns a new array with the same length.
 filter → Remove items which don't satisfy a condition.
 Reduce → Creates a single value from elements of Array.
 4.Create your own map, filter, reducer methods and attach it to an array using prototype chain?
 A.ForMap:  const numbers = [1, 2, 3, 4];
            const doubled = numbers.map(item => item * 2);
            console.log(doubled); // [2, 4, 6, 8];
   for Filter: const numbers = [1, 2, 3, 4];
               const evens = numbers.filter(item => item % 2 === 0);
               console.log(evens); // [2, 4]
               
   for reduce: const numbers = [1, 2, 3, 4];
               const sum = numbers.reduce(function (result, item) {
               return result + item;
               }, 0);
               console.log(sum); // 10
