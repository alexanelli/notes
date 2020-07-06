## string substitute around a pattern

changing:
> print "xx"

> print x,y

> print 'xx'

to:

> logging.info("xy") 

or

> logging.info(x,y)

the following command will change all occurrences:

`%s/print\( .*\)/logging.info\(\1\)/g`

more here: https://vim.fandom.com/wiki/Search_and_replace#Details
