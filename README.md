# Leasup PHP coding test

## Introduction

This test is designed to not be particularly hard on purpose. You can therefore dedicate some time on the error management part as well as the readability of your code.

You are free to use any external resources (except AI tools like Github Copilot or ChatGPT) to complete the task. You might need [https://php.net/](https://php.net/).

## The task

You are tasked to write a program that can navigate through client directories and get the size of each file.

The final output of your program should be an array of key/value with the key corresponding to the name of the client (given by the name of the file) and the value being the size in bytes (as shown below).

You must "handle" errors by displaying error (`[E]`) or information (`[I]`) messages. Feel free to reuse the one given in the output below.

At the end of the execution your output should look like this:

```
$> php main.php
[I] Client folder client3 is empty.
array(3) {
  ["client3"]=>
  int(0)
  ["client2"]=>
  int(16)
  ["client1"]=>
  int(17932293)
}
-- -- -- --
[E] Empty or incorrect folder to scan.
```

## Execution

First of all, you should clone this repository.
Then delete the `.gitkeep` file inside `for-the-task/clients/client3`.

In order to complete this task, use the `main.php` file in this repository and complete the "`task`" function.

For running the program, you can just execute in a shell of your choice:
```shell
$> php main.php
```
