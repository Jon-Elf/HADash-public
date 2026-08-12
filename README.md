# [Download on the App Store](https://apps.apple.com/us/app/hadash/id6748312657)

# HADash – What's New



### v1.10 - 23 Jun 2026
- Added localization: Arabic, Chinese (Simplified), Dutch, French, German, Italian, Japanese, Korean, Portuguese, Russian, Spanish.
- Fixed a bug with Weather Card updates
  
<details>
<summary>Changelog</summary>

**v1.10 - 23 Jun 2026**
- Added localization: Arabic, Chinese (Simplified), Dutch, French, German, Italian, Japanese, Korean, Portuguese, Russian, Spanish.
- Fixed a bug with Weather Card updates

**v1.9.2 - 13 Jun 2026**
- Added fullscreen mode for History
- Added weather forecast support
- Fixed Gauge limits issue
- Optimized data flow for History Graph Card
- Fixed dashboard duplication issue in older Home Assistant versions
- Minor bug fixes

**v1.9 - 6 Jun 2026**
- Added History Graph Card
- Added more Gauge Card styles

**v1.8.2 – 12 Nov 2025**
- Added Glance Card
- Added device registration for the mobile_app platform
- Automatic opening of the last dashboard on app launch
- Optimized memory usage
- Minor visual improvements
- Minor bug fixes

**v1.7.3 - 24 Sep 2025**
- Fixed issue with empty cards in dashboard when using sections layout

**v1.7.2 - 16 Sep 2025**
- Minor visual tweaks for tvOS 26

**v1.7.1 – 13 Sep 2025**
- Added Button Card
- Redesigned the statistics graph card with support for multiple entities and multiple types
- Fixed a bug where dashboards with the original-states strategy were not loading

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

## What's HADash?

HADash is a native Apple TV (tvOS) app that brings your existing Home Assistant dashboards to the big screen.
It connects directly to your Home Assistant instance using a Long-Lived Access Token, displays your current dashboards without reconfiguration, and lets you view and control lights, sensors, cameras, graphs, and other devices from the couch or a wall-mounted display. It supports multiple servers, light/dark/custom themes, live camera feeds, and real-time data.

<img width="3840" height="2160" alt="Simulator Screenshot - Apple TV 4K (3rd generation) - 2026-07-30 at 17 54 46" src="https://github.com/user-attachments/assets/ca3edc86-e50c-4cb9-9420-06a5f2e3da51" />
<img width="3840" height="2160" alt="simulator_screenshot_7DDCDAAA-9D73-4271-ADC7-70D0EDD9A378" src="https://github.com/user-attachments/assets/df674bf3-b703-47df-aa0f-92d78795e37a" />



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
| Button Card              | ✅ Supported, v1.7.1    | -                                 |
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
| Statistics Graph Card    | ✅ Supported, v1.0        | Supports only: min, max, mean     |
| Markdown Card            | ✅ Supported, v1.0        | Simplified                        |
| Picture Elements Card    | ✅ Supported, v1.0        | Elements are not clickable        |
| Picture Card             | ✅ Supported, v1.0        | -                                 |
| Picture Entity Card      | ✅ Supported, v1.0        | Only cameras                      |
| Grid Card                | 🔜 Work In Progress     | partially works in v1.6           |
| Glance Card              | 🔜 Work In Progress     | -                                 |
| Horizontal Stack Card    | ⏳ Planned              | -                                 |
| Statistic Card           | ⏳ Planned              | -                                 |
| Picture Glance Card      | ⏳ Planned              | -                                 |
| To-do List Card          | ⏳ Planned              | -                                 |
| Entity Filter            | ⏳ Planned              | -                                 |
| History Graph            | ⏳ Planned              | -                                 |
| Energy Distribution Card | ⏳ Planned              | -                                 |
| Area Card                | ⏳ Planned              | -                                 |
| Webpage Card             | ❌ Not Planned          | Apple does not allow using Apple TV as a browser |


# Resources
- [![Discord Chat](https://img.shields.io/discord/1403038611661918389?logo=discord&logoColor=ffffff&color=7389D8)](https://discord.gg/a8Ucmcv8J4)
- [![Reddit Community](https://img.shields.io/reddit/subreddit-subscribers/HADashATV?logo=reddit)](https://www.reddit.com/r/HADashATV/)
