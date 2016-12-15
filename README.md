# idea-material-theme
IntelliJ IDEA, WebStorm, PHPStorm Material UI theme modification

Custom colors based on [Material Theme](http://equinsuocha.io/material-theme/#/default) for IntelliJ idea products (_Used IntelliJ IDEA 16.2+_).

## Setup

* Goto IDEA `Settings->Plugins` and install *Color IDE* and *Material UI* with `Browse repostories...`.

![Color IDE](images/color-ide.png)

![Material UI](images/material-ui.png)

* Copy `*.icls` in your IDEA `config/colors` folder and restart IDEA if it's opened. You can find your settings folder location [here](https://intellij-support.jetbrains.com/hc/en-us/articles/206544519).

* Open settings, goto `Editor -> Color And Fonts` and select `Material Theme - Default (Custom)`.

### Using Darker Theme

* Show IDE toolbar from `View->Toolbar`. Hide it after you are done and not using it.
    ![Toolbar](https://camo.githubusercontent.com/6881abd21d426cf76e3c0f905f368d6a5c4076e5/68747470733a2f2f706c7567696e732e6a6574627261696e732e636f6d2f66696c65732f383030362f73637265656e73686f745f31353732322e706e67)

    _Instructions here:_ https://github.com/ChrisRM/material-theme-jetbrains#screenshots
    
* Select `Material Theme - Darker (Custom)` from `Color and Fonts`.

## Changes from the default

Changes applied on top of the default material UI color scheme:

* Parent theme changed from Default to Darcula.
* Font size changed from 15px to 12px (_I prefer smaller font showing more content on the screen_)
* Line height changed from 1.6 to 1.2 (_Better looking with smaller font size_)
* *Breadcrumbs* colors were not matching the dark them so I used the colors from IDEA Darcula theme for them.
* *Annotation* colors were Light. Colors changes to matched Darcula theme.
* Console colors copied from Darcula theme. Material UI colors wer too bright on the eyes.
* Console font changed to Consolas. It has less details which makes it easier to read.

![Theme Preview](images/theme-preview.png)  
_Theme Preview (Default)_

![Theme Preview - Dark](images/theme-preview-dark.png)  
_Theme Preview (Dark)_

## More

* Great [Laracasts](https://laracasts.com/series/setup-a-mac-dev-machine-from-scratch/episodes/3) tutorial on customizing PHP Storm
* Laracasts on how to [Be Awesome in PHPStorm](https://laracasts.com/series/how-to-be-awesome-in-phpstorm).