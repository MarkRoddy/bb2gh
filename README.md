
bb2gh - Light weight mirroring of your public bitbucket projects to github


All you need is:
* curl
* git (with your ssh key configured)
* hg (only if you hg bitbucket repos)


Usage:

1. Create an empty repo on github for each of your public bitbucket repo, to
see a list of these repos, run:

    bb2gh -l BITBUCKET_USERNAME

1. Run the following to execute the replication.  If you don't specify a 
github username, your bitbucket username will be used.  Note that github 
user names are case sensative for these operations. So if your bitubcket 
username is foobar and your github username is FooBar you'll need to 
specify it.

    bb2gh BITBUCKET_USERNAME [GITHUB_USERNAME]

