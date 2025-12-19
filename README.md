description:
this is the best submodule example, here "say_hello" is the submodule, "6kconfig_demo" is the main application, here cone the application from "7sub_module_example" 
will clone both the folder, the git is considering that both are submodule, but by practical "7sub_module_example" is the submodule, once the git clone is 
initialized then you can find two folders, both will be empty, as they are submodules, now the command "git submodule update --init --recursive" will update 
both the submodules, 
build procedure:
now enter into the folder "6kconfig_demo", there issue the command "west build -p always -b nucleo_f411re", now the project will build including the submodule
