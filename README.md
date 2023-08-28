## Website for Principles of Programming Group at CMU

To build the website locally:
- [Install Jekyll](https://jekyllrb.com/docs/installation/).
- Run `bundle install` in root of this repository.
- Run `bundle exec jekyll serve` to host website on `localhost:4000/pop`.

To make the website live on https://cs.cmu.edu/~pop, run the following
scripts

    $ ./deploy.sh

This script will push the `_site` directory to
`/afs/cs.cmu.edu/project/pop/www/`; users will be prompted for
kerberos credentials if none are found.
