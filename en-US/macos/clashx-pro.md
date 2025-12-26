# 🛡️ ClashX Pro Configuration Guide

## 📱 Software Overview

**ClashX Pro** is a powerful macOS proxy software designed specifically for Mac users as a modern network proxy tool. It features an intuitive user interface and rich functionality, supporting multiple proxy protocols to provide users with stable and efficient network proxy services.

### ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🔒 **Multi-Protocol Support** | Shadowsocks (SS), V2Ray (VMess), Trojan, HTTP/HTTPS, SOCKS5, SOCKS5 over TLS |
| 🎯 **Smart Routing** | Rule-based traffic splitting, geo-location routing, domain matching, etc. |
| 📊 **Real-time Monitoring** | Traffic statistics, connection monitoring, node latency testing |
| 🔄 **Auto Update** | Subscription link auto-update for node information |
| 🛠️ **Advanced Configuration** | Custom rules, proxy chains, load balancing, etc. |
| 🖥️ **System Integration** | Native macOS design with system proxy settings support |

### 🔧 System Requirements

| Item | Requirement |
|------|-------------|
| **Operating System** | macOS 10.15 or higher |
| **Device Type** | MacBook, iMac, Mac Pro, Mac mini |
| **Network Environment** | Stable internet connection |
| **Storage Space** | At least 50MB available space |

## 📥 Software Download

### 🌐 Official Download Links

