# 14.2.8_find_and_findIndex_Exercises
Springboard unit 14.2.8 find and findIndex Exercises

# Springboard Instructions:
# ****Find / Findindex****

### **findUserByUsername**

Write a function called ***findUserByUsername*** which accepts an array of objects, each with a key of username, and a string. The function should return the first object with the key of username that matches the string passed to the function. If the object is not found, return undefined.

```jsx
const users = [
  {username: 'mlewis'},
  {username: 'akagen'},
  {username: 'msmith'}
];

findUserByUsername(users, 'mlewis') // {username: 'mlewis'}
findUserByUsername(users, 'taco') // undefined
```

### **removeUser**

Write a function called ***removeUser*** which accepts an array of objects, each with a key of username, and a string. The function should remove the object from the array and return this object. If the object is not found, return undefined.
