# nad__guillaume__ma__200529
 Référenciel de code source et de liens - ressources supportant le reste de la documentation

# Intentions

## --@STCGoal A well reviewed of what is available in the market to create using artificial intelligence 


### --@a Professional Application ./app

### --@a Plugins ./plugins

### --@a Librairy  ./lib

# --@STCGoal Well Organized Folder Structure


# Methodologies

## --@STCGoal Creative Coding

### Un référenciel maître avec des modules de chaque librairies.

#### --@STCGoal Creative Coding::Submodule add on procedure

```sh
mkdir -p lib
export lib_repo=git@github.com:GuillaumeAI/stylegan2.git
export target_rel_path=lib/stylegan2
git submodule add $lib_repo $target_rel_path
git submodule update $target_rel_path

```