| Download Source | Link | Notes |
|----------------|------|-------|
| **Official Site** | [ClashX Pro Official](https://clashxhub.com/apps/ClashXPro.dmg) | Recommended |
| **Backup Address 1** | [Backup Download](https://dl.haojichang.com/apps/ClashX_Pro/ClashXPro.dmg) | Stable and reliable |
| **Backup Address 2** | [KrakenFiles](https://krakenfiles.com/view/5RdlIY2HKL/file.html) | International server |

> 💡 **Download Tips**: We recommend downloading from the official address to ensure software security and feature completeness.

## ⚙️ Detailed Configuration Tutorial

### 📋 Prerequisites

Before starting configuration, please ensure you have:

- ✅ Downloaded and installed ClashX Pro
- ✅ Obtained a valid proxy service subscription link or configuration file
- ✅ Verified normal network connectivity

### 🔧 Step One: Software Installation

#### 1.1 Download Installation Package

Obtain the ClashX Pro installation package from the download addresses above.

![Installation Package Download](ClashX-00.png)

#### 1.2 Install Software

1. Double-click the downloaded `.dmg` file
2. Drag ClashX Pro to the Applications folder
3. Wait for installation to complete

![Software Installation](ClashX-01.png)

#### 1.3 First Launch

1. Launch ClashX Pro from the Applications folder
2. System may show security warning, click "Open"
3. Software will display an icon in the menu bar

![First Launch](ClashX-02.png)

### 🌐 Step Two: Import Configuration

#### 2.1 Access Configuration Menu

1. Click the ClashX Pro icon in the menu bar
2. Select "Config" option
3. Enter configuration management interface

![Configuration Menu](ClashX-03.png)

#### 2.2 Add Subscription Link

1. Click "Add" button in the configuration interface
2. Select "Import from URL"
3. Paste your subscription link

![Add Subscription](ClashX-04.png)

#### 2.3 Configuration Verification

1. Wait for configuration file download to complete
2. System will automatically verify configuration file format
3. Confirm configuration information is correct

![Configuration Verification](ClashX-05.png)

#### 2.4 Enable Proxy

1. Select the newly imported configuration file
2. Click "Set as System Proxy"
3. Proxy service is now officially enabled

![Enable Proxy](ClashX-06.png)

### 🚀 Step Three: Advanced Configuration

#### 3.1 Node Selection

- **Auto Select**: Let software automatically choose optimal node
- **Manual Select**: Manually select specific node as needed
- **Load Balancing**: Distribute traffic across multiple nodes

#### 3.2 Rule Configuration

- **Global Mode**: All traffic through proxy
- **Rule Mode**: Traffic splitting according to preset rules
- **Direct Mode**: No proxy usage

#### 3.3 Custom Rules

```yaml
# Example rule configuration
rules:
  - DOMAIN-SUFFIX,google.com,PROXY
  - DOMAIN-SUFFIX,github.com,PROXY
  - DOMAIN-KEYWORD,google,PROXY
  - GEOIP,CN,DIRECT
```

## 📊 Feature Details

### 🔍 Real-time Monitoring

| Feature | Description |
|---------|-------------|
| **Traffic Statistics** | View real-time upload/download speed and cumulative traffic |
| **Connection Monitoring** | Monitor current active connection count |
| **Latency Testing** | Test response latency of various nodes |
| **Log Viewing** | View detailed connection log information |

### 🛠️ Advanced Features

| Feature | Description |
|---------|-------------|
| **Auto Update** | Automatically update subscription configurations at scheduled intervals |
| **Auto Start** | Automatically run when system starts |
| **System Proxy** | Automatically configure system proxy settings |
| **Rule Editing** | Customize traffic splitting rules |

## ❓ Frequently Asked Questions

### 🔧 Installation Issues

**Q: Software cannot install or launch?**

A: Solutions:

1. Check if macOS version meets requirements
2. Allow app to run in "System Preferences" → "Security & Privacy"
3. Try right-clicking app icon and select "Open"

**Q: Prompt "From unidentified developer"?**

A: Solution steps:

1. Hold Control key and click app icon
2. Select "Open" from shortcut menu
3. Click "Open" in the popup dialog

### 🌐 Connection Issues

**Q: Cannot connect after importing configuration?**

A: Checklist:

1. ✅ Confirm subscription link is valid and not expired
2. ✅ Check network connection is normal
3. ✅ Verify configuration file format is correct
4. ✅ Try switching to different nodes

**Q: Slow speed or frequent disconnections?**

A: Optimization suggestions:

1. 🔄 Select nodes with lower latency
2. 🎯 Adjust proxy mode (Rule/Global)
3. 📊 Check local network conditions
4. 🔧 Try different encryption protocols

### ⚙️ Configuration Issues

**Q: How to update subscription configuration?**

A: Update steps:

1. Click menu bar icon
2. Select "Config" → "Update"
3. Wait for configuration file to auto-update

**Q: How to backup configuration?**

A: Backup method:

1. Export current configuration file
2. Save to a secure location
3. Re-import when needed

## 💡 Best Practices

### 🎯 Usage Recommendations

1. **Choose Proxy Mode Wisely**
   - "Rule Mode" recommended for daily use
   - "Global Mode" for special needs
   - "Direct Mode" for debugging

2. **Regular Maintenance**
   - Update subscription configuration weekly
   - Clean log files regularly
   - Update software version timely

3. **Security Considerations**
   - Use trusted proxy service providers
   - Change passwords and configurations regularly
   - Avoid usage on public networks

### ⚡ Performance Optimization

| Optimization Item | Recommendation |
|------------------|----------------|
| **Node Selection** | Choose geographically closer nodes with lower latency |
| **Connection Limit** | Adjust maximum connections according to needs |
| **DNS Configuration** | Use reliable DNS servers |
| **Cache Settings** | Adjust cache size appropriately |

## 🔗 Related Resources

### 📚 Official Documentation

- [ClashX Pro Official Website](https://clashxhub.com/)
- [Clash Core Documentation](https://github.com/Dreamacro/clash)
- [Configuration File Format Guide](https://github.com/Dreamacro/clash/wiki/configuration)

### 🛠️ Recommended Tools

- **Configuration Converter**: [Online Converter](https://acl4ssr.netlify.app/)
- **Rule Subscription**: [ACL4SSR Rules](https://github.com/ACL4SSR/ACL4SSR)
- **Node Testing**: Built-in latency testing functionality

---

> � Last Updated: July 10, 2025 | 🛡️ Applicable Version: ClashX Pro 1.118.0

---

*For questions or technical support, please refer to the FAQ section or contact relevant technical personnel.*
