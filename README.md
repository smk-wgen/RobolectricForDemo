Import both projects into your eclipse workspace.
Create a robolectric run configuration.
Please refer to the following link to create one.
http://pivotal.github.com/robolectric/eclipse-quick-start.html

Here is how I created the config file.

Eclipse > Run > Run Configurations > Junit 

Run tests in ItDoesntMatterTest

TestRunner > Junit4

Use the Eclipse Junit launcher


Arguments tab > Working Directory > other > ${workspace_loc:ItDoesntMatter}

finally inform Eclipse about your Android_Home

Environment
New variable 
NAME > ANDROID_HOME
VALUE > Location of your Android SDK 
