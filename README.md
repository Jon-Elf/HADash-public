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

### Supported Cards

HADash currently supports the following card types:

- **Entities Card**
- **Entity Card**
- **Button Card**
- **Gauge Card**
- **Weather Card**
- **Statistics Graph Card** - only one entity and one state
- **Heading Card**
- **Markdown Card** - simplified
- **Picture Elements Card** - elements are not clickable
- **Picture Card**
- **Picture Entity Card** – only cameras
- **Sensor Card**

> ⚠️ Some card types may have limited features or be displayed in a simplified format.

Support for additional card types is planned for future updates.
If you have any requests or suggestions, feel free to [create a ticket](https://github.com/Jon-Elf/HADash-public/issues)


# Resources
- [![Discord Chat](https://img.shields.io/discord/1403038611661918389?logo=discord&logoColor=ffffff&color=7389D8)](https://discord.gg/a8Ucmcv8J4)
