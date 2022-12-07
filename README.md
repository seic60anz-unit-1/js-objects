# Objects

### Getting Started

1. Fork this repo and `git clone` it down to your computer
1. Create two files `index.html` and `script.js`
1. Include `script.js` in `index.html` using a `<script>` tag
1. Open `index.html` in your web browser and open the console
1. After answering each section below, `git commit` your work
1. When you're finished or when time is up, push your work to your remote repo, file a Pull Request

---

Copy and paste this object into `script.js`:

``` js
let users = {
  theresa: {
    fullName: 'Theresa Smith',
    admin: true,
    age: 45,
    friends: ['freddie', 'meredith']
  },
  freddie: {
    fullName: 'Frederick Jones',
    admin: false,
    age: 32,
    friends: ['meredith']
  },
  meredith: {
    fullName: 'Meredith Johnson',
    admin: false,
    age: 56,
    friends: ['freddie', 'sally', 'theresa']
  },
  sally: {
    fullName: 'Sally Brown',
    admin: false,
    age: 28,
    friends: ['meredith', 'freddie']
  }
}
```


1. Print theresa's full name e.g. "Theresa Smith"
2. Print Freddie's age
3. Add yourself to the `users` object (fill out the same info as everyone else)
4. Add a new friend `'sally'` to Freddie's list of friends
5. Delete yourself from the `users` object
6. Write a `for..in` loop that prints each user object.
9. Write a loop that prints the names of each of Meredith's friends

    Example output:
    ``` text
    freddie
    sally
    theresa
    ```

10. Write a loop that prints the **full names** of each of Meredith's friends

    Example output:
    ``` text
    Frederick Jones
    Sally Brown
    Theresa Smith
    ```

10. Write a nested loop that prints the number of friends each user has and the names of those friends.
  _HINT_ You'll need both a `for..in` and a `for..of`
  
    Example output:
    ``` text
    theresa has 2 friends:
    freddie
    meredith
    
    meredith has 3 friends:
    freddie
    sally
    theresa 
    
    …
    ```
