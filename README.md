Zucchini.tmbundle
---------------------

A **TextMate Bundle** for the **Zucchini** functional testing framework.

The bundle includes syntax highlighting, the ability to run feature walkthroughs and reports and a number of useful snippets.

![screenshot](http://zucchiniframework.org/i/zucchini-textmate.png)

### Installation

```
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone git@github.com:vaskas/zucchini.tmbundle.git Zucchini.tmbundle
```

### Running features on a device

Make sure you set the [ZUCCHINI_DEVICE environment variable in TextMate preferences](http://zucchiniframework.org/i/zucchini-textmate-preferences.png) to reflect the desired device listed in your project's support/config.yml.

If your TextMate.app is having trouble finding the `zucchini` command, remember that [TextMate doesn't inherit your regular PATH](http://wiki.macromates.com/Troubleshooting/TextMateAndThePath). The bundle also executes a `.rvmrc` it finds in the project directory.

Patches and additions are welcome.
