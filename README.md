# Assistant
For the time being assistant is only a translator assist in my daily reading course.
It exercise google translate as it core side to traslate selected text, ask for better translation and if it's not already in the "phrase book" prompt for append in database.

## Installation
1. Rename "AccountInfo_sample.sh" to "AccountInfo.sh".
2. get Cookie and phrasebook path by sniff http request. you can do that in firefox by ctrl+shift+q in Firefox
3. Replace AccountInfo data with your cookie and url value.
4. Compile Qt project
5. Add Assistant to your start up list ( I guarantee that it will be a quiet boy :) )
6. Create a shortcut for Script/Translate.sh
7. Enjoy


## Acknowledgments
Assistant used following library, I just want to mention that this conquer can't achieved without their affords.
- Google Translate API
- sed
- wget
- awk
- qt
- xrandr
- D-Bus
- [webupd8](http://www.webupd8.org/2016/03/translate-any-text-you-select-on-your.html)