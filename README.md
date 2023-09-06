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

The go to the branches panel in the Dev Ops repository and delete any branches with the format grN_taskX.

## Modifying Dev Ops permissions

Prior to the workshop make sure all attendees have a Dev Ops Basic licence (you can check this under [Organisation settings > Users](https://dfe-gov-uk.visualstudio.com/_settings/users)).

Once that's checked, you need to add all attendees to the [Contributors group](https://dfe-gov-uk.visualstudio.com/official-statistics-production/_settings/permissions?subjectDescriptor=vssgp.Uy0xLTktMTU1MTM3NDI0NS0zNDAzODMyMjY2LTIxMzE0MjczOTMtMjg3NjM5NDc5NS0zODY2Mzg3NjctMS0yNDYxMTYxNjUxLTQwNTMwNTE0NjMtMjU4NjE0Mjc5MS0yNDI1MDA4MzA5) in the Official Statistics Production project. Being in the Contributors group allows users to create and modify tickets on Boards.

Finally, remove previous attendees and assign current attendees to teams of 3 in the [Teams area](https://dfe-gov-uk.visualstudio.com/official-statistics-production/_settings/teams) of Dev Ops (workshop_devopsintro_1-5).



# Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)