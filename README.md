# ZPort: The Pirate Port System

**ZPort** is a modular and flexible Port System designed for both **text-based RPG apps** and **tabletop RPG (TTRPG)** systems. Whether you are developing a digital pirate-themed adventure or running a tabletop campaign, ZPort provides an immersive port experience, enabling dynamic interactions with ports, trade, quests, and travel.

---

## Compatible With:

- **Text-Based RPG Apps**
  - Integrates seamlessly with text RPG apps, using HTML/JS widgets and Firebase for dynamic content and multiplayer support.
  - Ideal for building interactive pirate-themed adventures.

- **TTRPG Systems**
  - Printable or screen-share-friendly PDFs for each port, ready for tabletop use.
  - GM tools for random port quests, rumors, trade shifts, and events.
  - Fully customizable for homebrew settings in pirate worlds.

---

## Core Features

- **Docking & Departing**
  - Manage travel costs, durations, and risks with optional modifiers.
  
- **Trade Interface**
  - Simulate local economies with dynamically changing goods, including black market trade and smuggling opportunities.

- **Port Quests & Rumors**
  - Generate local quests, procedurally generated rumors, and events.
  - Includes rumor tables for easy use by GMs in tabletop games.

- **Port Services**
  - Taverns, inns, guilds, doctors, and shipwrights are available.
  - Expandable service templates to support homebrew content.

- **World Map Navigation**
  - Travel across a dynamically generated world map with unlockable routes.
  - Weather, reputation, and world events affect travel and quests.

---

## Example Port JSON (for App Integration)

```json
{
  "portId": "tortuga",
  "name": "Tortuga",
  "region": "Crimson Gulf",
  "services": ["inn", "blackMarket", "shipwright", "doctor"],
  "questTypes": ["bounty", "delivery", "rescue"],
  "fameRequired": 10,
  "tradeGoods": ["rum", "spices", "silk"]
}
```

---

## License

ZPort is licensed under the **Apache License 2.0**, allowing you to freely use, modify, and distribute the code. However, it provides patent protection, meaning contributors grant you patent rights for their contributions.

You can find the full license text in the `LICENSE` file or at the official site:  
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

For a more detailed explanation, see the `LICENSE` and `NOTICE` files included in this repository.

---

## Credits

- **ZPort**: Developed as part of the **Captain’s Quill** universe, designed and maintained by **Pir8 Eye Web Solutions LLC** on behalf of **ZHodlers LLC**.
- For more information about the **Captain's Quill** project and other assets, visit the official website at [Captain's Quill](#).

---

## Planned Features

- **Port Siege Events**: PvE/PvP mechanics for intense port battles.
- **Seasonal Trade Cycles**: Trade goods that change seasonally.
- **Port Factions**: Various factions vying for control over ports, with branching quests.
- **Port Storylines**: Rich, narrative-driven port events and quests.

---

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/zport.git
   ```
2. **For app developers**: Integrate `zport.js` into your text RPG interface to add port interactions.
3. **For TTRPG GMs**: Print or share the port sheets and rumor tables for easy use in your tabletop game.

---

## Support & Community

- If you encounter issues, feel free to open an issue in the **[GitHub Issues section](https://github.com/your-username/zport/issues)**.
