# text-decoder
Python script to decode a txt file in pyramid format.

This function reads an encoded message from a .txt file and return its decoded version as a string. 

# Example

Say you have a txt file with words and corresponding numbers:

```bash
3 love
6 computers
2 dogs
4 cats
1 I
5 you
```

In this file, each line contains a number followed by a word. The task is to decode a hidden message based on the arrangement of these numbers into a "pyramid" structure. The pyramid increases by one number per line, like so:

```bash
 1
 2 3
4 5 6
```

The key to decoding the message is to use the words corresponding to the numbers at the end of each pyramid line (in this example, 1, 3, and 6). We ignore all the other words. Hence the decoded output is:

```bash
I love computers
```


