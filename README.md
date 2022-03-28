# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (dog in person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

| Input                                                            | Output        |
| -----                                                            | ------        |
|  {name: "Brad", dogs: ["Banjo","Rainy","Laney","Banjo"] ,"Banjo" | {dog: "Banjo"}| 
|  {name:"Tiffany", dogs: ["Elsa","Molly","Annie"], "Elsa"        | {dog: "Elsa" }  | 


<table>
  <tr>
    <th>What does this program do?</th>
    <td>The function takes a person's name and a pet name and looks  for the Person's dogs to see if they have a dog and if that persons dog name matches the pet name given it returns dog. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
