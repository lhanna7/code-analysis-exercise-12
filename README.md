# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (currentColor){
  if (currentColor === "green"){
    nextColor = "yellow"
  } else if (currentColor === "yellow"){
    nextColor = 'red'
  } else if (currentColor === "red"){
    nextColor = 'green'
  }

  return nextColor
}
```

| Input | Output |
| ----- | ------ |
| green      |   "yellow"     | 
| yellow     |    "red"   | 
|  blue    |  undefined   | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program is basically a stoplight. A stoplight will never go from green to red, just like this program wouldn't. I also assume there can't be a defined output for blue since it's not listed in an else if and there are no other else's. This function takes the input, currentColor, and first looks to see if it ===green. If so, then the return will be yellow. If the color input wasn't green, then the function looks if ===yellow. If so, then the return will be red. If the color input wasn't green or yellow, then the function looks if ===red. If so, then the return will be green.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
