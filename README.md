# Oh My Posh Custom Themes 🎨

Welcome to the **Oh My Posh Custom Themes** repository! This project offers a collection of custom themes for [Oh My Posh](https://ohmyposh.dev), a prompt theme engine that transforms your terminal into a visually stunning and functional workspace.

## 🌟 Features
- 🎨 A variety of custom themes to enhance your shell prompt.
- ⚙️ Easy to use and customize.
- 🖼️ Previews of each theme for easy selection.
- 🚀 Optimized for an improved user experience in the terminal.

## Quick Preview
<!-- ![App Screenshot](./Assets/Screenshot%20.png) -->
<div align="center">

![App Screenshot](./Assets/Screenshot-u.png)
</div>

## 📋 Requirements

Before using the custom themes, ensure you have the following installed:

- [Oh My Posh](https://ohmyposh.dev/docs/installation): A prompt theme engine for any shell.
- **Powerline fonts**: Required for proper display of symbols and icons used in themes. You can install them from [Nerd Fonts](https://www.nerdfonts.com).
- A supported shell, such as:
  - PowerShell
  - Bash
  - Zsh
  - Fish

## 🚀 Quick Start

Follow these steps to get started with the custom themes:

1. **Install Oh My Posh**  

   Make sure you have installed Oh My Posh by following the official [installation guide](https://ohmyposh.dev/docs/installation).

2. **Clone the Repository**  

   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/sakibtalukqder/Oh-my-posh-Castom-Thmes.git
   cd Oh-my-posh-Castom-Thmes
   ```


4. **Get Powershell Path**

```shell
$env:Path += ";C:\Users\user\AppData\Local\Programs\oh-my-posh\bin"
```

4. **Create a PowerShell Profile and Openit in Notepad**

   To set up Oh My Posh, you'll need to create or edit your PowerShell profile. This profile runs every time a new PowerShell session starts.
   ```bash
   notepad $PROFILE
   ```
   If the file does not exist, PowerShell will create it. This profile script runs every time a new PowerShell session starts.
   
5. **Add Theme Configuration to PowerShell Profile**:

   After opening your PowerShell profile in Notepad, you’ll need to add a line to configure Oh My Posh with a custom theme from this repository:
   Add the following line to your profile

   ```bash
   oh-my-posh init pwsh --config '<path-to-your-cloned-repository>' | Invoke-Expression
   ```

# **Install Terminal Icons**  

```shell
Install-Module -Name Terminal-Icons -Repository PSGallery
Import-Module -Name Terminal-Icons
```

# notepad $PROFILE (For Windows)

```bash
& ([ScriptBlock]::Create((oh-my-posh init pwsh --config "$env:C:\Users\iam Readoy\Documents\o-posh\1_shell_v2.omp.json" --print) -join "`n"))
Import-Module -Name Terminal-Icons
```




<div align="center">
<br>
<br>
<br>

# <img src="assets/hello.gif" width="28px" alt="hi"> Stay Connected with Sakib Talukqder

[![Facebook Badge](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/sakibtalukqder)
[![Instagram Badge](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/sakibtalukqder)
[![Telegram Badge](https://img.shields.io/static/v1?message=Telegram&logo=telegram&label=&color=2CA5E0&logoColor=white&labelColor=&style=for-the-badge)](t.me/+8801799232910)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/<+8801799232910>)
[![Mail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sakibtalukqder07@gmail.com)

</div>