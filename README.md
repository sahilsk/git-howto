# git-howto



### Remove git tags

Source: http://www.abeautifulsite.net/how-to-delete-a-tag-on-github/

    git tag -d [tag];
    git push origin :[tag]

And if your tag has the same name as one of your branches, use this instead:

    git tag -d [tag]
    git push origin :refs/tags/[tag]

