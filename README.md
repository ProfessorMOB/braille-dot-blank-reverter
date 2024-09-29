# braille-art-aesthetic (was braille-art-dot-inverter)
the purpose of this project was so that I could have neater and better looking neovim dashboards involving braille art. I felt that they looked bad
Sometimes the mode just didn't fit right with the art, i.e. I have dark mode but the art was lightmode. Sometimes it was the background too.
I'll share two examples demonstrating the usage of this project

Below is an image of a tree, it might look nice on light mode, but it doesn't on dark mode
⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⢀⡀⠀⠀⢀⣻⣿⣧⣴⡿⢿⣦⣀⠀⠀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣠⣦⣾⣿⣿⣷⣶⣶⡿⠿⣟⠛⠶⠾⢻⡾⢿⣶⢾⣿⣦⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⢰⣾⣿⡿⠿⠉⠀⠉⠳⠉⠉⠀⠐⠂⢀⠐⠀⠀⠈⠁⠒⠋⡽⣿⡗⠀⠀⠀⠀⠰⠀⠀⠀
⠀⠀⠀⠀⠀⠘⠿⣿⣁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⡀⠀⡀⠀⣀⠰⣎⣿⣿⣄⡀⠀⠀⠀⠀⠀
⠀⡀⠀⠀⠀⢠⣾⡿⢤⡤⠀⠀⠐⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠃⠠⢤⠀⠀⠼⠛⣿⣇⢀⡀⠀⠀⠀
⠀⠇⢀⣀⣶⣾⣿⠅⠈⠉⠁⠤⠀⠠⠀⠀⠀⡀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢹⣿⣷⣦⠀⠀
⠀⠀⠈⢿⣿⣿⡟⠀⠆⠈⠁⣀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠂⠀⠀⠀⠀⠂⠀⠀⠀⡀⠾⢹⡏⠁⠀⠀
⠀⠀⠀⠀⢀⣿⣿⠇⠀⠐⠂⠐⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡄⣼⣿⡇⠀⠀⠀
⠀⠀⠘⣿⣿⣿⣱⡾⠃⠀⢂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠤⠀⠀⠀⠀⠀⠃⡀⠁⣡⣾⣇⠀⠀⠀
⠀⠀⢸⣿⣿⣿⣉⡡⠶⠁⠼⠁⠀⠠⠄⠀⠀⠀⠀⢀⠀⠀⠀⠀⠄⠁⠄⠁⠄⡀⠀⢨⣹⡿⠿⠀⠀⠀
⠀⠀⠀⠙⠻⣿⣿⣧⣰⣷⣶⣄⠁⠴⠆⢀⡐⠒⠐⠀⠀⠀⠀⠀⠀⡀⠂⠀⠀⡀⠒⣾⡟⠓⠀⠀⠀⠀
⠀⠀⠀⠀⠈⢻⡟⢻⣿⣿⣿⣿⡓⣤⣄⠈⠱⣆⠀⣀⣲⣤⣷⣤⣀⣽⣓⣤⣠⣯⣾⡿⠋⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠁⠀⢸⣿⣿⡿⢷⣶⣾⣿⣶⣿⣶⣿⣿⢾⣿⠿⠋⠉⠙⣿⠿⠃⠀⠀⠀⠀⠐⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢰⠀⠈⠻⠟⠀⠈⠙⠿⢿⣿⡏⠛⣿⣿⢺⣿⠀⠀⠀⠀⠀⠀⡄⠀⢠⠀⠀⢁⠀⠀⠀
⠀⠀⠀⠈⡀⠀⡼⠀⠀⢀⠀⠀⠀⠀⠀⢸⣿⡿⠀⣿⠁⠀⣿⠀⠀⠀⠀⠀⢠⠇⠀⠸⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠁⠀⠇⢀⠀⠘⠀⢀⠀⠀⣾⡗⣿⣿⣹⠀⣦⠰⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⢀⣰⣆⣰⣷⣾⣷⣶⣆⡀⡇⠀⣿⣿⣼⣿⣿⡇⣽⠀⣿⢠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⣾⣿⣿⠿⣛⣹⡿⣿⡿⠃⠁⠀⠉⢽⣿⣿⣭⣹⡇⢰⣿⠘⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⢀⣽⣿⠋⠁⠀⠀⢹⣿⢇⠀⠀⠀⠀⢼⣿⡷⠿⡏⣷⠘⣿⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠸⢿⢿⣿⠄⡀⠀⢠⣼⣯⣾⣷⣶⣄⠀⣸⡟⢻⠃⣿⠛⢀⣿⢸⠀⠀⠀⠀⠀⠇⡀⢠⠀⠀⢸⠀⠀⠀
⠀⠀⠈⢉⣿⣿⣼⡿⠋⠉⢹⣿⣿⣟⣛⣿⠇⠈⣿⠻⡇⢸⣿⠈⠀⠀⠀⣠⣶⣾⣿⣶⣦⣰⣆⣀⠀⠀
⠀⠀⠀⠀⠙⠿⠉⠀⠀⠀⠀⠈⠉⠹⣯⣿⣾⣇⣿⡇⣿⢸⣿⢀⠀⠀⠸⢿⣿⠿⠿⢏⣹⠿⢿⣿⣦⡀
⠀⠀⠀⠀⠀⠀⢸⠀⠀⡆⠀⠀⠀⠀⠈⢹⣿⡿⣯⡴⠅⢸⣿⠘⠀⠀⠀⢸⣿⣤⡄⠀⣀⠐⢻⣿⣄⡅
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⠀⠀⠀⠀⠀⢻⣿⣧⡋⣷⠂⣽⣿⣀⣀⣶⣴⢿⣿⣿⣆⠀⠈⢳⣾⣿⣿⡇
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣿⣟⠢⠷⢉⣿⣛⣻⣿⣾⠿⠉⠉⢿⣿⣶⣼⡟⠁⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⡟⣿⣮⣿⣡⣿⣿⡟⠉⠉⠀⠀⠀⠈⠉⠹⠏⠁⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢽⣿⡿⣿⡂⠻⣿⣿⠉⠀⠀⠀⠀⢰⠀⠀⠀⠀⠀⢠⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⡄⠀⠀⠀⢀⣤⣾⣿⣇⠿⣏⡑⣿⣿⣦⠀⠀⠄⠀⠘⡦⠀⢰⠂⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠃⠀⠀⢦⣸⣿⡓⣿⡟⣷⡘⢷⣌⠘⢻⣶⠀⠀⠀⠀⠃⠀⠘⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⣈⣤⣄⣸⣿⣏⣿⣿⡿⣯⣷⡈⣎⠳⣶⡹⠾⢟⣤⣠⣄⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢠⣴⡿⠿⢿⣟⠻⣯⣿⣿⣿⣿⣷⣟⣩⣿⡿⢿⣟⣾⣿⣛⣽⡷⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠘⠃⠀⠙⡟⠀⠛⡁⠀⠛⡟⠁⠛⡋⠁⠀⠀⠛⣋⠈⢛⠋⠀⠀⠀⠀⠀⠀⠀⠀

