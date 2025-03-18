# Code/Monospace Text ion Markdown

To add code or monospaced text in a markdown file, we need to write it between \`  \`.

`code text`

This only works for one line of text.

For multiple lines of text, we need to open and close a "block" using three backticks ( \` \` \` ):


``` 

code
also code
more code

```

For code highlighting, only add the name of the language after the triple backticks ( \` \` \` ):

``` Java

public static void main(String[] args) {
  System.out.println("Hello World!");
}

```