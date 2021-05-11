```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->
loqef
2. Answer the following with reason:

- `user == newUser;` // ihwd
- `user === newUser;`//wqdkp
- `user.name === newUser.name;` wlmd
- `user.name == newUser.name;`// qdlj
- `user.sibling == newUser.sibling;`//ojqw
- `user.sibling === newUser.sibling;`//iwndq
- `user.sibling == allBrothers;`//qjwm
- `user.sibling === allBrothers;`//ijwnqd
- `brothersCopy === allBrothers;`//lowkq
- `brothersCopy == allBrothers;`//lmqw
- `brothersCopy == user.sibling;`//okwq
- `brothersCopy === user.sibling;`//wqdn
- `brothersCopy[0] === user.sibling[0];`//wqdk
- `brothersCopy[1] === user.sibling[1];`//qwd
- `user.sibling[1] === newUser.sibling[1];`//qwd
