# TabFern

[![Join the chat at https://gitter.im/TabFern/Lobby](https://badges.gitter.im/TabFern/Lobby.svg)](https://gitter.im/TabFern/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Developing on TabFern

 - For more information on developing TabFern, see below



## What is TabFern?

![screenshot](https://raw.githubusercontent.com/cxw42/TabFern/gh-pages/assets/img/screenshot.png)

**TabFern** is a [Google Chrome extension](https://chrome.google.com/webstore/detail/tabfern-tab-manager-and-b/hbajjpcdbninabigakflkhiogmmjaakm) that:

 - Gives you a vertical list of all your open tabs
 - Groups your tabs by window
 - Saves sets of tabs so you can close them and resume later
 - Backs up and restores sets of tabs

# Usage

 - Click the icon to open the TabFern view.  The view will also open when
   you start Chrome.
 - When you open windows or tabs, or rearrange windows or tabs _within a
   particular browser window_, the tree will update.
 - To mark a window to be saved, you have two choices:

     1. Give the window a name using the pencil icon (![image](https://raw.githubusercontent.com/cxw42/TabFern/master/static/assets/icons/pencil.png)).
     1. Hit the middle icon showing a rectangle with a red dot
   (![image](https://raw.githubusercontent.com/cxw42/TabFern/master/static/assets/icons/picture_delete.png)).  The window will close.

 - Folder icons are:

     - Open, unsaved: a monitor (![image](https://raw.githubusercontent.com/cxw42/TabFern/master/static/assets/icons/monitor.png))
     - Open, saved: a monitor with a green dot (![image](https://raw.githubusercontent.com/cxw42/TabFern/master/static/assets/icons/monitor_add.png)).
     - Closed, saved (closed unsaved aren't in the tree): a white file folder.

 - Saved windows will be saved even if you close them manually.  To remove them
   from the tree, hit the delete icon (red X,
   ![image](https://raw.githubusercontent.com/cxw42/TabFern/master/static/assets/icons/cross.png)).

 - Windows you do not expressly save will not be saved when you exit!
   I am open to discussion of better ways to handle this.

# Limitations

 - There is only a two-level hierarchy --- tabs cannot be the children
   of other tabs in the tree.
 - You cannot open and close individual tabs --- you have to open and close
   the window as a whole (work is in progress --- see issue 35).
 - Where new windows open may not always be where Chrome would open a new
   window.
   Currently, the original size/position of the last-focused or last-closed
   window is generally where the new window will end up.
 - Lots of others I'm not going to list right now!

