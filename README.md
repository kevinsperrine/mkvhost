mkvhost
=======

script to create new virtualhosts

## Instructions

1. Update the "ava" and "ena" directories at the top of mkvhost
2. Copy mkvhost into a $PATH directory
3. Copy the template files into your apache "sites-available" directory
4. Run

### Usage: mkvhost <replacevhost> <replacedomain>

This will create the site example.com on localhost.
```
mkvhost example.com
```

This will create the site www.example.com on localhost
```
mkvhost example.com www
```
