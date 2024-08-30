Normal Text 
new line but we wont't get any new lines in the preview as this newline will be treated as a space only 

Put one extra empty line to add the newline to the the markdown.
There is also other way to achieve this is by adding two spaces  
To the end of previos line.

# Heading 1(H1)

## Heading 2(H2)

this is an example of how heading works in markdown as we keep on increasing the number of # in the markdown heading keeps becoming smaller.
###### Heading 6 (H6)
This is the smallest heading possible that is h6 in case of html

This is **Bold** and this is also __bold__.

This is _italic_ 

This is ***Bold and italic*** and this is also __*Bold and italic*__.

This is ~~StrickThoughed~~ .

Text is <mark>Hightlight</mark>. this is ==hightlight== but it didn't work in some cases.

x<sup>2</sup> and this is H<sub>2</sub>O

:smile: to add smileys

#### Code example 
This is `int x=11` and if we want to multiline code then we need to add ``` .
###### Example 1 :
```
#include<iostream>
using namespace std;

int main() {
  cout<<"Hello world!<<endl;
  return 0;
}
```
***Other way that we can use the show code is by using two and more indentation i.e. tabs***

    #include<iostream>
    using namespace std;

    int main() {
    cout<<"Hello world!<<endl;
    return 0;
    }
_But this is not a good way to achieve this_.

#### Note : we can also provide the language in which the code is written after ``` .
***_Example 3_*** : 

```cpp
#include<iostream>
using namespace std;

int main() {
  cout<<"Hello world!<<endl;
  return 0;
}
```
Now as we can see the code hightlight in the cpp syntax if we compare it with example 1.

#### Links and How it Works

[This is a link](https://github.com/) : we can provide the relative link and absoulte link of any webpages. Now we want to show the actual link as the name also then we can do this simply by doing this <https://google.com>  and https://www.youtube.com/ this way also achieve the same thing.

![Github logo](https://github.com/) : This image will be rendered if there is a image at the location specified.

> int main() {}
>>cout<<"Hello World""<<endl;
>>>return 0;

***How to put horizontal line :***

---
***
___

They should be atleast three in numbers .

## Rendering lists : 
#### Unordered lists can be redered using + * and - where as ordered lists can be rendered using any Number followed by period(.)

****Example :****
- Item 1
+ Item 2
* Item 3
- Item 4

1. Item1
2. Item2
2. Item3
1. Item4

### Now nesting lists

* Grocery
  1. Flour
  2. Breadcrumbs
  2. Rice
- Stationary
  1. Scale
  1. Notebook
      1. spiral
      1. Drawing
  1. Color palette

### Rendering tables





### Creating checklists or checkboxes

- [ ] Wake up at 5 A.M.
- [] Workout.
