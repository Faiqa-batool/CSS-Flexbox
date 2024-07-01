# CSS-Flexbox
This repository includes the practice code I implemented while learning CSS Flexbox

Flexbox is applied to position the elements easily </br>
We apply display: flex; to the parent div, so that the flexbox sets the position of the child divs </br>
### Before applying flexbox:

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/6c54749e-23c3-4f34-9c11-bd36dee25d1d)
</br>

### After Applying Flexbox:

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/8029c326-7a50-473d-ab19-ad5767f0a4d5)
</br>

### Justify-content : center; 

/flex-start /flex-end /space-berwen /space-evenly /space-around </br>
//align item horizontally

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/15c1a2e0-f2ac-465a-a39e-7cbbc1f18257)
</br>

### align-items: center; 

// align items vertically
</br>

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/6fc6a247-295f-4287-b678-fce3fb6314e2)

</br>

But it depends on flex-direction, that is row by default.</br>

### flex-direction: column;

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/aaa1cf8f-e975-438f-a60b-36414bda530c)

</br>

### flex-direction: column-reverse;

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/bef11961-3c1d-466c-a939-1ddbd203245e)
</br>

### flex-direction: row-reverse;

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/8b367864-fedc-4abd-a0c6-405f1194ef90)
</br>

### Flex-axes concept:

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/73bc6924-9ee3-433a-9e9e-9c55c9b3ccb9)
</br>
Justify-content works along main-axis
</br>

### flex-wrap: wrap;

### align-content: center;

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/9d067448-0b59-45dd-9735-72a15b50ded4)
</br>

There is no justify-items in flexbox

### flex-flow property:

flex-flow: <flex-direction> <flex-wrap>
</br>
the above was container properties. Now we will discuss item properties.
</br>

### Order property:

Change item’s order by using css, the higher the order, the last the item  //bd me show hoga </br>
Order 1 will come first, after all the non-order items</br>
Default order is 0, that’s why all the other items will come first.</br>

### flex-grow:

flex-grow:1;  // all the items take equal space in the container, full width. </br>

### flex-shrink:2;

Ability of a flexbox to shrink </br>
2 means--> it will shrink with the double speed</br>

### align-self:

align-self --> only that particular item of flexbox will align separately</br>

#### align-self: flex-end;

#### align-self: flex-start;

![image](https://github.com/Faiqa-batool/CSS-Flexbox/assets/115587465/80ab4c3f-e180-4907-9a8f-e573387fd29b)

