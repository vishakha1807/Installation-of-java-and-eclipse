# Installation-of-java-and-

follow this blog:

https://websiteforstudents.com/how-to-install-eclipse-oxygen-ide-on-ubuntu-167-04-17-10-18-04/

OR

Run all these command:

Step1:

1. sudo add-apt-repository ppa:webupd8team/java

2.sudo apt update

3.sudo apt install oracle-java8-installer

4.select yeson popup.

5. To set the java env.

sudo apt install oracle-java8-set-default

6.javac -version

Step 2: Download Eclipse Oxygen

https://www.eclipse.org/downloads/

Step 3: Install Eclipse IDE

1. tar xfz ~/Downloads/eclipse-inst-linux64.tar.gz

2. ~/Downloads/eclipse-installer/eclipse-inst

3. Select eclipse ide for java ee developers.

4.Install and launch the browser.

Step 4: Create Eclipse App Launcher

1. nano .local/share/applications/eclipse.desktop

2. Next, copy and paste the content below into the file and save

[Desktop Entry]

Name=Eclipse JEE Oxygen

Type=Application

Exec=/home/richard/eclipse/jee-oxygen/eclipse/eclipse

Terminal=false

Icon=/home/richard/eclipse/jee-oxygen/eclipse/icon.xpm

Comment=Integrated Development Environment

NoDisplay=false

Categories=Development;IDE;

Name[en]=Eclipse
