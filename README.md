# FakeProfile  
## Temporary solution for faker.js => image.avatar()  




Script Usage : 
```
async function fetchAvatar() {
  const response = await fetch('https://roxgame95.github.io/FakeProfile/RandomAvatar.js');
  const text = await response.text();
  eval(text);
  return RandomAvatarUrlApi();
}

var imageUrl = await fetchAvatar();
console.log(imageUrl); //https://roxgame95.github.io/FakeProfile/avatars/008869.jpg

```
  
  
  
Preview :  
Get Random fake Profile picture:  
https://roxgame95.github.io/FakeProfile/  
Get Random fake Profile picture URL:  
https://roxgame95.github.io/FakeProfile/GetAvatar.html  
