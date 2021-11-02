# List of Topics

In this collaborative repository we will go deep into NodeJS concepts in depth along with hands on implementation of concepts learned. 

## Introduction to NodeJS

What is NodeJS?  
Why to use nodejs  
How NodeJS works under the hood  

## Asynchronous vs Synchronous Communication

![1618364613028](https://user-images.githubusercontent.com/8051789/139827734-66dc3782-2999-404a-b119-38ab05600379.png)

### Asynchronous
Asynchronous is also known as non blocking, In Asynchronous communication we can move to another task before the previous one finishes.

  - In asynchronous communication data is sent in byte or character.
  - Asynchronous communication is slow.
  - Asynchronous communication is economical.
  - In Asynchronous communication there is gap present between data.

#### Examples
  - In Person Meeting
  - Phone Call
  - Video Conferences (Zoom)

### Synchronous
Synchronous is also known as blocking, In Synchronous Communication tasks are performed one at a time, when one is completed the following is unblocked. We have to wait for a task to finish to move to the next one.

  - In synchronous communication data is sent in blocks or frames
  - Synchronous communication is fast.
  - Synchronous communication is costly.
  - In synchronous communication there is no gap present between data.
  - Efficient use of transmission line is done in synchronous transmission.

#### Examples
  - Email
  - Text Messaging
  - Direct Messaging (Whatsapp, Twitter or Facebook)
  - Video Messaging (Loom)

## Callbacks

In computer programming a callback is also know as call after function, its executable code that is passed as an argument to other code.
Callback also called higher order functions.

Functions are objects in Javascript.

```javascript
var users = ['user1','user2','user3'];
function addUser(username){
  setTimeout(function(){
      users.push(username)
  },200);
}
function getUser(){
  setTimeout(function(){
    console.log(users);
  },100);
}
```

```html
When we add user and then get user its display this result

addUser('user4');
getUser();

Output:    [ 'user1', 'user2', 'user3' ]
```

## Event Loop

## Libuv
