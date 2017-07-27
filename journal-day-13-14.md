# July 27th, 2017

## Day 13-14

- Added in a way to track and store local data.
if(localStorage.length) = 0 than it moves to the else statement if(localStorage.length) = 1 then its true.

- if(localStorage.length) {
  console.log('There is local storage!');
  ProductImage.all = JSON.parse(localStorage.ProductImage);
} else {
  for(var i = 0; i < ProductImage.allNames.length; i++) {
    new ProductImage(ProductImage.allNames[i]);
  }
  console.log('There is no local storage!');
};
