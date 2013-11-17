:sparkles: :heart:  Emojize Java :heart: :sparkles:
=======

Emojize is a Java library to convert keyboard emojis to chearsheet emojis


## Emojize Java
#### A class that turns iOSStyle icons to [Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com/) codes and viceversa

## Components
* *EmojiEditText*: EditText subclass that allows you to convert Android icons into iOS Style emoticons
* *EmojiTextView*: TextView subclass that convert icons into iOS style icons
_Both above works with icons in the following format [1fa6b] [1f3ba] ... ( Not in unicode )_
* *emojiParser*: This class convert the previous format into EmojiCheatSheet one


## Getting Started
Wherever you want to use Emojis set the textView or editText of type *EmojiEditText* or *EmojiTextView*

### Get the String with emojis converted in chear sheet format

```java
String emojiString = emojiParser.emojiText(emojitextview.getText())
System.out.println(emojiString);
```

### Set the text with emojis in chear sheet format into iOS Style format
```java
emojitextview.setText(emojiParser.demojizedText(text));
```

---

## Methods
```java
public static String emojiText(String text){}
public static String demojizedText(String text){}
```

---


