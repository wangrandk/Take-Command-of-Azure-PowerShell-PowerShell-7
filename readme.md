# Topic: Take Command of Azure PowerShell & PowerShell 7

## Abstract
Cloud providers like Azure continually deliver new features and capabilities each day, like pieces to an ever expanding puzzle. I've found an edge to the puzzle in Azure PowerShell, and I'll share that edge with you in this beginner level session.

Using the latest PowerShell 7 release, we'll begin from first login, discovering command syntax, common command features and shortcuts, and how command line increases your understanding and ability to build confidently in the cloud.

## Bio
About the Speaker:
[David Cobb](https://davidcobb.net), Principal Consultant of Cobb Information Technologies

David loves to learn and solve problems with technology, and teach others to do the same. He is principal consultant for Cobb Information Technologies since 1996, providing technology training and consulting for his clients. He is a MCT since 2002, certified in Azure Admin & Data Platform and AWS Sysops & Architect.

# :) Warning and Guidance :)
## This is a CODE-INTENSIVE presentation/tutorial. 
## My goal is to encourage you to learn by doing after this presentation.
## All code available on GitHub, and designed for you to fork or clone and step through (and customize and extend) on your own.
## Submit an issue if you have question or find a problem (link).

# Goals for Session
## Brief background on PS & Azure and the migration to PSCore/PS7
## Into the code with PowerShell basics
## Deeper into the code with PowerShell AZ Module
## Learning syntax, command features, shortcuts
## Increase understanding and confidence in Azure using PowerShell

# PowerShell - _Brief_ History
## The Windows Years
* PowerShell for Windows 2-5.1
* Windows XP-Win10
* [PowerShell on Wikipedia](https://en.wikipedia.org/wiki/PowerShell)
## The Core of the Matter
* Microsoft made open source .Net Core to enable .Net Devs & Admins to be productive in Linux & macOS
* PowerShell Core is built on .Net Core, and serves I.T. Admins, DevOps folks, AND Devs the same way.
## "But I like PowerShell for Windows, why have they changed it to PowerShell Core?"
* PowerShell for Windows is not going away, PowerShell Core / PowerShell 7 is a new creation
* Check this [Don Jones post on PowerShell](https://powershell.org/2018/01/can-we-talk-about-powershell-core-6-0/
## Current State
* [PowerShell 7 RC1](https://devblogs.microsoft.com/powershell/announcing-the-powershell-7-0-release-candidate/)
## Installing
### Windows
### Linux
#### WSL

# My Environment
## Win10 (could be any, because all cross platform)
## VSCode with extensions (PowerShell Preview, Azure optional)
## PS 7, AZ Module Installed
    
## PowerShell Primer
### How to run PowerShell
* Default PowerShell in your OS (5.1)
* This is the OLD way, going away, not cross platform, not open source, no more development

    How to install PS7 latest
        Windows
        Linux (no macOS)
        Docker
            [Performance improvements in PS Docker Images](https://devblogs.microsoft.com/powershell/improvements-in-windows-powershell-container-images/)
        Or... just use cloud shell from the portal


## Azure PowerShell
### Out with AzureRM, in with AZ
### Installing
### Logging in
### Exploring
* Accounts
* Resources
* Storage
* Websites(WebApps)
* KeyVault
* Compute(VMs)
* Monitor


### Teaser: From Imperative to Declarative 
* ARM Templates
* Terraform?