# HADash – What's New



### v1.6.0 – 1 Sep 2025
- Added Light card
- Added Thermostat Card

<details>
<summary>Changelog</summary>

**v1.6.0 – 1 Sep 2025**
- Added Light card
- Added Thermostat Card
- Minor bug fixes

**v1.5.0 – 13 Aug 2025**  
- Multiple dashboard views support (sections & masonry)  
- Custom icon support  
- Performance improvements and bug fixes  

**v1.4.7 – 12 Aug 2025**  
- Bug fixes  
- Added Debug section  

**v1.4.5 – 10 Aug 2025**  
- Vertical Stack Card  
- HTTPS support  
- Fixed dashboard name conflicts  

**v1.4 – 8 Aug 2025**  
- Sensor Card, Clock Card  
- Improved statistics graph  
- Fullscreen mode for cameras/graphs  
- Badges in section headings  
- Animated toggle switches  
- Auto-hiding top toolbar  

</details>
 

---

# Connecting HADash to Your Home Assistant

Follow these steps to connect the HADash app to your Home Assistant instance:

### 1. Create an API Key
To create an API key:

- Go to your Home Assistant web interface.
- Click on your **user profile** (bottom left corner).
- Scroll down to the **Long-Lived Access Tokens** section.
- Click **Create Token**, and give it any name (e.g., `hadash-key`).
- After clicking "OK", you'll see your API key. **Copy it immediately**, as it will not be shown again after closing the window.
<img width="2528" height="1226" alt="Screenshot 2025-07-22 at 16 35 08" src="https://github.com/user-attachments/assets/e5f9e72f-643e-47de-bdf1-d2ad60a1ec85" />


---

### 2. Add Your Home Assistant Server in HADash

- Open the **HADash** app.
- Navigate to the **Servers** tab.
- Tap **Add New Server**.
- Open the **Apple TV Remote** on your iPhone and enter the required information:
  - **Home Assistant IP address**
  - **API key** you created earlier

---

### 3. You're All Set!

Congratulations — HADash is now connected!  
If you wish, you can customize dashboards via the Home Assistant web interface. HADash will automatically display them.

---

# Cards Support

| Card Name               | Status / Version         | Notes / Supported Functions       |
|-------------------------|-------------------------|-----------------------------------|
| Light Card               | ✅ Supported, v1.6     | Only toggle action                |
| Thermostat Card          | ✅ Supported, v1.6     | -                                 |
| Vertical Stack Card      | ✅ Supported, v1.4.5      | -                                 |
| Heading Card             | ✅ Supported, v1.4        | -                                 |
| Sensor Card              | ✅ Supported, v1.4        | -                                 |
| Clock Card               | ✅ Supported, v1.4        | -                                 |
| Entity Card              | ✅ Supported, v1.4        | -                                 |
| Entities Card            | ✅ Supported, v1.0        | -                                 |
| Gauge Card               | ✅ Supported, v1.0        | -                                 |
| Weather Card             | ✅ Supported, v1.0        | -                                 |
| Statistics Graph Card    | ✅ Supported, v1.0        | Only one entity and one state     |
| Markdown Card            | ✅ Supported, v1.0        | Simplified                        |
| Picture Elements Card    | ✅ Supported, v1.0        | Elements are not clickable        |
| Picture Card             | ✅ Supported, v1.0        | -                                 |
| Picture Entity Card      | ✅ Supported, v1.0        | Only cameras                      |
| Grid Card                | 🔜 Work In Progress     | partially works in v1.6           |
| Button Card              | 🔜 Work In Progress     | -                                 |
| Horizontal Stack Card    | ⏳ Planned              | -                                 |
| Statistic Card           | ⏳ Planned              | -                                 |
| Glance Card              | ⏳ Planned              | -                                 |
| Picture Glance Card      | ⏳ Planned              | -                                 |
| To-do List Card          | ⏳ Planned              | -                                 |
| Entity Filter            | ⏳ Planned              | -                                 |
| History Graph            | ⏳ Planned              | -                                 |
| Button Card              | ⏳ Planned              | -                                 |
| Energy Distribution Card | ⏳ Planned              | -                                 |
| Area Card                | ⏳ Planned              | -                                 |
| Webpage Card             | ❌ Not Planned          | Apple does not allow using Apple TV as a browser |


# Resources
- [![Discord Chat](https://img.shields.io/discord/1403038611661918389?logo=discord&logoColor=ffffff&color=7389D8)](https://discord.gg/a8Ucmcv8J4)
- [![Reddit Community](https://img.shields.io/reddit/subreddit-subscribers/HADashATV?logo=reddit)](https://www.reddit.com/r/HADashATV/)
