# 3 Key Takeaways About Markdown

This week we learned about how to further format instructions or content with Markdown
documents, here are 3 most interesting things I have learned about Markdown structure.

## Structuring lists

I have learned how to structure a list in both sequential and nonconsecutive order:

1. I learned I could begin by simply typing out "1." to begin formatting my list 
2. I found that Markdown automatically formats the following, and previous, numbers in a sequence by simply pressing "enter" between entries
3. Non-sequential lists use either a "*" or a "-" instead of any particular number.

An example of a non-sequential list may look like this:

Ingredients in a BLT:

* Bacon
* Tomato
* Lettuce
* Mayo

This is useful to me incase I ever want to use Markdown to compile a library of information
that contains sub-catagories more easily readable in a list format. This is also useful for if
I ever want to compose some instructions in my Markdown file.

## Code Samples

As somebody who does not intend on using back-end code for my career, I think it will be useful to 
understand how Markdown can help me communicate with coders for technical projects. So I appreciated
learning how to format code samples so my documentation could use some base examples of where things
go, or just what types of code to include in general. I have also found that it makes it much more
convenient for readers who are trying to navigate more complex instructions to install a program
offered via GitHub, where one is required to enter specific lines of code into one's command prompt to get
an element within a program to function properly.

For example I can insert code contained within three backticks "```"

```
print("Hello, world")
```

I  also think I would prefer to section code examples using the fence method rather than using four 
spaces, since it seperates content in a much more visible way in the editing UI, so I can clearly see
where the code begins and ends. I also do remember from some coding classes that it can be important to
put a certain number of spaces before particular lines, so I understand that using the four spaces method
could get confusing pretty quick, when there's just that one extra set of spaces to keep track of.


## Use of Images

I found challenging how to add images to my project, since Markdown does not have a simple UI to insert an image
as in usual, front end systems like Google Docs. I already knew somewhat of how to add an image using code where I could
redirect to the path and file name, but it took me a bit to learn how to create a path that I could use in MarkDown in general.
I ended up creating a separate file of "images" where I could insert whatever I wanted and reference it via code to add my images. 

So I learned doing this:

```
![tomato](/images/Tomato.png)
```

adds the tomato image I put in the dedicates "images" folder. This results in the image becoming visible.

![tomato](/images/Tomato.png)


Although this image is quite large and takes up too much of the screen, which could make my file difficult to read and just look unprofessional depending on
how I want to present this.

So I decided to look online and found that one could use HTML in Markdown to control the size of an image.

Here's my code:

```
<img src="/images/Tomato.png" alt="tomato" width="200"/>
```

Which results in this: <img src="/images/Tomato.png" alt="tomato" width="200"/>


### Conclusion

Overall, I learned that both online and class resources are helpful when learning how to add different types of informative content to your Markdown file.
GitHub has a somewhat odd way of incorperating images for somebody not accustomed to its system, but I was able to find a solution which made 
sense to me based on my previous knowlage of ensuring paths are all in the right place when utilizing external files in editing programs. I learned how to
add code examples for convenience in one's documentation and how to properly create lists for ease of reading using the Markdown format, and to make my information
clear and understandable both to the reader and myself.
