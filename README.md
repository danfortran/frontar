# !IMPORTANT!
!---!

**Frontar is unmaintained and undocumented. It was not intended to be used by anyone other than the theme's designer, but it is technically possible to use it. It's unlikely that there will be any issue using it; Hugo may introduce new updates in the future which may result in code becoming obsolete. However, you're still able to fork the project and update the code if that happens and you have the desire to.**

!---!

# Frontar
Minimalism done right; accessibility and good user interface are essential.

Frontar is an anagram of "Fortran". The "Front" represents "frontend"; the name sounds like "Frontier".

# Installation
## Step 1: Create a New Site
``hugo new site enteryoursitename``

## Step 2: Add The Theme
### Step 2.1: Git
```
cd enteryoursitename
git init
git submodule add https://github.com/danfortran/frontar.git themes/frontar
```
### Step 2.2: Without Git
- Download the ZIP: https://github.com/danfortran/frontar/archive/refs/heads/main.zip.
- Extract the .ZIP.
- Get the "frontan" directory.
- Place that folder in the "themes/" directory.

### Step 3: Move the config.toml
(assuming your directory is located at: /home/user/enteryoursitename)

``mv /home/user/enteryoursitename/themes/config.toml /home/user/enteryoursitename/``

You can replicate this process with your graphical file manager.
