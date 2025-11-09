# ZSafe
A secure and interactive verification system that uses number pad codes to verify users, similar to a digital safe combination.
> 💡 **Built for the Zygnal Ecosystem — to download and use this extension, you must be part of the Zygnal Ecosystem.**  
> This extension (cog) is part of the **Zygnal Ecosystem** and is only available through its supported platforms.  
> You can use it with:  
> - The **[Discord Bot Framework](https://github.com/TheHolyOneZ/discord-bot-framework)** — ideal for developers who want full control and flexibility *(includes an integrated extension marketplace)*, or  
> - The **[ZygnalBot](https://zygnalbot.de)** — a prebuilt, plug-and-play Discord bot *(also includes an integrated extension marketplace)*.  
>
> Browse and install extensions at [zygnalbot.com/extension](https://zygnalbot.com/extension).  
> For help or community discussions, join us on Discord: [discord.gg/sgZnXca5ts](https://discord.gg/sgZnXca5ts)
# 🔐 ZSafe Verification System

A secure and interactive verification system that uses number pad codes to verify users, similar to a digital safe combination.

## ✨ Features

### 🎯 **Interactive Verification**
- **Number Pad Interface** - Users enter codes using an interactive keypad
- **Random Code Generation** - Generates secure random codes (1-8 digits)
- **Real-time Code Display** - Shows entered digits as users type
- **Ephemeral Messages** - Only the user can see their verification process
- **Auto-Expiring Codes** - Codes expire after 5 minutes for security

### 🎨 **Full Customization**
- **Custom Embed Design** - Personalize title, description, and colors
- **Custom Button Labels** - Set your own verification button text
- **Flexible Code Length** - Choose from 1-8 digit verification codes
- **Color Themes** - Use hex colors to match your server's branding

### 🎭 **Role Management**
- **Add Roles** - Automatically give roles after successful verification
- **Remove Roles** - Remove specific roles after verification
- **Multiple Roles** - Configure multiple roles to add/remove at once
- **Role Feedback** - Shows users exactly which roles were changed

### 🔒 **Security Features**
- **User-Specific Verification** - Each verification is isolated to one user
- **One-Time Codes** - Each code can only be used once
- **Timeout Protection** - Prevents multiple pending verifications
- **Automatic Cleanup** - Expired codes are automatically removed

### ⚡ **Easy Setup**
- **All-in-One Menu** - Complete setup through interactive buttons
- **Live Previews** - See embed changes in real-time
- **Quick Deployment** - Post verification with a single command
- **Status Overview** - View all current settings at a glance

## 📋 Commands

### 👑 **Admin Commands**
- `!zsafe` - Open the main setup menu
- `!zsafe-post [channel]` - Post verification embed to a channel
- `!zsafe-status` - View current configuration
- `!zsafe-reset` - Reset all settings
- `!zsafe-help` - Show detailed help information

### 🛠️ **Setup Options** (via `!zsafe` menu)
- **📝 Basic Settings** - Configure code length and button label
- **🎨 Embed Design** - Customize title, description, and colors
- **➕ Add Roles** - Select roles to give after verification
- **➖ Remove Roles** - Select roles to remove after verification
- **📊 View Status** - Check current configuration

## 🎮 How It Works

### **For Users:**
1. Click the verification button
2. Receive a random code (only you can see it)
3. Use the number pad to enter the code
4. Get verified and receive your roles automatically

### **For Admins:**
1. Run `!zsafe` to open setup menu
2. Configure your verification settings
3. Design your custom embed
4. Set up role rewards
5. Use `!zsafe-post` to deploy verification

## ⚠️ Requirements

- **Manage Server** permission for setup commands
- **Manage Roles** permission for role assignment
- Bot needs **Send Messages** permission in target channels
- Bot needs **Embed Links** permission for proper display

## 🎯 Perfect For

- **Member Verification** - Verify new members before giving access
- **Role Gates** - Control access to specific server areas
- **Anti-Bot Protection** - Interactive verification stops automated accounts
- **Custom Onboarding** - Create unique verification experiences
- **Security Checkpoints** - Add verification layers to sensitive channels

---

*Made By TheHolyOneZ*
