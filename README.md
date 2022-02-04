# repo_practice
# Making a Better README: It's MARKDOWN Time!
This is where I will implement various markdown techniques that can help improve README files.

---------------------------------

## Here is my first subheading:

In this section, I will try different text styles:
* Making an unordered list?
* **This should be bold text**
* *And this should be italicized*

This link contains a useful guide:
[Markdown Guide](https://www.markdownguide.org)

And here is some JavaScript code I wrote this morning to solve a warmup exercise in which a professor decides to use a specific method of rounding students' grades up. What a kind professor, rounding grades up:

```
function gradingStudents(grades) {
    for (let i=0; i<grades.length; i++) {
        if ((grades[i] > 37) && (grades[i] % 5 > 2)) {
                grades[i] = Math.ceil(grades[i] / 5) * 5;
        }
    }
    return grades;
}
```

## It's probably a good time for another subheading

Things are really taking shape now. Maybe here would be a good spot for an image or two.

Let's put them in a numbered list this time:

1. The list formatting is pretty straightforward

![A pleasant image](https://cache.desktopnexus.com/thumbseg/670/670481-bigthumbnail.jpg)

2. Plenty of space for space

![A space image](https://www.universetoday.com/wp-content/uploads/2007/03/2007-0305ngc253.thumbnail.jpg)