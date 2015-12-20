# Far
Far manager settings, tips &amp; tricks
![Screenshot](https://github.com/mattia72/Far/blob/master/Far%203.0.4400%20x86.png?raw=true "Screenshot")

## "Navy blue a'la NC" color schema for the editor
* Install FarColorer if you haven't installed it yet.
* Copy [my-mirror.hrd](https://github.com/mattia72/Far/blob/master/Plugins/FarColorer/base/hrd/rgb/contrib/my-mirror.hrd) into your `%FARHOME%\Plugins\FarColorer\base\hrd\rgb\contrib` directory.
* Open `%FARHOME%\Plugins\FarColorer\base\hrd\catalog-rgb.xml` and add an entry for my-mirror.hrd:
```xml
    <hrd class="rgb" name="my-mirror" description="Navy Blue a'la NC">
      <location link="&hrd;/rgb/contrib/my-mirror.hrd"/>
    </hrd>
```
* In the editor of Far push <kbd>F11</kbd> then select `FarColorer`, then push <kbd>C</kbd> for configure.
* Check Enabled under `TrueMod` settings (<kbd>n</kbd>) and set `Color style` (<kbd>t</kbd>) to `Navy blue a'la NC`.
![Settings](https://github.com/mattia72/Far/blob/master/FarColorer-settings.png?raw=true "Settings")
* If everithing went ok, you should see navy background in the editor:
![Screenshot](https://github.com/mattia72/Far/blob/master/edit-catalog-rgb.xml.png?raw=true "Screenshot")

