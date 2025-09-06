<div align="center">

# 🚀 OCI Discord Bot
### Fully Automated Always Free Instance Creator

<img src="https://img.shields.io/badge/OCI-Always_Free-orange?style=for-the-badge&logo=oracle" alt="OCI Always Free">
<img src="https://img.shields.io/badge/Discord-Bot-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord Bot">
<img src="https://img.shields.io/badge/Bash-Automation-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash Automation">
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">

**Easily create Oracle Cloud Infrastructure Always Free instances from Discord!**

[🚀 Quick Start](#🛠️-quick-start) • [📖 Usage](#🎮-usage) • [🔧 Advanced Setup](#🎨-advanced-setup) • [🤝 Contributing](#🤝-contributing)

**English** | [한국어](README_KR.md)

</div>

---

## 🎬 Demo

<div align="center">

### 📱 Discord Bot Commands Demo

```bash
# Example usage in Discord channel
/status                    # Check bot status and instance overview
/launch                    # Instantly create Always Free instance
/log count:5               # View last 5 execution logs
/config                    # Check current configuration
```

### 🧙‍♂️ Setup Wizard Execution Screen

```bash
╔══════════════════════════════════════════════════════════════════════════════╗
║                    🧙‍♂️ OCI Always Free Discord Bot                          ║
║                             Setup Wizard                                    ║
║         Oracle Cloud Infrastructure Always Free Instance Auto Creator      ║
╚══════════════════════════════════════════════════════════════════════════════╝

ℹ️ [12:34:56] 🎯 Always Free Optimized: E2.1.Micro (2x), A1.Flex (4 OCPU, 24GB)
ℹ️ [12:34:56] 🤖 Discord Integration: Slash commands, Real-time monitoring
ℹ️ [12:34:56] 🔧 Full Automation: Auto-detect config, Real-time validation
```

### 📊 Always Free Usage Monitoring

```bash
📊 Always Free Usage:
  • Shape: VM.Standard.A1.Flex
  • Specs: 2 OCPU, 12GB RAM
  • A1 Total Limit: 2/4 OCPU, 12/24GB RAM
  • Remaining Resources: 2 OCPU, 12GB RAM
  • Boot Volume: 100/200GB (Free)
```

</div>

---

## 💎 Oracle Cloud Always Free - What Is It?

<div align="center">

**Oracle Cloud Always Free** provides powerful cloud infrastructure at no cost forever - perfect for developers, students, and small projects!

</div>

### 🎁 What Oracle Always Free Provides

<table>
<tr>
<td width="50%">

#### 🖥️ **Compute Instances**
- **2x E2.1.Micro** (AMD EPYC)
  - 1 OCPU, 1GB RAM each
  - Perfect for: Web servers, APIs, bots
- **4 OCPU A1.Flex** (ARM Ampere)
  - 4 OCPU, 24GB RAM total
  - Configurable: 1-4 instances

</td>
<td width="50%">

#### 💾 **Storage & Network**
- **200GB Block Storage**
- **10GB Object Storage**
- **Load Balancer** (10 Mbps)
- **VCN & Security Lists**
- **Autonomous Database** (20GB)

</td>
</tr>
</table>

### 🎮 Popular Use Cases & Examples

<details>
<summary><b>🎯 A1.Flex (ARM) - High Performance Applications</b></summary>

#### 🎮 **Gaming Servers**
```bash
# Minecraft Server (Recommended: 2 OCPU, 8GB)
Shape: VM.Standard.A1.Flex
Config: 2 OCPU, 8GB RAM
Players: ~10-20 concurrent
Performance: Excellent for modded servers
```

#### 🌐 **Development Environment**
```bash
# Full Development Stack
Shape: VM.Standard.A1.Flex  
Config: 4 OCPU, 24GB RAM
Stack: Docker, Kubernetes, CI/CD
Perfect for: Team development, microservices
```

#### 🤖 **AI/ML Workloads**
```bash
# Machine Learning Training
Config: 4 OCPU, 24GB RAM
Frameworks: TensorFlow, PyTorch
Use: Model training, data processing
```

</details>

<details>
<summary><b>⚡ E2.1.Micro (AMD) - Lightweight Services</b></summary>

#### 🌐 **Web Applications**
- Personal websites & blogs
- REST APIs & microservices
- Discord/Telegram bots
- Monitoring services

#### 📊 **Database & Caching**
- Small databases (PostgreSQL, MySQL)
- Redis cache servers
- Message queues
- Log aggregators

</details>

### 💰 Always Free vs Paid Comparison

| Feature | Always Free | Paid Plans |
|:---:|:---:|:---:|
| **Cost** | $0/month forever | Pay-as-you-use |
| **Performance** | Production-ready | Scalable |
| **Duration** | No time limit | Flexible |
| **Support** | Community | Professional |

> **💡 Pro Tip**: Always Free is perfect for learning, development, and small production workloads. Scale to paid plans when you need more resources!

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🎯 **Always Free Optimized**
- ✅ **E2.1.Micro** (up to 2 instances)
- ✅ **A1.Flex** (4 OCPU, 24GB RAM)
- ✅ 200GB Boot Volume Free
- ✅ Real-time limit checking

</td>
<td width="50%">

### 🤖 **Discord Integration**
- ✅ Slash command support
- ✅ Real-time status monitoring
- ✅ Log and error notifications
- ✅ PM2 service management

</td>
</tr>
<tr>
<td>

### 🔧 **Full Automation**
- ✅ Auto OCI CLI installation
- ✅ Auto-detect existing config
- ✅ Real-time API validation
- ✅ One-click setup

</td>
<td>

### 🎨 **User-Friendly**
- ✅ Colorful log output
- ✅ Emoji-based UI
- ✅ Step-by-step guidance
- ✅ Auto error diagnosis

</td>
</tr>
</table>

---

## 🚀 Core Features

<details>
<summary><b>🎯 Always Free Optimization</b></summary>

- **Shape Auto-filtering**: Shows only E2.1.Micro, A1.Flex
- **Real-time limit check**: Auto-calculate OCPU/RAM usage
- **Billing protection**: Warns when exceeding Always Free limits
- **Usage dashboard**: Real-time display of remaining resources

</details>

<details>
<summary><b>🤖 Discord Bot Commands</b></summary>

| Command | Function | Example |
|:---:|:---|:---|
| `/status` | Bot status and instance overview | Uptime, success rate, recent activity |
| `/launch` | Instant instance creation | Auto-select Always Free Shape |
| `/log` | View recent execution logs | Success/failure history, error diagnosis |
| `/config` | Check configuration info | Current Shape, region, specs |
| `/help` | All commands guide | Usage and tips |

</details>

<details>
<summary><b>🔧 Smart Setup Wizard</b></summary>

- **Auto environment detection**: Auto-load existing OCI config files
- **Real-time API validation**: Real-time query of available Shape/Image
- **Custom spec configuration**: Auto-validate OCPU/RAM combinations
- **Intuitive UI**: User-friendly interface

</details>  

---

## 🛠️ Quick Start

### 1️⃣ Prerequisites

<table>
<tr>
<td width="33%">

#### 🔑 **OCI Account**
- Oracle Cloud free account
- Always Free eligibility confirmed
- Credit card registration (free)

</td>
<td width="33%">

#### 🤖 **Discord Bot**
- [Developer Portal](https://discord.com/developers/applications)
- Bot Token generation
- Server invite link creation

</td>
<td width="33%">

#### 🖥️ **Server Environment**
- Linux (Ubuntu/CentOS)
- Bash 4.0+
- curl, jq installed

</td>
</tr>
</table>

### 2️⃣ OCI API Key Setup

```bash
# 🔐 Generate API key pair
mkdir -p ~/.oci
openssl genrsa -out ~/.oci/oci_api_key.pem 2048
openssl rsa -pubout -in ~/.oci/oci_api_key.pem -out ~/.oci/oci_api_key_public.pem
chmod 600 ~/.oci/oci_api_key.pem

# 📋 Copy public key content (for OCI Console registration)
cat ~/.oci/oci_api_key_public.pem
```

> **🔗 OCI Console Registration Path**  
> `Identity & Security` → `Users` → `Your Account` → `API Keys` → `Add API Key`

### 3️⃣ OCI CLI Setup

```bash
# 🚀 Install OCI CLI (automatic)
bash -c "$(curl -L https://raw.githubusercontent.com/oracle/oci-cli/master/scripts/install/install.sh)"

# 📝 Interactive setup (recommended)
oci setup config

# 🔍 Verify configuration
oci iam region list --output table
```

### 4️⃣ Run Setup Wizard

```bash
# 📥 Download scripts
git clone https://github.com/CorelLinux/oci-simple-script.git
cd oci-simple-script

# 🧙‍♂️ Run setup wizard
bash oci-config-wizard.sh
```

<div align="center">

**🎉 Once all setup is complete, `config.json` will be auto-generated!**

</div>

### 5️⃣ Run Discord Bot

```bash
# 🤖 Start bot
bash oci-script-and-bot.sh

# 📊 Check status
pm2 status
pm2 logs oci-discord-bot
```

---

## 🎮 Usage

### Discord Commands

<div align="center">

| Command | Icon | Description | Result |
|:---:|:---:|:---|:---|
| `/status` | 📊 | **Check bot status** | Uptime, success rate, recent activity |
| `/launch` | 🚀 | **Create instance** | Auto-select Always Free Shape |
| `/log` | 📋 | **View logs** | Recent N execution history |
| `/config` | ⚙️ | **Check configuration** | Current Shape, region, specs |
| `/stop` | ⏹️ | **Stop auto creation** | Pause bot |
| `/start` | ▶️ | **Restart auto creation** | Resume bot |
| `/schedule` | ⏰ | **Set creation interval** | 3-60 minutes (default: 5 min) |
| `/stats` | 📊 | **Detailed statistics** | Success rate, period analysis |
| `/instances` | 🖥️ | **List instances** | Running/stopped instance overview |
| `/resources` | 💰 | **Resource usage** | Always Free limits and usage |
| `/alert` | 🔔 | **Notification settings** | Configure alerts |
| `/help` | ❓ | **Help** | All commands guide |

</div>

### Always Free Usage Monitoring

```bash
# 🔍 Check current instances
oci compute instance list --compartment-id $COMPARTMENT_ID --output table

# 📊 Check A1.Flex usage
oci limits resource-availability get --compartment-id $COMPARTMENT_ID \
    --service-name compute --limit-name vm-standard-a1-core-count
```

### ⚡ New Features in v2.0

<div align="center">

| Feature | Description | Benefit |
|:---|:---|:---|
| **🎯 Smart Interval** | Default 5-minute attempts | Faster instance acquisition |
| **⚙️ Flexible Timing** | 3-60 minute range via `/schedule` | Customizable based on demand |
| **🌐 Multi-language** | English/Korean support | Better accessibility |
| **🔧 Error Recovery** | Improved command error handling | More stable operation |
| **📊 Enhanced Stats** | Detailed success rate analysis | Better monitoring |

</div>

> **💡 Pro Tip**: Use `/schedule 3` during high-demand periods and `/schedule 30` during low-demand periods to optimize success rates.

---

## 🎨 Advanced Setup

### 🎯 Always Free Optimization

<details>
<summary><b>💡 Shape Selection Guide</b></summary>

| Shape | OCPU | RAM | Instances | Use Case | Notes |
|:---:|:---:|:---:|:---:|:---|:---|
| **E2.1.Micro** | 1 | 1GB | 2 | Lightweight web servers, bots | AMD-based |
| **A1.Flex** | 1-4 | 6-24GB | 1-4 | Development servers, learning | ARM-based |

**💰 Cost Calculator:**
- E2.1.Micro: Free (up to 2)
- A1.Flex: Total 4 OCPU, 24GB RAM free
- Boot Volume: 200GB free

</details>

<details>
<summary><b>🔧 Custom SSH Keys</b></summary>

```bash
# 🔑 Use existing SSH keys
export CUSTOM_PRIVATE_KEY_PATH="/path/to/your/private_key"
export CUSTOM_PUBLIC_KEY_PATH="/path/to/your/public_key.pub"

# 🔐 Generate new SSH keys
ssh-keygen -t rsa -b 2048 -f ~/.ssh/oci_key -N ""
export CUSTOM_PRIVATE_KEY_PATH="$HOME/.ssh/oci_key"
export CUSTOM_PUBLIC_KEY_PATH="$HOME/.ssh/oci_key.pub"
```

</details>

<details>
<summary><b>🌐 Language Configuration</b></summary>

The bot supports both English and Korean interfaces. Configure in `config.json`:

```json
{
  "LANGUAGE": "en",  // "en" for English, "ko" for Korean
  // ... other config options
}
```

**Language Features:**
- 🎯 Discord command descriptions in chosen language
- 📝 Bot response messages in chosen language  
- 🔧 Error messages and help text localized
- 🚀 Seamless switching - just edit config and restart

**Change Language:**
```bash
# Edit config.json
nano config.json
# Change "LANGUAGE": "ko" to "LANGUAGE": "en"

# Restart bot
pm2 restart oci-discord-bot
```

</details>

---

## 🔧 Troubleshooting

<details>
<summary><b>🚨 Common Issues</b></summary>

### ❌ OCI CLI Installation Error

```bash
# 🔍 Check installation
oci --version

# 🔧 Check PATH configuration
echo $PATH | grep -o "$HOME/bin"

# 🔄 Reinstall
curl -L https://raw.githubusercontent.com/oracle/oci-cli/master/scripts/install/install.sh | bash
```

### ❌ OCI CLI Not Accessible with sudo

When OCI CLI is installed via symlink in user path, it may not be accessible with sudo.

```bash
# 🔍 Check OCI CLI installation location
which oci
# Result: /home/user/bin/oci

# 🔧 Create symlink in system path
sudo ln -s $(which oci) /usr/local/bin/oci

# ✅ Verify sudo access
sudo oci --version
```

**Automatic Solution:**
```bash
# Script handles this automatically, but manual setup is also possible
sudo ln -s $HOME/bin/oci /usr/local/bin/oci
sudo ln -s $HOME/.local/bin/oci /usr/local/bin/oci
sudo ln -s $HOME/lib/oracle-cli/bin/oci /usr/local/bin/oci
```

### ❌ API Key Permission Error

```bash
# 🔐 Check and fix permissions
ls -la ~/.oci/
chmod 600 ~/.oci/oci_api_key.pem
chmod 644 ~/.oci/oci_api_key_public.pem

# 🔍 Validate key
oci iam region list --auth api_key
```

### ❌ Discord Bot Token Error

```bash
# 🔍 Check token
grep -o "discord_token" config.json

# 🔧 Reset token
bash oci-config-wizard.sh
# Re-run Discord configuration section only
```

### ❌ "Out of Capacity" Error

- **🔄 Try different regions**: `ap-tokyo-1`, `ap-mumbai-1`
- **⏰ Change time zone**: Recommended during early morning hours
- **🎯 Change Shape**: E2.1.Micro → A1.Flex

</details>

<details>
<summary><b>📊 Status Check Commands</b></summary>

```bash
# 🤖 Bot status
pm2 status
pm2 logs oci-discord-bot --lines 50

# 📊 Instance list
oci compute instance list --compartment-id $COMPARTMENT_ID --output table

# 💰 Always Free usage
oci limits resource-availability get \
    --compartment-id $COMPARTMENT_ID \
    --service-name compute \
    --limit-name vm-standard-a1-core-count
```

</details>

<details>
<summary><b>🔧 Configuration File Check</b></summary>

```bash
# 📄 OCI configuration
cat ~/.oci/config

# 📋 Bot configuration
cat config.json | jq .

# 📝 Log file
tail -f oci_bot.log
```

</details>

---

## 📚 References

<div align="center">

### 🔗 Useful Links

| Category | Link | Description |
|:---:|:---|:---|
| **🏛️ Official** | [Oracle Cloud Console](https://cloud.oracle.com) | OCI Management Console |
| **📖 Documentation** | [OCI CLI Guide](https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/cliinstall.htm) | Official Installation Guide |
| **🤖 Bot** | [Discord Developer](https://discord.com/developers/applications) | Bot Creation and Management |
| **💡 Tips** | [Out of Capacity Solution](https://hitrov.medium.com/resolving-oracle-cloud-out-of-capacity-issue-and-getting-free-vps-with-4-arm-cores-24gb-of-a3d7e6a027a8) | Capacity shortage solution |

</div>

### 🎓 Recommended Learning Resources

- **OCI Basics**: [Getting Started with Oracle Cloud Infrastructure](https://docs.oracle.com/en-us/iaas/Content/GSG/Concepts/baremetalintro.htm)
- **Discord.js**: [Official Guide](https://discordjs.guide/)
- **PM2**: [Process Management Guide](https://pm2.keymetrics.io/docs/)

---

## 🤝 Contributing

<div align="center">

### 🙋‍♂️ How to Participate

<table>
<tr>
<td width="33%" align="center">

**🐛 Bug Reports**  
Let us know about issues you find

[Create Issue](https://github.com/CorelLinux/oci-simple-script/issues)

</td>
<td width="33%" align="center">

**💡 Feature Requests**  
Share your new ideas

[Feature Request](https://github.com/CorelLinux/oci-simple-script/issues)

</td>
<td width="33%" align="center">

**🔧 Code Contributions**  
Write improvements yourself

[Pull Request](https://github.com/CorelLinux/oci-simple-script/pulls)

</td>
</tr>
</table>

</div>

### 📋 Contribution Guidelines

1. **🍴 Fork** this repository to your account
2. **🌿 Branch** Create a new feature branch
3. **💻 Code** Write improvements and test
4. **📝 Commit** Write clear commit messages
5. **🚀 PR** Create Pull Request

---

<div align="center">

## 📄 License

**MIT License** - Feel free to use, modify, and distribute!

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

### 🌟 If this project helped you, please give it a Star!

**Made with ❤️ for the Oracle Cloud Always Free Community**

</div>
