<img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/bd1c6c5f-0db6-416f-b5b7-70f5d534dc5a" alt="HyperFluent" width="400"/>

### v1.0.1

An all-new fluent, modern, and clean GRUB theme.

<a href="https://www.pling.com/p/2133341">
<img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/91a092ea-85ce-4690-a4da-2b43754a67cd" alt="Download on PlingStore" width="140"/></a>

***
[![GitHub](https://img.shields.io/github/license/Coopydood/HyperFluent-GRUB-Theme?label=Licence&logo=unlicense&logoColor=white&style=for-the-badge)](https://github.com/Coopydood/HyperFluent-GRUB-Theme/blob/main/LICENSE) [![Discord](https://img.shields.io/discord/574943603466436628?color=7d86ff&label=Discord&logo=discord&logoColor=white&style=for-the-badge)](https://sl.coopydood.com/discord)

***

<img src="https://github.com/Coopydood/ultimate-macOS-KVM/assets/39441479/33c8ce96-132a-479b-9403-b15d377fbe40" alt="Arch Linux theme" width="1400"/>
<p align="center"><i>Arch Linux, one of the several OS-themed variants. I use Arch btw.</i></p>

***

## Variants

Even while maintaining the same shared fluent design language, each variant of  HyperFluent has a distinct look and feel, tailored around the subject of the theme.

**OS / Distros**
- Arch Linux 
- Ubuntu 
- Redhat 
- Fedora 
- NixOS 
- endeavourOS 
- Debian 
- Linux Mint 
- Manjaro 
- OpenSUSE 
- OpenSUSE (Tumbleweed) 
- macOS 
- Windows (Dark) 
- Windows (Light) 
- Gentoo
- ALT Linux
- Zorin OS

**Other**
- Generic

***

## Quick Installation Guide
### Written by [neoapps](https://github.com/neoapps-dev)

- Pick a variant from [Pling](https://www.pling.com/p/2133341)
- After downloading the archive, copy the contents to: `/usr/share/grub/themes/fluent` (with `sudo` or `su`)
- Edit `/etc/default/grub` using (`nano`,`vi`,`vim`,`neovim`, or any text editor) with `sudo` or `su`.
  - Comment `GRUB_TERMINAL_OUTPUT="console"` by prepending a `#` to the start of the line
  - Uncomment `# GRUB_THEME = "..."` and replace the path with `/usr/share/grub/themes/fluent/theme.txt`
- Now, run this command in the terminal,

```sh
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

(If you're on Arch that is installed manually, replace `/boot` with `/YOUR_ESP_PARTITION`, but if you didn't change it, you're alright)

- `reboot`! done, now reboot to see your new awesome-looking GRUB theme :)

> [!TIP]
> An unofficial AUR package of each theme variant is maintained by [Eugenenoble2005](https://github.com/Eugenenoble2005)!

## Gallery

|                                                   **Arch** (btw)                                                  |
|:-----------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/ultimate-macOS-KVM/assets/39441479/33c8ce96-132a-479b-9403-b15d377fbe40" width="525"></img> |

|                                                      **Ubuntu**                                                     |                                                      **Redhat**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/9883e5eb-6fee-4221-9616-cca6691afd5b" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/cac16170-9215-44a9-8f96-c573bde22b14" width="250"></img> |


|                                                      **Fedora**                                                     |                                                      **NixOS**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/86631c68-acda-4584-b906-5d7720e2d4f6" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/2480a2c0-8fae-4e51-9480-8b5d627da0a9" width="250"></img> |


|                                                      **endeavourOS**                                                     |                                                      **Debian**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/044ac4a8-ff71-48e3-89eb-9423d81f4675" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/16785aef-4328-4d0e-84f1-f074b1436f92" width="250"></img> |

|                                                      **Linux Mint**                                                     |                                                      **Manjaro**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/3db368ee-eb6e-49b8-a5c6-3eabafaa44d8" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/c7cf6b1a-2511-48b5-b0d7-34d16a3cdc6c" width="250"></img> |

|                                                      **OpenSUSE**                                                     |                                                      **OpenSUSE (Tumbleweed)**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/c3f15e54-96ec-4552-a92b-09d1ebc9f119" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/37186c86-21fc-4e9f-a8d5-551479878fbd" width="250"></img> |

|                                                      **macOS**                                                     |                                                      **Generic**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/4a48a055-0b04-4975-b2d1-3d5760cbb7e5" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/45eca0ef-5e90-4938-85f7-ec68459cb626" width="250"></img> |

|                                                      **Windows (Dark)**                                                     |                                                      **Windows (Light)**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/198e446b-65ce-4957-a829-9c5dfbe1408a" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/c985fe0a-3f09-432a-a211-504cd78c32e9" width="250"></img> |

|                                                      **Gentoo**                                                     |                                                      **ALT Linux**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/c3817bb4-5f7d-4792-902e-8725f22ef4e8" width="250"></img> | <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/5533becf-b207-4906-9c95-7f6f996d43d1" width="250"></img> |

|                                                      **Zorin OS**                                                     |
|:-------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/Coopydood/HyperFluent-GRUB-Theme/assets/39441479/72999177-e869-490e-a46c-7deb23f6cbec" width="250"></img> 

***

<p align="center">
  <img src="https://github.com/Coopydood/ultimate-macOS-KVM/assets/39441479/39d78d4b-8ce8-44f4-bba7-fefdbf2f80db" width="10%"> </img>
</p>

