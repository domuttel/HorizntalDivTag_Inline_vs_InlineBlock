#Horizontal inline block centering vs. inline centering

1. Inline block centering can be done __only__ by creating a parent element that wraps the inline block div tag with ```text-allign: center;```. This __will not__ work if used within the inline block div tag. 
```
.parent-element-for-inline-block-centering {
  __text-align: center;__
}
.inline-block-centering {
  display: inline-block;
  height: 200px;
  width: 200px;
  background-color:red;
  margin: auto;
}
```
1. Inline centering can be done within the inline div tag with ```margin: auto;```.
```
.block-centering {
  background-color: red;
  height: 200px;
  width: 500px;
  __margin: auto;__
}
```
