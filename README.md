# Godot Tiny MMO Demo

A small-scale MMO / MMORPG developed with Godot Engine 4.3, without relying on the built-in multiplayer nodes.  
Both the client and server are included within the same project, utilizing export presets to manage the separation.  
These presets allow to export only the client-side without including server components, and vice versa.  
Feel free to explore the project details in the [**Wiki**](https://github.com/SlayHorizon/godot-tiny-mmo-demo/wiki).

![M.M.O.A.R.P.G](https://github.com/user-attachments/assets/8831d50b-7350-47b2-adbc-5d1cb3992301)

## 🚀 Features

The current and planned features are listed below:

- [X] **Client-Server connection** through `WebSocketMultiplayerPeer`
- [x] *Playable on web browser**
- [X] **Authentication system** with Login UI
- [X] **Entity synchronization** for players within the same instance
- [X] **Instance-based maps** with traveling between different map instances
- [ ] **Basic RPG class system** with three initial classes: Knight, Rogue, Wizard
- [ ] **Private instances** for solo players or small groups
- [ ] **Basic combat system**
- [ ] **Entity interpolation** to handle rubber banding
- [ ] **Instance-based chat**
- [ ] **Persistent data saving** on the server

*...and more features in the pipeline.*

You can track development and report issues by checking the [**open issues**](https://github.com/SlayHorizon/godot-tiny-mmo-template/issues) page.

## 🛠️ Getting Started

To get started with the project, follow these steps:
1. Clone this repository.
2. Open the project with **Godot 4.3**
3. In the Debug tab, choose **Customizable Run Instance...**
4. Enable **Multiple Instances** and set at least 2 or more.
5. Under **feature tags**, ensure to have:
   - Exactly **one** "server" tag
   - At least **one or more** "client" tags
6. Run the project!

Example setup for multiple instances:  
![multiple-instances-screenshot](https://github.com/user-attachments/assets/5cf7cc61-e8e6-468d-b917-b505a59168cf)

## 🤝 Contributing

If you have ideas or improvements in mind, fork this repository and submit a pull request. You can also open an issue with the tag `enhancement`.

### To contribute:
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a **Pull Request**

## Credits
- Screenshots provided by [@WithinAmnesia](https://github.com/WithinAmnesia).  
- Thanks to [@Anokolisa](https://anokolisa.itch.io/dungeon-crawler-pixel-art-asset-pack) for allowing us to use its assets for this open source project!