Now with some braille art aesthetics magic we can 
~~~ 
braille-art-aesthetics -if inputs/input4.txt
~~~
(note: input/input4.txt is one of the example inputs provided to demonstrate this project)
and voilà

﻿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠿⡿⢿⣿⣿⡿⠄⠀⠘⠋⢀⡀⠙⠿⣿⣿⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⠟⠙⠁⠀⠀⠈⠉⠉⢀⣀⠠⣤⣉⣁⡄⢁⡀⠉⡁⠀⠙⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡏⠁⠀⢀⣀⣶⣿⣶⣌⣶⣶⣿⣯⣽⡿⣯⣿⣿⣷⣾⣭⣴⢂⠀⢨⣿⣿⣿⣿⣏⣿⣿⣿
⣿⣿⣿⣿⣿⣧⣀⠀⠾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣿⣿⢿⣿⢿⣿⠿⣏⠱⠀⠀⠻⢿⣿⣿⣿⣿⣿
⣿⢿⣿⣿⣿⡟⠁⢀⡛⢛⣿⣿⣯⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣼⣟⡛⣿⣿⣃⣤⠀⠸⡿⢿⣿⣿⣿
⣿⣸⡿⠿⠉⠁⠀⣺⣷⣶⣾⣛⣿⣟⣿⣿⣿⢿⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⠈⠙⣿⣿
⣿⣿⣷⡀⠀⠀⢠⣿⣹⣷⣾⠿⣷⣿⣿⣿⣿⣿⣿⣿⣿⣿⣽⣿⣿⣿⣿⣽⣿⣿⣿⢿⣁⡆⢰⣾⣿⣿
⣿⣿⣿⣿⡿⠀⠀⣸⣿⣯⣽⣯⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢻⠃⠀⢸⣿⣿⣿
⣿⣿⣧⠀⠀⠀⠎⢁⣼⣿⡽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣛⣿⣿⣿⣿⣿⣼⢿⣾⠞⠁⠸⣿⣿⣿
⣿⣿⡇⠀⠀⠀⠶⢞⣉⣾⣃⣾⣿⣟⣻⣿⣿⣿⣿⡿⣿⣿⣿⣿⣻⣾⣻⣾⣻⢿⣿⡗⠆⢀⣀⣿⣿⣿
⣿⣿⣿⣦⣄⠀⠀⠘⠏⠈⠉⠻⣾⣋⣹⡿⢯⣭⣯⣿⣿⣿⣿⣿⣿⢿⣽⣿⣿⢿⣭⠁⢠⣬⣿⣿⣿⣿
⣿⣿⣿⣿⣷⡄⢠⡄⠀⠀⠀⠀⢬⠛⠻⣷⣎⠹⣿⠿⠍⠛⠈⠛⠿⠂⠬⠛⠟⠐⠁⢀⣴⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣾⣿⡇⠀⠀⢀⡈⠉⠁⠀⠉⠀⠉⠀⠀⡁⠀⣀⣴⣶⣦⠀⣀⣼⣿⣿⣿⣿⣯⣿⣿⣿
⣿⣿⣿⣿⣿⣿⡏⣿⣷⣄⣠⣿⣷⣦⣀⡀⠀⢰⣤⠀⠀⡅⠀⣿⣿⣿⣿⣿⣿⢻⣿⡟⣿⣿⡾⣿⣿⣿
⣿⣿⣿⣷⢿⣿⢃⣿⣿⡿⣿⣿⣿⣿⣿⡇⠀⢀⣿⠀⣾⣿⠀⣿⣿⣿⣿⣿⡟⣸⣿⣇⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣾⣿⣸⡿⣿⣧⣿⡿⣿⣿⠁⢨⠀⠀⠆⣿⠙⣏⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⡿⠏⠹⠏⠈⠁⠈⠉⠹⢿⢸⣿⠀⠀⠃⠀⠀⢸⠂⣿⠀⡟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⠁⠀⠀⣀⠤⠆⢀⠀⢀⣼⣾⣿⣶⡂⠀⠀⠒⠆⢸⡏⠀⣧⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⡿⠂⠀⣴⣾⣿⣿⡆⠀⡸⣿⣿⣿⣿⡃⠀⢈⣀⢰⠈⣧⠀⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣇⡀⡀⠀⣻⢿⣿⡟⠃⠐⠁⠈⠉⠻⣿⠇⢠⡄⣼⠀⣤⡿⠀⡇⣿⣿⣿⣿⣿⣸⢿⡟⣿⣿⡇⣿⣿⣿
⣿⣿⣷⡶⠀⠀⠃⢀⣴⣶⡆⠀⠀⠠⠤⠀⣸⣷⠀⣄⢸⡇⠀⣷⣿⣿⣿⠟⠉⠁⠀⠉⠙⠏⠹⠿⣿⣿
⣿⣿⣿⣿⣦⣀⣶⣿⣿⣿⣿⣷⣶⣆⠐⠀⠁⠸⠀⢸⠀⡇⠀⡿⣿⣿⣇⡀⠀⣀⣀⡰⠆⣀⡀⠀⠙⢿
⣿⣿⣿⣿⣿⣿⡇⣿⣿⢹⣿⣿⣿⣿⣷⡆⠀⢀⠐⢋⣺⡇⠀⣧⣿⣿⣿⡇⠀⠛⢻⣿⠿⣯⡄⠀⠻⢺
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⣿⣿⣿⣿⣿⡄⠀⠘⢴⠈⣽⠂⠀⠿⠿⠉⠋⡀⠀⠀⠹⣿⣷⡌⠁⠀⠀⢸
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠀⠠⣝⣈⡶⠀⠤⠄⠀⠁⣀⣶⣶⡀⠀⠉⠃⢠⣾⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⢠⠀⠑⠀⠞⠀⠀⢠⣶⣶⣿⣿⣿⣷⣶⣆⣰⣾⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡂⠀⢀⠀⢽⣄⠀⠀⣶⣿⣿⣿⣿⡏⣿⣿⣿⣿⣿⡟⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⢻⣿⣿⣿⡿⠛⠁⠀⠸⣀⠰⢮⠀⠀⠙⣿⣿⣻⣿⣧⢙⣿⡏⣽⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣼⣿⣿⡙⠇⠀⢬⠀⢠⠈⢧⡈⠳⣧⡄⠉⣿⣿⣿⣿⣼⣿⣧⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⠷⠛⠻⠇⠀⠰⠀⠀⢀⠐⠈⢷⠱⣌⠉⢆⣁⡠⠛⠟⠻⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⡟⠋⢀⣀⡀⠠⣄⠐⠀⠀⠀⠀⠈⠠⠖⠀⢀⡀⠠⠁⠀⠤⠂⢈⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣧⣼⣿⣦⢠⣿⣤⢾⣿⣤⢠⣾⣤⢴⣾⣿⣿⣤⠴⣷⡤⣴⣿⣿⣿⣿⣿⣿⣿⣿

