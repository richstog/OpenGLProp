# OpenGLProp

Settings in VS Project Properties:
Project -> Properties -> Linker -> Input -> Additional Dependencies -> Add "GLFW\glfw3.lib;opengl32.lib;";
Project -> Properties -> VC++ Directories -> Include Directories -> Add "$(SolutionDir)\Linking\include;";
Project -> Properties -> VC++ Directories -> Library Directories -> Add "$(SolutionDir)\Linking\lib;".
