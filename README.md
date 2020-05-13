[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]


<p align="center">
  <img src="https://i.imgur.com/Ukcci0S.png" width="80" height="80">
  <h3 align="center">Monty</h3>

  <p align="center">
        <em>C - Stacks, Queues - LIFO, FIFO</em>
    <br /><br />
    <a href="https://github.com/AlejoCasti/monty/issues">Report Bug</a>
    ·
    <a href="https://github.com/AlejoCasti/monty/issues">Request Feature</a>
  </p>
</p>

### About the project
The goal of this project is to create an interpreter for Monty ByteCodes files.

### Resources
...

### Usage C scripts
```sh
gcc -Wall -Werror -Wextra -pedantic *.c -o monty
./monty <file>
```

</br>

## Commands

| Opcode | Description |
|---------------- | -----------|
|push   | Pushes an element to stack |
|pall   | Prints all elements in stack |
|pint   | Prints first stack node|
|pop    | Removes removes last stack node |
|swap   | Inverts stack nodes positions |
|add    | Adds top two stack elements|
|nop    | Ignores command |
|sub    | Subtracts top two stack elements |
|div    | Divides top two stack elements |
|mul | Multiplies top two stack elements|
|mod    | Computes division remainder from top two stack elements|
|#      | Comments instruction|
|pchar  | Prints first stack element in ascii value |
|pstr   | Prints all stack elements in ascii value |
|rotl   | Sends first stack element to last position |
|rotr   | Send last stack element to first position |
|stack  | Sets stack format to LIFO (Last In First Out) |
|queue  | Sets stack format to FIFO (First In, First Out) |

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Authors
[Alejandro Castiblanco](https://www.linkedin.com/in/alejandro-castiblanco-prieto/)  
[Fredy Acuña](https://www.linkedin.com/in/fredhii/)

[contributors-shield]: https://img.shields.io/github/contributors/AlejoCasti/monty?style=flat-square
[contributors-url]: https://github.com/AlejoCasti/monty/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AlejoCasti/monty.svg?style=flat-square
[forks-url]: https://github.com/AlejoCasti/monty/network/members
[stars-shield]: https://img.shields.io/github/stars/AlejoCasti/monty.svg?style=flat-square
[stars-url]: https://github.com/AlejoCasti/monty/stargazers
[issues-shield]: https://img.shields.io/github/issues/AlejoCasti/monty?style=flat-square
[issues-url]: https://github.com/AlejoCasti/monty/issues
