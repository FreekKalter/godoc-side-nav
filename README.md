# godoc side-nav

View the go package documentation with a side navigation of all the available packages. This gives a big pane
to read the documentation for a given package on the right, and on the left you get a list to quickly switch to another package.

It is all based on the original code that you see when you launch godoc without the templates flag. Just apllied
a few hacks to make it a little easier to use on a daily basis.

## Usage

Clone this repo and feed it to godoc with the -templates flag.

```
git clone https://github.com/FreekKalter/godoc-side-nav
godoc -http=:6060 -templates="./godoc-side-nav"
```

## Disclaimer
I am a by no means a 'front-end guy' (wich most of these hacks are), so any pull request are welcome.

## *TODO*

- figure out what causes the glitch when switching to a package in another branch
- make side-nav interactive by colapsing treebranches