I think this is pretty neat. 
Lets do another example
here is an some skibid toilet art (please dont ask why)

⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣤⣤⣤⣤⣤⣤⣤⣤⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣿⣿⡿⡟⣯⡯⠿⣉⠭⠩⡍⠝⣛⢻⠿⣿⣿⣿⣷⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣿⣿⡿⣏⢳⡩⣕⣾⣓⣯⣿⣿⣿⡻⣿⣿⡾⢷⣻⡿⣿⣿⣆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣾⣿⣿⡿⣝⢎⣧⣿⣿⣿⣿⡿⣿⣻⡉⠀⣝⠻⣿⣷⣿⣿⣯⢿⣿⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⣿⣿⣿⡽⣎⣿⣿⢟⣽⡳⢯⣽⣳⣏⣿⠐⣾⣿⣛⣯⡿⣿⣿⣿⣻⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⣿⣿⣿⣷⣻⣽⣿⢇⠫⢞⣹⣇⠾⣷⢯⣿⢜⣿⡷⢣⡾⣽⠢⣘⢻⣿⣿⡆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣾⣿⣿⣿⡷⣳⡻⣜⢠⣱⢾⣿⡿⡗⢯⣛⡾⢸⣿⡹⣳⣿⠦⣑⠠⣻⣿⣿⣇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣿⣿⣿⣿⣻⢧⡻⣄⣿⠟⠸⣿⡿⢻⠜⣣⣿⠸⣟⣣⡿⢻⣿⣿⡠⣿⣼⣿⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⡿⣽⢎⣷⣭⠿⢶⢶⠶⡶⢾⣳⣿⡹⣘⢻⣾⣁⣈⣛⠋⢹⣿⣿⣿⣏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣸⣿⣿⣿⡿⣽⣞⡻⣌⠏⡐⠈⠐⣈⡶⠾⢓⡱⠉⢻⡿⣭⣙⠻⢻⡟⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣿⣿⣬⣿⣿⣟⡷⣮⡳⡜⢦⠕⠲⡀⣿⢿⣷⣦⣴⡡⣮⣿⣽⣿⡦⣁⡜⣿⢿⣿⠇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⢺⣿⣿⣟⢾⣻⣗⣻⡟⢀⢊⡔⡐⠆⢢⢘⣻⣿⣿⣿⣿⡿⣛⢷⡡⢿⣯⣿⣿⠱⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢻⢧⣿⣼⣏⣿⣿⣾⣏⣿⣿⣿⣿⣷⣬⣯⣍⣳⣻⢛⢛⣳⣍⣝⣮⣽⣆⣹⣿⡏⢳⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⣏⢮⣹⣿⣾⣟⣿⣸⢿⣻⣿⣿⣿⢿⢿⢻⠛⢟⠻⡿⣿⣿⣿⣿⣿⣿⣿⣿⠁⠎⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⢯⣽⣿⢿⣯⢿⣯⢿⡷⠙⣿⣟⣾⢺⠚⡖⠖⢤⠧⠯⣿⣿⣿⢿⣿⣿⣯⡖⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⢯⣟⣾⣹⣗⣣⠈⠻⣿⣾⣶⣳⣶⣼⣤⣿⣿⠟⣡⣿⣿⣿⠧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣻⣞⣧⣟⣦⠍⡄⠴⢋⣩⣉⣩⣝⣻⡟⡡⢞⣷⣿⣿⡏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣽⣾⣾⡽⣞⠤⣈⠉⡉⠉⠉⢩⢙⡶⣥⢿⣿⣿⣏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣹⣿⣿⣿⣿⣟⣿⣯⣟⣦⢳⣐⠦⣑⣎⢶⣽⣾⣿⣿⣿⣿⣿⣦⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣼⣇⣿⣞⣿⣿⣿⣿⣿⣿⣿⣿⣯⣿⣽⣾⣿⣿⣿⣿⣿⣿⣿⣿⡿⠈⢦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣰⣿⣿⡧⢿⣜⡾⣭⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠇⠀⠀⠱⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⡠⠔⠒⠒⠒⠐⠈⠒⠐⠒⡾⣿⣿⣿⣏⣿⢯⣷⢣⡓⠜⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠀⠀⠀⠀⠘⢖⠒⠒⠒⠒⠒⠒⠒⠒⠒⠒⠒⠢⣄⠀⠀
⠀⠀⠀⡞⠀⠀⠀⠀⠀⠀⠀⠀⠀⡜⠀⢹⣿⣿⣿⢼⡿⣯⠳⡌⡘⠤⣉⠙⠻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠈⢦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢣⠀
⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⡜⠀⠀⠀⠻⣿⣿⣾⢽⣿⣳⢡⠘⡰⠠⠁⠂⡇⢬⢉⢯⡻⣽⣿⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⢦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡸⠀
⠀⠀⠀⢉⡟⠚⠓⠚⠒⠒⠒⡺⠁⠀⠀⠀⠀⠈⣿⣟⡾⣿⢧⢢⠁⢆⠱⠀⠐⣏⠦⣉⠶⣹⣳⡿⣿⣿⣿⣿⠁⠀⠀⠀⠀⠀⠀⠀⠈⣖⠒⠒⠒⠒⠒⠒⠒⠒⠒⢾⠁⠀
⠀⠀⠀⡏⠉⠉⠉⠉⠉⠉⢹⠃⠀⠀⠀⠀⠀⠀⣿⣿⡳⣿⣯⠆⣁⠊⠤⠁⠀⣿⠰⡡⢏⡷⣽⣿⣿⣿⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⡉⠉⠉⠉⠉⠉⠉⠉⠉⠉⢳⠀
⠀⣀⣀⡇⠀⠀⠀⠀⠀⠀⡎⠀⠀⠀⠀⠀⠀⠀⢸⣺⡷⣿⣷⠩⢄⡘⢄⠃⠀⢿⡱⢌⡳⡽⢾⣿⣿⣿⣿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢣⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀
⢸⠤⣤⡇⠀⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⢳⣿⣯⣓⠂⢌⢢⠡⠀⣹⢆⠣⣽⣹⢿⣿⣿⣿⠇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⡄⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀
⢠⣀⣧⡇⠀⠀⠀⠀⠀⡎⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⡯⣾⣿⢦⡉⢂⠦⡑⠠⢸⣋⠖⣱⢯⣿⣿⣿⡿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢣⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀
⠈⠣⠼⡇⠀⠀⠀⠀⠀⠇⠀⠀⠀⠀⠀⠀⠀⠀⢸⡷⣿⡽⣿⡶⡑⢌⢲⡁⠆⣹⢮⠸⣭⣟⣾⣿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣟⣷⢿⣿⡷⣭⠌⣆⢣⠒⣸⢧⢛⡶⣯⣿⣿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⢫⣿⡿⡜⡰⢊⡇⢒⢸⣯⢎⡷⣿⣿⡏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢇⠀⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⡞⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⢯⣿⣿⡱⢡⢫⡜⢠⢻⣗⢮⡽⣷⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣯⣿⣷⣫⠕⡮⡜⢄⢺⡿⢬⣟⣿⣿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢹⣿⡗⣿⣟⡶⡙⢶⣙⠢⣩⣿⢣⣟⣿⡿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⡀⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣏⣿⣯⢷⡙⢮⣇⢃⠖⣿⢣⣟⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⢾⣿⢧⢏⡳⣞⠌⣚⢿⡹⣞⣿⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠆⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⣇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⡿⣿⣛⠮⡵⣎⠣⢜⣻⢵⣻⣿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⠃⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⢻⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠨⣿⣿⣟⣿⣽⢳⡹⣬⠃⡜⣺⢧⡿⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡞⠀⠀⠀⠀⠀⠀⠀⢸⠀
⠀⠀⠀⡇⠀⠀⠀⠀⠈⢿⣦⡀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣿⣯⣿⣞⡧⣝⡖⢣⠘⣽⡾⣽⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣾⠃⠀⠀⠀⠀⠀⠀⠀⣺⠀
⠀⠀⠀⠹⢄⡀⠀⠀⠀⠈⠻⣿⣷⣦⣄⣀⠀⠀⠀⠀⣿⣿⣷⣿⣻⡜⣧⣛⠤⠑⡎⢿⣽⡏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣾⡿⠃⠀⠀⠀⠀⠀⠀⠀⢀⠇⠀
⠀⠀⠀⠀⠀⠉⡲⠚⠉⠉⠉⠉⠉⢉⣩⣭⠭⠭⠭⠭⠽⣿⣿⣻⢷⣛⠶⣭⠂⠱⡘⡽⣾⡿⠭⠭⠭⠭⠭⠭⣍⣓⠒⠒⠒⠛⠛⠛⠿⠿⠤⠤⣄⣀⣀⣀⣤⠤⠖⠋⠀⠀
⠀⠀⠀⠀⠀⡜⠀⠀⠀⠀⠀⠀⡴⢋⠀⠀⠀⠀⠀⠀⢀⣿⣿⣿⡿⣽⣻⢶⡁⢦⡱⣹⣿⣇⡀⠀⠀⠀⠀⠀⠀⢀⡉⣶⠀⠀⠀⠀⠀⠀⠀⠀⣸⠌⠙⡄⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢠⡇⠀⠀⠀⢀⠀⠀⠙⢦⣶⣶⣾⣿⡿⠿⠿⣿⣿⣷⣿⡿⣽⣯⡗⣬⢳⣯⣿⡟⠿⠿⣿⣿⣿⣷⣶⠶⠛⠁⠀⠀⠀⠀⠀⠀⠀⣼⠃⠀⢠⡇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⡞⠳⣄⠀⠀⠀⠀⠀⠀⠀⠀⠉⠉⠑⠒⠲⠦⠼⠿⠷⠿⠿⠿⠾⠷⠾⠻⠞⠛⠓⠒⠒⠊⠉⠉⠁⠀⠀⠀⠀⠀⠀⠀⢀⣠⠴⠋⠁⠀⠀⢰⠇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⡧⠀⠈⠓⠲⠤⣀⣀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣀⡠⠤⠒⠚⠉⠀⠀⠀⠀⠀⢀⢺⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⣧⠡⠀⠀⠀⠀⠀⠀⠉⠉⠁⠒⠒⠒⠲⠤⠤⠤⠤⠤⠤⠤⠤⠤⠤⠤⠴⠂⠒⠒⠒⠒⠒⠂⠉⠉⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢂⢾⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⣷⠈⡔⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢈⠤⡏⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢹⡘⢄⠈⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⡈⣼⠃⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠘⡇⡎⠐⢠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⠁⠒⡟⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⢻⡔⢣⢀⠂⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠢⢌⣳⠃⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠈⣷⠡⠆⡌⢀⠂⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠐⡄⢣⢮⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠘⢯⡚⣄⠣⣈⠐⡈⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠠⠐⡀⢎⡰⣳⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠈⢻⣤⠓⡤⢒⠠⣁⠂⠌⡀⠄⡀⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠀⠄⡁⠂⢄⠱⣈⢶⡝⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣗⡘⢆⡱⢀⠎⡰⢐⢂⡐⠄⣈⠐⡀⢂⠀⠄⡀⢀⠀⡀⢀⠠⠀⠠⢀⠂⡈⠄⡁⢂⠅⠢⠑⡈⢆⠱⣼⠎⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⡜⡄⠢⢉⠢⠑⠌⢂⠜⡐⠠⢃⠐⠂⠌⠐⢀⠂⠐⠀⠂⠀⠁⠂⠀⠐⠀⠐⠀⠂⠈⠄⠡⠐⡨⢱⠏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢹⡄⢁⠂⠄⠡⠈⠀⠠⠀⠁⠀⠈⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢂⠱⡟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⣇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⢻⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢈⣿⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣾⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢺⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⣿⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⣯⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⡗⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⡆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡜⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠉⠢⢄⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡤⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠒⠒⠀⠤⠤⠤⠤⠤⣀⣀⣀⣀⣀⣀⣀⣀⣀⡀⠤⠤⠄⠒⠒⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀

