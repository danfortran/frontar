# Frontar
Minimalism done right; accessibility and good user interface are essential.

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
