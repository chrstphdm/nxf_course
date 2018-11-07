# training
Training lectures and materials

## Subtree 

The `day2/patterns` is a subtree created with these commands:

    git remote add patterns git@github.com:nextflow-io/patterns.git
    git subtree add --squash --prefix=day2/patterns/ patterns master

To pull changes use 

     git subtree pull --squash --prefix=day2/patterns/ patterns master
    
To push back changes use:

     git subtree push --squash --prefix=day2/patterns/ patterns master