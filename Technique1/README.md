# GNU/UNIX-style command-line arguments  

## PROBLEM  

```
Those of us who write for non-Windows systems will likely be working with a UNIX variant, 
and our users will expect UNIX style flag processing. How do you write Go command-line tools that meet users’ expectations? 
Ideally, you want to do this with out writing one-off specialized flag processing.  
```

## Solution  

using github.com/jessevdk/go-flags