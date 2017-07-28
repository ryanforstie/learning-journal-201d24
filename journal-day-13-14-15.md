# July 27th, 2017

## Day 13-14-15

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

- The last lab we make an order form that when user inputed values it transfers to another page through local storage. So having 2 html pages and a js page for each one was super important.

- A few new book to read, Eloquent Javascript, Javascript the good parts, you dont know JS, eric elliots articles. Also some articles, the state of js in 2016, how it feels to learn javascript in 2016
