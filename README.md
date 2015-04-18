# Programming Wisdom, work in progress

Programming wisdom from articles, books, comments & videos. Learning from other's experience.

[A Million Lines of Bad Code](http://varianceexplained.org/programming/bad-code/) [(Comments on HN)](https://news.ycombinator.com/item?id=9396694)

> “Everyone has a million bad words in them. Only once they’ve written those million words can they start writing well. So get writing!”

> "The only way to write good code is to write tons of shitty code first. Feeling shame about bad code stops you from getting to good code"

> "Code is art and every artist wants to go back and redo their bad works. But the best thing to do is learn and move on to create better art." (comment)

Practical Lesson: when reading a file in Java line-by-line, don't concatenate every line to a String variable. Use either Builder or read the whole file using `Files.readAllLines` or `Files.readAllBytes` - [more info on SO](http://stackoverflow.com/questions/326390/how-to-create-a-java-string-from-the-contents-of-a-file)