it looks pretty horrid in dark mode, so lets fix it
~~~
braille-art-aesthetics -if input/input.txt
~~~
and voilà!

⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠿⠛⠛⠛⠛⠛⠛⠛⠛⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠋⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠋⠀⠀⢀⢠⠐⢐⣀⠶⣒⣖⢲⣢⠤⡄⣀⠀⠀⠀⠈⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠀⠀⢀⠰⡌⢖⠪⠁⠬⠐⠀⠀⠀⢄⠀⠀⢁⡈⠄⢀⠀⠀⠹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠁⠀⠀⢀⠢⡱⠘⠀⠀⠀⠀⢀⠀⠄⢶⣿⠢⣄⠀⠈⠀⠀⠐⡀⠀⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠃⠀⠀⠀⢂⠱⠀⠀⡠⠂⢌⡐⠂⠌⠰⠀⣯⠁⠀⠤⠐⢀⠀⠀⠀⠄⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⠀⠀⠀⠈⠄⠂⠀⡸⣔⡡⠆⠸⣁⠈⡐⠀⡣⠀⢈⡜⢁⠂⣝⠧⡄⠀⠀⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⠀⠀⠀⢈⠌⢄⠣⡟⠎⡁⠀⢀⢨⡐⠤⢁⡇⠀⢆⠌⠀⣙⠮⣟⠄⠀⠀⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠀⠀⠀⠀⠄⡘⢄⠻⠀⣠⣇⠀⢀⡄⣣⠜⠀⣇⠠⠜⢀⡄⠀⠀⢟⠀⠃⠀⠘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⢀⠂⡱⠈⠒⣀⡉⡉⣉⢉⡁⠌⠀⢆⠧⡄⠁⠾⠷⠤⣴⡆⠀⠀⠀⠰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠇⠀⠀⠀⢀⠂⠡⢄⠳⣰⢯⣷⣯⠷⢉⣁⡬⢎⣶⡄⢀⠒⠦⣄⡄⢠⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠀⠀⠓⠀⠀⠠⢈⠑⢌⢣⡙⣪⣍⢿⠀⡀⠈⠙⠋⢞⠑⠀⠂⠀⢙⠾⢣⠀⡀⠀⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⠀⡅⠀⠀⠠⡁⠄⠨⠄⢠⡿⡵⢫⢯⣹⡝⡧⠄⠀⠀⠀⠀⢀⠤⡈⢞⡀⠐⠀⠀⣎⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡄⡘⠀⠃⠰⠀⠀⠁⠰⠀⠀⠀⠀⠈⠓⠐⠲⠌⠄⡤⡤⠌⠲⠢⠑⠂⠹⠆⠀⢰⡌⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⠰⡑⠆⠀⠁⠠⠀⠇⡀⠄⠀⠀⠀⡀⡀⡄⣤⡠⣄⢀⠀⠀⠀⠀⠀⠀⠀⠀⣾⣱⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⡐⠂⠀⡀⠐⡀⠐⡀⢈⣦⠀⠠⠁⡅⣥⢩⣩⡛⣘⣐⠀⠀⠀⡀⠀⠀⠐⢩⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⡐⠠⠁⠆⠨⠜⣷⣄⠀⠁⠉⠌⠉⠃⠛⠀⠀⣠⠞⠀⠀⠀⣘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠄⠡⠘⠠⠙⣲⢻⣋⡴⠖⠶⠖⠢⠄⢠⢞⡡⠈⠀⠀⢰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⠀⠂⠁⠁⢂⠡⣛⠷⣶⢶⣶⣶⡖⡦⢉⠚⡀⠀⠀⠰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⠆⠀⠀⠀⠀⠠⠀⠐⠠⠙⡌⠯⣙⠮⠱⡉⠂⠁⠀⠀⠀⠀⠀⠙⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠃⠸⠀⠡⠀⠀⠀⠀⠀⠀⠀⠀⠐⠀⠂⠁⠀⠀⠀⠀⠀⠀⠀⠀⢀⣷⡙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠏⠀⠀⢘⡀⠣⢁⠒⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⣿⣿⣎⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⢟⣫⣭⣭⣭⣯⣷⣭⣯⣭⢁⠀⠀⠀⠰⠀⡐⠈⡜⢬⣣⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣿⣿⣿⣿⣧⡩⣭⣭⣭⣭⣭⣭⣭⣭⣭⣭⣭⣝⠻⣿⣿
⣿⣿⣿⢡⣿⣿⣿⣿⣿⣿⣿⣿⣿⢣⣿⡆⠀⠀⠀⡃⢀⠐⣌⢳⢧⣛⠶⣦⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣷⡙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡜⣿
⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⢣⣿⣿⣿⣄⠀⠀⠁⡂⠀⠌⡞⣧⢏⣟⣾⣽⢸⡓⡶⡐⢄⠂⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⡙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢇⣿
⣿⣿⣿⡶⢠⣥⣬⣥⣭⣭⣭⢅⣾⣿⣿⣿⣿⣷⠀⠠⢁⠀⡘⡝⣾⡹⣎⣿⣯⠰⣙⠶⣉⠆⠌⢀⠀⠀⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣷⠩⣭⣭⣭⣭⣭⣭⣭⣭⣭⡁⣾⣿
⣿⣿⣿⢰⣶⣶⣶⣶⣶⣶⡆⣼⣿⣿⣿⣿⣿⣿⠀⠀⢌⠀⠐⣹⠾⣵⣛⣾⣿⠀⣏⢞⡰⢈⠂⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⢶⣶⣶⣶⣶⣶⣶⣶⣶⣶⡌⣿
⣿⠿⠿⢸⣿⣿⣿⣿⣿⣿⢱⣿⣿⣿⣿⣿⣿⣿⡇⠅⢈⠀⠈⣖⡻⢧⡻⣼⣿⡀⢎⡳⢌⢂⡁⠀⠀⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡜⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿
⡇⣛⠛⢸⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⡌⠀⠐⠬⣽⡳⡝⣞⣿⠆⡹⣜⠂⠆⡀⠀⠀⠀⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⢻⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿
⡟⠿⠘⢸⣿⣿⣿⣿⣿⢱⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⢐⠁⠀⡙⢶⡽⣙⢮⣟⡇⠴⣩⠎⡐⠀⠀⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡜⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿
⣷⣜⣃⢸⣿⣿⣿⣿⣿⣸⣿⣿⣿⣿⣿⣿⣿⣿⡇⢈⠀⢂⠀⢉⢮⡳⡍⢾⣹⠆⡑⣇⠒⠠⠁⠀⠀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠠⠈⡀⠀⢈⠒⣳⠹⡜⣭⠇⡘⡤⢉⠐⠀⠀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⡔⠀⢀⢣⢏⡵⢸⡭⡇⠐⡱⢈⠀⠀⢰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡸⣿⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⢡⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⡐⠀⠀⢎⡞⡔⢣⡟⡄⠨⡑⢂⠈⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠐⠀⠈⠔⣪⢑⢣⡻⡅⢀⡓⠠⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⢨⠀⠠⢉⢦⡉⠦⣝⠖⠀⡜⠠⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⢿⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠰⠀⠐⡈⢦⡑⠸⡼⣩⠀⡜⠠⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⡁⠀⡘⡰⢌⠡⣳⠥⡀⢆⠡⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣹⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⢀⠀⠤⣑⢊⠱⣜⡣⠄⡊⠄⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⣼⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⡄⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣗⠀⠀⠠⠀⠂⡌⢆⠓⣼⢣⠅⡘⢀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢡⣿⣿⣿⣿⣿⣿⣿⡇⣿
⣿⣿⣿⢸⣿⣿⣿⣿⣷⡀⠙⢿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠐⠀⠡⢘⠢⢩⡜⣧⠂⢁⠂⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠁⣼⣿⣿⣿⣿⣿⣿⣿⠅⣿
⣿⣿⣿⣆⡻⢿⣿⣿⣿⣷⣄⠀⠈⠙⠻⠿⣿⣿⣿⣿⠀⠀⠈⠀⠄⢣⠘⠤⣛⣮⢱⡀⠂⢰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⠁⢀⣼⣿⣿⣿⣿⣿⣿⣿⡿⣸⣿
⣿⣿⣿⣿⣿⣶⢍⣥⣶⣶⣶⣶⣶⡶⠖⠒⣒⣒⣒⣒⣂⠀⠀⠄⡈⠤⣉⠒⣽⣎⢧⢂⠁⢀⣒⣒⣒⣒⣒⣒⠲⠬⣭⣭⣭⣤⣤⣤⣀⣀⣛⣛⠻⠿⠿⠿⠛⣛⣩⣴⣿⣿
⣿⣿⣿⣿⣿⢣⣿⣿⣿⣿⣿⣿⢋⡴⣿⣿⣿⣿⣿⣿⡿⠀⠀⠀⢀⠂⠄⡉⢾⡙⢎⠆⠀⠸⢿⣿⣿⣿⣿⣿⣿⡿⢶⠉⣿⣿⣿⣿⣿⣿⣿⣿⠇⣳⣦⢻⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡟⢸⣿⣿⣿⡿⣿⣿⣦⡙⠉⠉⠁⠀⢀⣀⣀⠀⠀⠈⠀⢀⠂⠐⢨⠓⡌⠐⠀⢠⣀⣀⠀⠀⠀⠈⠉⣉⣤⣾⣿⣿⣿⣿⣿⣿⣿⠃⣼⣿⡟⢸⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⢡⣌⠻⣿⣿⣿⣿⣿⣿⣿⣿⣶⣶⣮⣭⣍⣙⣃⣀⣈⣀⣀⣀⣁⣈⣁⣄⣡⣤⣬⣭⣭⣵⣶⣶⣾⣿⣿⣿⣿⣿⣿⣿⡿⠟⣋⣴⣾⣿⣿⡏⣸⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⢘⣿⣷⣬⣍⣛⠿⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠿⢟⣛⣭⣥⣶⣿⣿⣿⣿⣿⡿⡅⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⠘⣞⣿⣿⣿⣿⣿⣿⣶⣶⣾⣭⣭⣭⣍⣛⣛⣛⣛⣛⣛⣛⣛⣛⣛⣛⣋⣽⣭⣭⣭⣭⣭⣽⣶⣶⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡽⡁⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⠈⣷⢫⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡷⣛⢰⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡆⢧⡻⣷⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⢷⠃⣼⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣧⢸⢱⣯⡟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣾⣭⢠⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⡄⢫⡜⡿⣽⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢿⣝⡳⠌⣼⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣷⠈⣞⣹⢳⡿⣽⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣯⢻⡜⡑⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣧⡐⢥⠻⣜⠷⣯⢷⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣟⣯⢿⡱⢏⠌⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣷⡄⠛⣬⢛⡭⣟⠾⣽⣳⢿⣻⢿⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣿⣻⢾⣽⡻⣎⠷⡉⢢⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠨⢧⡹⢎⡿⣱⢏⡯⡽⢯⣻⠷⣯⢿⡽⣿⣻⢿⡿⣿⢿⡿⣟⣿⣟⡿⣽⢷⣻⢾⡽⣺⣝⣮⢷⡹⣎⠃⣱⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⢣⢻⣝⡶⣝⣮⣳⡽⣣⢯⣟⡼⣯⣽⣳⣯⡿⣽⣯⣿⣽⣿⣾⣽⣿⣯⣿⣯⣿⣽⣷⣻⣞⣯⢗⡎⣰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⢻⡾⣽⣻⣞⣷⣿⣟⣿⣾⣿⣷⣿⣿⣷⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡽⣎⢠⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⡄⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡷⠀⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡅⠘⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⠐⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⢨⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⢼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⢣⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣝⡻⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⢛⣵⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣶⣭⣭⣿⣛⣛⣛⣛⣛⠿⠿⠿⠿⠿⠿⠿⠿⠿⢿⣛⣛⣻⣭⣭⣶⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿

