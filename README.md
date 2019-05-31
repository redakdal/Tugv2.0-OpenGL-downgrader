# Tugv2.0-OpenGL-downgrader
This is a project to attempt to downgrand Tugv2.0 Opengl verison, as older cards do not support version 4.3, this project will lower these requirements so you won't crash when trying to play it
nothing is here yet,  but will include the directories that the changed ext is going to be at, and should be as easy as extracting the zip to the TUGv2.0 file location
this is to get you started on what are issue kinda looks like https://stackoverflow.com/questions/16100308/how-to-copy-texture1-to-texture2-efficiently/16100837#16100837

Extisons that need to be replaced with 4.0 or earlier opengl ext are :
    ARB_copy_image

    EXT_copy_image

    NV_copy_image

    OES_copy_image
    
    we do not know at the moment which ext NK devs used, when we do find out, these extesions have to be replaced, so that Low end hardware 
   can play TUGv2.0, and hopefully this leads us to a version that anyone can play via the browser or unity
