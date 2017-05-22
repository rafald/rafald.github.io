# rafald.github.io

[_"Functional programmers can not write quicksort"_](https://www.youtube.com/watch?v=cK_kftBNgBc&t=56m50s) Sean Parent

### My C++ development environment
**Editor**: [Atom](https://atom.io/) (It is well integrated with github) with plugins:
- [autocomplete-clang](https://atom.io/packages/autocomplete-clang)  
- [linter-clang](https://atom.io/packages/linter-clang)
If your project has some extra include directories, put them in a file called **".clang_complete"** (in root dir) and list them line by line. 
Spaces must not be escaped or surraouded by "", example:
```
-Ilib/dir with spaces/include
```

References: https://promethe.io/2015/07/31/atom-plugins-for-c-development/

