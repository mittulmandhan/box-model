# BOX MODEL

Every element in css is a box wether it is a text, div or span.CSS Box Model is a box that wraps around every HTML element.You need to know howbox model works in order to set the height and width of an element.

CSS Box Model consists of :
    ->Content
    ->Padding
    ->Border
    ->Margin

->Content: The content of the box, where text and images appear.

->Padding: Clears an area aroun the content.The padding is transparent.

->Border: A border is what goes around the padding and content.You can also say that border is the outline of an element.Unlike margin and padding it is not transparent.

->Margin: Clears the area outside the border. The margin is transparent.

When you set the height and width properties of an element with CSS,you just set the width and height of the content area.Height and width of content,padding,border and margin combined is the actual height and width of an element.

For example: The total width and height of the following div is 350px and 200px respectively.

div {
  width: 320px;
  height: 170px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}

Total element width = width + left padding + right padding + left border + right border + left margin + right margin
[320+10+10+5+5+0+0]=350

Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin
[170+10+10+5+5+0+0]=200