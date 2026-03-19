## 1.1 Preparing for the project

To create your project and get it ready to work on, follow these instructions:

**1.** Open the Unity Hub and install Unity 6.

**2.** Create a new project using Editor version 6.000 LTS, name it “Roguelike”, and select the **Universal 2D** template.

**3.** Enable **Connect to Unity Cloud** and **Use Unity Version Control**.

![Image](images/Screenshot_2026-02-27_193028.png)

This will allow you to use Unity Cloud and Unity Version Control in your project.

**4.** Select **Create project**.

- Once your new Roguelike project is open in Unity, you need to change some default settings for this project.

**5.** In the **Project** window, select **Assets** > **Settings**, then select the **Renderer2D** file.

- This is all the settings used by the rendering pipeline to display your assets in the game.

**6.** In the **Inspector** window, under the **General** section, change the **Default Material Type** from **Lit** to **Unlit**.

- Lit materials are affected by dynamic lighting, where lights can move and be switched on and off for a more realistic look. But Lit materials require additional computation in order to be rendered. As this project uses a traditional pixel art style, where lighting is drawn directly on the sprite, dynamic lighting isn't needed, so Unlit materials should be used, because they are easier and faster to render.
- Now every time a new sprite is created, it will be assigned an Unlit material automatically instead of a Lit one.

Your project is now set up for you to start working on it.

## 1.2 Importing Assets

- Download [the asset package](https://unity-connect-prd.storage.googleapis.com/20241025/13b51e19-dc52-4982-b67a-fdfb35c7a3b8/Roguelike2DTutorialAssets.unitypackege.zip), unzip the file and drag and drop it into the **Assets** folder of the **Project** window.
- The **Import Unity Package** window will open, listing all the assets this package will import into your project.

![Image](images/8e5bd774-272a-4041-91ba-4b25cbb85f95_roguelike-assets.png)