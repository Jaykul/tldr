# tldr

The PoshCode *tldr* module is a collection of simplified and community-driven example pages.

## What does tldr mean?

TL;DR stands for "Too Long; Didn't Read".
It has its origins in internet and email slang, where it is used to indicate parts of a text were skipped as too lengthy to read.
Read more in the [TLDR article on Wikipedia](https://en.wikipedia.org/wiki/TL;DR).

## What is tldr?

Found a new module? Or just a little rusty on one?
Or maybe you can't always remember the syntax for `Set-ACL` or `Get-OdbcDsn`?

Maybe it doesn't help that the parameter explanations in `Get-Help Set-Acl -Full` start with this:

```
-AclObject <Object>
    Specifies an ACL with the desired property values. Set-Acl changes the ACL of item specified by the Path or InputObject
    parameter to match the values in the specified security object.

    You can save the output of a Get-Acl command in a variable and then use the AclObject parameter to pass the variable, or type
    a Get-Acl command.

    Required?                    true
    Position?                    2
    Default value
    Accept pipeline input?       true (ByValue)
    Accept wildcard characters?  false
```

Or maybe you're just frustrated that in 74 lines of the `Get-Help Set-Acl -Examples` there's not a single example that doesn't just copy the ACL from one file to another.

I figured people like me would prefer simple syntax blocks and "show me common usage" help pages. How about something like this:

![tldr screenshot](http://raw.github.com/poshcode/tldr/gh-pages/images/screenshot.png)

So, this module and repository is an ever-growing collection of examples
for the most common PowerShell commands, and some code to generate starter files from the help documentation already available for the command.

## Antecedents

I've borrowed the idea from a similar linux project, [tldr-pages](http://tldr-pages.github.io/), and so I expect that once we have a little content we should be able to modify [their clients](https://github.com/tldr-pages/tldr#clients), including the interactive web client and android client to point at this repository and get PowerShell examples.

## Contributing

- Your favourite command isn't covered?
- You can think of more examples for an existing command?

Contributions are most welcome!
Have a look at the [contributing guidelines](CONTRIBUTING.md)
and help us out!