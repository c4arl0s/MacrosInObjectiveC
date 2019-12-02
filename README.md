# MarcrosInObjectiveC
MarcrosInObjectiveC

# what are they ?

- it Use the preprocessor to define new syntax
- it is a rule that defines how specific pattern is replaced with a specific construction.

``` objective-c
#define expression_to_replace replacement
```

``` objective-c
#define AppDelegate [[UIApplication sharedApplication] delegate]
```

# for some programmers a macro is an advance find and replace tool.

Macros simplify your work when building bar buttons because the creation task is so repetitive.

The following macro creates a basic button item:

``` objective-c
#define BARBUTTON(TITLE, SELECTOR) [[UIBarButtonItem alloc] \ initWithTitle:TITLE style:UIBarButtonItemStylePlain \ target:self action:SELECTOR]
```



