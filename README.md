# JMEInputManagerModifiers
Add modifiers (Shift, Control) to JME InputManager.java
To implement this:
1) Make a new project, i.e. \Modifiers
2) Copy the sources from C:\Program Files\jmonkeyplatform\jmonkeyplatform\libs\jMonkeyEngine3-sources.zip into your \Modifiers project's, src directory.  Put my InputManager.java into the com.jme3.input directory and then open Main.java and compile.  You'll have to modify all the classes that have onAction() in them.  The compiler will tell you what files to fix.  
3) Make a new folder in a JME\libs\JME3-core.dir.
Copy com, Common, Interface, Jme3tools into JME\libs\JME-core.dir.  Then in your other projects, refer to JME\libs\JME3-core.dir.  If you set the InputManager.java setEcho(true), it will print debug info and show you what it's thinking.    If you have menus and you hit the Alt key, you may have to hit Alt-Esc or Alt-Tab.  
