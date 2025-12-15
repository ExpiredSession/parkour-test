# בניית פארקור
## שלב 1
בואו נבנה פארקור עם בלוק שנעלם וחוזר

## שלב 2
כדי לבנות בלוק שנעלם וחוזר נצטרך לבנות לולאה שחוזרת על עצמה

``||loops:forever||`` גררו את הלולאת  מהתפריט הירוק
 

```blocks
loops.forever(function () {
})
```


## שלב 3
כדי שהבלוק יהיה במיקום קבוע בעולם, נשתמש במיקום עולמי.


פתחו את תפריט **POSITIONS** (טורקיז), 

וגררו את הבלוק ``||positions:world (0) (0) (0)||``.


שימו אותו בתוך הבלוק הירוק.

בין הבלוקים נצטרך לשים את בלוק ההשהייה כמו בדוגמא



```blocks
loops.forever(function () {
    blocks.place(AIR, world(-9, -51, 34))
    loops.pause(500)
    blocks.place(GRASS, world(-9,-51, 34))
    loops.pause(500)
})
```

## שלב 4
בתוך בלוק ההשהייה ובלוק המיקום רשמו את המספרים:

בלוק השהייה :500

מיקום:
9- 51- 34
```blocks
loops.forever(function () {
    blocks.place(AIR, world(-9,-51, 34))
    loops.pause(500)
    blocks.place(GRASS, world(-9,-51, 34))
    loops.pause(500)
})
```