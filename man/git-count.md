git-count(1) -- Show commit count
=================================

## SYNOPSIS

`git-count` [-a|--all] [-f|--full]

## DESCRIPTION

  Show commit count.

## OPTIONS

  --all
  --full

  Show commit count details.

## EXAMPLES


 Output commit total:

    $ git count

    total 1844
 
 Output full commits total:

    $ git count --full

    1904

 Output verbose commit count details:

    $ git count --all

	  visionmedia (1285)
	  Tj Holowaychuk (430)
	  Aaron Heckmann (48)
	  csausdev (34)
	  ciaranj (26)
	  Guillermo Rauch (6)
	  Brian McKinney (2)
	  Nick Poulden (2)
	  Benny Wong (2)
	  Justin Lilly (1)
	  isaacs (1)
	  Adam Sanderson (1)
	  Viktor Kelemen (1)
	  Gregory Ritter (1)
	  Greg Ritter (1)
	  ewoudj (1)
	  James Herdman (1)
	  Matt Colyer (1)

	  total 1844

## AUTHOR

Written by Tj Holowaychuk &lt;<tj@vision-media.ca>&gt;

## REPORTING BUGS

&lt;<https://github.com/tj/git-extras/issues>&gt;

## SEE ALSO

&lt;<https://github.com/tj/git-extras>&gt;
