

Place the following files here:

From (ANDROID_SDK)\extras\android\support\v7\appcompat\libs:
 * android-support-v4.jar
 * android-support-v7-appcompat.jar
 * appcompat.zip

To create appcompat.zip
-----------------------
1. Build the v7 support library in eclipse. 
 * Choose new -> project
 * Android project from existing source
 * Finish

2. Build

3. Move the drawable folders from bin\res\crunch\* to bin\res\

4. Compress only the bin and res folders into appcompat.zip