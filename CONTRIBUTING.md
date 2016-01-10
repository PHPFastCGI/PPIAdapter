Contributing
------------

*PHPFastCGI PPI Adapter* is an open source, community-driven project. Contributions are very welcome and may come as
[suggestions](https://github.com/PHPFastCGI/PPIAdapter/issues), support in our
[discussion channel](https://gitter.im/PHPFastCGI/PPIAdapter) or
[pull requests](https://github.com/PHPFastCGI/PPIAdapter/pulls).



If you're submitting a **pull request**, please follow these guidelines:

Start by forking the *PHPFastCGI PPI Adapter* repository and cloning your fork locally:

    $ git clone git@github.com:YOUR_USERNAME/PPIAdapter.git
    $ git remote add upstream git://github.com/PHPFastCGI/PPIAdapter.git
    $ git checkout -b feature/BRANCH_NAME master

Apply *PHPFastCGI PPI Adapter* Coding Standards using the [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) tool:

    $ ./vendor/bin/php-cs-fixer fix -v

After your work is finished rebase the feature branch and push it:

    $ git checkout master
    $ git fetch upstream
    $ git merge upstream/master
    $ git checkout feature/BRANCH_NAME
    $ git rebase master
    $ git push --force origin feature/BRANCH_NAME