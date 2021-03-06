# mac-mini-server
Description of how I set up my Mac mini (M1, 2020) as a server

## Hardware

1. Mac mini (M1, 2020)
  * Model Identifier: Macmini9,1
  * Chip: Apple M1
  * Total Number of Cores: 8 (4 performance and 4 efficiency)
  * Memory: 16GB (LPDDR4)
  * System Firmware Version: 7429.81.3
  * OS Loader Version: 7429.81.3
2. SanDisk Professional - G-DRIVE 6TB External USB-C Hard Drive
  * Model: SDPH91G-006T-NBAAD
3. SanDisk Professional - G-DRIVE 6TB External USB-C Hard Drive
  * Model: SDPH91G-006T-NBAAD

## Software

1. macOS
  * Version: 12.3
  * Configuration:
    For much of the configuration, I utilized the information provided by Stuart Ellis in his [FIELD NOTES blog](https://www.stuartellis.name) in an entry titled [*How to Set up an Apple Mac for Software Development*](https://www.stuartellis.name/articles/mac-setup/#configuring-a-user-account).  In particular, I made sure to cover these sections:
    * [Do This First!](https://www.stuartellis.name/articles/mac-setup/#do-this-first)
    * [Configuring a User Account](https://www.stuartellis.name/articles/mac-setup/#configuring-a-user-account)
    * [Creating a Private Applications Folder](https://www.stuartellis.name/articles/mac-setup/#creating-a-private-applications-folder)
    * [Securing the Safari Browser](https://www.stuartellis.name/articles/mac-setup/#securing-the-safari-browser)
    * [Configuring Security](https://www.stuartellis.name/articles/mac-setup/#configuring-security)
    * [Basic Settings](https://www.stuartellis.name/articles/mac-setup/#basic-settings)
    * [Disable Spotlight](https://www.stuartellis.name/articles/mac-setup/#disable-spotlight)
    * [Enable File Vault NOW](https://www.stuartellis.name/articles/mac-setup/#enable-file-vault-now)
  * Create RAID 1 volume for additional software not provided with macOS   