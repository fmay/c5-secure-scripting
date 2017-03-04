Now let's play with the `grep` command.

On the command line, enter the following command.

```
grep 'verse' *
```

This searches for the word `verse` in all the files in the current folder. You will see it outputs

```
repeat.sh:cat verse1.txt
```

This is telling you that it found it in the file `repeat.sh` and it then shows the whole line that contains the word.

```
cat verse1.txt
```

If you open up `repeat.sh` you will indeed see it there.