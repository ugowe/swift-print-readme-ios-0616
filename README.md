# Print Function 
  

## Learning Objectives - The student should be able to..
* Explain the importance of being able to print your variables.
* Print a string literal  

```swift
print("Hello Pluto")
``` 

* Print a sentence using string interpolation.

```swift
let favoriteWord = "Serendipity" 
let favoriteColor = "Green"
let favoriteSinger = "Billy Joel"

print("Hi Mom! My favorite word is \(favoriteWord), my favorite color is \(favoriteColor), and my favorite singer is \(favoriteSinger).")

// prints "Hi Mom! My favorite word is serendipity, my favorite color is green, and my favorite singer is Billy Joel"
```

* Create a sentence to store in a variable using string interpolation - as follows:

```swift
let favoriteWord = "Serendipity"

let favoriteSentence = "Hello everyone, how are you doing? My favorite word is \(favoriteWord)"

print(favoriteSentence)
// prints "Hello everyone, how are you doing? My favorite word is Serendipity"
```

## What the student can do at this point 
* Create variables and constants only using String types 

```swift
let name = "Ned Stark"  // the student has seen this
```
* The student has NOT seen type annotations yet. It isn't something I want to have the student see (yet).

```swift
let name: String = "Ned Stark"  // the student has not seen this
```



## Outline / Notes

* Have the student follow along in the playground file. For example, asking the question.. "If you were asked to create three variables that represent your favorite word, color and singer, would you create them with let or var? Your favorite word, color and singer change over time." I like the idea of reinforcing what they had just learned in the prior readme and challenge them on that again.
* After the student creates their favorite word, color, or singer (you can decide on this narrative, it doesn't have to fall in line with this if you don't want it to), show them how to print them out individually.
* Then show the student how to print a sentence.

```swift
print("It's a UNIX system! I know this!")
``` 
* Challenge the student at this point to print the following sentence. "Hi Mom! My favorite word is serendipity, my favorite color is green, and my favorite singer is Billy Joel" 
* After the prints that sentence (not knowing yet about string interpolation), pose the quesiton.. "Wouldn't it be easier if we could print the values of various variables within that sentence we structured in the print function"? Or something like that.. then going into string interpolation.

```swift
print("Hi Mom! My favorite word is \(favoriteWord), my favorite color is \(favoriteColor), and my favorite singer is \(favoriteSinger).")
```
* Have the student get used to the syntax, asking them to print out a few things in the playground file.
* Challenge the student to be able to create something like this: 

```swift
let favoriteSentence = "Hello everyone, how are you doing? My favorite word is \(favoriteWord)"
print(favoriteSentence)
```

* Then show them how (if they can't figure it out)


<a href='https://learn.co/lessons/Print' data-visibility='hidden'>View this lesson on Learn.co</a>
