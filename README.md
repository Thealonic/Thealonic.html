                                    .uef^"                                          .~uOOOOu+~.    
                  ...     ..      :d88E                   .u    .     .xn!~%x.     Z8F      `8N.  
               :~""888h.:^"888:   `888E          .uuu   .d88B :@8c   x888' '888.  d88L       98E  
             X888n. 8888X  ?888>   888E~?888L :888'8888. 4888>'88"  8888l   X8888 "88888888NNu.   
               `*88 8888~ x88x.    888E  888E 8888.+"    4888>      `8888  :88888  .zf""*8888888L 
              ..<"  88*`  88888X   888E  888E 8888L     .d888L .+     `"**~ 88888 d8F      ^%888E 
               :888888H.    `%88> m888N= 888>  "88888%     "Y"      '8888>  8888~ '%N.       dl"  
                 `"888888:    X"   `Y"   888     "YP'                888"  :88%     '^"====="'    
                    %888888x.-`         J88"                          ^^"==^""                      
                     '""**""            @%                                                           
                                      :"                                                             
                 <!--https://twitter.com/VeryVhersty // https://veryvhersty.tumblr.com/-->
                       
I'll add to this at some point

Global look-up documentation:
#ref5000: changes current wallpaper background colour
#ref5001: changes taskbar text colour and active header colour if active or unactive
#ref5002: changes header background images through github directs
#ref5003: changes current theme active colours for desktop windows and store them into preview colours to be applied later through #ref0001
#ref5004: changes current header background colour from var #ref1002, and changes the current invert status for icons such as minimize, help, ect.
#ref5005: makes adjustments to different spritesheets if alternate versions are needed, usually just the same by default.
#ref5006; assigns varable to taskbar grabbing #ref1006
#ref5007: opens the task, resets window position and enables the taskbar. #ref1007
#ref5008: assigns a positional value based on how many tasks x the width of the task, and sets the position. Then determines the current state of the task.
#ref5009: checks the positional value of the current task and updates if it is visible on the taskbar.
#ref5010: inactive placement holder as there's no need to update the current position of the task that is being removed.
#ref5011: disables the task that is current being updated as inactive from the taskbar.
#ref5012: removes a task from the current amount of active tasks.
#ref5013: toggle checks to see if the current task is focused or unfocused. Only one can be active at a time.
#ref5014: variable storing of grabbing elemenets to save file space.
#ref5015: changes the default positional values based on absolute values and changes to default widths / heights.
#ref5016: When pressing on the (tab-number) tab, set zindex to highest tab.
#ref5017: resets the index of all tabs to prevent weird z-index or positional bugs.
#ref5018: changes to the current tab and adjusts height and width to overlap / prioritise the tab
#ref5019: Resets ALL potential background selection background color through #ref0019, stores the #ref selected option to a varable under #ref1015 #ref1000. 
          Changes the current active wallpaper as a variable which is pulled from github and stores it to #ref1016, 
          changes the apperance preview of said wallpaper through #ref0020.
          Finally, uses #ref1017's current selection to change the background the selected wallpaper.
#ref5020: changes monitor previews to the current wallpaper.
#ref5021: changes the appearance preview and icon preview to current wallpaper
#ref5022: boolean toggle gates for dropdown menus.
#ref5023: opens the boolean toggle dropdown menu.
#ref5024: closes the boolean toggle dropdown menu.
#ref5025: enforces closing the boolean toggle dropdown menu.
#ref5026: Variable storage for colours to be applied later.
#ref5027: Makes all other windows inactive and checks current layer and adds one to then add it through the var cal and updates it.
          Toggles the taskbar to an active position through (taskname)ButtonOpen = false. changing the taskbar to the active text (curactivetitle)
          Changes the titlebar header to active and changes margin-left from -20000 to 0.
#ref1028: Changes taskbar to active.
#ref1029: Closes the window by moving margin-left to -20000px and deactivating the taskbar.
#ref1030: Closes the window by moving margin-left to -20000px
#ref1031: Resets positional values through left and up for said window. 

