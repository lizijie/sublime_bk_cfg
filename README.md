Reference from https://packagecontrol.io/docs/syncing


1. (Install ***Package Control***)[https://packagecontrol.io/installation#st3] before restoring those missing packages. 
<br>

2. change your path to the sublime install path. For exmale `Sublime Text 3/Packages`. And remove the the default `User` folder
```
cd Sublime Text 3/Packages
rm -rf User
git clone git@github.com:lizijie/sublimetext_backup_configuration.git
mv sublimetext_backup_configuration User
```
<br>

3. git clone ***SUBLIME_PK_CFG***. And change name to `User`
```
git clone git@github.com:lizijie/sublime_bk_cfg.git
mv sublime_bk_cfg User
```
<br>

4. reopen sublime text, enjoy~!




