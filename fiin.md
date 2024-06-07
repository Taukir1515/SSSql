apk rev engg
*.dex
dex > jar
jar > read > jdgui
class vulnerab class
class file > exploit

Full Process

# APKtoolkit
1. Import APK to apktool
2. Decompile and Extract
3. copy 'classes.dex' from Extracted folder

# dex2jar
4. paste "classes.dex" to dex2jar-2.0 folder
5. copy dex2jar-2.0 folder path

# Execute dex2jar with CMD
6. D:
7. cd path\to\folder
8. d2j-dex2jar.bat classes.dex

file created as "classes-dex2jar"

# jd-gui
9. select location of "classes-dex2jar"
10. Open
