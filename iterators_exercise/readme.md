## Iterators Exercise

### Part I 

Use the following object for this set of questions:

```javascript
var users = [
{
    username: "larry",
    email: "larry@foo.com",
    years_experience: 22.1,
    favorite_languages: ["Perl", "Java", "C++"],
    favorite_editor: "Vim",
    hobbies: ["Fishing", "Sailing", "Hiking"],
    hometown: {
        city: "San Francisco",
        state: "CA"
    }
},
{
    username: "jane",
    email: "jane@test.com",
    years_experience: 33.9,
    favorite_languages: ["Haskell", "Clojure", "PHP"],
    favorite_editor: "Emacs",
    hobbies: ["Swimming", "Biking", "Hiking"],
    hometown: {
        city: "New York",
        state: "NY"
    }
},
{
    username: "sam",
    email: "jane@test.com",
    years_experience: 8.2,
    favorite_languages: ["JavaScript","Ruby", "Python", "Go"],
    favorite_editor: "Atom",
    hobbies: ["Golf", "Cooking", "Archery"],
    hometown: {
        city: "Fargo",
        state: "SD"
    }
},
{
    username: "anne",
    email: "anne@test.com",
    years_experience: 4,
    favorite_languages: ["C#", "C++", "F#"],
    favorite_editor: "Visual Studio Code",
    hobbies: ["Tennis", "Biking", "Archery"],
    hometown: {
        city: "Albany",
        state: "NY"
    }
},
{
    username: "david",
    email: "davis@test.com",
    years_experience: 12.5,
    favorite_languages: ["JavaScript", "C#", "Swift"],
    favorite_editor: "Sublime Text",
    hobbies: ["Volunteering", "Biking", "Coding"],
    hometown: {
        city: "Los Angeles",
        state: "CA"
    }
}
]
```

1. Write a function called `printEmails` which console.log's each emails for the users.
2. Write a function called `printHobbies` which console.log's each hobby for each user.
3. Write a function called `longestFavoriteLanguage` which console.logs the longest language in each of the user's `favorite_language` array.
4. Write a function called `findHometownByState` which returns the first user which has a 
5. Write a function called `formatYears` which returns an array of objects with the username as the key and the years experience in days.
6. Write a function called `allLanguages` which returns an array of all of the **unique** values 
7. Write a function called `hasFavoriteEditor` which returns a boolean if any of the users have 

### Part II

1. Write a function called `vowelCount` that accepts a string and returns an object
2. Write a function called `removeVowels` that accepts a string and returns an array of each character that is not a vowel. 


