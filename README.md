# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks(`)
- Not to be confused with quotation (')

```
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

```
- When you can should attempt to apply syntax highlighting to your codeblocks

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

```

- Make note of where the backtick button is located.
- It should appear above the tab key,
- but it may vary based on your keyboard type.

<img src="https://github.com/sanju2/github-docs-example/assets/41699526/7619999a-c39f-4a8d-a639-93cc6ce77b00" width="300px" height="200px" />

Good Cloud Engineers use codeblocks for both code & errors that appear in the console.

```bash
public class ExampleError {
    public static void main(String[] args) {
        String text = null;

        // Attempt to access a method or field on a null object
        int length = text.length();

        // The above line will result in a NullPointerException, and you will see the following error message in the console:

        // Exception in thread "main" java.lang.NullPointerException
        //   at ExampleError.main(ExampleError.java:6)
    }
}
```

> Here is an example of using a codeblock for and error that appear in bash.

## Step 2 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items.[^1]

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Use Emojis (Optional)

Github Flavored markdown (GFM) support emoji shortcodes.
Here are some examples

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lightning` | 🌩️ |

## Step 3 - how to create a table

You can use following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lightning` | 🌩️ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.[^2]

<img src="/assets/img2.jpg" width="300px" height="200px" />

[Secret Window Hidden Garden](secret-window/hidden-garden.md)

## References

- [ChatGPT](https://chat.openai.com/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#relative-links)
[^1] : [GFM - Tasks List}(https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- [GFM - Emoji Cheet Sheet](https://gist.github.com/rxaviers/7360908)
[^2] : [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)
