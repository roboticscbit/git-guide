# A simple guide for Git

Basic commands needed for working with Git

## Installation

For Windows users : Download [git](https://git-scm.com/downloads)

For Linux users : ```sudo apt install git-all``` in Terminal

## Version

```git --version```

## Set Config Values (Only once)

```git config –-global user.name “name”```

```git config –-global user.email “name@email.com”```

## To push the changes to GitHub (First Time)

```git init```

```git add *```

```git commit –m “message”```

```git remote add origin <link>``` 

```git push origin master```

## To push the changes to GitHub (From Second Time)

```git add *```

```git commit –m “message”```

```git push origin master```

## If you want to contribute to a project

Step 1: Fork the repo to your account

Step 2: ```git clone <link>```(From your account)

Then make the changes in your PC

Step 3: 

```git add *```

```git commit –m “message”```

```git push origin master```

Step 4: Make a Pull Request


## To download a repository from GitHub to your PC

```git clone <link>``` 

## To update the changes made in Github to you PC

```git pull``` 





## License
[MIT](https://choosealicense.com/licenses/mit/)