but one thing is really bothering me, and its the background. I don't like all these dots i want them to go away
thankfully this tool can fix this
~~~
braille-art-aesthetics -irlf inputs/input.txt
~~~
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠠⠀⠀⠀⠀⠀⠀⠀⠀⠄⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⠂⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠐⠄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⠊⠀⠀⢀⢠⠐⢐⣀⠶⣒⣖⢲⣢⠤⡄⣀⠀⠀⠀⠈⢢⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠜⠀⠀⢀⠰⡌⢖⠪⠁⠬⠐⠀⠀⠀⢄⠀⠀⢁⡈⠄⢀⠀⠀⠱⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡰⠁⠀⠀⢀⠢⡱⠘⠀⠀⠀⠀⢀⠀⠄⢶⣿⠢⣄⠀⠈⠀⠀⠐⡀⠀⢣⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⠃⠀⠀⠀⢂⠱⠀⠀⡠⠂⢌⡐⠂⠌⠰⠀⣯⠁⠀⠤⠐⢀⠀⠀⠀⠄⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡎⠀⠀⠀⠈⠄⠂⠀⡸⣔⡡⠆⠸⣁⠈⡐⠀⡣⠀⢈⡜⢁⠂⣝⠧⡄⠀⠀⢱⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢰⠁⠀⠀⠀⢈⠌⢄⠣⡟⠎⡁⠀⢀⢨⡐⠤⢁⡇⠀⢆⠌⠀⣙⠮⣟⠄⠀⠀⠸⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡜⠀⠀⠀⠀⠄⡘⢄⠻⠀⣠⣇⠀⢀⡄⣣⠜⠀⣇⠠⠜⢀⡄⠀⠀⢟⠀⠃⠀⠘⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⢀⠂⡱⠈⠒⣀⡉⡉⣉⢉⡁⠌⠀⢆⠧⡄⠁⠾⠷⠤⣴⡆⠀⠀⠀⠰⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠇⠀⠀⠀⢀⠂⠡⢄⠳⣰⢯⣷⣯⠷⢉⣁⡬⢎⣶⡄⢀⠒⠦⣄⡄⢠⠀⠀⠀⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡜⠀⠀⠓⠀⠀⠠⢈⠑⢌⢣⡙⣪⣍⢿⠀⡀⠈⠙⠋⢞⠑⠀⠂⠀⢙⠾⢣⠀⡀⠀⡸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢇⠀⡅⠀⠀⠠⡁⠄⠨⠄⢠⡿⡵⢫⢯⣹⡝⡧⠄⠀⠀⠀⠀⢀⠤⡈⢞⡀⠐⠀⠀⡎⠆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⡄⡘⠀⠃⠰⠀⠀⠁⠰⠀⠀⠀⠀⠈⠓⠐⠲⠌⠄⡤⡤⠌⠲⠢⠑⠂⠹⠆⠀⢰⡌⡆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢱⠰⡑⠆⠀⠁⠠⠀⠇⡀⠄⠀⠀⠀⡀⡀⡄⣤⡠⣄⢀⠀⠀⠀⠀⠀⠀⠀⠀⡾⠱⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠣⡐⠂⠀⡀⠐⡀⠐⡀⢈⣦⠀⠠⠁⡅⣥⢩⣩⡛⣘⣐⠀⠀⠀⡀⠀⠀⠐⢡⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⡐⠠⠁⠆⠨⠜⣷⣄⠀⠁⠉⠌⠉⠃⠛⠀⠀⣠⠞⠀⠀⠀⡘⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠄⠡⠘⠠⠙⣲⢻⣋⡴⠖⠶⠖⠢⠄⢠⢞⡡⠈⠀⠀⢰⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⠀⠀⠀⠂⠁⠁⢂⠡⣛⠷⣶⢶⣶⣶⡖⡦⢉⠚⡀⠀⠀⠰⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢇⠆⠀⠀⠀⠀⠠⠀⠐⠠⠙⡌⠯⣙⠮⠱⡉⠂⠁⠀⠀⠀⠀⠀⠑⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡠⠃⠸⠀⠡⠀⠀⠀⠀⠀⠀⠀⠀⠐⠀⠂⠁⠀⠀⠀⠀⠀⠀⠀⠀⢀⣷⡑⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠎⠀⠀⢘⡀⠣⢁⠒⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⣿⣿⣎⢢⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢀⢄⣢⣤⣤⣤⣦⣷⣭⣯⣭⢁⠀⠀⠀⠰⠀⡐⠈⡜⢬⣣⢀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣿⣿⣿⣿⣧⡡⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣤⣔⠠⡀⠀
⠀⠀⢰⢡⣿⣿⣿⣿⣿⣿⣿⣿⣿⢣⣿⡆⠀⠀⠀⡃⢀⠐⣌⢳⢧⣛⠶⣦⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣷⡙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡜⡄
⠀⠀⢸⢸⣿⣿⣿⣿⣿⣿⣿⣿⢣⣿⣿⣿⣄⠀⠀⠁⡂⠀⠌⡞⣧⢏⣟⣾⣽⢸⡓⡶⡐⢄⠂⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⡙⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢇⠇
⠀⠀⠈⡰⢠⣥⣬⣥⣭⣭⣭⢅⣾⣿⣿⣿⣿⣷⠀⠠⢁⠀⡘⡝⣾⡹⣎⣿⣯⠰⣙⠶⣉⠆⠌⢀⠀⠀⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣷⠩⣭⣭⣭⣭⣭⣭⣭⣭⣭⡁⡎⠀
⠀⠀⢸⢰⣶⣶⣶⣶⣶⣶⡆⣼⣿⣿⣿⣿⣿⣿⠀⠀⢌⠀⠐⣹⠾⣵⣛⣾⣿⠀⣏⢞⡰⢈⠂⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⢶⣶⣶⣶⣶⣶⣶⣶⣶⣶⡌⡆
⢀⠀⠸⢸⣿⣿⣿⣿⣿⣿⢱⣿⣿⣿⣿⣿⣿⣿⡇⠅⢈⠀⠈⣖⡻⢧⡻⣼⣿⡀⢎⡳⢌⢂⡁⠀⠀⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡜⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⡇
⡇⣛⠛⢸⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⡌⠀⠐⠬⣽⡳⡝⣞⣿⠆⡹⣜⠂⠆⡀⠀⠀⠀⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣇⢻⣿⣿⣿⣿⣿⣿⣿⣿⡇⡇
⡄⠼⠘⢸⣿⣿⣿⣿⣿⢱⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⢐⠁⠀⡙⢶⡽⣙⢮⣟⡇⠴⣩⠎⡐⠀⠀⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡜⣿⣿⣿⣿⣿⣿⣿⣿⡇⡇
⠑⠜⢃⢸⣿⣿⣿⣿⣿⣸⣿⣿⣿⣿⣿⣿⣿⣿⡇⢈⠀⢂⠀⢉⢮⡳⡍⢾⣹⠆⡑⣇⠒⠠⠁⠀⠀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠠⠈⡀⠀⢈⠒⣳⠹⡜⣭⠇⡘⡤⢉⠐⠀⠀⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⡔⠀⢀⢣⢏⡵⢸⡭⡇⠐⡱⢈⠀⠀⢰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡸⣿⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⢡⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⡐⠀⠀⢎⡞⡔⢣⡟⡄⠨⡑⢂⠈⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠐⠀⠈⠔⣪⢑⢣⡻⡅⢀⡓⠠⠀⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⣿⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡆⠀⢨⠀⠠⢉⢦⡉⠦⣝⠖⠀⡜⠠⠀⢀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣧⢿⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠰⠀⠐⡈⢦⡑⠸⡼⣩⠀⡜⠠⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣻⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⡁⠀⡘⡰⢌⠡⣳⠥⡀⢆⠡⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣹⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⠀⠀⢀⠀⠤⣑⢊⠱⣜⡣⠄⡊⠄⠀⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡏⣼⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⡄⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣗⠀⠀⠠⠀⠂⡌⢆⠓⣼⢣⠅⡘⢀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢡⣿⣿⣿⣿⣿⣿⣿⡇⡇
⠀⠀⢸⢸⣿⣿⣿⣿⣷⡀⠙⢿⣿⣿⣿⣿⣿⣿⣿⣿⠀⠀⠐⠀⠡⢘⠢⢩⡜⣧⠂⢁⠂⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠁⣼⣿⣿⣿⣿⣿⣿⣿⠅⡇
⠀⠀⠈⠆⡻⢿⣿⣿⣿⣷⣄⠀⠈⠙⠻⠿⣿⣿⣿⣿⠀⠀⠈⠀⠄⢣⠘⠤⣛⣮⢱⡀⠂⢰⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⠁⢀⣼⣿⣿⣿⣿⣿⣿⣿⡿⡸⠀
⠀⠀⠀⠀⠈⢐⢍⣥⣶⣶⣶⣶⣶⡶⠖⠒⣒⣒⣒⣒⣂⠀⠀⠄⡈⠤⣉⠒⣽⣎⢧⢂⠁⢀⣒⣒⣒⣒⣒⣒⠲⠬⣭⣭⣭⣤⣤⣤⣀⣀⣛⣛⠻⠿⠿⠿⠛⡛⠩⠐⠁⠀
⠀⠀⠀⠀⢠⢣⣿⣿⣿⣿⣿⣿⢋⡴⣿⣿⣿⣿⣿⣿⡿⠀⠀⠀⢀⠂⠄⡉⢾⡙⢎⠆⠀⠸⢿⣿⣿⣿⣿⣿⣿⡿⢶⠉⣿⣿⣿⣿⣿⣿⣿⣿⠇⣳⣦⢣⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⡜⢸⣿⣿⣿⡿⣿⣿⣦⡙⠉⠉⠁⠀⢀⣀⣀⠀⠀⠈⠀⢀⠂⠐⢨⠓⡌⠐⠀⢠⣀⣀⠀⠀⠀⠈⠉⣉⣤⣾⣿⣿⣿⣿⣿⣿⣿⠃⣼⣿⡟⢸⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢰⢡⣌⠻⣿⣿⣿⣿⣿⣿⣿⣿⣶⣶⣮⣭⣍⣙⣃⣀⣈⣀⣀⣀⣁⣈⣁⣄⣡⣤⣬⣭⣭⣵⣶⣶⣾⣿⣿⣿⣿⣿⣿⣿⡿⠟⣋⣴⣾⣿⣿⡏⡸⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢸⢘⣿⣷⣬⣍⣛⠿⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠿⢟⣛⣭⣥⣶⣿⣿⣿⣿⣿⡿⡅⡇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢸⠘⣞⣿⣿⣿⣿⣿⣿⣶⣶⣾⣭⣭⣭⣍⣛⣛⣛⣛⣛⣛⣛⣛⣛⣛⣛⣋⣽⣭⣭⣭⣭⣭⣽⣶⣶⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡽⡁⡇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⢸⠈⣷⢫⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡷⣛⢰⠁⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠈⡆⢧⡻⣷⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⢷⠃⡜⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⢣⢸⢱⣯⡟⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⣾⣭⢠⠃⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠘⡄⢫⡜⡿⣽⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢿⣝⡳⠌⡜⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⢱⠈⣞⣹⢳⡿⣽⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣯⢻⡜⡑⡜⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠣⡐⢥⠻⣜⠷⣯⢷⣿⣻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣟⣯⢿⡱⢏⠌⡜⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠑⡄⠛⣬⢛⡭⣟⠾⣽⣳⢿⣻⢿⡿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⣿⣻⢾⣽⡻⣎⠷⡉⢢⠊⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠈⢆⠨⢧⡹⢎⡿⣱⢏⡯⡽⢯⣻⠷⣯⢿⡽⣿⣻⢿⡿⣿⢿⡿⣟⣿⣟⡿⣽⢷⣻⢾⡽⣺⣝⣮⢷⡹⣎⠃⡱⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢆⢣⢻⣝⡶⣝⣮⣳⡽⣣⢯⣟⡼⣯⣽⣳⣯⡿⣽⣯⣿⣽⣿⣾⣽⣿⣯⣿⣯⣿⣽⣷⣻⣞⣯⢗⡎⡰⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⡆⢻⡾⣽⣻⣞⣷⣿⣟⣿⣾⣿⣷⣿⣿⣷⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡽⣎⢠⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢱⠸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣟⡄⡎⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡷⠀⢇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡅⠘⡄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣆⠀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⠐⡅⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⣸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⢨⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡇⢼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⢸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢇⢹⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⢣⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠐⠝⡻⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⢛⠕⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠐⠉⠉⠻⠛⠛⠛⠛⢛⠿⠿⠿⠿⠿⠿⠿⠿⠿⢿⠛⠛⠻⠉⠉⠂⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀

voilà! this looks much nicer
what the tool basically did was clear all dots that didn't have an empty dot after them if from left to right or an empty dot if from right to left
essentially the 'r' option clears everything on the right starting from the end and finishing at where there is a dot, similar thing with the l option

i use this tool mainly so i can beautify braille art, ive got a tonna ideas I want to implement such as borders (and perhaps even AI) but i haven't really gotten there yet

TODO: 
rewrite this in Rust, implement as many ideas that come to mind as possible (its super easy given how I abstracted the code)
