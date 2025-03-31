Wurst Client v7
Downloads: https://www.wurstclient.net/download/

Installation guide: https://www.wurstclient.net/tutorials/how-to-install/

Feature list: https://www.wurstclient.net/

Wiki: https://wurst.wiki/

Forum: https://wurstforum.net/

Twitter/X: https://x.com/Wurst_Imperium

YouTube: https://www.youtube.com/@Alexander01998

Donations/Perks: https://ko-fi.com/wurst

Installation
Wurst 7 can be installed just like any other Fabric mod. Here are the basic installation steps:

Run the Fabric installer.
Add the Wurst Client and Fabric API to your mods folder.
Please refer to the full Wurst 7 installation guide if you need more detailed instructions or run into any problems.

Also, this should be obvious, but you do need to have a licensed copy of Minecraft Java Edition in order to use Wurst. Wurst is a cheat client, not a pirate client.

Development Setup
Important

Make sure you have Java Development Kit 21 installed. It won't work with other versions.

Development using Eclipse
Clone the repository:

git clone https://github.com/Wurst-Imperium/Wurst7.git
cd Wurst7
Generate the sources:

./gradlew genSources eclipse
In Eclipse, go to Import... > Existing Projects into Workspace and select this project.

Optional: Right-click on the project and select Properties > Java Code Style. Then under Clean Up, Code Templates, Formatter, import the respective files in the codestyle folder.

Development using VSCode / Cursor
Tip

You'll probably want to install the Extension Pack for Java to make development easier.

Clone the repository:

git clone https://github.com/Wurst-Imperium/Wurst7.git
cd Wurst7
Generate the sources:

./gradlew genSources vscode
Open the Wurst7 folder in VSCode / Cursor.

Optional: In the VSCode settings, set java.format.settings.url to https://raw.githubusercontent.com/Wurst-Imperium/Wurst7/master/codestyle/formatter.xml and java.format.settings.profile to Wurst-Imperium.

Development using IntelliJ IDEA
I don't use or recommend IntelliJ, but the commands to run would be:

git clone https://github.com/Wurst-Imperium/Wurst7.git
cd Wurst7
./gradlew genSources idea
Contributing
Please always contact me before opening a Pull Request. Any method works. That way we can discuss your ideas early and avoid wasting your time working on unwanted features or having to make lots of changes later.

We also have contributing guidelines to help you get started.

Translations
To enable translations in-game, go to Wurst Options > Translations > ON.

The preferred way to submit translations is through a Pull Request here on GitHub. The translation files are located in this folder.

Names of features (hacks/commands/etc.) should always be kept in English. This ensures that everyone can use the same commands, keybinds, etc. regardless of their language setting. It also makes it easier to communicate with someone who uses Wurst in a different language.

License
This code is licensed under the GNU General Public License v3. You can only use this code in open-source clients that you release under the same license! Using it in closed-source/proprietary clients is not allowed!
