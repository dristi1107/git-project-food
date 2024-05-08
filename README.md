<p align="center"> 
  <p align="center" style="text-transform:uppercase;font-weight:700;font-size:25px">
    Dojo Git/GitFlow
  </p>
</p>

><b>Git</b> is a version control system that helps you manage your code base.
<br/>

><b>Gitflow</b> is a git branching management strategy involving the use feature branches and multiples primary branches.

# Context
Mr Ashleeey 🐓 is someone who is as stubborn as a mule that have a PhD in "Roi des têtus" 👑. After a long discussion, he was finally convinced to use git for proper management of his codes instead of keeping it on his laptop and sharing the codes via emails or teams.

He realised that he needs a lot of practice to become an expert. To begin with, he needs to install the [command line utility](https://git-scm.com/download/win) for git.

Be like Ashleeey and take the first step to becoming a git guru.
To get the most of git features, he asked a colleague to collaborate on a mock project. 

# Clone
To be able to practice, Ashleeey needs to <b>clone</b> a <b>remote repository</b> (Online project/CodeBase) on his laptop for him to have a <b>local repository</b> (Local project/CodeBase) where he can practice in an isolated environment.

Help Ashleeey clone the repository using the following url: https://github.com/Build744/git-training.git

# Create a new branch
Now that Ashleeey has a local repository on his laptop, he needs to create a new branch to implement a new feature. It is a good practice to create a new <i>feature</i> branch whenever you have a new feature to work on.

Branch name: <b><i>"feature/food"</i></b>
 
# Commit changes to Local Repository
On the newly created branch, he will have to create 2 files:
> <b>ProteinList.txt</b>
<br/>
Poulet
<br/>
Poisson
<br/>
Oeufs
<br/>

>  <b>VegetableList.txt</b>
<br/>
Pomme de terre
<br/>
Chou-fleur
<br/>
Aubergine

He then needs to commit those changes <b>separately</b> in order on his local repository.

# Split a commit into multiple commits
As a newbie, Ashleeey did not know that separation of commits is important for readability, history, isolation of changes, code review and more.

He is counting on you to help him on this matter.

# Modifying existing commits
Now, Ashleeey was informed that his vegetable list should also contain:
> Concombre
<br/>
Avocat
<br/>
Kiwi

Moreover, the list now also contains fruits.

He now needs to accomodate the above changes. How can he do that <b>without</b> creating a new commit ? 

Similarly, he also needs to amend the protein list with the following:
> Agneau
<br/>
Boeuf
<br/>
Cerf

How can he do that <b>without</b> creating a new commit ?

# Pick a commit from another branch
Ashleeey's colleague was also working in parallel to create a list of beverages.

> <b>BeverageList.txt</b>
<br/>
Juice
<br/>
Coffee
<br/>
Wine

He has already pushed his branch <b>"feature/beverages"</b> on the remote repository.
Help Ashleeey retrieve the commit containing the beverage list so that he will not need to redo existing work.

Furthermore, this commit needs to be before the commits of vegetable and protein list to have a clean commit history.

# Putting aside work in progress locally
Ashleeey needs to create a dessert list but does not need to commit his changes yet 
> <b>DessertList.txt</b>
<br/> 
Ice Cream
<br/>
Tiramisu
<br/>

How can he put aside his changes locally so that he may continue with it when needed ?

# Renaming a branch

He realised that his branch name is not meaningful. He needs to rename his branch.

Branch name: <b><i>"feature/grocery-list"</i></b>

# Resuming working in progress that was previously put aside
Finally, Ashleeey needs to resume his work on dessert by adding 
> Moeulleux au chocolat
<br/>
Gaufrettes
<br/>

Help him finish his work.

# Removing a specific commit
Ashleeey has decided to become a vegetarian 🌿 and thus does not need the ProteinList.txt anymore. 

Help him to remove the list without having a new commit.

# Resetting a commit 
Ashleeey has decided to cut on sugar 🍰 and thus does not need the DessertList.txt anymore. 

Help him reset the commit containing the dessert list.
