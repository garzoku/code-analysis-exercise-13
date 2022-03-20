# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input                  | Output                                              |
| ---------------------- | --------------------------------------------------- |
| Kurt, Garzone, 33      |``{firstName: "Kurt", lastName: "Garzone", age: 33}``|  
|	                       |    ``age: 33``                                      | 
|	                       |    ``firstName: "Kurt"``                            |
|	                       |    ``lastName: "Garzone"``                          |
| John, Smith, 20        |``{firstName: "John", lastName: "Smith", age: 20}``  | 
|	                       |    ``age: 20``                                      |
|	                       |    ``firstName: "John"``                            | 
|	                       |    ``lastName: "Smith"``                            |
| Bubba, Gump, 45        |``{firstName: "Bubba", lastName: "Gump", age: 45}``  |
|	                       |    ``age: 45``                                      |
|	                       |    ``firstName: "Bubba"``                           |
|	                       |    ``lastName: "Gump"``                             |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>1). The function accepts 3 arguments: firstName, lastName, age.<br>
2). The const variable called "person" is declared as an object with 3 attributes.<br>
3). The value of firstName is assigned to the attribute called firstName, the value of lastName is assigned to the attribute called lastName, the value of age is assigned to the attribute called age.<br>
4). The function returns the object named "person"  including its saved attributes.<br>
Summary: This function saves a person's first name, last name, and age to an object. It's an essential part of any "call to action" whereby the user is required to create an account.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
