<script>
  // Exercise 1
  let arr = [43, "what", 9, true, "cannot", false, "be", 3, true];

  const arrReverse = arr.reverse();
  console.log(arrReverse);

  // Exercise 2
  const n = 22;
  const arr2 = [];
  for (let i = 2; i <= n; i+=2) {
    console.log(i);
    arr2.push(i);
  }

  // Exercise 3
  let integers = [3, 5, 22, 5,  7,  2,  45, 75, 89, 21, 2]; // --> 276

  let sum = 0;

  for (let number of integers) {
    sum += number;
  }
</script>

<h1>Welcome to Tony's Loop exercise spoilers!</h1>

<h2>Exercise 1</h2>
<ul>
  {#each arrReverse as item}
    <li>{item}</li>
  {/each}
</ul>

<h2>Exercise 2</h2>
<ul>
  {#each arr2 as item}
     <li>{item}</li>
  {/each}
</ul>

<h2>Exercise 3</h2>
<p>The sum of all integers is: {sum}!</p>

<style>
  h1 {
    color: rebeccapurple;
  }
</style>