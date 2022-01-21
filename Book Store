const bookInfo = [
  {
  bookId: "1",
  bookTitle: "Start with why",
  author: "Simon Sinek",
  price: "80.0",
  quantity: "13"
},
{
  bookId: "2",
  bookTitle: "But how do it know",
  author: "Robert Cecil Martin",
  price: "59.9",
  quantity: "22"
},
{
  bookId: "3",
  bookTitle: "Clean Code",
  author: "J. Clark Scott",     
  price: "50.0",
  quantity: "5"
},
{
  bookId: "4",
  bookTitle: "Zero to One",
  author: "Peter Thiel",
  price: "45.0",
  quantity: "12"
},
{
  bookId: "5",
  bookTitle: "you don\'t know JS",
  author: "Kyle Simpson",
  price: "39.9",
  quantity: "9"
}
]

for(j=0; j < bookInfo.length ; j++)
{
  let inputId = prompt("search by id ")
  if(bookInfo[j].bookId == inputId)
  console.log(bookInfo[j].bookTitle + ' , ' + bookInfo[j].author)
  else {console.log("check again")}
}

for(i=0; i < bookInfo.length ; i++)
{
  let inputTitle = prompt("search by title ")
  if(bookInfo[i].bookTitle.includes(inputTitle))
  console.log(bookInfo[i].bookId + ' , ' + bookInfo[i].author)
  else {console.log("check again")}
}

for(k=0; k < bookInfo.length ; k++)
{
  let inputPrice = prompt("search by price ")
  if(bookInfo[k].price.includes(inputPrice))
  console.log(bookInfo[k].bookId + ' , ' + bookInfo[k].author)
  else {console.log("check again")}
}

function selling ( array, title, bookQuantity, balance ) {
  for( let i=0 ; i<array.length ; i++){
if( array[i].bookTitle == title && array[i].quantity >= bookQuantity ){
let totalPrice = bookQuantity * array[i].price
if(totalPrice <= balance){array[i].quantity -= bookQuantity;
if(bookQuantity >= 2){
  return `sale invoice: Your books: '${array[i].bookTitle}', it is ${totalPrice}SR, Was purchased ${bookQuantity} pieces`;} 
else{
    return `sale invoice: Your book: '${array[i].bookTitle}', it is ${totalPrice}SR, 
Was purchased ${bookQuantity} piece`;}} 
else{
    return 'Your balance it\'s not enough'}} 
else if(array[i].bookTitle !== title) {
  return 'Sorry, We didn\'t found it. Please sure your book title'} else if(array[i].quantity < bookQuantity){
return 'Sorry, We don\'t have quantity enough'}}};

let balance = 200;
console.log(selling(bookInfo, 'Start with why', 1, balance));
