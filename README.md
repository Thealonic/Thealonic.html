# Thealonic.html
I'll add to this at some point


Global look-up documentation:
#ref1000: changes current wallpaper background colour
#ref1001: changes taskbar text colour and active header colour if active or unactive
#ref1002: changes header background images through github directs
#ref1003: changes current theme active colours for desktop windows and store them into preview colours to be applied later through #ref0001
#ref1004: changes current header background colour from var #ref1002, and changes the current invert status for icons such as minimize, help, ect.
#ref1005: makes adjustments to different spritesheets if alternate versions are needed, usually just the same by default.
#ref1006; assigns varable to taskbar grabbing #ref1006
#ref1007: opens the task, resets window position and enables the taskbar. #ref1007
#ref1008: assigns a positional value based on how many tasks x the width of the task, and sets the position. Then determines the current state of the task.
#ref1009: checks the positional value of the current task and updates if it is visible on the taskbar.
#ref1010: inactive placement holder as there's no need to update the current position of the task that is being removed.
#ref1011: disables the task that is current being updated as inactive from the taskbar.
#ref1012: removes a task from the current amount of active tasks.
#ref1013: toggle checks to see if the current task is focused or unfocused. Only one can be active at a time.
#ref1014: variable storing of grabbing elemenets to save file space.
#ref1015: changes the default positional values based on absolute values and changes to default widths / heights.
#ref1016: When pressing on the (tab-number) tab, set zindex to highest tab.
#ref1017: resets the index of all tabs to prevent weird z-index or positional bugs.
#ref1018: changes to the current tab and adjusts height and width to overlap / prioritise the tab
#ref1019: Resets ALL potential background selection background color through #ref0019, stores the #ref selected option to a varable under #ref1015 #ref1000. 
          Changes the current active wallpaper as a variable which is pulled from github and stores it to #ref1016, 
          changes the apperance preview of said wallpaper through #ref0020.
          Finally, uses #ref1017's current selection to change the background the selected wallpaper.
#ref1020: changes monitor previews to the current wallpaper.
#ref1021: changes the appearance preview and icon preview to current wallpaper
#ref1022: boolean toggle gates for dropdown menus.
#ref1023: opens the boolean toggle dropdown menu.
#ref1024: closes the boolean toggle dropdown menu.
#ref1025: enforces closing the boolean toggle dropdown menu.
#ref1026: Variable storage for colours to be applied later.
#ref1027: Makes all other windows inactive and checks current layer and adds one to then add it through the var cal and updates it.
          Toggles the taskbar to an active position through (taskname)ButtonOpen = false. changing the taskbar to the active text (curactivetitle)
          Changes the titlebar header to active and changes margin-left from -20000 to 0.
#ref1028: Changes taskbar to active.
#ref1029: Closes the window by moving margin-left to -20000px and deactivating the taskbar.
#ref1030: Closes the window by moving margin-left to -20000px
#ref1031: Resets positional values through left and up for said window. 

