# Introduction 
This is a demo repository for the Stats Development workshop on Dev Ops.

# Getting Started
TODO: Guide users through getting your code up and running on their own system. In this section you can talk about:
1.	Installation process
2.	Software dependencies
3.	Latest releases
4.	API references

# Pre-workshop set up

## Resetting the repository

To reset the repo prior to a workshop, we need to reset the main and each working group branch to their original state and remove any leftover sub-branches on Dev Ops.

To reset a given branch, switch to the branch you want to reset and then run the git reset command as follows:

```
git switch workshop_group_1
git log # to find the required commit code to reset to (currently 600c40955f38fa88e5e361f5164252f104e87d98)
git reset --hard <commit_code>
git push -f
```

## Modifying Dev Ops permissions


# Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)