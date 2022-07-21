# AWSourceLinkCell
>This class I wrote because I really f\***ed up to import some kind of f\***ing libraries every time.

### Including AWSourceLinkCell
Just drag and drop **AWSourceLinkCell.h** & **AWSourceLinkCell.m** to _YourTweakProj/Preferences_

### Usage
The AWSourceLinkCell offers two options for creating a cell:
- [<code>**source**</code>](https://github.com/AppIeWorm/AWSourceLinkCell#Source-cell)
- [<code>**customSource**</code>](https://github.com/AppIeWorm/AWSourceLinkCell#Custom-source-cell)

## Source cell


##### Example:

 <img src="githubAssets/sourceCell.jpg">

```
<dict>
    <key>cellClass</key>
    <string>AWSourceLinkCell</string>
    <key>source</key>
    <string>GitHub</string>
    <key>username</key>
    <string>AppIeWorm</string>
    <key>footerText</key>
    <string>See more on my GitHub</string>
    <key>tintColor</key>
    <string>#CCCCFF</string>
    <key>height</key>
    <real>60</real>
</dict>
 ```
 ##### Attributes:
 
|  Attribute                  | Necessity             | Value                                      |   Default        |
|:---------------------------:|:---------------------:|:------------------------------------------:|:-----------------|
| <kbd>source</kbd>           | **Required**          | Twitter, Telegram, Instagram, GitHub or VK |-|
| <kbd>username</kbd>         | **Required**          | Username of your account                   |-|
| <kbd>height</kbd>           | **Required**          | \<real>60\</real>                 | - |
| <kbd>image</kbd>            | **Optional**, required for VK          | A link to the image | The image will be taken from your account profile|
| <kbd>square</kbd> | **Optional** | <code>\<true/></code> or <code>\<false/></code> | Circle avatar |
| <kbd>contour</kbd> | **Optional** | <code>\<true/></code> or <code>\<false/></code> | No contour |
| <kbd>rightImage</kbd> | **Optional** | [UIImage systemImageNamed:] | No image |
| <kbd>headerText</kbd> | **Optional** | Any string | Username |
| <kbd>footerText</kbd> | **Optional** | Any string | Source |
| <kbd>tintColor</kbd> | **Optional** | <code>#RRGGBB</code> | [UIColor labelColor] |
| <kbd>footerTextColor</kbd> | **Optional** | <code>#RRGGBB</code> | [UIColor labelColor] |
| <kbd>rightImageColor</kbd> | **Optional** | <code>#RRGGBB</code> | [UIColor labelColor] |
| <kbd>contourColor</kbd> | **Optional** | <code>#RRGGBB</code> | [UIColor labelColor] |
| <kbd>tintedFooterText</kbd> | **Optional** | <code>\<true/></code> or <code>\<false/></code> | false |
| <kbd>tintedRightImage</kbd> | **Optional** | <code>\<true/></code> or <code>\<false/></code> | false |
| <kbd>tintedContour</kbd> | **Optional** | <code>\<true/></code> or <code>\<false/></code> | false |

 
##### Circled and Squared avatars with tinted contours and right images:
 <img src="githubAssets/tintedGuys.jpg">
 
  ```
  <dict>
      <key>cellClass</key>
      <string>AWSourceLinkCell</string>
      <key>source</key>
      <string>GitHub</string>
      <key>username</key>
      <string>AppIeWorm</string>
      <key>footerText</key>
      <string>See more on my GitHub</string>
      <key>tintColor</key>
      <string>#ff9900</string>
      <key>contour</key>
      <true/>
      <key>tintedContour</key>
      <true/>
      <key>tintedRightImage</key>
      <true/>
      <key>height</key>
      <real>60</real>
  </dict>
  <dict>
     <key>cellClass</key>
     <string>AWSourceLinkCell</string>
     <key>source</key>
     <string>GitHub</string>
     <key>username</key>
     <string>AppIeWorm</string>
     <key>footerText</key>
     <string>See more on my GitHub</string>
     <key>tintColor</key>
     <string>#ff9900</string>
     <key>square</key>
     <true/>
     <key>contour</key>
     <true/>
     <key>tintedContour</key>
     <true/>
     <key>tintedRightImage</key>
     <true/>
     <key>height</key>
     <real>60</real>
 </dict>
  ```


## Custom source cell



