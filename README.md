# Copilot_plugin_patch
This is a quick fix for "Failed to initiate the GitHub login process. Please try again".

Tested on:

Android studio
IntelliJ IDEA Community Edition
How to use :

1- Download and install 7-zip https://www.7-zip.org/

2- Download the above patch file "CopilotAgent.class"

3- Update your github-copilot to the latest version, then close the IDE

4- Navigate to

For IntelliJ IDEA: ...\AppData\Roaming\JetBrains\IdeaIC2022.1\plugins\github-copilot-intellij\lib

For AndroidStudio: ...\AppData\Roaming\Google\AndroidStudio2021.2\plugins\github-copilot-intellij\lib

5- Right click on core-V.x.xx then open archive with 7-Zip (Don't extract just open it )

6- Navigate to ...\core-1.1.25.jar\com\github\copilot\lang\agent\

7- Replace CopilotAgent.class with the Patched one

8- close 7-Zip

done !!
