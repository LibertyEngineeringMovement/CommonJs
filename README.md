CommonJs
========

A collection of my more common scripts

## The following are from the Prototype collection found on mozilla.org ##

1. Array.filter()
2. Array.find()
3. Array.findOrNull()
4. Array.findIndex()
5. String.fromCodePoint()
6. String.codePointAt()
7. String.contains()
8. String.endsWith()
9. String.startsWith()
10. String.trim()
11. Object.is()
12. Object.setPrototypeOf()
13. Number.parseFloat()
14. JSON //this is for the Parse and Stringify functions.

## The following are from a collection of code that I have found, modified, or just wrote outright. ##
 
1. String.format(), you can also use "string".format(). Follows the .NET String.Format()
2. clone(obj) Returns a clone of the object.
3. newGuid(postback, url, count) Get the GUIDs from the server. Assumes you have a restful Guid generator API.
4. Digest($scope) Angular Specific Digest() Command. The difference between this and the Apply, is that I don't needlessly hit your console.log with information.
5. XPath by Cybozu Labs, Inc. (MIT Lic.)
6. JSONPath 0.8.0 - XPath for JSON Stefan Goessner (goessner.net) (MIT Lic.).
 
## Constants, or functions that act like constants ##
1. function TimeRegEx(){ return "(([0-1]\d)|(2[0-3])):([0-5]\d)(:([0-5]\d))?"};
 1. This is done because time gets marshalled back to the server as a date object, but a .NET Timespan object cannot parse that correctly without going through a custom converter. But if you marshal as text, then you can timespan can parse into a proper timespan object.

## 12/18/2014 Update Notice ## 

Since MS has moved everything .NET to Open Source, and much of it is now MIT lic, I will be changing my String.Format to theirs, but with a minor changes. Though I plan on preserving their Lic.
