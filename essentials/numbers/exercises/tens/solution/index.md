---
title: Solution to ‘Number of tens’
---

{% include menu.html %}

This is how you can solve the task.

## Code

```raku
my $n = prompt 'Enter a positive integer number: ';

say ($n % 100) div 10;
```

🦋 You can find the full code in the file [tens.raku](https://github.com/ash/raku-course/blob/master/exercises/numbers/tens.raku).

## Output

Run the program and test a few different cases:

* A three-digit round number such as 120;
* A multiple of 100, for example, 400;
* A number which is bigger than 10 but smaller than 100.
* A number less than 10.

For number 234, the program’s output looks like this:

```console
$ raku exercises/numbers/tens.raku
Enter a positive integer number: 234
3
```

## Comments

In this solution, the combination of the modulo `%` and integer division `div` is used again.

Notice the space before the opening parenthesis. It has to be there; otherwise, you get a syntax error. We’ll return to [this aspect](/essentials/more-on-functions/mind-the-space) of Raku in the section about functions, but for now, type the code as shown above or add another pair of parentheses to surround the argument of the function — in this case, no space is needed:

```raku
    say(($n % 100) div 10);
```

{% include nav.html %}
