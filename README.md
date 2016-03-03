# nightly
automate your nightly tasks quicker

## using nightly
1. stick your scripts in the */night* folder
2. add nightly to your `crontab` (`59 23 * * * path/to/nightly/script/nighly`)
3. done! nightly will now trigger these scripts automatically every night

## setting up `crontab`
1. run `crontab -e` anywhere
2. if asked what editor, enter `2 [enter]`
3. add the above code to the editor
4. type `^O` (`ctrl + o`)
5. press `enter`
