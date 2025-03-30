# Capslock-to-hyper
remap capslock to other key combos <br>
Modified from [Vonng/Capslock](https://github.com/Vonng/Capslock) <br>

Capslock serves via  [**Karabiner-Elements**](https://karabiner-elements.pqrs.org/)  on MacOS


### Basic

|   Key   |   MapsTo   | Comment                                            |
| :-----: | :--------: | -------------------------------------------------- |
| <kbd>⇪</kbd> Hold  |  <kbd>✱</kbd>  Hyper  | Hold Capslock to enable **Hyper** modifier.        |
Note that <kbd>✱</kbd> is implemented as combination of **ALL RIGHT MODIFIERS**:  <kbd>⌘</kbd><kbd>⌥</kbd><kbd>⌃</kbd><kbd>⇧</kbd>. 
Hold  **<kbd>✱</kbd> Hyper** to enable hyper functionalities. We will assume and omit that in subsequent document.

### Navigation

* <kbd>J</kbd>, <kbd>K</kbd>, <kbd>I</kbd>, <kbd>L</kbd>, <kbd>U</kbd>, <kbd>H</kbd>, <kbd>N</kbd>, <kbd>O</kbd> are used as **Navigators**. Maps to <kbd>←</kbd><kbd>↓</kbd><kbd>↑</kbd><kbd>→</kbd><kbd>⇞</kbd><kbd>↖</kbd><kbd>↘</kbd><kbd>⇟</kbd> by default. (pink area). 
* 9 control planes has already been allocated for navigators.
* Hold additional <kbd>⌘</kbd> Command for **selection**.  (like holding <kbd>⇧</kbd>shift in normal), additional <kbd>⌥</kbd> Option for **word/para selection**.
* Hold additional <kbd>⇧</kbd> Shift for **app/win/tab switching**.  Hold additional <kbd>⌃</kbd> Control for **desktop management** .
* Hold additional <kbd>⌥</kbd> Option for 🖱️ **mouse move**.  Add <kbd>⇧</kbd>shift to **⏫ accelerate**.  (<kbd>U</kbd>, <kbd>I</kbd>, <kbd>O</kbd>, <kbd>P</kbd> maps to mouse buttons) .
* <kbd>⇧</kbd><kbd>⌥</kbd> turns navigator to **🖲️ mouse wheel**, and <kbd>⇧</kbd><kbd>⌘</kbd> is the ⏫ **accelerated** version .  `HJKL` for wheel, wihle `UIOP` for reversed wheel move.

| Feature | **Move** | **Select** | **WordSel** | **Window** | **Desktop** |  🖱️   | **🖱️⏫** |  🖲️   |  🖲️⏫  |
| :-----: | :------: | :--------: | :---------: | :--------: | :---------: | :--: | :----: | :--: | :--: |
| Key\Mod |    <kbd>✱</kbd>     |     <kbd>⌘</kbd>      |     <kbd>⌘</kbd><kbd>⌥</kbd>      |     <kbd>⇧</kbd>      |      <kbd>⌃</kbd>      |  <kbd>⌥</kbd>   |   <kbd>⇧</kbd><kbd>⌥</kbd>   |  <kbd>⇧</kbd><kbd>⌃</kbd>  |  <kbd>⇧</kbd><kbd>⌘</kbd>  |
|    <kbd>J</kbd>    |   Left   | word left  |  word left  |  prev tab  |  prev desk  |  ⬅️   |   ⬅️⏫   |  ⬅️   |  ⬅️⏫  |
|    <kbd>L</kbd>    |  Right   | word right | word right  |  next tab  |  next desk  |  ➡️   |   ➡️⏫   |  ➡️   |  ➡️⏫  |
|    <kbd>I</kbd>    |    Up    |  line up   |  3 line up  |  prev app  | expose all  |  ⬆️   |   ⬆️⏫   |  ⬆️   |  ⬆️⏫  |
|    <kbd>K</kbd>    |   Down   | line down  | 3 line down |  next app  |    focus    |  ⬇️   |   ⬇️⏫   |  ⬇️   |  ⬇️⏫  |
|    <kbd>H</kbd>    |   Home   | line head  |  end2head   |  prev win  |    hide     |  🖱️R  |   🖱️R   |  ⬆️   |  ⬆️⏫  |
|    <kbd>N</kbd>    |   End    |  line end  |  head2end   |  next win  |  hide all   |  🖱️B  |   🖱️B   |  ⬇️   |  ⬇️⏫  |
|    <kbd>U</kbd>    |   PgUp   | prev page  |  prev page  |   zoom-    | fullscreen  |  🖱️L  |   🖱️L   |  ➡️   |  ➡️⏫  |
|    <kbd>O</kbd>    |   PgDn   | next page  |  next page  |   zoom+    |  Launchpad  |  🖱️F  |   🖱️F   |  ⬅️   |  ⬅️⏫  |



#### Arrow Navigation


* Arrows <kbd>←</kbd>↓<kbd>↑</kbd>→ to 🖱️ **mouse**  actions too. Hold <kbd>⌥</kbd> Option to ⏬ **slow down**, hold <kbd>⌘</kbd> Command  to ⏫ **speed up**.
* Hold  <kbd>⇧</kbd> Shift  turns to 🖲️ **wheel move**.  Extra <kbd>⌥</kbd> Option to ⏬ **slow down**, extra <kbd>⌘</kbd> Command  to ⏫ **speed up**.
* <kbd>↩</kbd> Return maps to left **click**.  And additional <kbd>⌘</kbd><kbd>⌥</kbd><kbd>⌃</kbd><kbd>⇧</kbd> turns into right click, middle click, backward, forward.

|   Feature   |      🖱️       |    🖱️⏬     |    🖱️⏫     |     🖲️      |    🖲️⏬     |    🖲️⏫     |
| :---------: | :----------: | :-------: | :-------: | :--------: | :-------: | :-------: |
| **Key\Mod** |      <kbd>✱</kbd>       |     <kbd>⌥</kbd>     |     <kbd>⌘</kbd>     |     <kbd>⇧</kbd>      |    <kbd>⇧</kbd><kbd>⌥</kbd>     |    <kbd>⇧</kbd><kbd>⌘</kbd>     |
| <kbd>←</kbd><kbd>↓</kbd><kbd>↑</kbd><kbd>→</kbd> | speed = 1600 | speed ÷ 2 | speed × 2 | speed = 32 | speed ÷ 2 | speed × 2 |
|      <kbd>↩</kbd>      |      🖱️L      |    🖱️M     |    🖱️R     |     🖱️L     |    🖱️B     |    🖱️F     |


### Window Control

* `Tab`, <kbd>Q</kbd>, <kbd>W</kbd>, <kbd>A</kbd>, <kbd>s</kbd> used as window control keys. Focuing on close/switch applications / windows / tabs / desktops. (azure area)
* Windows management (resize, layout) leaves to external application such as [Moom](https://manytricks.com/moom/), [Magnet](https://apps.apple.com/us/app/magnet/id441258766), and [Slate](https://github.com/jigish/slate). Bind <kbd>⌃</kbd><kbd>⌥</kbd><kbd>⇧</kbd><kbd>⌘</kbd>A manually.


| Key\Mod |      <kbd>✱</kbd>      |   
| :-----: | :---------: | 
|    <kbd>W</kbd>    |  previous app   | 
|    <kbd>Q</kbd>    |  next app  |   
|    <kbd>S</kbd>    |  next tab  | 
|    <kbd>A</kbd>    |  previous tab |
|    <kbd>X</kbd>    |  next window   |
|    <kbd>Z</kbd>    |  previous window   | 



### App Shortcuts



* <kbd>E</kbd> <kbd>R</kbd> <kbd>T</kbd> <kbd>Y</kbd> <kbd>F</kbd> <kbd>G</kbd> are used as application shortcuts. (yellow area)
* Popular apps and dev tools are registed to 3 default planes: <kbd>✱</kbd>/<kbd>⌘</kbd>/<kbd>⌥</kbd>. Assign these shortcuts according to your own needs.

| Key\Mod |         <kbd>✱</kbd>          |     <kbd>⌘</kbd>     |   
| :-----: | :----------------: | :-------: |
|    <kbd>E</kbd>    |       finder  |  safari   |   
|    <kbd>R</kbd>    |       terminal       |    |
|    <kbd>T</kbd>    | notes|     

## References

### Symbols


| Glyph |             Name             | Glyph |           Name           |
| :---: | :--------------------------: | :---: | :----------------------: |
|   <kbd>⇪</kbd>   |           Capslock           |   <kbd>✱</kbd>   |          Hyper           |
|   <kbd>⎋</kbd>   |            Escape            |   <kbd>␣</kbd>   |          Space           |
|   <kbd>⌘</kbd>   |        Command (Mac)         |   <kbd>⎇</kbd>   |       Alter (Win)        |
|   <kbd>⌥</kbd>   |         Option (Mac)         |   <kbd>⊞</kbd>   |        Win (Win)         |
|   <kbd>⌃</kbd>   |           Control            |   <kbd>⇧</kbd>   |          Shift           |
|   <kbd>↩</kbd>   |            Return            |   <kbd>⌤</kbd>   |          Enter           |
| <kbd>←</kbd><kbd>↓</kbd><kbd>↑</kbd><kbd>→</kbd> |         Arrow Cursor         |  <kbd>↖</kbd><kbd>↘</kbd>   |         Home/End         |
|  <kbd>⇥</kbd><kbd>⇤</kbd>   |             Tab              |  <kbd>⌫</kbd><kbd>⌦</kbd>   |  Delete / ForwardDelete  |
|   <kbd>⇭</kbd>   |           Numlock            |  ⏫⏬   |       Fast / Slow        |
|  🖱️L   |  Mouse Left Click (Button1)  |  🖱️B   | Mouse Backward (Button4) |
|  🖱️R   | Mouse Right Click (Button2)  |  🖱️F   | Mouse Forward (Button5)  |
|  🖱️M   | Mouse Middle Click (Button3) |   🖲️   |       Mouse Wheel        |

